#### Test 8149356279477ac_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-16 17:57:52.423  6280  6467 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 3.864479
08-16 17:57:52.423  1470  1483 D TP/MmsSmsProvider: query,matched:0, calling pid = 6280
08-16 17:57:52.423  1470  1483 V TP/MmsSmsProvider: getSimpleConversations entered.
08-16 17:57:52.423  1470  1483 D TP/MmsSmsProvider: match 0:Elapsed time : 1.188 ms
08-16 17:57:52.423  6280  6468 D Mms/Synchronizer: [start]    doSync consume time = 6.645157
08-16 17:57:52.423  6280  6280 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-16 17:57:52.423  6280  6280 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-16 17:57:52.433  1470  1681 D TP/MmsSmsProvider: update, matched:300, calling pid = 6280
08-16 17:57:52.433  1470  1681 V TP/MmsSmsProvider: syncDBData start
08-16 17:57:52.433  6280  6280 D Mms/MethodReflector: getSubId is called
08-16 17:57:52.433  6280  6280 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-16 17:57:52.433  1470  1485 D TP/MmsSmsProvider: query,matched:400, calling pid = 6280
08-16 17:57:52.433  1019  1448 E EdmStorageProvider: Admin not in database, something went wrong
08-16 17:57:52.433  6280  6280 D Mms/MethodReflector: getTelephonyProperty is called
08-16 17:57:52.433  6280  6280 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-16 17:57:52.433  1929  6365 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-16 17:57:52.433  1470  1681 V TP/MmsSmsProvider: syncDBData sms end
08-16 17:57:52.433  1929  6368 W BaseAppContext: Using Auth Proxy for data requests.
08-16 17:57:52.433  1929  6365 I qtaguid : Tagging socket 97 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1929, getuid(): 10011
08-16 17:57:52.433  1470  1681 V TP/MmsSmsProvider: syncDBData mms end
08-16 17:57:52.433  6280  6280 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-16 17:57:52.433  6280  6280 D Mms/DownloadManager: auto download without roaming -> true
08-16 17:57:52.433  6280  6280 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-16 17:57:52.433  6280  6280 D Mms/DownloadManager: mAutoDownload ------> true
08-16 17:57:52.433  1470  1681 V TP/MmsSmsProvider: syncDBData end
08-16 17:57:52.433  6280  6467 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 10.515312
--------- beginning of system
08-16 17:57:52.433  1019  1752 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-16 17:57:52.443  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.443  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.443  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.443  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.453  6469  6469 E Zygote  : MountEmulatedStorage()
08-16 17:57:52.453  6469  6469 E Zygote  : v2
08-16 17:57:52.453  6469  6469 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:57:52.453  6469  6469 I libpersona: KNOX_SDCARD checking this for 10068
08-16 17:57:52.453  6469  6469 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:52.453  1019  1752 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6469 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-16 17:57:52.463  6280  6468 D Mms/Synchronizer: [end]    doSync consume time = 21.085781
08-16 17:57:52.463  6469  6469 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:57:52.463  6469  6469 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-16 17:57:52.483  1929  6368 W BaseAppContext: Using Auth Proxy for data requests.
08-16 17:57:52.483  6280  6280 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-16 17:57:52.483  6469  6469 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:57:52.483  6469  6469 D ActivityThread: Added TimaKeyStore provider
08-16 17:57:52.483  1019  4459 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:57:52.483  1019  4459 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:57:52.483  1019  4459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-16 17:57:52.483  1019  4459 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-16 17:57:52.483  1019  4459 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-16 17:57:52.493  1929  6365 I qtaguid : Tagging socket 105 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1929, getuid(): 10011
08-16 17:57:52.493  1929  6368 W BaseAppContext: Using Auth Proxy for data requests.
08-16 17:57:52.493  1019  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-16 17:57:52.493  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.493  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.493  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.493  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.503  6486  6486 E Zygote  : MountEmulatedStorage()
08-16 17:57:52.503  6486  6486 I libpersona: KNOX_SDCARD checking this for 10042
08-16 17:57:52.503  6486  6486 E Zygote  : v2
08-16 17:57:52.503  6486  6486 I libpersona: KNOX_SDCARD not a persona
,08-16 17:57:52.503  6486  6486 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:57:52.513  1019  1490 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6486 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-16 17:57:52.513  6486  6486 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:57:52.513  6486  6486 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-16 17:57:52.533  6486  6486 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:57:52.533  6486  6486 D ActivityThread: Added TimaKeyStore provider
08-16 17:57:52.543  1929  6368 W BaseAppContext: Using Auth Proxy for data requests.
08-16 17:57:52.543  6280  6496 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-16 17:57:52.543  6280  6496 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-16 17:57:52.553  1019  4803 I ActivityManager: Killing 6135:com.android.defcontainer/u0a3 (adj 15): empty #21
08-16 17:57:52.553  1019  4803 I ActivityManager: Killing 6056:com.android.calendar/u0a131 (adj 15): empty #22
08-16 17:57:52.553  6486  6486 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:57:52.553  6486  6486 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 17:57:52.553  6486  6486 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-16 17:57:52.573  6469  6469 D BadgeProvider: onCreate
08-16 17:57:52.573  6469  6469 D BadgeProvider: DatabaseHelper
08-16 17:57:52.593  6280  6464 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-16 17:57:52.603  1470  1483 D TP/SmsProvider: query,matched:26, calling pid = 6280
08-16 17:57:52.603  1470  1483 D TP/SmsProvider: match 26:Elapsed time : 1.182 ms
08-16 17:57:52.623  1470  1681 D TP/MmsSmsProvider: query,matched:6, calling pid = 6280
08-16 17:57:52.623  1470  1681 D TP/MmsSmsProvider: match 6:Elapsed time : 2.925 ms
08-16 17:57:52.643  1019  1125 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-16 17:57:52.643  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.643  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.643  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.643  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.653  6504  6504 E Zygote  : MountEmulatedStorage()
08-16 17:57:52.653  6504  6504 E Zygote  : v2
08-16 17:57:52.653  6504  6504 I libpersona: KNOX_SDCARD checking this for 10023
08-16 17:57:52.653  6504  6504 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:52.653  6504  6504 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:57:52.653  1019  1125 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6504 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-16 17:57:52.663  6504  6504 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:57:52.663  6504  6504 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:57:52.683  6504  6504 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:57:52.683  6504  6504 D ActivityThread: Added TimaKeyStore provider
08-16 17:57:52.683  1019  1737 I ActivityManager: Killing 5952:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-16 17:57:52.723  6486  6486 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-16 17:57:52.723  1019  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-16 17:57:52.723  1019  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-16 17:57:52.723  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.723  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.723  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.723  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:52.743  6519  6519 E Zygote  : MountEmulatedStorage()
08-16 17:57:52.743  6519  6519 E Zygote  : v2
08-16 17:57:52.743  6519  6519 I libpersona: KNOX_SDCARD checking this for 10003
08-16 17:57:52.743  6519  6519 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:52.753  6519  6519 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:57:52.753  6519  6519 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:57:52.753  6519  6519 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:57:52.763  1019  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6519 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-16 17:57:52.763  1019  4803 I ActivityManager: Killing 6180:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-16 17:57:52.783  6519  6519 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:57:52.783  6519  6519 D ActivityThread: Added TimaKeyStore provider
08-16 17:57:52.793  6504  6504 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-16 17:57:52.793  6502  6502 D AndroidRuntime: 
08-16 17:57:52.793  6502  6502 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 17:57:52.793  6502  6502 D AndroidRuntime: CheckJNI is OFF
08-16 17:57:52.793  6502  6502 D AndroidRuntime: readGMSProperty: start
08-16 17:57:52.793  6502  6502 D AndroidRuntime: readGMSProperty: already setted!!
08-16 17:57:52.793  6502  6502 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 17:57:52.793  6502  6502 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 17:57:52.793  6502  6502 D AndroidRuntime: readGMSProperty: end
08-16 17:57:52.793  6502  6502 D AndroidRuntime: addProductProperty: start
08-16 17:57:52.813  1019  1499 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-16 17:57:52.823  1929  1948 W art     : Suspending all threads took: 9.609ms
08-16 17:57:52.833   284   284 E installd: system dir 0 : /system/app/
08-16 17:57:52.833   284   284 E installd: system dir 1 : /system/priv-app/
08-16 17:57:52.833   284   284 E installd: system dir 2 : /vendor/app/
08-16 17:57:52.833   284   284 E installd: system dir 3 : /oem/app/
08-16 17:57:52.843  6280  6464 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-16 17:57:52.883  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-16 17:57:52.883  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-16 17:57:52.883  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-16 17:57:52.883  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-16 17:57:52.883  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-16 17:57:52.893  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-16 17:57:52.893  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-16 17:57:52.893  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-16 17:57:52.893  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-16 17:57:52.893  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-16 17:57:52.893  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-16 17:57:52.893  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-16 17:57:52.893  6504  6504 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-16 17:57:52.903  1019  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-16 17:57:52.953  6502  6502 E AffinityControl: AffinityControl: registerfunction enter
08-16 17:57:52.983  6502  6502 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 17:57:53.003  1019  1752 E PersonaManagerService: inState():  stateMachine is null !!
08-16 17:57:53.003  1019  1752 I PersonaManagerService: PersonaId don't exist
08-16 17:57:53.003  1019  1752 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-16 17:57:53.003  1019  1752 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 17:57:53.013  1019  1752 W ActivityManager: mDVFSHelper.acquire()
08-16 17:57:53.023  1019  1752 D FocusedStackFrame: Set to : 0
08-16 17:57:53.023  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.023  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.023  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.023  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.033  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 17:57:53.033  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-16 17:57:53.043  6547  6547 E Zygote  : MountEmulatedStorage()
08-16 17:57:53.043  6547  6547 E Zygote  : v2
08-16 17:57:53.043  6547  6547 I libpersona: KNOX_SDCARD checking this for 10170
08-16 17:57:53.043  6547  6547 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:53.043  6547  6547 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:57:53.053  6547  6547 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:57:53.053  6547  6547 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-16 17:57:53.053  1019  1752 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-16 17:57:53.053  1019  1752 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6547 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 17:57:53.053  1019  1752 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 17:57:53.053  1019  1752 D InputDispatcher: Focused application set to: xxxx
08-16 17:57:53.053  1019  1752 D InputDispatcher: Focus left window: 1497
08-16 17:57:53.053  6502  6502 D AndroidRuntime: Shutting down VM
08-16 17:57:53.063  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 17:57:53.063  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 17:57:53.063  1929  6365 I qtaguid : Untagging socket 97
08-16 17:57:53.063   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-16 17:57:53.063  1929  1929 I ConfigFetchService: fetch service done; releasing wakelock
08-16 17:57:53.073  1929  1929 I ConfigFetchService: stopping self
08-16 17:57:53.073  6547  6547 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:57:53.073  6547  6547 D ActivityThread: Added TimaKeyStore provider
08-16 17:57:53.083  1019  1031 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-16 17:57:53.093  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-16 17:57:53.093  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:57:53.093  1019  1019 V ActivityManager: Display changed displayId=0
08-16 17:57:53.093  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 17:57:53.103  1019  1125 I art     : Explicit concurrent mark sweep GC freed 128977(7MB) AllocSpace objects, 3(1646KB) LOS objects, 33% free, 23MB/34MB, paused 3.867ms total 181.390ms
08-16 17:57:53.133  1019  1031 D PersonaManager: isKioskContainerExistOnDevice
08-16 17:57:53.153  6304  6375 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-16 17:57:53.153  6304  6375 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 17:57:53.153  6304  6375 I GAv4    :   adb logcat -s GAv4
08-16 17:57:53.163  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-16 17:57:53.163   258  6102 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-16 17:57:53.163   258   434 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-16 17:57:53.173  1929  4410 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-16 17:57:53.173  1019  3382 D SSRM:n  : SIOP:: AP = 400
08-16 17:57:53.173  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{25426524 token=android.os.BinderProxy@1c88340 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-16 17:57:53.173  1497  1497 D Launcher: onTrimMemory. Level: 20
08-16 17:57:53.193  6304  6375 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-16 17:57:53.193  1019  1737 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-16 17:57:53.243  6304  6375 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-16 17:57:53.263  6502  6502 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 17:57:53.283  6547  6547 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-16 17:57:53.293  1019  1051 I PowerManagerService: [PWL] Off : 30s ago
08-16 17:57:53.293  1019  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-16 17:57:53.293  1019  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-16 17:57:53.293  1019  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1929, ws=null) (elapsedTime=49674)
08-16 17:57:53.293  1019  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=1929, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=1695)
08-16 17:57:53.303  6304  6375 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-16 17:57:53.303  6304  6566 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-16 17:57:53.333  1929  4410 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-16 17:57:53.353  6547  6547 I cr.library_loader: Time to load native libraries: 18 ms (timestamps 2994-3012)
08-16 17:57:53.353  6547  6547 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-16 17:57:53.373  6547  6547 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {227e88fc}
08-16 17:57:53.373  6547  6547 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-16 17:57:53.383  6547  6547 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 17:57:53.393  6304  6319 W art     : Suspending all threads took: 30.315ms
08-16 17:57:53.423  1019  1097 V AlarmManager: waitForAlarm result :4
08-16 17:57:53.433  6547  6547 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-16 17:57:53.433  1929  4410 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-16 17:57:53.433  6547  6547 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:57:53.443  6547  6547 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 17:57:53.453  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-16 17:57:53.463  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:57:53.463  1019  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:57:53.463  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:57:53.503  6547  6547 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:57:53.503  6547  6547 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:57:53.503  6547  6547 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:57:53.503  6547  6547 I Adreno-EGL: Local Branch: 
08-16 17:57:53.503  6547  6547 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:57:53.503  6547  6547 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:57:53.503  6547  6547 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-16 17:57:53.553  1019  1499 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-16 17:57:53.553  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.553  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.553  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.553  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.563  6579  6579 E Zygote  : MountEmulatedStorage()
08-16 17:57:53.563  6579  6579 E Zygote  : v2
08-16 17:57:53.563  6579  6579 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:57:53.563  6579  6579 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:53.563  6579  6579 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:57:53.563  6579  6579 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:57:53.573  6579  6579 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:57:53.573  1019  1499 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6579 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 17:57:53.573  1019  1499 I ActivityManager: Killing 6210:com.sec.spp.push/u0a32 (adj 15): empty #21
08-16 17:57:53.603  6547  6547 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 17:57:53.613  6547  6547 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-16 17:57:53.613  6547  6547 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-16 17:57:53.623  6547  6547 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-16 17:57:53.623  6547  6547 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-16 17:57:53.623  6579  6579 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:57:53.623  6579  6579 D ActivityThread: Added TimaKeyStore provider
08-16 17:57:53.653  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{2efb4a92 u0 com.test.thalitest/.MainActivity t163}
08-16 17:57:53.683  6579  6579 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-16 17:57:53.683  6579  6579 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-16 17:57:53.683  1019  1490 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-16 17:57:53.683  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-16 17:57:53.683  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:57:53.683  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:57:53.683  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-16 17:57:53.693  1019  1032 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-16 17:57:53.693  6579  6579 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-16 17:57:53.703  6579  6607 E FilterInstaller: installFilters
08-16 17:57:53.703  6579  6607 E FilterInstaller: There is no requred permission
08-16 17:57:53.713  1019  1031 I ActivityManager: Killing 5105:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-16 17:57:53.723  6304  6576 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 17:57:53.733  6304  6576 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-16 17:57:53.763  6304  6576 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-16 17:57:53.773  1019  1019 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-16 17:57:53.773  1019  1019 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
08-16 17:57:53.783  1019  1390 D NtpTrustedTime: forceRefresh() from cache miss
08-16 17:57:53.783   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 17:57:53.783   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 1000
08-16 17:57:53.793  1019  1019 I BackgroundCompactionService: onStart. jobID=801
08-16 17:57:53.793  1019  1019 I BackgroundCompactionService: onStart done. jobID=801
08-16 17:57:53.793  6547  6547 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:57:53.793  1019  6611 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-16 17:57:53.803  1019  6611 I BackgroundCompactionService: compact_memory command done
08-16 17:57:53.823  6547  6547 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 17:57:53.833  6547  6547 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 17:57:53.833  6547  6547 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-16 17:57:53.833  6304  6576 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-16 17:57:53.833  6304  6576 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a5f5c52: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-16 17:57:53.843  1019  1390 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1471363073788 mCachedNtpElapsedRealtime : 93499 mCachedNtpCertainty : 8
08-16 17:57:53.843  1019  1390 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:57:53.843  1019  1390 D AlarmManagerService: Setting time of day to sec=1471363073
08-16 17:57:53.843  1019  1390 D AlarmManagerService: Trying to open a file
08-16 17:57:53.843  6304  6576 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-16 17:57:53.843  6547  6547 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-16 17:57:53.843  1019  1390 D AlarmManagerService: File Open Success
08-16 17:57:53.843  1019  1390 D AlarmManagerService: File Close Success
08-16 17:57:53.843  1019  1390 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
08-16 17:57:53.790  1019  1097 V AlarmManager: waitForAlarm result :65536
08-16 17:57:53.790  1019  1390 W AlarmManagerService: Unable to set rtc to 1471363073: Invalid argument
08-16 17:57:53.790  1019  1097 V AlarmManager: No more alarm at this time.nowELAPSED=93521 batch.start=99721
08-16 17:57:53.790  1019  1019 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1471363073805
08-16 17:57:53.790  1019  1019 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
08-16 17:57:53.799  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
08-16 17:57:53.799  1182  1182 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 17:57:53.799  1019  1019 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
08-16 17:57:53.809  1182  1182 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-16 17:57:53.809  1182  1182 D SecKeyguardClockView: HomeTimezone(): 1
08-16 17:57:53.819  1019  1019 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:57:53.819  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-16 17:57:53.819  1182  1182 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
08-16 17:57:53.819  6547  6547 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:57:53.819  6547  6547 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:57:53.829  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-16 17:57:53.829  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-16 17:57:53.829  1019  1019 I DrmEventService:  no response from SecureClock 
08-16 17:57:53.829  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-16 17:57:53.829  1019  1019 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-16 17:57:53.829  1019  1019 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-16 17:57:53.829  1019  1019 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-16 17:57:53.829  1019  1019 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
08-16 17:57:53.829  1182  1182 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
08-16 17:57:53.829  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-16 17:57:53.839  1019  3411 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-16 17:57:53.839  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.839  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.839  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.839  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.839  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-16 17:57:53.849  1019  1125 D SettingsProvider: name = lockscreen_zoom_panning_effect
08-16 17:57:53.849  1019  1125 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:57:53.849  1019  1125 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:57:53.849  1019  1125 D SettingsProvider: selectionArgs: false
08-16 17:57:53.849  1019  1125 D SettingsProvider: selectionArgs: 10049
08-16 17:57:53.849  1019  1125 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:57:53.849  1019  1125 D SettingsProvider: ret = -1
08-16 17:57:53.849  6614  6614 E Zygote  : MountEmulatedStorage()
08-16 17:57:53.849  6614  6614 E Zygote  : v2
08-16 17:57:53.849  6614  6614 I libpersona: KNOX_SDCARD checking this for 10008
08-16 17:57:53.849  6614  6614 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:53.849  6614  6614 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:57:53.859  6614  6614 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:57:53.859  1019  1019 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6614 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:57:53.859  6614  6614 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-16 17:57:53.879  6547  6627 D OpenGLRenderer: Render dirty regions requested: true
08-16 17:57:53.879  1019  1125 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
08-16 17:57:53.879  1019  1449 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 17:57:53.879  1019  1449 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 17:57:53.879  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
08-16 17:57:53.879  1019  1449 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 17:57:53.879  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 17:57:53.879  1182  1182 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
08-16 17:57:53.889  6547  6591 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-16 17:57:53.889  6547  6547 V ActivityThread: updateVisibility : ActivityRecord{c5627cf token=android.os.BinderProxy@15b8d2a9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 17:57:53.889  6614  6614 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:57:53.889  6614  6614 D ActivityThread: Added TimaKeyStore provider
08-16 17:57:53.889  1182  1182 D KeyguardEffectViewController: isPreloadedWallpaper=true
08-16 17:57:53.889  1182  1182 I GeometricMosaic_Keyguard: update
08-16 17:57:53.889  1182  1182 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
08-16 17:57:53.899  6547  6547 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 17:57:53.899  6547  6547 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-16 17:57:53.919   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-16 17:57:53.919  1019  4803 D InputDispatcher: Focus entered window: 6547
,08-16 17:57:53.929  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:57:53.929  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:57:53.929  6547  6547 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 17:57:53.929  6547  6627 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 17:57:53.939  6547  6627 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-16 17:57:53.939  6547  6627 D OpenGLRenderer: Enabling debug mode 0
,08-16 17:57:53.969  1019  1752 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 17:57:53.969  6614  6614 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-16 17:57:53.969  1019  6636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:57:53.979  6614  6614 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-16 17:57:53.979  1019  4459 I ActivityManager: Killing 6225:com.samsung.helphub/1000 (adj 15): empty #21
,08-16 17:57:53.989  6547  6547 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-16 17:57:53.989  6547  6547 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@15b8d2a9 time:93725
,08-16 17:57:53.989  1019  1049 I ActivityManager: Displayed Component not be shown by security: +930ms (total +1s42ms)
,08-16 17:57:53.989  1019  1049 W ActivityManager: mDVFSHelper.release()
,08-16 17:57:53.989  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2efb4a92 u0 com.test.thalitest/.MainActivity t163} time:93728
,08-16 17:57:53.999   258   434 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-16 17:57:53.999   258  6102 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-16 17:57:54.019  1019  1125 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:57:54.019  1019  1125 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,08-16 17:57:54.029  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:54.029  1019  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:57:54.029  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:57:54.029  1879  1879 I SamsungIME: getCurrentCandidateView
,08-16 17:57:54.039  1182  1182 I KeyguardEffectViewUtil: set current wallpaper info
,08-16 17:57:54.039  1019  1490 D SettingsProvider: name = keyguard_current_wallpaper_type
08-16 17:57:54.039  1019  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:57:54.039  1019  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:57:54.039  1019  1490 D SettingsProvider: selectionArgs: false
08-16 17:57:54.039  1019  1490 D SettingsProvider: selectionArgs: 10049
08-16 17:57:54.039  1019  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:57:54.039  1019  1490 D SettingsProvider: ret = -1
,08-16 17:57:54.079  1019  1490 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,08-16 17:57:54.079  1019  1449 D SettingsProvider: name = keyguard_current_wallpaper_file_path
,08-16 17:57:54.079  1019  1449 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:57:54.079  1019  1449 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:57:54.079  1019  1449 D SettingsProvider: selectionArgs: false
,08-16 17:57:54.079  1019  1449 D SettingsProvider: selectionArgs: 10049
08-16 17:57:54.089  1019  1449 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:57:54.089  1019  1449 D SettingsProvider: ret = -1
,08-16 17:57:54.089  1019  1499 I ActivityManager: Killing 6195:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-16 17:57:54.099  1019  1444 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:57:54.099  1019  1444 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
08-16 17:57:54.099  1019  1444 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:57:54.099  1019  1444 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:57:54.099  1019  1444 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:57:54.119  2850  2850 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Aug 16 17:57:54 GMT+02:00 2016
,08-16 17:57:54.119  1019  1449 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,08-16 17:57:54.119  1019  1491 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-16 17:57:54.119  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 17:57:54.119  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:54.129  1019  1752 D SettingsProvider: name = keyguard_current_wallpaper_res_id
,08-16 17:57:54.129  1019  1752 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:57:54.129  1019  1752 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:57:54.129  1019  1752 D SettingsProvider: selectionArgs: false
08-16 17:57:54.129  1019  1752 D SettingsProvider: selectionArgs: 10049
08-16 17:57:54.129  1019  1752 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:57:54.129  1019  1752 D SettingsProvider: ret = -1
,08-16 17:57:54.129  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:57:54.129  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 17:57:54.139  1019  1752 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,08-16 17:57:54.139  2850  2850 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-16 17:57:54.139  1019  1449 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-16 17:57:54.149  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:54.149  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:54.149  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:54.149  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:54.159  6643  6643 E Zygote  : MountEmulatedStorage(),
08-16 17:57:54.159  6643  6643 E Zygote  : v2
,08-16 17:57:54.159  1019  1449 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6643 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:57:54.159  6643  6643 I libpersona: KNOX_SDCARD checking this for 10036
08-16 17:57:54.159  6643  6643 I libpersona: KNOX_SDCARD not a persona
,08-16 17:57:54.169  6643  6643 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:57:54.169  6643  6643 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:57:54.169  6643  6643 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-16 17:57:54.169  2850  2850 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-16 17:57:54.179  2850  2850 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 17:57:54.189  2850  2850 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 17:57:54.189  2850  6642 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-16 17:57:54.199  2850  6642 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-16 17:57:54.199  6643  6643 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:57:54.199  6643  6643 D ActivityThread: Added TimaKeyStore provider
,08-16 17:57:54.209  2850  6642 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Tue Aug 16 17:57:54 GMT+02:00 2016
,08-16 17:57:54.219  6547  6547 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6547
,08-16 17:57:54.219  2850  6642 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,08-16 17:57:54.219  2850  2850 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-16 17:57:54.229  1182  1609 D TEST    : run!!!
,08-16 17:57:54.229  1879  1879 D SamsungIME: Dismiss ExpandCandiate
,08-16 17:57:54.249  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
,08-16 17:57:54.249  1182  1182 D PanelView: There is/are notification(s) 
,08-16 17:57:54.249  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 17:57:54.259  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-16 17:57:54.259  1182  1609 I GeometricMosaic_Renderer: setBackgroundBitmap
,08-16 17:57:54.269  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 17:57:54.279  6643  6643 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@24387164
,08-16 17:57:54.279  1182  1182 D KeyguardEffectViewController: isPreloadedWallpaper=true
,08-16 17:57:54.299  6643  6643 I SA      : [SSP] onCreated
,08-16 17:57:54.319  6280  6280 I Mms/MmsApp:  start initViewCache mms
,08-16 17:57:54.319  6280  6280 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1938.303749
,08-16 17:57:54.319  6280  6280 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-16 17:57:54.329  6643  6643 I SA      : [TPM] There is no property file
,08-16 17:57:54.329  6643  6643 I SA      : [SCU] isHaveSA() - false
,08-16 17:57:54.349  6643  6643 I SA      : [TPM] getModelProperty : null
,08-16 17:57:54.349  6643  6643 I SA      : [TPM] getCSCProperty : null
,08-16 17:57:54.369  6643  6643 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-16 17:57:54.369  6643  6643 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-16 17:57:54.369  6643  6643 I SA      : [DM] TFT FEATURE: false
,08-16 17:57:54.389  6643  6643 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-16 17:57:54.389  6643  6643 I SA      : [DM] init START
,08-16 17:57:54.389  6643  6643 I SA      : [DM] This device is not a Vodafone
,08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-16 17:57:54.399  6643  6643 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-16 17:57:54.399  6643  6643 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-16 17:57:54.409  6643  6643 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-16 17:57:54.419  6643  6643 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-16 17:57:54.419  6643  6643 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-16 17:57:54.419  6643  6643 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-16 17:57:54.419  6643  6643 I SA      : [SCU] isHaveSA() - false
08-16 17:57:54.419  6643  6643 I SA      : support phone number id : false
08-16 17:57:54.419  6643  6643 I SA      : [DM] Supports Ref Jpn : true
,08-16 17:57:54.419  6643  6643 I SA      : [DM] init END
,08-16 17:57:54.459  6280  6280 D AbsListView: Get MotionRecognitionManager
,08-16 17:57:54.459  1019  4459 D MotionRecognitionService:  ssp status : false
,08-16 17:57:54.469  6280  6280 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 145.897708
,08-16 17:57:54.499  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 17:57:54.519  6547  6547 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 17:57:54.539  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 17:57:54.559  6280  6280 D Mms/BubbleViewCache: fillCache bubble = 1
,08-16 17:57:54.559  1879  1879 I SamsungIME: KeybaordView init() : load resources
,08-16 17:57:54.569  1019  1444 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-16 17:57:54.569  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:54.569  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:54.569  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:54.569  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:54.579  6667  6667 E Zygote  : MountEmulatedStorage()
08-16 17:57:54.579  6667  6667 E Zygote  : v2
08-16 17:57:54.579  6667  6667 I libpersona: KNOX_SDCARD checking this for 10058
08-16 17:57:54.579  6667  6667 I libpersona: KNOX_SDCARD not a persona
,08-16 17:57:54.579  1019  1444 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6667 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:57:54.589  1019  1444 I ActivityManager: Killing 5608:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-16 17:57:54.589  6667  6667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:57:54.589  6667  6667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 17:57:54.599  6667  6667 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:57:54.599  1879  1879 I SamsungIME: getCurrentKeyboard
08-16 17:57:54.599  1879  1879 I SamsungIME: getTextKeyboard
,08-16 17:57:54.619  6667  6667 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:57:54.619  6667  6667 D ActivityThread: Added TimaKeyStore provider
,08-16 17:57:54.629  6547  6639 D jxcore_app_log: JniHelper::setJavaVM(0xb7c132b0), pthread_self() = -1206257464
,08-16 17:57:54.629  1879  1879 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 17:57:54.639  6547  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 17:57:54.639  6547  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 17:57:54.639  6547  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 17:57:54.639  6547  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 17:57:54.639  6547  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 17:57:54.639  6547  6639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38d8cd92 added. We now have 1 listener(s)
,08-16 17:57:54.639  6547  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-16 17:57:54.639  6547  6639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-16 17:57:54.649  6547  6639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:57:54.649  6547  6639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 17:57:54.649  6547  6639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8eb819 added. We now have 1 listener(s)
,08-16 17:57:54.649  6547  6639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:57:54.659  6547  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-16 17:57:54.659  6547  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 17:57:54.659  6547  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 17:57:54.659  6547  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
08-16 17:57:54.659  6547  6639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 17:57:54.659  6547  6639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:57:54.669  6547  6639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-16 17:57:54.679  6547  6639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 17:57:54.679  6547  6639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:57:54.679  6547  6639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:57:54.679  6547  6639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:57:54.679  6547  6639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:57:54.679  6547  6639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:57:54.679  6547  6639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:57:54.679  6547  6639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:57:54.679  6547  6639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:57:54.679  6547  6639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-16 17:57:54.679  6547  6639 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:57:54.679  6547  6639 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 17:57:54.679  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:57:54.679  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:57:54.679  6667  6667 I ExternalOEMControlProvider: onCreate
,08-16 17:57:54.699  6667  6684 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-16 17:57:54.709  1019  1031 I ActivityManager: Killing 5794:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-16 17:57:54.719  1822  1822 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-16 17:57:54.719  1822  1822 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-16 17:57:54.719  1019  1444 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-16 17:57:54.719  6547  6547 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 17:57:54.729  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:54.729  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:54.729  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:54.729  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:54.749  1019  1444 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6685 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:57:54.749  6685  6685 E Zygote  : MountEmulatedStorage()
08-16 17:57:54.749  6685  6685 E Zygote  : v2
08-16 17:57:54.749  6685  6685 I libpersona: KNOX_SDCARD checking this for 10081
08-16 17:57:54.749  6685  6685 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:54.749  6685  6685 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:57:54.759  6685  6685 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 17:57:54.759  6685  6685 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:57:54.779   307   307 I art     : Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 39.045ms
,08-16 17:57:54.789  6685  6685 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:57:54.789  6685  6685 D ActivityThread: Added TimaKeyStore provider
,08-16 17:57:54.799   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 19.249ms
,08-16 17:57:54.819   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 623us total 17.059ms
,08-16 17:57:54.829  6685  6685 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-16 17:57:54.829  6685  6685 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:57:54.829  6685  6685 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:57:54.829  6685  6685 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:57:54.829  6685  6685 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-16 17:57:54.879  1019  4803 D SettingsProvider: name = next_alarm_formatted
,08-16 17:57:54.879  1019  4803 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:57:54.879  1019  4803 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:57:54.879  1019  4803 D SettingsProvider: selectionArgs: false
,08-16 17:57:54.879  1019  4803 D SettingsProvider: selectionArgs: 10081
08-16 17:57:54.879  1019  4803 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:57:54.879  1019  4803 D SettingsProvider: ret = -1
,08-16 17:57:55.009  6249  6299 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-16 17:57:55.029  6249  6299 I AcmsKeyStoreHelper: Key Store exist
,08-16 17:57:55.029  6249  6299 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-16 17:57:55.079  1019  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-16 17:57:55.079  6249  6299 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-16 17:57:55.079  6249  6299 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-16 17:57:55.079  6249  6299 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-16 17:57:55.079  6249  6299 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-16 17:57:55.079  6249  6299 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-16 17:57:55.079  6249  6299 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-16 17:57:55.089  6249  6299 D AcmsCore: This is NOT a valid MirrorLink app
08-16 17:57:55.089  6249  6299 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-16 17:57:55.089  6249  6299 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-16 17:57:55.089  6249  6299 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-16 17:57:55.089  6249  6299 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-16 17:57:55.089  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.089  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.089  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.089  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.099  6700  6700 E Zygote  : MountEmulatedStorage(),
08-16 17:57:55.099  6700  6700 I libpersona: KNOX_SDCARD checking this for 10090
08-16 17:57:55.099  6700  6700 E Zygote  : v2
08-16 17:57:55.099  6700  6700 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:55.099  6700  6700 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:57:55.099  6700  6700 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:57:55.099  1019  1491 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6700 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
08-16 17:57:55.109  1019  1491 I ActivityManager: Killing 5879:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-16 17:57:55.109  6700  6700 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:57:55.109  6249  6249 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-16 17:57:55.109  6249  6249 D AcmsService: Enter onDestroy
,08-16 17:57:55.109  6249  6249 I AcmsService: cleanUp(): inside service clean up
08-16 17:57:55.109  6249  6249 D AcmsCore: AcmsCore: inside DeInit
08-16 17:57:55.109  6249  6249 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,08-16 17:57:55.109  6249  6249 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,08-16 17:57:55.109  6249  6249 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-16 17:57:55.109  6249  6249 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-16 17:57:55.109  6249  6249 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-16 17:57:55.109  6249  6249 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-16 17:57:55.109  6249  6249 D AcmsService: killing acms process
08-16 17:57:55.119  6249  6249 I Process : Sending signal. PID: 6249 SIG: 9
,08-16 17:57:55.119  6700  6700 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:57:55.119  6700  6700 D ActivityThread: Added TimaKeyStore provider
,08-16 17:57:55.149  6700  6700 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-16 17:57:55.149  6700  6700 D elm:15121: ELMEngine.ELMEngine( context ).
,08-16 17:57:55.159  6700  6700 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-16 17:57:55.159  1019  1490 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-16 17:57:55.159  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-16 17:57:55.159  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:57:55.159  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:57:55.159  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-16 17:57:55.159  6700  6700 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-16 17:57:55.159  1019  1317 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-16 17:57:55.159  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.169  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.169  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.169  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.169  6700  6700 D elm:15121: ElmAgentService : onCreate()
,08-16 17:57:55.169  6700  6716 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,08-16 17:57:55.179  6700  6716 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,08-16 17:57:55.179  6700  6700 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,08-16 17:57:55.179  6700  6700 D elm:15121: ModuleBase.ModifySetAlarm()
08-16 17:57:55.179  6700  6700 D elm:15121: MDMBridge.getInstance()
,08-16 17:57:55.179  6700  6700 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 17:57:55.189  6719  6719 E Zygote  : MountEmulatedStorage()
08-16 17:57:55.189  6719  6719 I libpersona: KNOX_SDCARD checking this for 10130
08-16 17:57:55.189  6719  6719 E Zygote  : v2
08-16 17:57:55.189  6719  6719 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:55.189  6719  6719 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:57:55.199  6719  6719 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:57:55.199  1019  1317 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6719 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,08-16 17:57:55.199  6719  6719 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-16 17:57:55.199  6700  6700 D elm:15121: ElmAgentService : onDestroy().
08-16 17:57:55.199  1019  1448 I ActivityManager: Process ACMS.Process (pid 6249)(adj 0) has died(32,766)
,08-16 17:57:55.199  1019  1317 I ActivityManager: Killing 6265:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-16 17:57:55.219  6719  6719 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:57:55.219  6719  6719 D ActivityThread: Added TimaKeyStore provider
,08-16 17:57:55.229   288   288 E SMD     : DCD OFF
,08-16 17:57:55.239  6719  6719 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:57:55.239  6719  6719 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-16 17:57:55.259  1019  1449 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-16 17:57:55.259  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.259  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.259  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.259  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.269  6734  6734 E Zygote  : MountEmulatedStorage()
08-16 17:57:55.269  6734  6734 E Zygote  : v2
08-16 17:57:55.269  6734  6734 I libpersona: KNOX_SDCARD checking this for 10131,
08-16 17:57:55.269  6734  6734 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:55.269  6734  6734 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:57:55.269  6734  6734 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 17:57:55.269  1019  1449 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6734 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-16 17:57:55.269  6734  6734 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:57:55.269  1019  1449 I ActivityManager: Killing 6304:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-16 17:57:55.289  6734  6734 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:57:55.289  6734  6734 D ActivityThread: Added TimaKeyStore provider
08-16 17:57:55.289  6547  6683 W jxcore-log: Initializing JXcore engine
08-16 17:57:55.289  6547  6683 W jxcore-log: JXcore engine is ready
,08-16 17:57:55.319  6734  6734 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 17:57:55.329  6734  6734 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:57:55.329  6734  6734 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:57:55.359  1019  1490 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-16 17:57:55.359  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-16 17:57:55.359  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:55.359  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:57:55.359  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-16 17:57:55.359  2018  2018 E audit   : type=1400 msg=audit(1471363075.359:205): avc:  denied  { ioctl } for  pid=6683 comm="Thread-1215" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 17:57:55.359  2018  2018 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:57:55.359  2018  2018 E audit   : type=1300 msg=audit(1471363075.359:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f33f8f8 items=0 ppid=307 ppcomm=main pid=6683 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1215" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-16 17:57:55.359  2018  2018 E audit   : type=1320 msg=audit(1471363075.359:205): 
,08-16 17:57:55.369  6547  6683 W jxcore-log: Starting JXcore engine
,08-16 17:57:55.379  2694  2703 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings,
,08-16 17:57:55.389  1019  1032 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-16 17:57:55.389  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-16 17:57:55.389  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:55.389  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:57:55.389  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-16 17:57:55.389  1019  1125 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-16 17:57:55.389  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.389  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.389  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.389  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.409  6754  6754 E Zygote  : MountEmulatedStorage()
,08-16 17:57:55.409  6754  6754 E Zygote  : v2
08-16 17:57:55.409  6754  6754 I libpersona: KNOX_SDCARD checking this for 10037
08-16 17:57:55.409  6754  6754 I libpersona: KNOX_SDCARD not a persona
,08-16 17:57:55.409  6754  6754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-16 17:57:55.409  1019  1125 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6754 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:57:55.409  6754  6754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 17:57:55.409  6754  6754 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-16 17:57:55.409  1019  1737 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-16 17:57:55.419  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.419  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.419  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.419  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.429  6765  6765 E Zygote  : MountEmulatedStorage()
08-16 17:57:55.429  6765  6765 E Zygote  : v2
08-16 17:57:55.429  6765  6765 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:57:55.429  6765  6765 I libpersona: KNOX_SDCARD not a persona
,08-16 17:57:55.429  6765  6765 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:57:55.439  6765  6765 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 17:57:55.439  1019  1737 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=6765 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 17:57:55.439  6754  6754 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:57:55.439  6765  6765 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 17:57:55.439  6754  6754 D ActivityThread: Added TimaKeyStore provider
,08-16 17:57:55.459  6754  6754 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-16 17:57:55.469  6765  6765 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:57:55.469  6765  6765 D ActivityThread: Added TimaKeyStore provider
,08-16 17:57:55.499  6547  6683 W jxcore-log: Platform android
08-16 17:57:55.499  6547  6683 W jxcore-log: 
08-16 17:57:55.499  6547  6683 W jxcore-log: Process ARCH arm
08-16 17:57:55.499  6547  6683 W jxcore-log: 
,08-16 17:57:55.499  6754  6754 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-16 17:57:55.509  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:57:55.509  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:57:55.509  6765  6765 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:57:55.519  1019  4803 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-16 17:57:55.519  1019  4803 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.519  1019  4803 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.519  1019  4803 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.519  1019  4803 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.529  6787  6787 E Zygote  : MountEmulatedStorage()
08-16 17:57:55.529  6787  6787 E Zygote  : v2
08-16 17:57:55.529  6787  6787 I libpersona: KNOX_SDCARD checking this for 10153
08-16 17:57:55.529  6787  6787 I libpersona: KNOX_SDCARD not a persona
,08-16 17:57:55.529  6787  6787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:57:55.539  6787  6787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:57:55.539  1019  4803 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6787 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,08-16 17:57:55.539  1019  4803 I ActivityManager: Killing 6323:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
08-16 17:57:55.539  6787  6787 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:57:55.569  6787  6787 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:57:55.569  6787  6787 D ActivityThread: Added TimaKeyStore provider
,08-16 17:57:55.589  6787  6787 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:57:55.589  1019  1490 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-16 17:57:55.589  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-16 17:57:55.599  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:55.599  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:57:55.599  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-16 17:57:55.599  1019  1499 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-16 17:57:55.609  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.609  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:55.609  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.609  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:57:55.619  6805  6805 E Zygote  : MountEmulatedStorage(),
,08-16 17:57:55.619  6805  6805 E Zygote  : v2
08-16 17:57:55.619  6805  6805 I libpersona: KNOX_SDCARD checking this for 1000
,08-16 17:57:55.619  6805  6805 I libpersona: KNOX_SDCARD not a persona
,08-16 17:57:55.619  6805  6805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:57:55.629  1019  1499 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6805 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-16 17:57:55.629  1019  1499 I ActivityManager: Killing 6348:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
08-16 17:57:55.629  6805  6805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:57:55.629  6805  6805 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:57:55.649  6805  6805 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:57:55.649  6805  6805 D ActivityThread: Added TimaKeyStore provider
,08-16 17:57:55.679  1019  1032 I ActivityManager: Killing 6369:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-16 17:57:55.679  6805  6805 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1471363075697
,08-16 17:57:55.679  6805  6805 D         : TimeServiceNative: User Time to be set is 1471363075698
08-16 17:57:55.679  6805  6805 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-16 17:57:55.679  6805  6805 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-16 17:57:55.679  6805  6805 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1471363075698
,08-16 17:57:55.689   322   560 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-16 17:57:55.689  6805  6805 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-16 17:57:55.689   322  6821 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1471363075698
08-16 17:57:55.689   322  6821 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1471363075698, operation = 0
08-16 17:57:55.689   322  6821 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/11/71 9:40:52
08-16 17:57:55.689   322  6821 D QC-time-services: Daemon:Value read from RTC seconds = 35113252000
08-16 17:57:55.689   322  6821 D QC-time-services: Daemon:new time 1471363075698 
08-16 17:57:55.689   322  6821 D QC-time-services: Daemon: delta 1436249823698 genoff 1436249823698 
08-16 17:57:55.689   322  6821 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249823698 to memory
08-16 17:57:55.689   322  6821 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-16 17:57:55.689   322  6821 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-16 17:57:55.689  6547  6683 I jxcore-log: JXcore Cordova bridge is ready!
08-16 17:57:55.689  6547  6683 I jxcore-log: 
,08-16 17:57:55.699  6547  6683 W jxcore-log: JXcore engine is started
,08-16 17:57:55.699  6547  6639 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 17:57:55.699  6547  6547 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 17:57:55.709   322  6821 D QC-time-services: Updating the TOD offset
08-16 17:57:55.709   322  6821 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249823698 to memory
08-16 17:57:55.709   322  6821 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-16 17:57:55.709   322  6821 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-16 17:57:55.709   322  6821 E QC-time-services: Daemon:Update to modem bit set
08-16 17:57:55.709  6805  6805 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-16 17:57:55.709   322  6821 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-16 17:57:55.709   322  6821 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285023698
,08-16 17:57:55.709  1019  4803 I ActivityManager: Killing 6417:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-16 17:57:55.709   322   558 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-16 17:57:55.709   322   560 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-16 17:57:55.719  2694  2694 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-16 17:57:55.719  2694  2694 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-16 17:57:55.719  2694  2694 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-16 17:57:55.729  2694  2694 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-16 17:57:55.729  2694  2694 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-16 17:57:55.729  2694  2694 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-16 17:57:55.729  2694  2694 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-16 17:57:55.729  2694  2694 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,08-16 17:57:55.739  2694  2694 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,08-16 17:57:55.739  2694  2694 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-16 17:57:55.739  2694  2694 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
08-16 17:57:55.739  2694  2694 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-16 17:57:55.739  2694  2694 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-16 17:57:55.749  2694  2694 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-16 17:57:55.749  2694  2694 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-16 17:57:55.749  2694  2694 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-16 17:57:55.749  2694  2694 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-16 17:57:55.749  2694  2694 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-16 17:57:55.759  2694  2694 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-16 17:57:55.759  2694  2694 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-16 17:57:56.139  1019  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:57:56.139  1019  1032 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4210, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-16 17:57:56.139  1019  1032 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-16 17:57:56.139  1019  1032 D BatteryService: stay LED for charging
08-16 17:57:56.139  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:57:56.149  1019  1019 I MotionRecognitionService: Plugged
,08-16 17:57:56.149  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:57:56.149  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:57:56.149  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 17:57:56.149  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 17:57:56.149  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 17:57:56.159  3214  3214 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-16 17:57:56.159  3214  3369 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:57:56.179  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 17:57:56.179  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 17:57:56.179  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 17:57:56.179  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-16 17:57:56.179  1182  1182 D SViewCoverView: level :100 plugged : 2
,08-16 17:57:56.599  6754  6754 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-16 17:57:56.599  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:56.599  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:57:56.599  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-16 17:57:56.609  1019  1448 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-16 17:57:56.609  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:56.609  1019  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:57:56.609  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-16 17:57:56.619  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:56.619  1019  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:57:56.619  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-16 17:57:56.619  1019  1752 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-16 17:57:56.619  1019  1752 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-16 17:57:56.619  1019  1752 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:56.629  1019  1752 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:57:56.629  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-16 17:57:56.629  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:56.629  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:57:56.629  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-16 17:57:56.639  1019  1031 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-16 17:57:56.639  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-16 17:57:56.639  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:57:56.639  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:57:56.639  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-16 17:57:56.649  1019  1491 I ActivityManager: Killing 6390:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-16 17:57:57.709   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7ebb7c8,
08-16 17:57:57.709   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-16 17:57:57.709   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-16 17:57:57.709   273   353 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1209288568)
,08-16 17:57:57.749   273   353 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-16 17:57:57.749   273   353 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,08-16 17:57:57.749   273   353 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1209288568) wakelock released: 1, error no: 0
08-16 17:57:57.749   273   353 I rmt_storage: 
,08-16 17:57:57.749   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7ebb7c8
,08-16 17:57:58.009  2634  2634 I ConfigService: onDestroy
,08-16 17:57:58.229   288   288 E SMD     : DCD OFF,
,08-16 17:57:58.859  1019  3411 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:57:59.989  1019  1097 V AlarmManager: waitForAlarm result :8
,08-16 17:58:01.229   288   288 E SMD     : DCD OFF
,08-16 17:58:02.879  1019  1058 D PackageManager: [MSG] MCS_UNBIND
,08-16 17:58:02.879  1019  1449 I ActivityManager: Killing 6446:com.sec.pcw.device/1000 (adj 15): empty #21
,08-16 17:58:02.949  1019  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-16 17:58:03.129  1019  3382 D SSRM:n  : SIOP:: AP = 390
,08-16 17:58:03.859  1019  3411 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:58:04.229   288   288 E SMD     : DCD OFF,
,08-16 17:58:06.189  1019  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:58:06.189  1019  1490 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-16 17:58:06.189  1019  1490 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-16 17:58:06.189  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-16 17:58:06.189  1019  1490 D BatteryService: stay LED for charging
,08-16 17:58:06.189  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:58:06.189  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 17:58:06.199  1019  1019 I MotionRecognitionService: Plugged
08-16 17:58:06.199  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:58:06.199  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 17:58:06.199  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 17:58:06.209  3214  3214 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 17:58:06.209  3214  3369 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:58:06.219  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 17:58:06.219  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 17:58:06.219  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-16 17:58:06.219  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-16 17:58:06.219  1182  1182 D SViewCoverView: level :100 plugged : 2
,08-16 17:58:07.229   288   288 E SMD     : DCD OFF,
,08-16 17:58:07.379  1019  1097 V AlarmManager: waitForAlarm result :4
,08-16 17:58:07.379  1019  1097 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-16 17:58:07.379  1019  1019 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-16 17:58:07.389  1019  1019 V AlarmManagerEXT: <AppSync3 Whitelist>
08-16 17:58:07.389  1019  1019 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-16 17:58:07.389  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-16 17:58:07.389  1182  1182 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 17:58:07.399  1182  1182 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-16 17:58:07.409  1182  1182 D SecKeyguardClockView: HomeTimezone(): 1
,08-16 17:58:07.409  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:58:07.409  1182  1182 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-16 17:58:07.409  1182  1182 I KeyguardEffectViewController: *** don't update sliding image ***
,08-16 17:58:07.429  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:58:07.449  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:58:07.449  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:58:07.459  1182  1182 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-16 17:58:07.469  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:58:07.629  5825  5944 D Finsky  : [1050] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-16 17:58:07.629  5825  5825 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-16 17:58:08.429  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-16 17:58:08.429  6547  6683 I jxcore-log: 
,08-16 17:58:08.429  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-16 17:58:08.429  6547  6683 I jxcore-log: 
,08-16 17:58:08.439  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-16 17:58:08.439  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:08.439  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:08.439  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:08.439  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:08.439  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:08.439  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:08.439  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:08.439  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:08.439  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:58:08.439  6547  6683 I jxcore-log: 
,08-16 17:58:08.449  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 17:58:08.449  6547  6683 I jxcore-log: 
,08-16 17:58:08.519  1019  1333 E Watchdog: !@Sync 3
,08-16 17:58:08.879  6547  6683 D ExecuteNativeTests: Running unit tests
,08-16 17:58:08.969  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:08.969  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 added. We now have 2 listener(s)
,08-16 17:58:08.969  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 17:58:08.969  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:08.969  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:08.969  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:08.969  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 added. We now have 2 listener(s)
08-16 17:58:08.969  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:08.969  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:08.969  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:08.969  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:08.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:08.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:08.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:08.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:08.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:08.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:08.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:08.979  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:08.979  6547  6683 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:08.979  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:08.979  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:58:08.979  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:58:08.979  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:58:08.979  6547  6683 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 17:58:08.979  6547  6683 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:58:08.979  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:58:08.979  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:58:08.979  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:58:08.979  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:08.979  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:08.979  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:08.979  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:08.979  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:08.979  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:08.979  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:08.979  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 removed from the list
08-16 17:58:08.979  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:08.979  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 removed from the list
,08-16 17:58:08.979  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:08.979  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:08.979  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:08.979  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:08.979  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:08.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:08.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:08.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:08.989  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
,08-16 17:58:08.989  6547  6683 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 17:58:08.989  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:08.989  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:08.989  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:08.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:08.989  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:08.989  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:08.989  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:08.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:08.989  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:08.989  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:08.989  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:08.989  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:08.989  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:08.989  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:08.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:08.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:08.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:08.989  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
,08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:58:08.999  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:08.999  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:08.999  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:08.999  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:08.999  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:08.999  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:08.999  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:08.999  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:08.999  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:08.999  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:08.999  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bl,uetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:08.999  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:08.999  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:08.999  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:08.999  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:08.999  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:08.999  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:08.999  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:08.999  6547  6683 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:58:08.999  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:09.009  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:09.009  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.009  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.009  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.009  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:09.009  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.009  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.009  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.009  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:09.009  6547  6683 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:09.009  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:09.009  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:09.009  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:09.009  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.009  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:09.009  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.009  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:58:09.019  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.019  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:09.029  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:09.029  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-16 17:58:09.029  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-16 17:58:09.029  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:58:09.029  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:09.029  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:58:09.039  3214  3379 D BtGatt.GattService: registerClient() - UUID=cff32796-9397-4d5c-bde8-36bf0747b670
,08-16 17:58:09.079  3214  3295 D BtGatt.GattService: onClientRegistered() - UUID=cff32796-9397-4d5c-bde8-36bf0747b670, clientIf=6
,08-16 17:58:09.079  6547  6555 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:58:09.089  3214  3227 D BtGatt.GattService: start scan with filters
,08-16 17:58:09.089  3214  3367 D BtGatt.ScanManager: handling starting scan
,08-16 17:58:09.089  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:58:09.089  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:58:09.089  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:09.089  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:58:09.089  3214  3367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:09.089  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.089  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:58:09.089  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.089  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:09.099  6547  6683 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:58:09.099  3214  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:58:09.099  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.099  3214  3367 D BtGatt.ScanManager: allow scan with filters
08-16 17:58:09.099  3214  3367 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 17:58:09.099  3214  3367 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-16 17:58:09.109  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:09.109  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 17:58:09.109  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.109  3214  3367 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 17:58:09.109  3214  3367 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:58:09.109  6547  6683 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:58:09.109  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.109  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:58:09.109  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.109  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:09.109  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 17:58:09.109  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:09.109  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:09.109  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:58:09.109  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:09.109  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:58:09.119  3214  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:58:09.119  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.119  3214  3349 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:09.119  3214  3379 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:58:09.119  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:58:09.119  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.119  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:58:09.119  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:58:09.119  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:09.119  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 17:58:09.129  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:09.129  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:09.129  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:58:09.129  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:09.129  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:58:09.129  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:09.129  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.129  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.139  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:09.139  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.139  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.139  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:09.139  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.139  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.139  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.139  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.139  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.139  6547  6683 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:58:09.139  3214  3367 D BtGatt.ScanManager: filter size is 1
,08-16 17:58:09.139  3214  3367 D BtGatt.ScanManager: delete FilterIndex - 3
08-16 17:58:09.139  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:09.149  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:09.149  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.149  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.149  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.149  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:09.149  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.149  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.149  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.149  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:58:09.149  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.149  3214  3367 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:09.149  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:09.149  6547  6683 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:09.149  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:09.149  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:09.149  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:09.149  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.149  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:09.159  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:58:09.159  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.159  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 17:58:09.159  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.159  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.159  3214  3367 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:58:09.169  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:09.169  3214  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-16 17:58:09.169  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.169  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:09.179  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:58:09.179  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:09.179  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:58:09.179  3214  3379 D BtGatt.GattService: registerClient() - UUID=fa807710-f1f1-49b1-91c5-7490bbcb9a97
,08-16 17:58:09.219  3214  3295 D BtGatt.GattService: onClientRegistered() - UUID=fa807710-f1f1-49b1-91c5-7490bbcb9a97, clientIf=6
,08-16 17:58:09.219  6547  6556 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:58:09.219  3214  3227 D BtGatt.GattService: start scan with filters
,08-16 17:58:09.229  3214  3367 D BtGatt.ScanManager: handling starting scan
,08-16 17:58:09.229  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:58:09.229  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:58:09.229  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:09.229  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:58:09.229  3214  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 17:58:09.229  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.229  3214  3367 D BtGatt.ScanManager: allow scan with filters
08-16 17:58:09.229  3214  3367 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 17:58:09.239  3214  3367 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-16 17:58:09.239  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:09.239  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.239  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:58:09.239  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:09.239  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 17:58:09.239  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.239  3214  3367 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:09.239  3214  3367 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:58:09.249  6547  6683 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:58:09.249  3214  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:58:09.249  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.249  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:09.249  6547  6683 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:58:09.249  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.259  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:58:09.259  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:09.259  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:09.259  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 17:58:09.259  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:09.259  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:09.259  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:58:09.259  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,08-16 17:58:09.259  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:58:09.259  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.259   320   320 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-16 17:58:09.259   320   320 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-16 17:58:09.259  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:58:09.259  3214  3349 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:09.259  3214  3367 D BtGatt.ScanManager: filter size is 1
08-16 17:58:09.259  3214  3379 D BtGatt.GattService: unregisterClient() - clientIf=6
08-16 17:58:09.269  3214  3367 D BtGatt.ScanManager: delete FilterIndex - 4
,08-16 17:58:09.269  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:58:09.269  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:09.269  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 17:58:09.269  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:09.269  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:09.269  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:09.269  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:58:09.269  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:09.269  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:58:09.269  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:58:09.269  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:09.269  3214  3367 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:58:09.269  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:09.269  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:09.269  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.269  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:09.269  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.279  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:09.279  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:09.279  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.279  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.279  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.279  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.279  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-16 17:58:09.279  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.279  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.279  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:09.279  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.279  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:09.279  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
,08-16 17:58:09.279  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-16 17:58:09.279  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:09.279  3214  3367 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-16 17:58:09.279  6547  6683 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:58:09.279  3214  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-16 17:58:09.279  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:09.279  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:09.289  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:09.289  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.289  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.289  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.289  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:09.289  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.289  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.289  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.289  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:09.289  6547  6683 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:09.289  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.299  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:09.299  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:58:09.299  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:09.299  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.299  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:09.299  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.299  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:58:09.299  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:09.299  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:09.309  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:58:09.309  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:09.309  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:58:09.309  3214  3223 D BtGatt.GattService: registerClient() - UUID=d19ffc45-11b3-41b3-b344-d1c321e802e1
,08-16 17:58:09.359  3214  3295 D BtGatt.GattService: onClientRegistered() - UUID=d19ffc45-11b3-41b3-b344-d1c321e802e1, clientIf=6
,08-16 17:58:09.359  6547  6556 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:58:09.359  3214  3349 D BtGatt.GattService: start scan with filters
,08-16 17:58:09.359  3214  3367 D BtGatt.ScanManager: handling starting scan
,08-16 17:58:09.359  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:58:09.359  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:58:09.359  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:58:09.359  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:58:09.359  3214  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 17:58:09.359  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.359  3214  3367 D BtGatt.ScanManager: allow scan with filters
,08-16 17:58:09.359  3214  3367 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 17:58:09.359  3214  3367 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-16 17:58:09.369  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.369  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:58:09.369  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.369  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 17:58:09.369  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.369  3214  3367 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 17:58:09.369  3214  3367 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:58:09.369  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:09.379  6547  6683 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:58:09.379  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:09.379  6547  6683 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:58:09.379  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.379  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 17:58:09.379  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:09.379  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:58:09.379  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 17:58:09.379  3214  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:58:09.379  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.389  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:09.389  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:09.389  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:09.389  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:09.389  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:58:09.389  3214  3223 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:09.389  3214  3349 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:58:09.389  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:58:09.389  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:58:09.389  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:58:09.389  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.399  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:09.399  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:09.399  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:09.399  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:09.399  3214  3367 D BtGatt.ScanManager: filter size is 1
08-16 17:58:09.399  3214  3367 D BtGatt.ScanManager: delete FilterIndex - 5
,08-16 17:58:09.399  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:58:09.399  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:09.399  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:58:09.399  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:09.399  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:09.399  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.399  6547  6683 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:58:09.399  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.399  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.399  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.399  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.399  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:09.399  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.399  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.399  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.399  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.399  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.399  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.399  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:09.399  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.399  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.399  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:58:09.399  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.399  3214  3367 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:58:09.399  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.399  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.399  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.399  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
,08-16 17:58:09.409  6547  6683 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 17:58:09.409  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.409  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.409  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.409  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.409  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.409  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.409  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.409  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.409  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.409  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.409  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.409  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.409  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
,08-16 17:58:09.409  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 17:58:09.409  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.409  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.409  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.409  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.409  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.409  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
,08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.409  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.409  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.409  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:09.409  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.409  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.409  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.409  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:58:09.409  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.409  3214  3367 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:09.409  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.409  6547  6683 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 17:58:09.409  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.409  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:09.409  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-16 17:58:09.409  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.409  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.409  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.409  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.409  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.409  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.409  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.409  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.409  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.409  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.419  3214  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:58:09.419  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.419  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
,08-16 17:58:09.419  6547  6683 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 17:58:09.419  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.419  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.419  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.419  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.419  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.419  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.419  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.419  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.419  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.419  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.419  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.419  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:09.419  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
,08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 17:58:09.419  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:58:09.419  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:58:09.419  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:58:09.419  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:09.419  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.419  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.419  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:09.419  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.419  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.419  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.419  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.419  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.419  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.419  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.429  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.429  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.429  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:09.429  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:09.429  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.429  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
,08-16 17:58:09.429  6547  6683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:09.429  6547  6683 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 17:58:09.429  6547  6683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:09.429  6547  6683 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-16 17:58:09.429  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:58:09.439  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-16 17:58:09.439  6547  6683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 17:58:09.439  6547  6683 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:58:09.439  6547  6683 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 17:58:09.439  6547  6683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:09.439  6547  6683 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:58:09.439  6547  6683 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 17:58:09.439  6547  6683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:09.439  6547  6683 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:58:09.439  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 17:58:09.439  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 17:58:09.439  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 17:58:09.439  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 17:58:09.449  6547  6683 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 17:58:09.449  6547  6683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:09.449  6547  6683 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 17:58:09.449  6547  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1279)
08-16 17:58:09.449  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.449  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.449  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.449  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 17:58:09.449  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.449  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.449  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.449  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.449  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.449  6547  6835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1279
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.449  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.449  6547  6683 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 17:58:09.449  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.449  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.449  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.449  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.449  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.449  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.449  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.449  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.449  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.449  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.449  6547  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 17:58:09.449  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.449  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.449  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.449  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.449  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.449  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.449  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.449  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.449  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.449  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.449  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.449  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.459  6547  6834 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-16 17:58:09.459  6547  6683 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 17:58:09.459  6547  6683 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 17:58:09.459  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:58:09.459  6547  6683 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 17:58:09.459  6547  6683 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:58:09.459  6547  6683 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 17:58:09.459  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:58:09.459  6547  6683 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 17:58:09.459  6547  6683 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:58:09.459  6547  6683 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:58:09.459  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:58:09.459  6547  6683 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 17:58:09.459  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.459  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.459  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.459  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.459  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.459  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.459  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.459  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.459  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.459  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.459  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.459  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.459  6547  6834 D BluetoothSocket: connect(): myUserId = 0
08-16 17:58:09.459  6547  6834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.459  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.459  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.459  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.459  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.459  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.459  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.459  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.459  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.459  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.459  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.459  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.459  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.459  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.459  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.459  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.459  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.459  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.459  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.459  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.459  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.459  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.459  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.459  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.459  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.459  3214  3379 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.459  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.459  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.469  6547  6834 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 17:58:09.469  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:09.469  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.469  6547  6547 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 17:58:09.469  6547  6547 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 17:58:09.469  6547  6836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 17:58:09.469  6547  6836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:09.,469  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.469  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.469  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.469  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.469  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.469  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.469  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.469  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.469  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.469  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.469  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.469  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.469  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:09.469  6547  6547 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.469  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.469  6547  6683 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 17:58:09.469  6547  6683 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:58:09.469  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:58:09.469  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.469  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:09.469  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.469  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.469  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.469  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.469  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.469  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.469  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.469  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.469  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.469  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.479  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.479  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.479  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.479  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.479  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.479  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.479  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.479  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.479  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.479  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.479  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.479  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.479  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.479  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.479  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.479  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.479  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.479  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.479  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.479  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.479  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.479  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.479  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.479  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.479  6547  6683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5d0718 not in the list
08-16 17:58:09.479  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.479  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.479  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.479  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.479  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.479  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.479  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.479  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.479  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.479  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.479  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33558571 not in the list
08-16 17:58:09.479  6547  6683 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 17:58:09.479  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:58:09.479  6547  6683 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 17:58:09.479  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:58:09.479  6547  6683 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 17:58:09.479  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:58:09.479  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:58:09.479  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 17:58:09.479  6547  6683 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 17:58:09.479  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:58:09.479  6547  6683 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 17:58:09.479  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:58:09.479  6547  6683 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 17:58:09.479  6547  6683 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 17:58:09.489  6547  6683 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 17:58:09.489  6547  6683 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 17:58:09.489  6547  6683 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 17:58:09.489  6547  6683 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 17:58:09.489  6547  6683 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 17:58:09.489  6547  6683 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 17:58:09.489  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:09.489  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de818eb added. We now have 2 listener(s)
08-16 17:58:09.489  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:09.489  6547  6683 D BluetoothAdapter: enable()
08-16 17:58:09.489  6547  6683 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 17:58:09.489  1019  1449 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:58:09.489  1019  1449 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:58:09.489  1019  1449 D SecContentProvider2: mCursor = null
08-16 17:58:09.489  1019  1449 D WifiService: setWifiEnabled: true pid=6547, uid=10170
08-16 17:58:09.489  1019  1449 W ActivityManager: Permission Denial: getCurrentUser() from pid=6547, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:09.499  1019  1449 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:58:09.499  1019  1449 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6547, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:09.499  1019  1449 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 17:58:09.499  1019  1449 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:58:09.,499  1019  1449 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:58:09.499  1019  1449 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:58:09.499  1019  1449 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:58:09.499  1019  1449 D SettingsProvider: name = wifi_on
08-16 17:58:09.499  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:09.499  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@142c6648 added. We now have 3 listener(s)
08-16 17:58:09.499  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:09.499  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:09.499  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c1ace1 added. We now have 4 listener(s)
08-16 17:58:09.499  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:09.509  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:09.509  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19295a06 added. We now have 5 listener(s)
08-16 17:58:09.509  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:09.509  1019  1491 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:58:09.509  1019  1491 D WifiService: setWifiEnabled: false pid=6547, uid=10170
08-16 17:58:09.509  1019  1491 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:58:09.509  1019  1491 D SecContentProvider2: mCursor = null
08-16 17:58:09.509  1019  1491 D SettingsProvider: name = wifi_on
,08-16 17:58:09.519  1019  1130 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 17:58:09.519  6547  6683 D BluetoothAdapter: disable()
,08-16 17:58:09.519  1350  1350 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:58:09.519  1350  1350 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-16 17:58:09.519  1350  1350 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:58:09.519  1019  1499 D SettingsProvider: name = bluetooth_on
,08-16 17:58:09.519  1350  1350 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
,08-16 17:58:09.529  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:09.529  3214  3292 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-16 17:58:09.529  3214  3292 D BluetoothAdapterProperties: Setting state to 13
08-16 17:58:09.529  3214  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:58:09.529  3214  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:09.529  3214  3292 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 17:58:09.529  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:09.529  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:09.529  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-16 17:58:09.529  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:09.529  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:09.529  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:09.539  3214  3214 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-16 17:58:09.539  3214  3292 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:09.539  3214  3292 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 17:58:09.539  3214  3292 D BluetoothAdapterService: terminating service from this receiver
,08-16 17:58:09.539  3214  3214 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22e3b9af, channel: 19, state: LISTENING
08-16 17:58:09.539  3214  3214 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@22e3b9af, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35902ab7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9e391bcmSocket: android.net.LocalSocket@3fb48545 impl:android.net.LocalSocketImpl@38d5f49a fd:FileDescriptor[80]
,08-16 17:58:09.539  3214  3214 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3fb48545 impl:android.net.LocalSocketImpl@38d5f49a fd:FileDescriptor[80],
08-16 17:58:09.539  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:09.539  1019  1019 I InputMethodManagerService: [BT Setting State] State =13,
08-16 17:58:09.539  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.539  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:09.539  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.539  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.539  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.539  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:09.539  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.539  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
08-16 17:58:09.539  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.539  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.539  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.539  6547  6683 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:09.539  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.549  1350  1350 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-16 17:58:09.549  1350  1350 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-16 17:58:09.549  1350  1350 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
08-16 17:58:09.549  1019  1130 E WifiNative-wlan0: do suspend true
,08-16 17:58:09.549  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.549  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:58:09.549  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:58:09.549  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:09.549  1182  1182 D BluetoothTile:  getBluetoothState : 13
,08-16 17:58:09.549  1879  1879 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:09.559  4838  4838 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:09.569  1019  1737 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:09.569  1019  1490 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:58:09.569  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:58:09.569  1019  1125 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 17:58:09.569  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:09.569  1019  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:09.569  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:09.569  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.569  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:09.569  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.569  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.569  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.569  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:09.569  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.569  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.569  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:09.569  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:09.569  3214  3292 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:58:09.569  3214  3292 D BluetoothAdapterProperties: mDiscovering is false
,08-16 17:58:09.579  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:09.579  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:09.579  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:09.579  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:09.579  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:58:09.579  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.699  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:58:09.699  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:58:09.709   278  1017 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:58:09.709  2634  2671 V NativeCrypto: Read error: ssl=0xb81211e0: I/O error during system call, Connection timed out
,08-16 17:58:09.709  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:09.709  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 17:58:09.709  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.709  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.709  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.709  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:09.719  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-16 17:58:09.719  1019  1132 E ConnectivityService: updateNetworkInfo()
08-16 17:58:09.719  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:58:09.719  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,08-16 17:58:09.719  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:58:09.729  1019  1129 D WifiP2pService: InactiveState{ what=131204 }
,08-16 17:58:09.729  1019  1032 I art     : Explicit concurrent mark sweep GC freed 29161(1661KB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 23MB/34MB, paused 2.596ms total 172.200ms
08-16 17:58:09.729  1019  1129 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-16 17:58:09.729  1019  1499 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
08-16 17:58:09.729  1019  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:58:09.729  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-16 17:58:09.729  2634  2671 V NativeCrypto: SSL shutdown failed: ssl=0xb81211e0: I/O error during system call, Broken pipe
08-16 17:58:09.729  3214  3292 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 17:58:09.729  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
,08-16 17:58:09.739  1019  1153 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:09.739  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:09.739  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:09.739  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:09.739  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.739  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.739  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:09.739  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:09.739  1019  1019 D RttService: SCAN_AVAILABLE : 1
08-16 17:58:09.739  1019  1154 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:09.749  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 17:58:09.749  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
,08-16 17:58:09.749  3214  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:58:09.749  3214  3295 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:58:09.749  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 17:58:09.749  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-16 17:58:09.749  1019  1499 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-16 17:58:09.749  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:09.749  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.749  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.749  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.749  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:09.749  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:09.749  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:09.749  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.759  1019  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:09.759  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:58:09.759  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:58:09.759  1019  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:09.759  1019  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 17:58:09.759  1019  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:09.759  1019  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-16 17:58:09.759  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.759  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:09.759  1019  1727 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 17:58:09.759  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 17:58:09.759  1019  1727 I qtaguid : Tagging socket 347 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000
,08-16 17:58:09.759  1019  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 17:58:09.759  1019  1132 V NetworkStats: updateIfacesLocked()
,08-16 17:58:09.759  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:09.759  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:09.759  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-16 17:58:09.759  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:09.759  1019  1049 D WifiDisplayController: disconnect
08-16 17:58:09.759  1019  1049 D WifiDisplayController: updateConnection
08-16 17:58:09.759  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:09.759  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:09.759  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:09.759  3214  3214 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cbc41cb, channel: 5, state: LISTENING
08-16 17:58:09.759  3214  3214 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2cbc41cb, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3bf02224, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16360da8mSocket: android.net.LocalSocket@251d30c1 impl:android.net.LocalSocketImpl@288ec066 fd:FileDescriptor[82]
08-16 17:58:09.759  3214  3214 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@251d30c1 impl:android.net.LocalSocketImpl@288ec066 fd:FileDescriptor[82]
,08-16 17:58:09.759  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:58:09.759  3214  3214 I BtOppRfcommListener: stopping Accept Thread
,08-16 17:58:09.759  3214  3214 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@384b2fa7, channel: 12, state: LISTENING
08-16 17:58:09.759  3214  3214 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@384b2fa7, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d3a8d8e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22b25c54mSocket: android.net.LocalSocket@1b0b17fd impl:android.net.LocalSocketImpl@2fb67cf2 fd:FileDescriptor[86]
08-16 17:58:09.759  3214  3214 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b0b17fd impl:android.net.LocalSocketImpl@2fb67cf2 fd:FileDescriptor[86]
,08-16 17:58:09.759  3214  5335 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:58:09.759  3214  5335 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 17:58:09.769  1019  1129 D WifiP2pService: P2pDisablingState
08-16 17:58:09.769  1019  1132 V NetworkStats: performPollLocked() took 6ms
08-16 17:58:09.769  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:09.769  1019  1129 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 17:58:09.769  1019  1129 D WifiP2pService: p2p socket connection lost
08-16 17:58:09.769  1019  1130 E WifiNative-wlan0: do suspend true
08-16 17:58:09.769  1019  1129 D WifiP2pService: P2pDisabledState
08-16 17:58:09.769  1019  1727 I qtaguid : Untagging socket 347
08-16 17:58:09.769  1019  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-16 17:58:09.769  1019  1727 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 17:58:09.769  1019  1132 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:58:09.769  1182  1662 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 17:58:09.769  1019  1129 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:58:09.769  4838  4838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:58:09.769  3214  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 17:58:09.769  1019  1449 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:58:09.769  3214  3292 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-16 17:58:09.769   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 17:58:09.769   278  1011 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-16 17:58:09.769  3214  3292 E bt-btif : cmd socket is not created
08-16 17:58:09.769  3214  3296 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-16 17:58:09.769  6547  6834 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9c59ef4, channel: -1, state: INIT
08-16 17:58:09.769  6547  6834 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9c59ef4, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@44b361d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35f11092mSocket: android.net.LocalSocket@d9cba63 impl:android.net.LocalSocketImpl@1817b660 fd:FileDescriptor[105]
08-16 17:58:09.769  6547  6834 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d9cba63 impl:android.net.LocalSocketImpl@1817b660 fd:FileDescriptor[105]
08-16 17:58:09.769  6547  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1279)
,08-16 17:58:09.769  3214  3292 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 17:58:09.769  1019  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-16 17:58:09.769  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-16 17:58:09.779  1019  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-16 17:58:09.779  1019  1132 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-16 17:58:09.779  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 17:58:09.779  3214  3214 V BluetoothOppManager: cleanUp...
08-16 17:58:09.779  1019  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-16 17:58:09.779  1019  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-16 17:58:09.779  1019  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:09.779  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:09.779  1019  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:09.779  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:09.779  1470  1470 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:58:09.779  1470  1470 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 17:58:09.779  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.779  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:09.779  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.779  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.779  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.779  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:09.779  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:09.779  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:09.779  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.779  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.779  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:09.779  4838  4838 D BluetoothPbap: Proxy object disconnected
08-16 17:58:09.779  4838  4838 D PbapServerProfile: Bluetooth service disconnected
,08-16 17:58:09.779  3214  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:09.779  3214  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:09.779  3214  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:58:09.779  3214  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:09.779  3214  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:09.779  3214  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 17:58:09.789  3214  3296 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,08-16 17:58:09.789  3214  3296 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-16 17:58:09.789  3214  3296 W bt-btif : invalid rfc slot id: 4
,08-16 17:58:09.789  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:58:09.789  1019  1737 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-16 17:58:09.789  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:58:09.789  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-16 17:58:09.789  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:58:09.789  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:58:09.789  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:58:09.799  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:09.799  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:09.799  1019  1132 D ConnectivityService: nai.networkMonitor.doQuit()
08-16 17:58:09.799  1019  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-16 17:58:09.799  1019  1132 E ConnectivityService: updateNetworkInfo()
08-16 17:58:09.799  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:58:09.799  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-16 17:58:09.799  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-16 17:58:09.799  4838  4838 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:09.799  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
,08-16 17:58:09.799  1019  1133 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:58:09.799  1019  1127 V NetworkStats: updateIfacesLocked()
08-16 17:58:09.799  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:09.799  1019  1127 V NetworkStats: performPollLocked(flags=0x1),
08-16 17:58:09.799  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 17:58:09.799  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:58:09.809  1019  1127 V NetworkStats: performPollLocked() took 5ms
08-16 17:58:09.799  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
08-16 17:58:09.809  1019  1128 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 17:58:09.799  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:58:09.799  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:58:09.799  1182  1182 D StatusBar.NetworkController: updateDataNetType()
08-16 17:58:09.799  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:09.809  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:09.809  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:09.809  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 17:58:09.809  1019  1129 D WifiP2pService: P2pDisabledState{ what=143375 }
08-16 17:58:09.809  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-16 17:58:09.809  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:09.809  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:09.809  1019  1129 D WifiP2pService: DefaultState{ what=143375 }
,08-16 17:58:09.809  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 17:58:09.809  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-16 17:58:09.809  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-16 17:58:09.809  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-16 17:58:09.809  2634  2634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:09.809   278  1017 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:58:09.819  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:09.819  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:09.819  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:09.819  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:58:09.819  1350  1350 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-16 17:58:09.819  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:09.819  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:09.819  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.819  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.819  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.819  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:09.819  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:09.819  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:09.819  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:58:09.829  1019  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-16 17:58:09.829  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:09.829  1019  1130 D SecContentProvider2: mCursor = null,
08-16 17:58:09.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:09.829  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-16 17:58:09.829  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:09.829  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:09.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 17:58:09.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.829  4838  4838 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:09.839  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 17:58:09.839  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:09.839  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.839  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:09.839  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:09.839  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:09.839  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.839  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.839  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:09.839  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.839  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:09.839  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:09.839  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-16 17:58:09.839  1182  1182 D HotspotTile: onReceive : 0, 0
08-16 17:58:09.839  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:58:09.839  4838  4838 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:09.839  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:09.839  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:09.839  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.839  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:09.849  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:09.849  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 17:58:09.849  1019  1317 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-16 17:58:09.849  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:09.849  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:09.849  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:09.849  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:09.859  6847  6847 E Zygote  : MountEmulatedStorage()
,08-16 17:58:09.859  6847  6847 I libpersona: KNOX_SDCARD checking this for 10055,
,08-16 17:58:09.859  6847  6847 E Zygote  : v2
08-16 17:58:09.859  6847  6847 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:09.869  6847  6847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:09.869  6847  6847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:09.869  1019  1317 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6847 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-16 17:58:09.869  6847  6847 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:09.899  6847  6847 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-16 17:58:09.899  6847  6847 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:09.919  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.919  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.919  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.929  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.929  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.929  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.929  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.929  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.929  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.929  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.929  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.939  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.939  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.939  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.939  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.939  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.939  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.939  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.939  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 17:58:09.939  6847  6847 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-16 17:58:09.949  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.949  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.949  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.949  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.949  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.949  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.949  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.949  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-16 17:58:09.949  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.949  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:09.959  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:09.969  6547  6547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:58:09.969  3214  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 17:58:09.969  3214  3292 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:58:09.969  3214  3292 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-16 17:58:09.969  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,08-16 17:58:09.979  3214  3292 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-16 17:58:09.979  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:58:09.979  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 17:58:09.979  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-16 17:58:09.979  1019  1125 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:09.979  1019  1125 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 17:58:09.979  6847  6847 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-16 17:58:09.979  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:09.979  1019  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:09.979  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:09.979  6847  6847 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-16 17:58:09.979  6847  6847 D UserAnalysis: Create SecureDbHelper
08-16 17:58:09.979  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:58:09.979  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:09.989  3214  3214 D HeadsetService: Received stop request...Stopping profile...
,08-16 17:58:09.989  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:09.989  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:09.989  1019  1444 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:09.989  1019  1444 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:09.989  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 17:58:09.989  1019  1444 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:09.989  1019  1444 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:09.989  1019  1444 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:09.989  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-16 17:58:09.989  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:58:09.989  6847  6847 D IntelligenceServiceApplication: onCreate()
08-16 17:58:09.989  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:58:09.989  1019  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-16 17:58:09.989  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 17:58:09.999  1350  1350 I wpa_supplicant: Blacklist: Clear (all) 
08-16 17:58:09.999  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:09.999  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:09.999  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:09.999  4838  4838 D HeadsetProfile: Bluetooth service disconnected
08-16 17:58:09.999  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:58:09.999  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 17:58:09.999  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:58:09.999  1019  1448 I ActivityManager: Killing 6469:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-16 17:58:09.999  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:09.999  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:58:09.999  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:09.999  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:09.999  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:09.999  6847  6847 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-16 17:58:10.009  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-16 17:58:10.009  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 17:58:10.009  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:58:10.009  1019  1448 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-16 17:58:10.009  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:10.009  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.009  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-16 17:58:10.009  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.009  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.009  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:10.009  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:10.009  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:10.009  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:10.009  1019  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:10.009  1019  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-16 17:58:10.009  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.009  1019  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.009  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:10.009  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-16 17:58:10.009  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:10.009  3214  3292 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-16 17:58:10.009  1019  1125 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:10.009  1019  1125 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.019  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.019  1019  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.019  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:10.019  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:10.019  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:10.019  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:10.019  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:10.019  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:10.019  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:10.019  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:58:10.019  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 17:58:10.019  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService,
08-16 17:58:10.019  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:58:10.019  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:58:10.019  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-16 17:58:10.019  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:58:10.019  3214  3292 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 17:58:10.019  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-16 17:58:10.019  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:10.019  3214  3214 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 17:58:10.019  3214  3214 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 17:58:10.019  3214  3214 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:58:10.019  3214  3214 D A2dpService: Received stop request...Stopping profile...
08-16 17:58:10.019  3214  3371 D A2dpStateMachine: Exit Disconnected: -1
,08-16 17:58:10.029  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:10.029  4838  4838 D BluetoothA2dp: Proxy object disconnected
,08-16 17:58:10.029  4838  4838 D A2dpProfile: Bluetooth service disconnected
08-16 17:58:10.029  1019  1019 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:10.029  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 17:58:10.029  3214  3214 D HidService: Received stop request...Stopping profile...
,08-16 17:58:10.029  3214  3214 D HidService: Stopping Bluetooth HidService
,08-16 17:58:10.029  3214  3214 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...,
08-16 17:58:10.029  3214  3214 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 17:58:10.029  3214  3214 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:58:10.029  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
08-16 17:58:10.029  4838  4838 D BluetoothInputDevice: Proxy object disconnected
08-16 17:58:10.029  4838  4838 D HidProfile: Bluetooth service disconnected
08-16 17:58:10.029  3214  3214 D HealthService: Received stop request...Stopping profile...
,08-16 17:58:10.029  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef,
08-16 17:58:10.029  1019  1448 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-16 17:58:10.029  1019  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:10.029  1019  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.029  1019  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:10.029  1019  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.049  6880  6880 E Zygote  : MountEmulatedStorage()
08-16 17:58:10.049  6880  6880 I libpersona: KNOX_SDCARD checking this for 10105
08-16 17:58:10.049  6880  6880 E Zygote  : v2
,08-16 17:58:10.049  6880  6880 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:10.049  6880  6880 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:10.049  1019  1448 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6880 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-16 17:58:10.049  6880  6880 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:10.049  3214  3214 D PanService: Received stop request...Stopping profile...
,08-16 17:58:10.049  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:10.049  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected,
08-16 17:58:10.049  3214  3214 D BluetoothMapService: Received stop request...Stopping profile...
08-16 17:58:10.049  6880  6880 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 17:58:10.059  4838  4838 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:58:10.059  4838  4838 D PanProfile: Bluetooth service disconnected
,08-16 17:58:10.059  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:10.059  4838  4838 D BluetoothMap: Proxy object disconnected
08-16 17:58:10.059  4838  4838 D MapProfile: Bluetooth service disconnected
,08-16 17:58:10.059  3214  3214 D SapService: Received stop request...Stopping profile...,
08-16 17:58:10.059  3214  3214 D SapService: Stopping Bluetooth SapService
08-16 17:58:10.059  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:10.059  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-16 17:58:10.059  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:10.059  3214  3214 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 17:58:10.059  3214  3214 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:10.059  3214  3214 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-16 17:58:10.059  4838  4838 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 17:58:10.059  4838  4838 D SapProfile: Bluetooth service disconnected
08-16 17:58:10.059  3214  3372 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 17:58:10.059  3214  3214 I GKI_LINUX: GKI_exit_task 2 done
08-16 17:58:10.059  3214  3214 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 17:58:10.059  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 17:58:10.059  3214  3214 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 17:58:10.059  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.069  3214  3214 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:10.069  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 17:58:10.069  3214  3214 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 17:58:10.069  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.069  3214  3214 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:10.069  3214  3214 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:58:10.069  3214  3214 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:58:10.069  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 17:58:10.069  3214  3214 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 17:58:10.069  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.069  3214  3214 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.069  3214  3214 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-16 17:58:10.069  3214  3214 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:58:10.069  1350  1350 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-16 17:58:10.069  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 17:58:10.069  3214  3214 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 17:58:10.069  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:10.069  3214  3214 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-16 17:58:10.069  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-16 17:58:10.069  3214  3214 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-16 17:58:10.069  3214  3214 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 17:58:10.069  3214  3214 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-16 17:58:10.069  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:10.069  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:58:10.069  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:58:10.069  3214  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 17:58:10.069  3214  3292 D BluetoothAdapterProperties: Setting state to 10
08-16 17:58:10.069  3214  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 17:58:10.069  3214  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:10.069  3214  3292 D BluetoothAdapterService: updateAdapterState state is 10
08-16 17:58:10.069  3214  3292 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:10.069  3214  3292 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-16 17:58:10.069  3214  3292 I BluetoothAdapterState: Entering OffState
08-16 17:58:10.069  4838  4846 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 17:58:10.069  4838  4850 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 17:58:10.069  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:58:10.069  3214  3349 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:10.079  4838  4846 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.079  4838  4846 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:58:10.079  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.079  1019  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.079  4838  5529 D Bluetoothsap: onBluetoothStateChange: up=false
08-16 17:58:10.079  4838  5529 D Bluetoothsap: Unbinding service...,
08-16 17:58:10.079  1470  2712 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.079  1470  2712 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:58:10.079  1446  6878 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.079  1446  6878 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:58:10.079  6547  6556 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.079  6547  6556 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:58:10.079  6547  6556 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-16 17:58:10.079  6547  6556 D BluetoothLeAdvertiser: Exit stop advertising
08-16 17:58:10.079  6547  6556 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 17:58:10.079  6547  6556 D BluetoothLeScanner: Exiting stopAllScan
,08-16 17:58:10.079  4838  4846 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:10.079  1756  1765 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.079  1756  1765 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:58:10.079  1182  1845 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.079  1182  1845 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.089  1462  1475 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.089  1462  1475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:58:10.089  4838  4850 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:58:10.089  3214  3227 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.089  3214  3227 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.089  2634  4572 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.089  2634  4572 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.089  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:10.089  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
08-16 17:58:10.089  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:58:10.089  1350  1350 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
,08-16 17:58:10.099  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:10.099  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:10.099  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:10.099  1350  1350 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-16 17:58:10.099  1019  1133 D Tethering: InitialState.processMessage what=4
08-16 17:58:10.099  1350  1350 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-16 17:58:10.099  1350  1350 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 17:58:10.099  1350  1350 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-16 17:58:10.099  6880  6880 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:10.099  6880  6880 D ActivityThread: Added TimaKeyStore provider
08-16 17:58:10.099  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:58:10.099  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:10.099  1182  1182 D BluetoothTile:  getBluetoothState : 10
08-16 17:58:10.099  1019  1133 E Tethering: No numeric data
08-16 17:58:10.099  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:10.099  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:10.099  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:58:10.109  1879  1879 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:10.109  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 17:58:10.109  1019  1491 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:58:10.109  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:10.109  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:58:10.109  4838  4838 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:10.109  1019  4803 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:58:10.109  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:58:10.119  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:58:10.119  1019  1133 D Tethering: clearTetheredNotification()
,08-16 17:58:10.119  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:10.119  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:10.119  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:10.119  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:10.119  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:10.119  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:10.129  1019  1127 V NetworkStats: performPollLocked() took 7ms
,08-16 17:58:10.129  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:10.129  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:10.129  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:10.129  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:10.139  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:10.139  1182  1182 D HotspotTile: updateTetherState():false, false
,08-16 17:58:10.229   288   288 E SMD     : DCD OFF
,08-16 17:58:10.239   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-16 17:58:10.239   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:58:10.239  6880  6900 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-16 17:58:10.249   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-16 17:58:10.249   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:58:10.259  6880  6900 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-16 17:58:10.289  1350  1350 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:58:10.299  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:10.299  1019  1019 I ApplicationPolicy: updateDataUsageMap
,08-16 17:58:10.309  1019  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:10.319  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:10.319  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:10.339  1350  1350 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 17:58:10.339  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:10.339  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:10.339  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:10.429  6880  6880 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 17:58:10.429  6880  6880 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 17:58:10.429  6880  6880 D StrictMode: StrictMode policy violation; ~duration=168 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.429  6880  6880 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.v.a(PG,:1161)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.e.b(PG:170)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.429  6880  6880 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.k.d(PG:583)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.e.b(PG:170)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a,(PG:48)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.429  6880  6880 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.429  6880  6880 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.429  6880  6880 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.429  6880  6880 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.439  1019  1491 I ActivityManager: Killing 6486:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
08-16 17:58:10.449  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-16 17:58:10.449  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-16 17:58:10.459  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 17:58:10.459  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:10.459  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:10.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:10.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:10.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:10.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:10.459  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:10.459  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-16 17:58:10.459  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:58:10.469  1756  2206 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:58:10.469  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:10.469  1182  1182 D HotspotTile: onReceive : 1, 0
08-16 17:58:10.469  4838  4838 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:10.469  1019  1317 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:10.469  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:58:10.469  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.469  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:10.469  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.469  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:58:10.479  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:10.479  1646  1646 I Hs20UtilService: Starting #8
08-16 17:58:10.479  1646  1684 I Hs20UtilService: Message received 5007
08-16 17:58:10.479  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:58:10.479  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:58:10.479  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:58:10.489  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:58:10.489  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:10.489  4838  4838 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:58:10.489  4838  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:58:10.499  6880  6910 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-16 17:58:10.499  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 17:58:10.499  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:58:10.499  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:58:10.499  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:58:10.499  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:10.499  4838  4838 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:58:10.499  4838  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:58:10.499  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-16 17:58:10.509  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:10.509  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:10.509  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:10.509  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.519  6911  6911 E Zygote  : MountEmulatedStorage()
08-16 17:58:10.519  6911  6911 E Zygote  : v2
08-16 17:58:10.519  6911  6911 I libpersona: KNOX_SDCARD checking this for 10064
08-16 17:58:10.519  6911  6911 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:10.519  6911  6911 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-16 17:58:10.519  1019  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6911 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:58:10.519  6911  6911 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:10.529  6911  6911 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:10.539  1019  1752 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:10.539  1019  1752 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.539  1019  1752 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:10.539  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 17:58:10.539  6911  6911 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:10.539  6911  6911 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:10.559  6911  6911 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 17:58:10.579  6911  6911 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:10.579  6911  6911 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:58:10.609  6911  6911 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:58:10.609  1019  1125 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-16 17:58:10.609  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.609  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:10.609  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:10.609  1019  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.619  6928  6928 E Zygote  : MountEmulatedStorage(),
08-16 17:58:10.619  6928  6928 E Zygote  : v2
,08-16 17:58:10.619  6928  6928 I libpersona: KNOX_SDCARD checking this for 10065
,08-16 17:58:10.629  1019  1125 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6928 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-16 17:58:10.629  1019  1125 I ActivityManager: Killing 6504:com.wsomacp/u0a23 (adj 15): empty #21
08-16 17:58:10.629  6928  6928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:58:10.629  6928  6928 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:10.629  6928  6928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:10.629  6928  6928 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:10.639   307   307 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 19.176ms
,08-16 17:58:10.649  6928  6928 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:58:10.649  6928  6928 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:10.659   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 16.815ms
,08-16 17:58:10.669  6928  6928 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:10.679   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.535ms
,08-16 17:58:10.679  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.679  1019  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:10.679  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-16 17:58:10.679  1019  1449 I ActivityManager: Killing 6579:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-16 17:58:10.679  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.679  1019  1019 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:10.689  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-16 17:58:10.689  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-16 17:58:10.689  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:58:10.689  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.689  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.689  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.699  6943  6943 E Zygote  : MountEmulatedStorage()
08-16 17:58:10.699  6943  6943 E Zygote  : v2
08-16 17:58:10.699  6943  6943 I libpersona: KNOX_SDCARD checking this for 10102
08-16 17:58:10.699  6943  6943 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:10.699  6943  6943 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:58:10.699  1019  1019 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6943 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,08-16 17:58:10.709  6943  6943 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 17:58:10.709  6943  6943 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:58:10.719  6943  6943 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:10.719  6943  6943 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:10.739  6943  6943 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 17:58:10.939  6943  6963 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 17:58:10.939  6943  6963 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 17:58:10.939  6943  6963 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-16 17:58:10.939  6943  6963 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 17:58:10.959  6943  6963 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-16 17:58:10.959  6943  6963 I Babel_SMS: MmsConfig.loadFromResources
,08-16 17:58:10.959  6943  6963 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 17:58:10.959  6943  6963 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-16 17:58:10.989  1019  1499 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-16 17:58:10.989  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.989  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.989  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:10.989  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 17:58:11.009  6943  6943 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:11.009  6943  6943 I Babel_Crash: startup - clean
,08-16 17:58:11.039  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.039  1019  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:11.039  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.049  1019  1046 D Tethering: interfaceRemoved wlan0
08-16 17:58:11.049  1019  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 17:58:11.049  1019  1449 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:11.049  1019  1449 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:11.049  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.049  1019  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.049  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:11.059  1646  1646 I Hs20UtilService: Starting #9
,08-16 17:58:11.059  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:58:11.059  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:58:11.059  1646  1684 I Hs20UtilService: Message received 5007
08-16 17:58:11.059  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:11.059  6943  6943 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:58:11.059  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:58:11.059  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:11.059  4838  4838 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:58:11.059  4838  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:11.059  6943  6943 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 17:58:11.059  6943  6943 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 17:58:11.069  6943  6943 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-16 17:58:11.069  6943  6943 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-16 17:58:11.069  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:11.069  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:11.069  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.069  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:11.069  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:11.069  1646  1646 I Hs20UtilService: Starting #10
,08-16 17:58:11.069  1646  1684 I Hs20UtilService: Message received 5011
,08-16 17:58:11.069  6943  6943 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 17:58:11.079  6943  6943 W AudioCapabilities: Unsupported mime audio/x-ima
,08-16 17:58:11.079  6943  6943 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 17:58:11.079  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:58:11.079  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:11.079  6765  6765 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:58:11.079  6765  6765 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:11.079  6943  6943 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 17:58:11.089  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.089  1019  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.089  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.089  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.089  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:11.089  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.099  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.099  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.099  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.099  6943  6943 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 17:58:11.099  6943  6943 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 17:58:11.099  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.099  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.099  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.109  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.109  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.109  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.109  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.109  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.109  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.109  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.109  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.109  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.109  6943  6943 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-16 17:58:11.119  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.119  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.119  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.119  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.119  6943  6943 W VideoCapabilities: Unsupported mime video/wvc1
08-16 17:58:11.119  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.119  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.119  6943  6943 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 17:58:11.119  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.119  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.119  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.119  6943  6943 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-16 17:58:11.119  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.119  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.119  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.129  6943  6943 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-16 17:58:11.129  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.129  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.129  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.129  6943  6943 W VideoCapabilities: Unsupported mime video/mp43
,08-16 17:58:11.129  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.129  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.129  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.129  6943  6943 W VideoCapabilities: Unsupported mime video/sorenson
,08-16 17:58:11.139  4838  4838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:11.139  1019  1448 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 17:58:11.139  1019  1448 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:11.139  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.139  6943  6943 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 17:58:11.139  1019  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:11.139  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:11.149  2634  2634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:11.149  4838  4838 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:11.149  4838  4838 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:11.159  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:11.159  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 17:58:11.159  6943  6943 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 17:58:11.169  1019  1448 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-16 17:58:11.169  1019  1046 D Tethering: interfaceRemoved p2p0
08-16 17:58:11.169  1019  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 17:58:11.169  1019  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.169  1019  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.169  1019  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.169  1019  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.189  6968  6968 E Zygote  : MountEmulatedStorage()
08-16 17:58:11.189  6968  6968 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:58:11.189  6968  6968 E Zygote  : v2
08-16 17:58:11.189  6968  6968 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:11.189  6943  6943 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 17:58:11.189  6968  6968 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:58:11.189  6943  6943 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 17:58:11.189  6968  6968 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:11.189  6943  6943 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 17:58:11.189  6968  6968 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:11.199  6943  6943 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:58:11.199  1019  1448 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6968 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 17:58:11.199  1019  1737 I ActivityManager: Killing 6614:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-16 17:58:11.199  6943  6943 I vclib   : onServiceConnected
,08-16 17:58:11.219  6968  6968 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:11.219  6968  6968 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:11.249  6968  6968 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-16 17:58:11.249  6968  6968 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-16 17:58:11.249  6968  6968 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-16 17:58:11.259  6968  6968 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-16 17:58:11.259  6968  6968 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-16 17:58:11.259  6968  6968 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 17:58:11.259  6968  6968 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:11.259  1019  1032 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-16 17:58:11.259  1019  1032 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter,
08-16 17:58:11.259  6968  6983 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-16 17:58:11.259  1019  1032 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-16 17:58:11.259  1019  1032 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-16 17:58:11.259  1019  1032 I ActivityManager: Killing 1929:com.google.android.gms/u0a11 (adj 15): empty #21
,08-16 17:58:11.269  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-16 17:58:11.269  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.269  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.269  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.269  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.289  6985  6985 E Zygote  : MountEmulatedStorage(),
08-16 17:58:11.289  6985  6985 I libpersona: KNOX_SDCARD checking this for 10001
08-16 17:58:11.289  6985  6985 E Zygote  : v2
08-16 17:58:11.289  6985  6985 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:11.289  6985  6985 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:11.289  6985  6985 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:11.299  6985  6985 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:58:11.299  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6985 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:58:11.309  6985  6985 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:11.309  6985  6985 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:11.379  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast,
,08-16 17:58:11.379  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.399  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:58:11.399  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.399  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.409  7003  7003 E Zygote  : MountEmulatedStorage()
08-16 17:58:11.409  1019  1031 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7003 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 17:58:11.409  7003  7003 E Zygote  : v2
08-16 17:58:11.409  1019  1031 I ActivityManager: Killing 6643:com.osp.app.signin/u0a36 (adj 15): empty #21
08-16 17:58:11.409  7003  7003 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:58:11.409  7003  7003 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:11.409  7003  7003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:11.409  7003  7003 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 17:58:11.409  7003  7003 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:11.429  7003  7003 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:58:11.429  7003  7003 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:11.469  7003  7003 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-16 17:58:11.609  7003  7003 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-16 17:58:11.619  7003  7003 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-16 17:58:11.619  7003  7003 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:11.619  7003  7003 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-16 17:58:11.619  7003  7003 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-16 17:58:11.619  7003  7003 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-16 17:58:11.619  1019  1737 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-16 17:58:11.619  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.619  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.619  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.619  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.639  7018  7018 E Zygote  : MountEmulatedStorage(),
,08-16 17:58:11.639  1019  1737 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7018 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 17:58:11.639  1019  1737 I ActivityManager: Killing 6280:com.android.mms/u0a41 (adj 15): empty #21
,08-16 17:58:11.639  7018  7018 E Zygote  : v2
08-16 17:58:11.639  7018  7018 I libpersona: KNOX_SDCARD checking this for 10008
08-16 17:58:11.639  7018  7018 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:11.639  7018  7018 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:11.649  7018  7018 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:11.649  7018  7018 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-16 17:58:11.659  7018  7018 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:11.659  7018  7018 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:11.719  1019  1449 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gms, hostingType: broadcast
,08-16 17:58:11.719  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.719  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.719  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.719  1019  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.739  1019  1449 I ActivityManager: Start proc com.google.android.gms for broadcast com.google.android.gms/.gcm.gmsproc.GmsAutoStarter: pid=7033 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-16 17:58:11.739  1019  1449 I ActivityManager: Killing 6667:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-16 17:58:11.739  7033  7033 E Zygote  : MountEmulatedStorage()
08-16 17:58:11.739  7033  7033 I libpersona: KNOX_SDCARD checking this for 10011
08-16 17:58:11.739  7033  7033 E Zygote  : v2
08-16 17:58:11.739  7033  7033 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:11.739  7033  7033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:11.749  7033  7033 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:11.749  7033  7033 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:58:11.759  1019  4803 D CountryDetector: No listener is left
,08-16 17:58:11.779  7033  7033 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:11.779  7033  7033 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:11.799  7033  7033 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-16 17:58:11.799  7033  7033 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 17:58:11.829  7033  7033 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-16 17:58:11.839  7033  7033 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-16 17:58:11.839  7033  7033 I MultiDex: VM with version 2.1.0 has multidex support
,08-16 17:58:11.839  7033  7033 I MultiDex: install
08-16 17:58:11.839  7033  7033 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 17:58:11.849  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 17:58:11.959  7033  7033 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-16 17:58:12.009  7033  7033 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 17:58:12.009  7033  7033 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3dc30d8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-16 17:58:12.009  7033  7033 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 17:58:12.019  1019  1449 I ActivityManager: Killing 5973:com.samsung.android.sm/1000 (adj 15): empty #21
,08-16 17:58:12.019  1019  4459 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:12.019  1019  4459 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-16 17:58:12.019  1019  4459 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:12.029  1019  4459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:12.029  1019  4459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:12.049  7033  7051 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-16 17:58:12.079  7033  7055 I iu.SyncManager: SYNC; picasa accounts
,08-16 17:58:12.089  7033  7033 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-16 17:58:12.109  1019  4803 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:12.109  1019  4803 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-16 17:58:12.109  1019  4803 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:12.109  1019  4803 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:12.109  1019  4803 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:12.129  7033  7033 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 17:58:12.159  7033  7033 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-16 17:58:12.159  2850  2850 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 17:58:12 GMT+02:00 2016
,08-16 17:58:12.159  1019  1490 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-16 17:58:12.159  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 17:58:12.159  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:12.159  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:12.159  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 17:58:12.169  2850  2850 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-16 17:58:12.169  1019  1737 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-16 17:58:12.169  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.169  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.169  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.169  1019  1737 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.179  2850  2850 I KLMS-2.5.123: : KLMSIntentService(): onCreate(),
,08-16 17:58:12.179  2850  2850 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 17:58:12.189  7060  7060 E Zygote  : MountEmulatedStorage()
08-16 17:58:12.189  7060  7060 E Zygote  : v2
08-16 17:58:12.189  7060  7060 I libpersona: KNOX_SDCARD checking this for 10031
08-16 17:58:12.189  7060  7060 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:12.189  7060  7060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:12.189  2850  2850 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 17:58:12.189  7060  7060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:12.189  1019  1737 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7060 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-16 17:58:12.189  7060  7060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:12.189  2850  7059 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
,08-16 17:58:12.189  2850  7059 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-16 17:58:12.199  2850  7059 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-16 17:58:12.199  2850  7059 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-16 17:58:12.199  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.209  7060  7060 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.209  2850  2850 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-16 17:58:12.239  7060  7060 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-16 17:58:12.239  1019  1444 I ActivityManager: Killing 6685:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-16 17:58:12.249  2789  7075 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-16 17:58:12.259  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-16 17:58:12.259  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.259  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.259  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.259  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.259  2789  7075 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-16 17:58:12.259  2789  7075 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-16 17:58:12.269  2789  7075 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-16 17:58:12.269  2789  7075 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-16 17:58:12.269  7076  7076 E Zygote  : MountEmulatedStorage()
,08-16 17:58:12.269  7076  7076 E Zygote  : v2
08-16 17:58:12.269  7076  7076 I libpersona: KNOX_SDCARD checking this for 10032
08-16 17:58:12.269  7076  7076 I libpersona: KNOX_SDCARD not a persona,
,08-16 17:58:12.269  7076  7076 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:12.279  1019  1031 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7076 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 17:58:12.279  7076  7076 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 17:58:12.279  7076  7076 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-16 17:58:12.309  7076  7076 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.309  7076  7076 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.369  7076  7092 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-16 17:58:12.369  7076  7092 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-16 17:58:12.379  7076  7092 D SPPClientService: PushLog.txt file is not deleted.
,08-16 17:58:12.379  7076  7092 D SPPClientService: PushLog.txt file is not deleted.
08-16 17:58:12.379  7076  7092 D SPPClientService: ============PushLog. stop!
,08-16 17:58:12.379  7076  7076 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-16 17:58:12.379  1019  1499 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-16 17:58:12.379  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.379  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.379  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.379  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.399  7094  7094 E Zygote  : MountEmulatedStorage()
,08-16 17:58:12.399  7094  7094 E Zygote  : v2
08-16 17:58:12.399  7094  7094 I libpersona: KNOX_SDCARD checking this for 10036
08-16 17:58:12.399  7094  7094 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:12.399  7094  7094 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:12.399  1019  1499 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7094 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 17:58:12.399  1019  1499 I ActivityManager: Killing 6700:com.sec.esdk.elm/u0a90 (adj 15): empty #21,
08-16 17:58:12.399  7094  7094 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:12.399  1019  1032 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-16 17:58:12.399  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-16 17:58:12.399  7094  7094 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
08-16 17:58:12.399  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:12.399  1019  1032 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-16 17:58:12.399  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-16 17:58:12.419  7094  7094 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.419  7094  7094 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.439  7076  7103 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-16 17:58:12.459  7094  7094 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@24387164
,08-16 17:58:12.469  7094  7094 I SA      : [SSP] onCreated
,08-16 17:58:12.479  7094  7094 I SA      : [TPM] There is no property file
,08-16 17:58:12.479  7094  7094 I SA      : [SCU] isHaveSA() - false
,08-16 17:58:12.479  7094  7094 I SA      : [TPM] getModelProperty : null
,08-16 17:58:12.479  7094  7094 I SA      : [TPM] getCSCProperty : null
,08-16 17:58:12.479  7094  7094 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-16 17:58:12.479  7094  7094 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-16 17:58:12.489  7094  7094 I SA      : [DM] TFT FEATURE: false
,08-16 17:58:12.489  7094  7094 I SA      : [DM] init START
,08-16 17:58:12.489  7094  7094 I SA      : [DM] This device is not a Vodafone
,08-16 17:58:12.489  7094  7094 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75),
08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-16 17:58:12.499  7094  7094 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-16 17:58:12.509  7094  7094 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-16 17:58:12.509  7094  7094 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-16 17:58:12.509  7094  7094 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-16 17:58:12.509  7094  7094 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-16 17:58:12.509  7094  7094 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-16 17:58:12.509  7094  7094 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-16 17:58:12.509  7094  7094 I SA      : [SCU] isHaveSA() - false,
08-16 17:58:12.509  7094  7094 I SA      : support phone number id : false
,08-16 17:58:12.509  7094  7094 I SA      : [DM] Supports Ref Jpn : true,
,08-16 17:58:12.509  7094  7094 I SA      : [DM] init END
,08-16 17:58:12.509  7094  7094 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ],
,08-16 17:58:12.509  7094  7094 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-16 17:58:12.509  7094  7094 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-16 17:58:12.519  7094  7094 I SA      : [SLFUCHKMGR] constructor called
,08-16 17:58:12.519  7094  7094 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-16 17:58:12.519  7094  7094 I SA      : [OR] == isSIMCardReady false ==
,08-16 17:58:12.529  7094  7094 I SA      : [SCU] == networkStateCheck == false
08-16 17:58:12.529  7094  7094 I SA      : [OR] onReceive END
,08-16 17:58:12.529  1019  1737 I ActivityManager: Killing 6787:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-16 17:58:12.529  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:12.539  1822  1822 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 17:58:12.539  2694  2949 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-16 17:58:12.539  1822  1822 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-16 17:58:12.549  1822  1822 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-16 17:58:12.549  1822  1822 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-16 17:58:12.549  1822  1822 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-16 17:58:12.549  1019  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 17:58:12.549  1019  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-16 17:58:12.549  1019  1031 D SecContentProvider2: mCursor = null
,08-16 17:58:12.549  1019  1031 D WifiService: setWifiEnabled: true pid=6547, uid=10170
,08-16 17:58:12.549  1019  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=6547, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:58:12.549  1019  1031 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:58:12.549  1019  1031 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6547, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:12.549  1019  1031 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 17:58:12.549  1019  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:58:12.549  1019  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:58:12.549  1019  1031 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:58:12.549  1019  1031 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:58:12.549  1019  1031 D SettingsProvider: name = wifi_on
,08-16 17:58:12.559  1019  1130 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 17:58:12.559  1822  1822 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 17:58:12.559  1822  1822 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-16 17:58:12.559  1019  1499 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-16 17:58:12.569  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.569  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:58:12.569  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-16 17:58:12.569  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-16 17:58:12.589  7117  7117 E Zygote  : MountEmulatedStorage()
,08-16 17:58:12.589  7117  7117 E Zygote  : v2
08-16 17:58:12.589  7117  7117 I libpersona: KNOX_SDCARD checking this for 10077
08-16 17:58:12.589  7117  7117 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:12.589  7117  7117 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-16 17:58:12.589  1019  1499 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7117 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:58:12.599  7117  7117 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:12.599  7117  7117 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-16 17:58:12.619  7117  7117 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.619  7117  7117 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.809  1019  1490 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-16 17:58:12.809  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-16 17:58:12.809  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:12.809  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:12.809  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 17:58:12.819  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-16 17:58:12.819  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.819  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.819  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.819  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.829  7141  7141 E Zygote  : MountEmulatedStorage()
,08-16 17:58:12.829  7141  7141 E Zygote  : v2
08-16 17:58:12.829  7141  7141 I libpersona: KNOX_SDCARD checking this for 10110
08-16 17:58:12.829  7141  7141 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:12.829  7141  7141 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:12.829  1019  1031 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7141 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 17:58:12.829  1019  1737 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
08-16 17:58:12.829  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0,
,08-16 17:58:12.839  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:12.839  1019  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:12.839  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-16 17:58:12.839  7141  7141 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:12.839  7141  7141 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 17:58:12.839  6943  7140 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 17:58:12.849  1019  1125 I ActivityManager: Killing 6754:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-16 17:58:12.859   307   307 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 23.499ms
,08-16 17:58:12.859  7141  7141 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.859  7141  7141 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.879   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 567us total 17.022ms
,08-16 17:58:12.889   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 17.002ms
,08-16 17:58:12.999  1019  1448 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 17:58:13.029  1019  1046 D Tethering: interfaceAdded wlan0
,08-16 17:58:13.039  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:13.039  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:13.039  1019  1133 E Tethering: No numeric data,
,08-16 17:58:13.039  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-16 17:58:13.039  1019  1133 D Tethering: clearTetheredNotification()
08-16 17:58:13.039  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:13.039  1019  1133 D Tethering: InitialState.processMessage what=4
08-16 17:58:13.039  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-16 17:58:13.039  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.039  1182  1182 D HotspotTile: updateTetherState():false, false
08-16 17:58:13.039  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:13.039  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:13.039  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:58:13.039  1019  1133 E Tethering: No numeric data
08-16 17:58:13.049  1019  1127 V NetworkStats: performPollLocked() took 5ms
,08-16 17:58:13.039  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:58:13.039  1019  1133 D Tethering: clearTetheredNotification()
08-16 17:58:13.049  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.049  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:13.049  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:58:13.049  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:13.049  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:58:13.049   278  1017 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-16 17:58:13.049  1182  1182 D HotspotTile: updateTetherState():false, false
08-16 17:58:13.049  1019  1046 D Tethering: interfaceAdded p2p0
08-16 17:58:13.049  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:13.049  1019  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
08-16 17:58:13.049  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.049  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.049  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.049   278  1017 D SoftapController: Softap fwReload - Ok
,08-16 17:58:13.049  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:13.049  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:13.049   278  1017 D CommandListener: Setting iface cfg
08-16 17:58:13.049   278  1017 D CommandListener: Trying to bring down wlan0
,08-16 17:58:13.049   278  1017 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:58:13.049  1019  1127 V NetworkStats: performPollLocked() took 3ms
08-16 17:58:13.049  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.049  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.049  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:13.059  1019  1130 E WifiHW  : supplicant_name : p2p_supplicant
,08-16 17:58:13.139  7141  7141 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 17:58:13.139  7141  7141 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 17:58:13.139  7141  7141 I GAv4    :   adb logcat -s GAv4
,08-16 17:58:13.139   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 17:58:13.139   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:58:13.139  7141  7161 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 17:58:13.149   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 17:58:13.149   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 17:58:13.149  7141  7161 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 17:58:13.149  1019  3382 D SSRM:n  : SIOP:: AP = 380
,08-16 17:58:13.159  1019  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-16 17:58:13.169  7158  7158 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-16 17:58:13.169  7158  7158 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 17:58:13.169  7158  7158 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 17:58:13.169   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 17:58:13.169  4838  4838 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:13.169   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 17:58:13.169  7141  7163 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
08-16 17:58:13.169  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:13.169  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:13.169  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:13.169  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:13.169  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:13.169  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:13.169  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:13.169  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:13.169  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:13.169  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-16 17:58:13.179  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:58:13.179  1182  1182 D HotspotTile: onReceive : 2, 0
,08-16 17:58:13.179  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:13.179   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 17:58:13.179   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:58:13.179  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:13.179  7141  7163 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 17:58:13.179  7141  7141 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:58:13.179  1019  1444 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 17:58:13.199  7141  7141 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:58:13.199  7158  7158 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-16 17:58:13.199   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7158
,08-16 17:58:13.199   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-16 17:58:13.199  7158  7158 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 17:58:13.199  7158  7158 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:13.199  7158  7158 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 17:58:13.199  7158  7158 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-16 17:58:13.209   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7158
,08-16 17:58:13.209   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-16 17:58:13.209  7141  7165 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:58:13.219  1019  1051 I PowerManagerService: [PWL] Off : 50s ago
08-16 17:58:13.219  1019  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-16 17:58:13.219  1019  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-16 17:58:13.219  1019  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1019, ws=null) (elapsedTime=3428)
,08-16 17:58:13.239   288   288 E SMD     : DCD OFF,
,08-16 17:58:13.419   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-16 17:58:13.429  7158  7158 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-16 17:58:13.469  1019  1317 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:13.469  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:13.469  1019  1317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:13.469  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-16 17:58:13.479  7158  7158 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-16 17:58:13.479  7158  7158 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-16 17:58:13.489  7158  7158 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-16 17:58:13.489   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7158
08-16 17:58:13.489   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 17:58:13.489  7158  7158 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-16 17:58:13.489  7158  7158 I wpa_supplicant: ssSupport state is = 1
,08-16 17:58:13.499  7158  7158 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:58:13.499  7141  7141 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-16 17:58:13.499  7158  7158 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:13.499  7158  7158 E wpa_supplicant: SIM READ ERROR
08-16 17:58:13.499  7158  7158 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:13.499  7158  7158 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:13.499  7158  7158 E wpa_supplicant: SIM READ ERROR
08-16 17:58:13.499  7158  7158 I wpa_supplicant: Blacklist: Clear (all) 
08-16 17:58:13.499  7158  7158 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:58:13.499  7158  7158 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:58:13.499  7158  7158 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:13.499  7158  7158 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 17:58:13.499  7158  7158 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:13.499  7158  7158 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:13.499  7158  7158 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 17:58:13.499  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:13.499  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:13.499  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:58:13.509  7141  7141 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 3245-3247)
08-16 17:58:13.509  7141  7141 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-16 17:58:13.519  7141  7141 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22e3b9af}
,08-16 17:58:13.519  7141  7141 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-16 17:58:13.519  7141  7141 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 17:58:13.539  7141  7141 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-16 17:58:13.539  7141  7141 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:58:13.539  7141  7141 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 17:58:13.559  7141  7141 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:58:13.559  7141  7141 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:58:13.559  7141  7141 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:58:13.559  7141  7141 I Adreno-EGL: Local Branch: 
08-16 17:58:13.559  7141  7141 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:58:13.559  7141  7141 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:58:13.559  7141  7141 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:58:13.569  7158  7158 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-16 17:58:13.619  7141  7194 W cr.media: Requires BLUETOOTH permission
,08-16 17:58:13.619  7141  7141 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 17:58:13.629  7141  7141 I NSApplication: Starting up...
,08-16 17:58:13.629  1019  1317 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 17:58:13.629  1019  1448 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 17:58:13.629  1019  1499 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-16 17:58:13.639  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:13.639  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.639  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:13.639  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:13.649  1019  1499 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7199 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-16 17:58:13.649  1019  1499 I ActivityManager: Killing 6805:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-16 17:58:13.659  7199  7199 E Zygote  : MountEmulatedStorage()
08-16 17:58:13.659  7199  7199 I libpersona: KNOX_SDCARD checking this for 10117
08-16 17:58:13.659  7199  7199 E Zygote  : v2
08-16 17:58:13.659  7199  7199 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:13.659  7199  7199 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:13.659  7199  7199 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:13.659  7199  7199 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:58:13.679  7199  7199 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:13.679  7199  7199 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:13.699  7199  7199 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:58:13.749  7158  7158 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-16 17:58:13.749  7158  7158 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-16 17:58:13.759  7158  7158 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-16 17:58:13.759   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7158
08-16 17:58:13.759   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 17:58:13.759  7158  7158 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-16 17:58:13.759  7158  7158 I wpa_supplicant: ssSupport state is = 1
,08-16 17:58:13.759  7158  7158 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 17:58:13.759  7158  7158 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-16 17:58:13.779  7158  7158 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-16 17:58:13.779   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7158
08-16 17:58:13.779   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-16 17:58:13.779  7158  7158 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-16 17:58:13.779  7158  7158 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:13.779  7158  7158 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:13.779  7158  7158 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:13.779  7158  7158 E wpa_supplicant: SIM READ ERROR
08-16 17:58:13.779  7158  7158 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:58:13.779  7158  7158 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:58:13.779  7158  7158 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 17:58:13.779  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 17:58:13.789  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:13.789  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:58:13.789  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:13.789  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:13.789  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-16 17:58:13.879  7158  7158 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-16 17:58:13.879  7158  7158 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 17:58:13.969  7158  7158 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-16 17:58:13.969  7158  7158 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-16 17:58:13.969  7158  7158 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 17:58:13.979  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-16 17:58:13.979  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21],
,08-16 17:58:13.979  7158  7158 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-16 17:58:13.979  7158  7158 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:58:13.979  7158  7158 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:13.979  7158  7158 E wpa_supplicant: SIM READ ERROR,
08-16 17:58:13.979  7158  7158 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:58:14.039  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 17:58:14.039  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:14.039  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:58:14.059  7158  7158 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-16 17:58:14.079  7158  7158 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 17:58:14.079  1019  1130 D WifiConfigStore: Loading config and enabling all networks 
,08-16 17:58:14.079  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:14.089  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:14.089  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:14.089  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:14.089  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:14.089  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:14.089  1019  1130 E WifiConfigStore: Not a HS20
08-16 17:58:14.089  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:14.089  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:14.089  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-16 17:58:14.089  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:14.089  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:58:14.089  1182  1182 D HotspotTile: onReceive : 3, 0
,08-16 17:58:14.089  4838  4838 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:14.089  1019  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-16 17:58:14.089  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:14.099  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-16 17:58:14.099  7158  7158 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 17:58:14.099  7158  7158 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 17:58:14.099  7158  7158 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:58:14.099  7158  7158 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:58:14.099  7158  7158 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 17:58:14.099  7158  7158 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 17:58:14.099  7158  7158 I wpa_supplicant: First Scan Start
08-16 17:58:14.099  7158  7158 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-16 17:58:14.099  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:14.099  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:14.099  1019  1130 D WifiNative-wlan0: Setting external_sim to 1
,08-16 17:58:14.099  1019  1130 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:58:14.099  1019  1130 I WifiNative-HAL: startHal
08-16 17:58:14.099  1019  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9ea0388c
08-16 17:58:14.099  1019  1130 I WifiNative-HAL: Could not start hal
,08-16 17:58:14.099  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:14.099  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:14.099  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:14.099  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:14.109  1019  1130 E WifiNative-wlan0: do suspend true
,08-16 17:58:14.109  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-16 17:58:14.109  1019  1129 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-16 17:58:14.109   278  1017 D CommandListener: Setting iface cfg
08-16 17:58:14.109   278  1017 D CommandListener: Trying to bring up p2p0
,08-16 17:58:14.109  1019  1129 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 17:58:14.109  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:58:14.109  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:58:14.109  1019  1130 E WifiNative-wlan0: invaild command id : 215
,08-16 17:58:14.109  1019  1129 D WifiP2pService: P2pEnablingState
,08-16 17:58:14.109  1019  1129 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 17:58:14.109  1019  1129 D WifiP2pService: P2p socket connection successful
,08-16 17:58:14.109  7158  7158 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:58:14.109  1019  1129 D WifiP2pService: P2pEnabledState
,08-16 17:58:14.109  7158  7158 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 17:58:14.119  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 17:58:14.119  6943  6943 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:14.119  1019  1019 D RttService: SCAN_AVAILABLE : 3
,08-16 17:58:14.119  1019  4803 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-16 17:58:14.119  1019  1154 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:14.119  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:14.119  7158  7158 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-16 17:58:14.119  1019  1130 E WifiStateMachine: Failed to set frequency band 0
,08-16 17:58:14.119  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:14.119  1019  1130 D SecContentProvider2: mCursor = null
08-16 17:58:14.119  1019  1153 I WifiNative-HAL: startHal
08-16 17:58:14.119  1019  1153 E wifi    : getStaticLongField sWifiHalHandle 0x990249bc
08-16 17:58:14.119  1019  4803 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.119  1019  1153 I WifiNative-HAL: Could not start hal
08-16 17:58:14.119  1019  4803 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.119  1019  1153 E WifiScanningService: could not start HAL
08-16 17:58:14.119  1019  4803 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.119  1019  4803 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.129  7226  7226 E Zygote  : MountEmulatedStorage()
08-16 17:58:14.129  1019  4803 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7226 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-16 17:58:14.129  7226  7226 E Zygote  : v2
08-16 17:58:14.129  7226  7226 I libpersona: KNOX_SDCARD checking this for 10121
08-16 17:58:14.129  7226  7226 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:14.139  7226  7226 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:14.129  1019  4803 I ActivityManager: Killing 6719:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-16 17:58:14.139  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 17:58:14.139  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:14.139  1019  1130 D SecContentProvider2: mCursor = null
08-16 17:58:14.139  7226  7226 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:14.139  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-16 17:58:14.139  7226  7226 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:14.149  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress
,08-16 17:58:14.149  1019  1129 D WifiP2pService: DeviceAddress: 0a:75:42
08-16 17:58:14.149  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-16 17:58:14.159  7226  7226 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-16 17:58:14.169  7226  7226 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:14.179  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 17:58:14.179  7226  7226 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:58:14.179  7226  7226 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 17:58:14.179  7226  7226 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:58:14.179  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-16 17:58:14.179  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:14.179  1019  1049 D WifiDisplayController: disconnect
,08-16 17:58:14.179  1019  1049 D WifiDisplayController: updateConnection
08-16 17:58:14.179  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-16 17:58:14.179  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:14.189  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:58:14.189  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:58:14.189  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:58:14.189  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:58:14.189  1019  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  secondary type: null
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  wps: 0
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  grpcapab: 0
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  devcapab: 0
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  status: 3
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  wfdInfo: null
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  groupownerAddress: null
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  GOdeviceName: null
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  interfaceAddress: 
08-16 17:58:14.189  1019  1049 D WifiDisplayController:  SConnectInfo : null
,08-16 17:58:14.189  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:58:14.189  1019  1737 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:14.189  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:58:14.199  7226  7226 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:14.219  1019  1129 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 17:58:14.219  1019  1129 D WifiP2pService: InactiveState
08-16 17:58:14.219  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
,08-16 17:58:14.219  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:58:14.219  7158  7158 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-16 17:58:14.219  7226  7226 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-16 17:58:14.219  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
08-16 17:58:14.219  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:58:14.219  7226  7226 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-16 17:58:14.229  1019  1444 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-16 17:58:14.229  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.229  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.229  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.229  1019  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.239  7243  7243 E Zygote  : MountEmulatedStorage()
08-16 17:58:14.239  7243  7243 I libpersona: KNOX_SDCARD checking this for 10141
08-16 17:58:14.239  7243  7243 E Zygote  : v2
08-16 17:58:14.239  1019  1444 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7243 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-16 17:58:14.239  7243  7243 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:14.249  7243  7243 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:58:14.239  1019  1444 I ActivityManager: Killing 6734:com.android.calendar/u0a131 (adj 15): empty #21
08-16 17:58:14.249  7243  7243 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:14.249  7243  7243 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:14.259   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:58:14.269  7243  7243 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:58:14.269  7243  7243 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:14.289  7243  7243 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-16 17:58:14.289  7243  7243 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:58:14.289  7243  7243 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:58:14.289  7243  7243 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 17:58:14.339  1019  1752 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:14.349  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:14.379  1019  1317 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:14.389  1019  4459 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:14.439  1019  1499 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-16 17:58:14.439  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.439  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.439  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.439  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.449  1019  1491 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:14.449  7266  7266 E Zygote  : MountEmulatedStorage(),
,08-16 17:58:14.459  7266  7266 E Zygote  : v2
08-16 17:58:14.459  7266  7266 I libpersona: KNOX_SDCARD checking this for 10068
08-16 17:58:14.459  7266  7266 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:14.459  7266  7266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:14.459  1019  1752 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:14.459  1019  1499 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7266 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,08-16 17:58:14.459  7266  7266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:14.469  7266  7266 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-16 17:58:14.489  7266  7266 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:14.489  7266  7266 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:14.499  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:14.499  1019  1317 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-16 17:58:14.499  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.499  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.499  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.499  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.519  7266  7266 D BadgeProvider: onCreate,
08-16 17:58:14.519  7266  7266 D BadgeProvider: DatabaseHelper
,08-16 17:58:14.519  7281  7281 E Zygote  : MountEmulatedStorage(),
08-16 17:58:14.519  7281  7281 E Zygote  : v2
08-16 17:58:14.519  7281  7281 I libpersona: KNOX_SDCARD checking this for 10009
,08-16 17:58:14.519  7281  7281 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:14.519  1019  1317 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7281 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-16 17:58:14.519  7281  7281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:14.529  1019  1317 I ActivityManager: Killing 5825:com.android.vending/u0a26 (adj 15): empty #21
,08-16 17:58:14.529  1019  1317 I ActivityManager: Killing 6519:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-16 17:58:14.529  7281  7281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:14.529  7281  7281 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-16 17:58:14.559  7281  7281 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:14.559  7281  7281 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:14.629  1019  1125 I ActivityManager: Killing 6911:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-16 17:58:14.639  1019  1317 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:14.639  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:14.639  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.639  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:14.639  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:14.639  1646  1646 I Hs20UtilService: Starting #11
,08-16 17:58:14.639  1646  1684 I Hs20UtilService: Message received 5011
,08-16 17:58:14.639  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:58:14.639  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:14.639  6765  6765 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:58:14.639  6765  6765 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:14.649  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.649  1019  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.649  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.659  1019  1125 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:14.659  1019  1125 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-16 17:58:14.659  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.659  1019  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.659  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.659  1019  1125 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-16 17:58:14.659  1019  1125 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-16 17:58:14.659  1019  1125 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-16 17:58:14.659  1019  1125 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-16 17:58:14.659  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.659  1019  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.659  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:58:14.659  2634  2661 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 17:58:14.679  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.679  1019  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.679  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.679  2634  2634 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 17:58:14.689  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.689  1019  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.689  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.689  1019  1499 I art     : Explicit concurrent mark sweep GC freed 61324(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 23MB/34MB, paused 7.351ms total 165.986ms
,08-16 17:58:14.699  1019  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:14.699  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-16 17:58:14.699  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.699  1019  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.699  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.699  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.699  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.699  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.709  1019  4803 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-16 17:58:14.709  1019  4803 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-16 17:58:14.709  1019  1752 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-16 17:58:14.709  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-16 17:58:14.709  7266  7280 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-16 17:58:14.719  2634  2634 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:14.719  2634  2634 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:14.719  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.719  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.719  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.729  7033  7033 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-16 17:58:14.729  7266  7280 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-16 17:58:14.729  7266  7280 D BadgeProvider: sendNotify, [notify] : null
08-16 17:58:14.729  7266  7280 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-16 17:58:14.729  7266  7280 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-16 17:58:14.729  7266  7280 D BadgeProvider: update, [UpdateCount] : 1
,08-16 17:58:14.729  1497  1497 D Launcher.Model: reloadBadges entered.
,08-16 17:58:14.749  1019  1737 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:14.749  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-16 17:58:14.749  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.749  1019  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.749  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.749  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.749  1019  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.749  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.759  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.759  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:14.759  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.759  1019  1317 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:58:14.759  1019  1317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.759  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.769  1019  4459 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:14.769  1019  4459 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.769  1019  4459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.769  1019  4459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.769  1019  4459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.769  1019  4459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.769  1019  4459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.769  1019  4459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.779  7300  7300 E Zygote  : MountEmulatedStorage()
,08-16 17:58:14.779  7300  7300 E Zygote  : v2
08-16 17:58:14.779  7300  7300 I libpersona: KNOX_SDCARD checking this for 10011
08-16 17:58:14.779  7300  7300 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:14.789  7300  7300 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:14.789  1019  4459 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7300 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-16 17:58:14.789  7300  7300 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:14.789  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.789  1019  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.789  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:58:14.789  7300  7300 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:58:14.799  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.799  1019  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.799  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.809  7300  7300 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:14.809  7300  7300 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:14.819  7300  7300 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-16 17:58:14.819  7300  7300 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 17:58:14.859  7300  7300 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-16 17:58:14.859  7300  7300 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-16 17:58:14.859  7300  7300 I MultiDex: VM with version 2.1.0 has multidex support
08-16 17:58:14.859  7300  7300 I MultiDex: install
08-16 17:58:14.859  7300  7300 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 17:58:14.869  1470  1681 D TP/SmsProvider: query,matched:0, calling pid = 7033,
,08-16 17:58:14.869  1470  1681 D TP/SmsProvider: match 0:Elapsed time : 0.958 ms
,08-16 17:58:14.869  1019  1444 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.869  1019  1444 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.869  1019  1444 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.879  1019  1444 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.879  1019  1444 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.879  1019  1444 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.879  1019  1448 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:14.889  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.889  1019  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.889  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.889  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.889  1019  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.889  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.899  7300  7300 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-16 17:58:14.899  1470  2712 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7033
,08-16 17:58:14.899  1019  4459 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:14.899  1019  4459 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:14.899  1019  4459 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.899  1019  4459 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:14.899  1019  4459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:14.899  1646  1646 I Hs20UtilService: Starting #12
,08-16 17:58:14.899  1646  1684 I Hs20UtilService: Message received 5011
,08-16 17:58:14.909  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:14.909  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:14.909  6765  6765 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:58:14.909  6765  6765 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:14.919  1470  1681 D TP/SmsProvider: query,matched:0, calling pid = 7033
,08-16 17:58:14.919  1470  1681 D TP/SmsProvider: match 0:Elapsed time : 1.354 ms
,08-16 17:58:14.919  1019  1737 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:14.919  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-16 17:58:14.919  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.919  1019  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.919  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.929  7033  7319 D LocationInitializer: Restart initialization of location
,08-16 17:58:14.929  1019  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:14.929  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:14.929  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.929  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:14.929  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:14.929  1646  1646 I Hs20UtilService: Starting #13
,08-16 17:58:14.929  1646  1684 I Hs20UtilService: Message received 5011
,08-16 17:58:14.929  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-16 17:58:14.929  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:58:14.929  1019  1130 E WifiNative-wlan0: invaild command id : 215
,08-16 17:58:14.939  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:58:14.939  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:14.939  6765  6765 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:58:14.939  6765  6765 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:14.939  1019  1752 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:14.939  1019  1752 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-16 17:58:14.939  1019  1752 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:14.939  1019  1752 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.939  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.949  1470  2712 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7033
,08-16 17:58:14.949  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:58:14.949  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:14.959  1019  1752 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:14.959  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:14.959  1019  1752 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.959  1019  1752 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:14.959  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:14.959  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:58:14.959  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:14.959  4838  4838 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:14.959  4838  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:14.959  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-16 17:58:14.959  7300  7300 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 17:58:14.959  7300  7300 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32541678: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-16 17:58:14.959  7300  7300 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 17:58:14.969  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.969  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.969  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:14.969  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:14.979  7321  7321 E Zygote  : MountEmulatedStorage(),
08-16 17:58:14.979  7321  7321 E Zygote  : v2
08-16 17:58:14.979  7321  7321 I libpersona: KNOX_SDCARD checking this for 10064
,08-16 17:58:14.979  7321  7321 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:14.979  1019  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7321 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:58:14.979  7321  7321 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:14.979  7321  7321 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:14.989  7321  7321 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:14.999  7300  7300 D WearableService: callingUid 10011, callindPid: 7300
,08-16 17:58:15.019  7321  7321 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:15.019  7321  7321 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:15.039  7300  7331 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-16 17:58:15.039  7321  7321 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 17:58:15.049  7321  7321 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:15.049  7321  7321 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:58:15.049  1756  5178 E MDM     : [188] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-16 17:58:15.079  7321  7321 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:58:15.079  6928  6928 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:15.089  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.089  1019  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.089  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.089  1019  4459 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:15.089  1019  4459 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-16 17:58:15.089  1019  4459 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:15.089  1019  4459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:15.089  1019  4459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.089  2634  3155 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 17:58:15.099  1019  1125 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,08-16 17:58:15.099  1019  1125 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-16 17:58:15.099  1019  1125 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,08-16 17:58:15.099  1019  1125 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-16 17:58:15.099  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.099  1019  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.099  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.099  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.099  1019  1737 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.099  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.109  2634  2634 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 17:58:15.109  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.109  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:15.109  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.109  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:15.109  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-16 17:58:15.109  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.109  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.119  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.119  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:15.119  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.119  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.129  2634  2634 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:15.129  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.129  1019  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.129  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.129  7033  7033 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-16 17:58:15.129  1019  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:15.129  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-16 17:58:15.129  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:15.129  1019  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.129  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.139  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:15.139  1019  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.139  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.139  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:15.139  1019  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.139  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.139  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.139  1019  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.139  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.149  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.149  1019  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.149  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:58:15.149  1756  5198 E MDM     : [189] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-16 17:58:15.159  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.159  1019  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:15.159  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.169  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.169  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:15.169  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.169  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.179  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:15.179  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.179  1019  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:15.179  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.179  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.179  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.189  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.189  1019  1317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.189  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.189  1019  1125 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:15.189  1019  1125 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-16 17:58:15.189  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:15.189  1019  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:15.189  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.189  7033  7341 D LocationInitializer: Restart initialization of location
,08-16 17:58:15.189  1019  1317 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:15.189  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-16 17:58:15.189  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:15.189  1019  1317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:15.199  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:15.249  2634  7342 I art     : Explicit concurrent mark sweep GC freed 17222(820KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 954us total 44.960ms
,08-16 17:58:15.269   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:15.349  7158  7158 I wpa_supplicant: nl80211: Received scan results (22 BSSes)
08-16 17:58:15.349  7158  7158 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-16 17:58:15.349  7158  7158 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-16 17:58:15.349  7158  7158 I wpa_supplicant: Trying to associate with  'G700'
08-16 17:58:15.349  7158  7158 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-16 17:58:15.349  7158  7158 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-16 17:58:15.349  1019  7221 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-16 17:58:15.369  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:58:15.369  1019  1130 D SecContentProvider2: mCursor = null
,08-16 17:58:15.459  7158  7158 E wpa_supplicant: Cmd 35605 not handled
,08-16 17:58:15.459  7158  7158 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:58:15.459  7158  7158 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-16 17:58:15.459  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:15.459  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:15.459  7158  7158 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-16 17:58:15.459  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:15.459  7158  7158 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-16 17:58:15.459  7158  7158 I wpa_supplicant: Associated with F4.99.3E
08-16 17:58:15.459  7158  7158 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:58:15.459  7158  7158 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-16 17:58:15.459  7158  7158 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-16 17:58:15.459  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 17:58:15.459  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-16 17:58:15.459  1019  1046 D Tethering: interfaceStatusChanged wlan0, false,
08-16 17:58:15.459  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:15.459  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:15.459  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-16 17:58:15.459  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:15.459  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:58:15.459  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
,08-16 17:58:15.469  1019  1133 E Tethering: No numeric data,
08-16 17:58:15.469  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:58:15.469  1019  1133 D Tethering: clearTetheredNotification()
08-16 17:58:15.469  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:15.469  1019  1130 D SecContentProvider2: mCursor = null
08-16 17:58:15.469  7158  7158 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:58:15.469  7158  7158 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-16 17:58:15.469  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:15.469  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:58:15.469  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:15.469  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:15.469  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:58:15.469  1182  1182 D HotspotTile: updateTetherState():false, false
08-16 17:58:15.469  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:15.469  1019  1130 D SecContentProvider2: mCursor = null
08-16 17:58:15.479  7158  7158 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
08-16 17:58:15.479  7158  7158 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-16 17:58:15.479  1019  1127 V NetworkStats: performPollLocked() took 8ms
08-16 17:58:15.479  7158  7158 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:58:15.479  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 17:58:15.479  7158  7158 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-16 17:58:15.479  7158  7158 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-16 17:58:15.479  7158  7158 I wpa_supplicant: Blacklist: Clear (temp) 
08-16 17:58:15.479  7158  7158 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-16 17:58:15.479  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:15.479  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:58:15.479  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
,08-16 17:58:15.489  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:15.489  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:15.489  1019  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-16 17:58:15.489  1019  1130 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-16 17:58:15.499  1019  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 17:58:15.499  1019  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-16 17:58:15.499  1019  1132 E ConnectivityService: updateNetworkInfo()
08-16 17:58:15.499  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 17:58:15.499  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:15.499  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:15.499  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:58:15.509  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.509  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:15.509  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.509  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:15.509  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:15.509  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:15.509  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:15.509  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:15.509  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:15.509  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:58:15.509  1646  1646 I Hs20UtilService: Starting #14
08-16 17:58:15.509  1646  1684 I Hs20UtilService: Message received 5007
08-16 17:58:15.519  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:58:15.519  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:15.519  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:58:15.519  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:58:15.519  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:15.519  4838  4838 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:15.519  4838  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:15.539  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-16 17:58:15.549   278  1017 D CommandListener: Setting iface cfg
08-16 17:58:15.549  1019  1130 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 17:58:15.549  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:58:15.549  1019  1130 D SecContentProvider2: mCursor = null
,08-16 17:58:15.559  1019  1499 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:58:15.559  1019  1499 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:58:15.559  1019  1499 D SecContentProvider2: mCursor = null
,08-16 17:58:15.559  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 17:58:15.559  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:15.559  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:58:15.569  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:15.569  1019  1499 D WifiService: setWifiEnabled: false pid=6547, uid=10170
08-16 17:58:15.569  1019  1499 D SettingsProvider: name = wifi_on
08-16 17:58:15.569  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 17:58:15.569  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.569  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:15.569  1019  1130 E WifiNative-wlan0: do suspend false
,08-16 17:58:15.569  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:15.569  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
08-16 17:58:15.569  1019  1130 D SecContentProvider2: mCursor = null
,08-16 17:58:15.569  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:58:15.579  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:15.589  1019  1130 E WifiNative-wlan0: do suspend true
,08-16 17:58:15.609  1019  1129 D WifiP2pService: InactiveState{ what=143375 },
08-16 17:58:15.609  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:58:15.609   278  1017 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:58:15.609  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-16 17:58:15.619  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:15.619  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:15.619  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:15.619  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.619  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:58:15.619  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:15.619  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
,08-16 17:58:15.619  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.619  1019  1129 D WifiP2pService: InactiveState{ what=131204 }
08-16 17:58:15.619  1019  1132 E ConnectivityService: updateNetworkInfo()
08-16 17:58:15.619  1019  1129 D WifiP2pService: P2pEnabledState{ what=131204 }
08-16 17:58:15.619  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-16 17:58:15.619  1019  1132 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-16 17:58:15.619   278  1017 E Netd    : no such netId 503,
08-16 17:58:15.619  1019  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 17:58:15.619  1019  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:58:15.619  1019  1132 V NetworkStats: updateIfacesLocked(),
08-16 17:58:15.619  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:15.619  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:58:15.619  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 17:58:15.619  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-16 17:58:15.619  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:15.619  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:15.629  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 17:58:15.629  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:15.629  1019  1019 D RttService: SCAN_AVAILABLE : 1
08-16 17:58:15.629  1019  1132 V NetworkStats: performPollLocked() took 10ms
08-16 17:58:15.629  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:15.629  1019  1154 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:15.639  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:15.639  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:15.639  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:15.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.639  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 17:58:15.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:15.639  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-16 17:58:15.639  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:58:15.639  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:58:15.639  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:58:15.639  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 17:58:15.639  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-16 17:58:15.639  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:15.639  1019  1049 D WifiDisplayController: disconnect
08-16 17:58:15.639  1019  1049 D WifiDisplayController: updateConnection
08-16 17:58:15.639  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:15.649  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:15.649  1019  1449 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:15.649  1019  1129 D WifiP2pService: P2pDisablingState
08-16 17:58:15.649  1019  1449 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:58:15.649  1019  1129 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 17:58:15.649  1019  1129 D WifiP2pService: p2p socket connection lost
,08-16 17:58:15.649  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:15.649  1019  1129 D WifiP2pService: P2pDisabledState,
08-16 17:58:15.649  1019  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:15.649  1019  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-16 17:58:15.649  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:58:15.649  1019  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 17:58:15.649  1019  7344 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:15.649  1019  1130 E WifiNative-wlan0: do suspend true
08-16 17:58:15.649  1019  1132 D ConnectivityService: nai.networkMonitor.doQuit()
08-16 17:58:15.649  1019  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-16 17:58:15.649  1019  1132 E ConnectivityService: updateNetworkInfo()
08-16 17:58:15.649  1019  1132 E ConnectivityService: updateNetworkInfo()
08-16 17:58:15.649  1019  7344 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-16 17:58:15.649  1646  1646 I Hs20UtilService: Starting #15
,08-16 17:58:15.649  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:15.649  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:15.649  1646  1684 I Hs20UtilService: Message received 5007
08-16 17:58:15.659  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 17:58:15.659  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:58:15.659  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:58:15.659  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:58:15.659  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:58:15.659  1019  1125 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:15.659  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:58:15.659  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:58:15.659  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:58:15.659  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:15.669  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:58:15.669  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 17:58:15.669  4838  4838 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:58:15.669  4838  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:15.679  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:58:15.679  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:15.679  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:15.679  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:58:15.679  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:15.679  4838  4838 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:15.679  1019  1129 D WifiP2pService: P2pDisabledState{ what=143375 }
08-16 17:58:15.679  1019  1129 D WifiP2pService: DefaultState{ what=143375 }
08-16 17:58:15.679   278  1017 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:58:15.679  4838  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:15.689  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-16 17:58:15.689  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:15.689  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-16 17:58:15.689  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.689  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.689  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.689  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 17:58:15.689  7321  7321 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-16 17:58:15.689  7321  7321 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 17:58:15.689  7321  7321 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:58:15.689  7158  7158 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-16 17:58:15.699  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:58:15.709  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:15.709  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:15.709  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:15.709  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.709  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.709  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.709  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:15.709  6928  6928 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:15.709  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:15.709  1019  1130 D SecContentProvider2: mCursor = null
,08-16 17:58:15.719  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:15.719  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:15.719  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:15.719  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.719  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.719  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:15.719  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.719  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:15.719  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:15.719  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-16 17:58:15.719  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:58:15.719  1182  1182 D HotspotTile: onReceive : 0, 0
,08-16 17:58:15.719  4838  4838 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:15.729  1019  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:15.729  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:58:15.729  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:15.729  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:15.729  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:15.729  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:15.729  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:15.729  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:15.729  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:15.729  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:15.729  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:15.729  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:15.739  1646  1646 I Hs20UtilService: Starting #16
,08-16 17:58:15.739  1646  1684 I Hs20UtilService: Message received 5007
,08-16 17:58:15.739  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:58:15.739  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:15.739  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:15.739  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:58:15.739  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:15.739  4838  4838 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:15.739  4838  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:15.749  1019  1499 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:15.749  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:15.749  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.749  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:15.749  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-16 17:58:15.759  1646  1646 I Hs20UtilService: Starting #17
,08-16 17:58:15.759  1646  1684 I Hs20UtilService: Message received 5011
,08-16 17:58:15.759  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:15.759  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:15.759  6765  6765 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:58:15.759  6765  6765 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:15.789  7347  7347 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-16 17:58:15.789  7347  7347 I dhcpcd  : version 5.5.6 starting,
,08-16 17:58:15.799  7347  7347 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-16 17:58:15.839  7347  7347 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-16 17:58:15.839  7347  7347 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-16 17:58:15.839  7347  7347 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-16 17:58:15.839  7347  7347 I dhcpcd  : bssid match,
,08-16 17:58:15.839  7347  7347 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
08-16 17:58:15.839  7158  7158 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:58:15.879  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 17:58:15.879  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-16 17:58:15.879  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:58:15.879  7158  7158 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-16 17:58:15.899  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 17:58:15.899  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:15.899  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:15.899  1019  1133 D Tethering: InitialState.processMessage what=4
,08-16 17:58:15.909  7158  7158 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-16 17:58:15.909  7158  7158 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-16 17:58:15.909  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:15.909  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:15.909  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:15.909  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:15.909  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:15.909  1019  1133 E Tethering: No numeric data
08-16 17:58:15.909  1182  1182 D HotspotTile: updateTetherState():false, false
08-16 17:58:15.909  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:58:15.909  1019  1127 V NetworkStats: performPollLocked() took 2ms
08-16 17:58:15.909  1019  1133 D Tethering: clearTetheredNotification()
08-16 17:58:15.909  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:15.909  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:15.909  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:58:15.909  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:15.909  7158  7158 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-16 17:58:15.909  7158  7158 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 17:58:15.909  7158  7158 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-16 17:58:15.909  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:15.909  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:15.909  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:15.909  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:15.909  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:16.139  7158  7158 I wpa_supplicant: Blacklist: Clear (all) ,
,08-16 17:58:16.219  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:16.219  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:16.219  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:16.219  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:16.219  7158  7158 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 17:58:16.219  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 17:58:16.219  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:16.239   288   288 E SMD     : DCD OFF
,08-16 17:58:16.249  1019  1444 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:58:16.249  1019  1444 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-16 17:58:16.249  1019  1444 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-16 17:58:16.249  1019  1444 D BatteryService: stay LED for charging
08-16 17:58:16.249  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-16 17:58:16.249  1019  1019 I MotionRecognitionService: Plugged
08-16 17:58:16.249  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
08-16 17:58:16.249  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-16 17:58:16.249  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 17:58:16.259  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 17:58:16.259  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 17:58:16.269   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:16.279  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 17:58:16.279  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 17:58:16.279  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-16 17:58:16.279  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-16 17:58:16.279  1182  1182 D SViewCoverView: level :100 plugged : 2
,08-16 17:58:16.319  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-16 17:58:16.319  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 17:58:16.319  6943  6943 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:16.329  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:16.329  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:16.329  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-16 17:58:16.329  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:16.329  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:16.329  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:16.329  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:16.329  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:16.329  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-16 17:58:16.329  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:16.329  4838  4838 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:16.329  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:58:16.339  1182  1182 D HotspotTile: onReceive : 1, 0
,08-16 17:58:16.339  1756  2206 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:16.339  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:16.339  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:16.339  1019  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:16.339  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:16.339  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:16.339  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:16.339  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:16.349  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:16.349  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:16.349  6765  6765 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:58:16.349  6765  6765 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:16.349  1646  1646 I Hs20UtilService: Starting #18
,08-16 17:58:16.349  1646  1684 I Hs20UtilService: Message received 5011
,08-16 17:58:16.969  7347  7347 E dhcpcd  : wlan0: send_raw_packet: Network is down
,08-16 17:58:17.139  1019  1046 D Tethering: interfaceRemoved wlan0,
08-16 17:58:17.139  1019  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 17:58:17.169  5752  5752 D FactoryTest: Not factory mode
,08-16 17:58:17.169  5752  5752 D FactoryTest: Not factory mode. isFactoryMode() returend false
08-16 17:58:17.169  5752  5752 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-16 17:58:17.169  5752  5752 D MTPRx   : still no open session command from host, so toast
,08-16 17:58:17.169  5752  5752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-16 17:58:17.169  5752  5752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-16 17:58:17.179  1019  7345 D NetUtils: dhcp_do_request failed : wlan0 (new)
08-16 17:58:17.179  1019  7345 E DhcpStateMachine: DHCP failed on wlan0: DHCP result was failed,
08-16 17:58:17.179  5752  5752 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116911
,08-16 17:58:17.179  1019  1448 E PersonaManagerService: inState():  stateMachine is null !!
08-16 17:58:17.179  1019  1448 I PersonaManagerService: PersonaId don't exist
,08-16 17:58:17.179  1019  1448 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-16 17:58:17.179  1019  1448 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-16 17:58:17.179  1019  1448 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:58:17.189  1019  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:17.189  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-16 17:58:17.189  1019  1448 W ActivityManager: mDVFSHelper.acquire(),
,08-16 17:58:17.209  1019  1448 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:58:17.219  1019  1448 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 17:58:17.219  1019  1448 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 17:58:17.219  1019  1448 D InputDispatcher: Focused application set to: xxxx
,08-16 17:58:17.219  1019  1448 D InputDispatcher: Focus left window: 6547
,08-16 17:58:17.219  5752  5752 E MTPRx   : started activity for popup
,08-16 17:58:17.229  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 17:58:17.229  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:58:17.249  5752  5752 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-16 17:58:17.249  5752  5752 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-16 17:58:17.249  5752  5752 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 17:58:17.249  5752  5752 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:58:17.249  5752  5752 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:58:17.249  5752  5752 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:58:17.269   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:17.269  5752  5752 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-16 17:58:17.279  1019  1499 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 17:58:17.279  1019  1499 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 17:58:17.279  1019  1499 D InputDispatcher: Focused application set to: xxxx
,08-16 17:58:17.279  1019  1499 D InputDispatcher: Focus entered window: 6547
,08-16 17:58:17.289  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 17:58:17.289  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:58:17.289  1019  1448 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 17:58:17.289  1019  1448 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1ad737f5 attribute=null, token = android.os.BinderProxy@9640b6d
,08-16 17:58:17.329  5752  5752 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-16 17:58:17.329  5752  5752 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-16 17:58:17.329  5752  5752 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-16 17:58:17.349  6547  6547 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:58:17.349  6547  6547 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-16 17:58:17.349  6547  6547 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 17:58:17.349  6547  6547 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-16 17:58:17.349  1019  1031 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 17:58:17.349  1019  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 17:58:17.349  1019  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 17:58:17.349  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 17:58:17.349  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 17:58:17.369  6547  6547 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:58:17.369  6547  6547 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 17:58:17.379  6547  6547 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@36891ff5 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@29ea1719, 16908290=android.view.AbsSavedState$1@29ea1719}, android:focusedViewId=100}]}]
08-16 17:58:17.379  6547  6547 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 17:58:17.379  6547  6547 V ActivityThread: updateVisibility : ActivityRecord{c5627cf token=android.os.BinderProxy@15b8d2a9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 17:58:17.379  6547  6547 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 17:58:17.379  6547  6547 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 17:58:17.379  6547  6547 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@15b8d2a9 time:117112
,08-16 17:58:17.389  1019  1490 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:58:17.459  1019  1046 D Tethering: interfaceRemoved p2p0,
08-16 17:58:17.459  1019  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 17:58:18.269  1019  1097 V AlarmManager: waitForAlarm result :4
,08-16 17:58:18.269   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:58:18.269   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 17:58:18.269   278  1011 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-16 17:58:18.279  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-16 17:58:18.289  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.289  1019  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:18.289  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-16 17:58:18.579  6547  6683 D BluetoothAdapter: enable()
,08-16 17:58:18.579  1019  1444 W ActivityManager: Permission Denial: getCurrentUser() from pid=6547, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:58:18.579  1019  1444 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 17:58:18.579  1019  1444 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6547, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:18.579  1019  1444 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 17:58:18.579  1019  1444 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-16 17:58:18.579  1019  1444 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-16 17:58:18.579  1019  1444 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-16 17:58:18.579  1019  1444 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:58:18.589  1019  1444 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:58:18.589  1019  1444 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:18.589  1019  1444 D SettingsProvider: name = bluetooth_on,
,08-16 17:58:18.589  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:18.589  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:18.589  1019  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 17:58:18.599  3214  3292 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-16 17:58:18.599  3214  3292 D BluetoothAdapterProperties: Setting state to 11
08-16 17:58:18.599  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:18.599  3214  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 17:58:18.599  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-16 17:58:18.599  3214  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:18.599  3214  3292 D BluetoothAdapterService: updateAdapterState state is 11
08-16 17:58:18.599  3214  3292 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:18.599  3214  3292 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-16 17:58:18.599  3214  3292 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
,08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService,
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService,
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:58:18.599  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:58:18.599  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-16 17:58:18.599  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.599  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.599  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:18.609  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:58:18.609  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:58:18.609  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:18.609  3214  3214 D HeadsetService: Received start request. Starting profile...
08-16 17:58:18.609  3214  3214 D HeadsetService: start()
08-16 17:58:18.609  3214  3214 D HeadsetStateMachine: make
,08-16 17:58:18.609  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:18.609  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,08-16 17:58:18.609  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:58:18.609  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:18.609  1182  1182 D BluetoothTile:  getBluetoothState : 11
,08-16 17:58:18.619  3214  3214 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 17:58:18.619  1879  1879 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:18.619  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:58:18.619  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:58:18.619  4838  4838 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:18.619  1019  1032 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:18.619  1019  4459 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 17:58:18.619  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:18.629  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:18.629  1019  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:18.629  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.629  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.629  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.629  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.629  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService,
,08-16 17:58:18.629  1019  1752 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-16 17:58:18.629  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:58:18.629  1019  1752 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-16 17:58:18.629  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-16 17:58:18.629  1019  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:18.629  1019  1752 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.629  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 17:58:18.629  1019  1752 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.629  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-16 17:58:18.629  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:18.629  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.629  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:18.629  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.639  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-16 17:58:18.639  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:58:18.639  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:58:18.639  2634  2634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:18.639  1019  1317 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-16 17:58:18.639  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.639  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.639  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.639  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:58:18.639  1019  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:18.639  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.649  3214  3214 I bluedroid: get_profile_interface handsfree
,08-16 17:58:18.649  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.649  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:18.649  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.649  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-16 17:58:18.649  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:58:18.649  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService,
,08-16 17:58:18.649  1019  1125 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-16 17:58:18.649  1019  1125 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 17:58:18.649  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.649  1019  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:18.649  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.659  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:58:18.659  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:18.659  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:18.659  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:18.659  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.659  4838  4838 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:18.659  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.659  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.659  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.659  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:58:18.659  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:18.659  3214  3292 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:58:18.659  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:18.659  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 17:58:18.659  1019  1752 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:18.659  1019  1752 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.669  1019  1752 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.669  1019  1752 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.669  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.669  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService,
08-16 17:58:18.669  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:18.669  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:18.669  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService,
,08-16 17:58:18.669  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:58:18.669  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:18.669  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:58:18.669  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 17:58:18.669  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:58:18.669  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:58:18.669  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 17:58:18.669  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:58:18.669  3214  3292 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 17:58:18.669  3214  3214 E DualScoManager: Dual Sco Manager already instantiated
08-16 17:58:18.669  3214  3214 I DualScoManager: Set HeadsetServiceHelper
08-16 17:58:18.669  3214  3214 D BluetoothAtMessage: createCMTIContentObservers,
08-16 17:58:18.669  1019  4803 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-16 17:58:18.669  1019  4803 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:18.669  1019  4803 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:18.669  1019  4803 D SettingsProvider: selectionArgs: false
08-16 17:58:18.669  1019  4803 D SettingsProvider: selectionArgs: 1002
08-16 17:58:18.669  1019  4803 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:58:18.669  1019  4803 D SettingsProvider: ret = -1
08-16 17:58:18.669  3214  7373 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 17:58:18.669  3214  7373 D HeadsetStateMachine: Clear mHeadsetBrsf
08-16 17:58:18.679  3214  7373 D HeadsetStateMachine: map size, before remove : 0
08-16 17:58:18.679  3214  7373 D HeadsetStateMachine: map size, after remove: 0
,08-16 17:58:18.679  3214  3214 D HeadsetService: mStartError = false
,08-16 17:58:18.679  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:18.679  3214  3214 D A2dpService: Received start request. Starting profile...
,08-16 17:58:18.679  3214  3214 D A2dpService: start()
,08-16 17:58:18.679  3214  3214 I bluedroid: get_profile_interface avrcp
,08-16 17:58:18.679  3214  3214 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:58:18.679  3214  3214 D Avrcp   : Initialize Media Controller
08-16 17:58:18.679  3214  3214 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-16 17:58:18.679  3214  3214 E Avrcp   : getActiveSessions
,08-16 17:58:18.679  3214  3214 D Avrcp   : pick active media Controller
08-16 17:58:18.679  3214  3214 D Avrcp   : Get the active Media Controller 
,08-16 17:58:18.689  3214  3214 I Avrcp   :  Updating now playing list upon AVRCP Start,
,08-16 17:58:18.689  3214  7374 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-16 17:58:18.689  3214  3214 D A2dpStateMachine: make
,08-16 17:58:18.689  3214  3214 I bluedroid: get_profile_interface a2dp
,08-16 17:58:18.699  3214  7376 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-16 17:58:18.699  3214  3214 E bt-btif : warning : media task started media_task_refcnt 1 
08-16 17:58:18.699  3214  3214 D A2dpService: mStartError = false
08-16 17:58:18.699  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:18.699  3214  7375 D A2dpStateMachine: Enter Disconnected: -2
08-16 17:58:18.699  3214  3214 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 17:58:18.699  1446  1455 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 17:58:18.699  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-16 17:58:18.699  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:58:18.699  1446  1455 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 17:58:18.699  3214  3214 D HidService: Received start request. Starting profile...
08-16 17:58:18.699  3214  3214 D HidService: start()
08-16 17:58:18.699  3214  3214 I bluedroid: get_profile_interface hidhost
08-16 17:58:18.699  3214  3214 D HidService: setHidService(): set to: null
08-16 17:58:18.699  3214  3214 D HidService: mStartError = false
08-16 17:58:18.699  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
08-16 17:58:18.699  3214  3214 D HeadsetStateMachine: Proxy object connected
08-16 17:58:18.699  3214  3214 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 17:58:18.699  3214  7373 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:58:18.709  3214  3214 D HealthService: Received start request. Starting profile...
08-16 17:58:18.709  3214  3214 D HealthService: start()
,08-16 17:58:18.709  3214  7374 D BluetoothMediaBrowser: no now playing list
08-16 17:58:18.709  3214  7374 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 17:58:18.709  3214  3214 I bluedroid: get_profile_interface health
,08-16 17:58:18.709  3214  3214 D HealthService: mStartError = false
08-16 17:58:18.709  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:18.709  3214  3214 D PanService: Received start request. Starting profile...
08-16 17:58:18.709  3214  3214 D PanService: start()
,08-16 17:58:18.709  3214  3214 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:58:18.709  3214  3214 I bluedroid: get_profile_interface pan
,08-16 17:58:18.709  3214  3214 D PanService: mStartError = false
08-16 17:58:18.709  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:18.709  3214  3214 D BluetoothMapService: Received start request. Starting profile...
,08-16 17:58:18.709  3214  3214 D BluetoothMapService: start()
,08-16 17:58:18.719  3214  3214 D BluetoothMapService: mStartError = false
,08-16 17:58:18.719  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:18.719  3214  3214 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-16 17:58:18.719  3214  3214 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-16 17:58:18.719  3214  7373 D HeadsetStateMachine: Disconnected process message: 18
,08-16 17:58:18.719  3214  3214 D SapService: Received start request. Starting profile...
08-16 17:58:18.719  3214  3214 D SapService: start()
08-16 17:58:18.719  3214  3214 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 17:58:18.719  3214  3214 I bluedroid: get_profile_interface sap
08-16 17:58:18.719  3214  3214 D SapService: mStartError = false
08-16 17:58:18.719  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
08-16 17:58:18.719  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 17:58:18.719  3214  3214 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 17:58:18.719  3214  7373 D HeadsetStateMachine: Disconnected process message: 10
08-16 17:58:18.719  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 17:58:18.719  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 17:58:18.719  3214  7373 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 17:58:18.719  3214  7373 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:58:18.719  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-16 17:58:18.719  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 17:58:18.739  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 17:58:18.739  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 17:58:18.739  3214  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-16 17:58:18.739  3214  3292 I bluedroid: enable
,08-16 17:58:18.749  3214  3295 E bt-btif : Calling BTA_HhEnable
,08-16 17:58:18.749  3214  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-16 17:58:18.749  3214  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-16 17:58:18.749  3214  3295 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 17:58:18.749  3214  3295 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-16 17:58:18.749  3214  3295 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:58:18.749  3214  3295 I bluedroid: getModelRssiValues
08-16 17:58:18.749  3214  3295 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-16 17:58:18.749  3214  3295 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:58:18.749  3214  3295 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-16 17:58:18.759  1019  1019 D SettingsProvider: name = bluetooth_name
,08-16 17:58:18.759  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:18.759  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:18.759  3214  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 17:58:18.759  3214  3295 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:58:18.759  3214  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:58:18.759  3214  3295 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-16 17:58:18.759  3214  3295 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-16 17:58:18.759  3214  3295 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-16 17:58:18.759  3214  3295 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-16 17:58:18.759  3214  3295 E bt-btif : JVenable fails
,08-16 17:58:18.769  3214  3295 D bte_conf: Device ID record 1 : primary
,08-16 17:58:18.769  3214  3295 D bte_conf:   vendorId            = 0075
08-16 17:58:18.769  3214  3295 D bte_conf:   vendorIdSource      = 0001
,08-16 17:58:18.769  3214  3295 D bte_conf:   product             = 0100
,08-16 17:58:18.769  3214  3295 D bte_conf:   version             = 0200
08-16 17:58:18.769  3214  3295 D bte_conf:   clientExecutableURL = 
08-16 17:58:18.769  3214  3295 D bte_conf:   serviceDescription  = 
,08-16 17:58:18.769  3214  3295 D bte_conf:   documentationURL    = 
,08-16 17:58:18.769  3214  3295 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 17:58:18.769  3214  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-16 17:58:18.769  3214  3295 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 17:58:18.769  3214  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 17:58:18.769  3214  3292 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:58:18.769  3214  3292 D BluetoothAdapterProperties: State =  11
,08-16 17:58:18.769  1019  1032 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:58:18.779  3214  3292 D BluetoothAdapterProperties: Setting state to 12,
08-16 17:58:18.779  3214  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 17:58:18.779  3214  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:58:18.779  3214  3295 D BluetoothAdapterProperties: Scan Mode:21
08-16 17:58:18.779  3214  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:58:18.779  1019  1490 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-16 17:58:18.779  1019  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:18.779  1019  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:18.779  1019  1490 D SettingsProvider: selectionArgs: false
,08-16 17:58:18.779  1019  1490 D SettingsProvider: selectionArgs: 1002
,08-16 17:58:18.779  1019  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:58:18.779  1019  1490 D SettingsProvider: ret = -1
08-16 17:58:18.779  3214  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:18.779  3214  3292 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 17:58:18.779  1019  1737 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:18.779  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.779  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.779  1019  1737 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.789  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.789  4838  4846 D BluetoothMap: onBluetoothStateChange: up=true
08-16 17:58:18.789  3214  3214 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-16 17:58:18.789  3214  3214 I BluetoothPbapService: Handler(): got msg=1
,08-16 17:58:18.789  3214  3292 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:18.789  3214  3292 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 17:58:18.789  3214  3292 D BluetoothAdapterService: starting service from this receiver
,08-16 17:58:18.789  1019  1444 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:18.789  1019  1444 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.789  1019  1444 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.789  1019  1444 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.789  1019  1444 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.789  1019  1031 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:58:18.789  3214  3292 I BluetoothAdapterState: Entering On State from state = 11
,08-16 17:58:18.799  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:18.799  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:18.799  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:18.799  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:18.799  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:18.799  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:18.799  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:18.799  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:18.799  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-16 17:58:18.799  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.799  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.799  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.799  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.799  4838  4850 D BluetoothPbap: onBluetoothStateChange: up=true,
,08-16 17:58:18.799  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-16 17:58:18.799  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.799  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:18.799  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.799  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.799  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.799  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:18.809  1019  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:18.809  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:18.809  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.809  3214  3379 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:18.809  3214  7381 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 17:58:18.809  3214  3379 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:18.809  1019  1048 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:18.809  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.809  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:18.809  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:18.809  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:18.809  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:18.809  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:18.809  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:18.809  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:18.809  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:18.809  4838  4838 D BluetoothMap: Proxy object connected
08-16 17:58:18.809  4838  4838 D MapProfile: Bluetooth service connected
08-16 17:58:18.809  4838  4838 D BluetoothMap: getConnectedDevices()
,08-16 17:58:18.809  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.809  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.809  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.819  1446  6878 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-16 17:58:18.819  1019  1019 D BluetoothA2dp: Proxy object connected
,08-16 17:58:18.819  3214  3214 D BluetoothA2dp: Proxy object connected
08-16 17:58:18.819  3214  3214 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-16 17:58:18.819  4838  4838 D BluetoothPbap: Proxy object connected
08-16 17:58:18.819  4838  4838 D PbapServerProfile: Bluetooth service connected
08-16 17:58:18.819  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:18.819  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:18.819  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:18.819  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.819  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.819  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.819  1446  6878 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:18.819  4838  5529 D BluetoothPan: Binding service...
08-16 17:58:18.819  3214  7381 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:58:18.819  3214  7381 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:18.819  3214  7381 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-16 17:58:18.819  3214  7381 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:18.819  3214  7381 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:18.819  3214  7381 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18c0fb38
,08-16 17:58:18.819  3214  7381 D BluetoothSocket: channel: 19
08-16 17:58:18.819  3214  7381 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 17:58:18.819  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-16 17:58:18.819  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.819  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.819  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.819  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.819  4838  4838 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:58:18.819  1446  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:18.829  4838  4838 D PanProfile: Bluetooth service connected
08-16 17:58:18.829  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:18.829  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:18.829  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.829  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.829  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.829  1446  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:18.829  4838  4846 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:18.829  4838  4846 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:18.829  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:18.829  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:18.829  4838  4850 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:18.829  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:18.829  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:18.829  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.829  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.829  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.829  4838  4850 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:18.829  4838  4850 D Bluetoothsap: onBluetoothStateChange: up=true
08-16 17:58:18.829  4838  4850 D Bluetoothsap: Binding service...
08-16 17:58:18.829  4838  4838 D HeadsetProfile: Bluetooth service connected
,08-16 17:58:18.829  4838  4850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 17:58:18.839  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-16 17:58:18.839  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.839  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.839  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.839  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.839  4838  4850 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 17:58:18.839  1470  1681 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:18.839  1470  1681 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:18.839  6880  6894 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:18.839  6880  6894 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:18.839  1446  6878 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:18.839  1446  6878 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:18.839  6547  6556 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:18.839  6547  6556 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:18.839  4838  4838 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 17:58:18.839  1019  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-16 17:58:18.839  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:18.839  4838  4838 D SapProfile: Bluetooth service connected
08-16 17:58:18.839  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:58:18.839  4838  4838 D Bluetoothsap: getConnectedDevices()
08-16 17:58:18.839  1019  1048 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:18.839  4838  4846 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:18.839  4838  4846 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:18.839  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:18.839  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.839  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.839  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.839  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.849  1756  1775 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:18.849  1756  1775 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:18.849  4838  4838 D BluetoothA2dp: Proxy object connected
08-16 17:58:18.849  4838  4838 D A2dpProfile: Bluetooth service connected
08-16 17:58:18.849  1182  4315 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:18.849  1182  4315 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:18.849  1462  1767 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:58:18.849  1462  1767 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:18.849  4838  5529 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:58:18.849  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-16 17:58:18.849  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.849  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.849  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:18.849  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.849  3214  3227 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:58:18.849  3214  3227 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:18.849  1019  1048 D BluetoothPan: Binding service...
,08-16 17:58:18.849  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:58:18.849  4838  4838 D BluetoothInputDevice: Proxy object connected
08-16 17:58:18.849  4838  4838 D HidProfile: Bluetooth service connected
,08-16 17:58:18.849  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.849  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:58:18.859  1470  1483 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:18.859  1019  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:58:18.859  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:18.859  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.859  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.859  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.859  1470  1483 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:18.859  1446  3368 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:18.859  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:58:18.859  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:18.859  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.859  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.859  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.859  1446  3368 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:18.859  2634  4414 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:58:18.859  2634  4414 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:18.859  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 17:58:18.869  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:58:18.869  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-16 17:58:18.869  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
08-16 17:58:18.869  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:58:18.869  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:58:18.869  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:58:18.879  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:18.879  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:18.879  1182  1182 D BluetoothTile:  getBluetoothState : 12
,08-16 17:58:18.879  1446  1446 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@38d8cd92, true
,08-16 17:58:18.879  1879  1879 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:18.879  4838  4838 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:18.879  1446  1446 D BluetoothHeadset: registerMessageListener
,08-16 17:58:18.879  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:18.889  3214  7382 D HeadsetService: registerMessageListener
,08-16 17:58:18.889  3214  7382 D HeadsetService: registerMessageListener
,08-16 17:58:18.889  3214  7373 D HeadsetStateMachine: Disconnected process message: 70
,08-16 17:58:18.889  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 17:58:18.889  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 17:58:18.889  3214  7373 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1c063711
08-16 17:58:18.889  4838  4838 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-16 17:58:18.889  4838  4838 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-16 17:58:18.889  4838  4838 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 17:58:18.889  4838  4838 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-16 17:58:18.889  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:18.889  1019  1449 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:18.899  3214  7383 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 17:58:18.899  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:18.899  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 17:58:18.899  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-16 17:58:18.899  1019  1125 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-16 17:58:18.899  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:18.899  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 17:58:18.899  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:18.899  3214  7373 D HeadsetStateMachine: Disconnected process message: 9
08-16 17:58:18.899  3214  7373 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 17:58:18.899   283   680 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-16 17:58:18.899   283   680 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 17:58:18.899   283   680 V voice   : voice_set_parameters: exit with code(-2)
08-16 17:58:18.899   283   680 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 17:58:18.899   283   680 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 17:58:18.899   283   680 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 17:58:18.899   283   680 V audio_hw_primary: adev_set_parameters: exit
08-16 17:58:18.899  3214  7383 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:58:18.899  3214  7383 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:58:18.909  3214  7373 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 17:58:18.909  4838  4838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:18.909  1019  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:58:18.909  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.909  3214  7383 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-16 17:58:18.909  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.909  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.909  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:18.909  3214  7383 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:18.909  3214  7383 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:18.909  3214  7383 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b92d076
08-16 17:58:18.909  3214  7383 D BluetoothSocket: channel: 5
,08-16 17:58:18.909  2634  2634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:18.919  4838  4838 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:18.919  4838  4838 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:18.919  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:18.929  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 17:58:18.929  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:18.929  3214  3214 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:58:18.929  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:18.929  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.939  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.939  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.939  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.949  1019  1737 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:58:18.959  3214  7389 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:58:18.959  3214  7389 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:18.959  3214  7389 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-16 17:58:18.959  3214  7389 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:18.959  3214  7389 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:18.959  3214  7389 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37537e02
08-16 17:58:18.959  3214  7389 D BluetoothSocket: channel: 12
08-16 17:58:18.959  3214  7389 I BtOppRfcommListener: Accept thread started.
,08-16 17:58:19.249   288   288 E SMD     : DCD OFF
,08-16 17:58:19.269   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-16 17:58:20.159  1019  1499 I ActivityManager: Killing 6968:com.sec.pcw.device/1000 (adj 15): empty #21
,08-16 17:58:20.199  1019  1044 W ActivityManager: mDVFSHelper.release()
,08-16 17:58:20.259  1019  1491 I ActivityManager: Killing 6985:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-16 17:58:21.599  6547  6683 D BluetoothAdapter: disable()
,08-16 17:58:21.619  1019  1031 D SettingsProvider: name = bluetooth_on,
,08-16 17:58:21.629  3214  3292 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-16 17:58:21.629  1019  1444 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:21.629  3214  3292 D BluetoothAdapterProperties: Setting state to 13
08-16 17:58:21.629  1019  1444 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-16 17:58:21.629  3214  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:58:21.629  3214  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:21.629  3214  3292 D BluetoothAdapterService: updateAdapterState state is 13
08-16 17:58:21.629  1019  1444 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:21.629  1019  1444 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:21.629  1019  1444 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:21.629  3214  3292 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:21.629  3214  3292 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 17:58:21.629  3214  3292 D BluetoothAdapterService: terminating service from this receiver
,08-16 17:58:21.629  3214  3214 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-16 17:58:21.629  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:21.629  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,08-16 17:58:21.639  3214  3214 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@367d7313, channel: 19, state: LISTENING
,08-16 17:58:21.639  3214  3214 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@367d7313, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18c0fb38, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2bf950mSocket: android.net.LocalSocket@1c8fb749 impl:android.net.LocalSocketImpl@3e7f784e fd:FileDescriptor[80]
,08-16 17:58:21.639  3214  3214 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c8fb749 impl:android.net.LocalSocketImpl@3e7f784e fd:FileDescriptor[80]
,08-16 17:58:21.649  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:58:21.649  1879  1879 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:21.649  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:58:21.649  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:21.649  1182  1182 D BluetoothTile:  getBluetoothState : 13
,08-16 17:58:21.659  4838  4838 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:21.659  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:21.659  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:21.669  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:21.669  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:21.669  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:21.669  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:21.669  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:21.669  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:21.669  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:21.669  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:21.669  1019  1125 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.669  1019  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:21.669  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:21.669  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:21.669  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
08-16 17:58:21.669  1019  4459 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:58:21.669  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:21.679  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:21.679  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:21.679  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:21.679  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:21.679  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:21.679  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:21.679  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:21.679  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:21.679  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:21.679  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:21.679  1019  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:21.679  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:21.679  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:21.679  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:21.679  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:58:21.679  3214  3292 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:58:21.679  3214  3292 D BluetoothAdapterProperties: mDiscovering is false
,08-16 17:58:21.679  1019  1752 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:58:21.679  4838  4838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:21.689  1019  1490 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:58:21.689  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.689  3214  3292 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 17:58:21.689  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:21.689  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:21.689  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:21.689  4838  4838 D BluetoothPbap: Proxy object disconnected
,08-16 17:58:21.689  4838  4838 D PbapServerProfile: Bluetooth service disconnected
,08-16 17:58:21.699  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:21.699  3214  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 17:58:21.709  3214  3295 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:58:21.709  2634  2634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:21.709  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:21.709  3214  3214 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d422d6f, channel: 5, state: LISTENING
,08-16 17:58:21.709  3214  3214 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@d422d6f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b92d076, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@21df5a7cmSocket: android.net.LocalSocket@31937f05 impl:android.net.LocalSocketImpl@f5ecb5a fd:FileDescriptor[82],
08-16 17:58:21.709  3214  3214 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31937f05 impl:android.net.LocalSocketImpl@f5ecb5a fd:FileDescriptor[82]
08-16 17:58:21.709  3214  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-16 17:58:21.709  3214  3214 I BtOppRfcommListener: stopping Accept Thread
08-16 17:58:21.709  3214  3214 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@eee318b, channel: 12, state: LISTENING
08-16 17:58:21.709  3214  3292 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-16 17:58:21.709  3214  3214 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@eee318b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37537e02, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@b05a268mSocket: android.net.LocalSocket@2d520681 impl:android.net.LocalSocketImpl@12ae4326 fd:FileDescriptor[86]
,08-16 17:58:21.709  3214  3214 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d520681 impl:android.net.LocalSocketImpl@12ae4326 fd:FileDescriptor[86]
08-16 17:58:21.709  3214  7389 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 17:58:21.709  3214  7389 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 17:58:21.709  3214  3292 E bt-btif : cmd socket is not created
08-16 17:58:21.709  3214  3292 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 17:58:21.719  3214  3296 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-16 17:58:21.719  4838  4838 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:21.719  3214  3214 V BluetoothOppManager: cleanUp...
,08-16 17:58:21.729  4838  4838 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:21.729  3214  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:21.729  3214  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:21.729  3214  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:58:21.729  3214  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:21.729  3214  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:21.729  3214  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 17:58:21.729  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:21.729  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 17:58:21.929  3214  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
08-16 17:58:21.929  1019  1444 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:21.929  3214  3292 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:58:21.929  1019  1444 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-16 17:58:21.929  3214  3292 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-16 17:58:21.929  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-16 17:58:21.929  3214  3292 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-16 17:58:21.929  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:58:21.929  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:58:21.929  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-16 17:58:21.929  1019  1444 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:21.929  1019  1444 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:21.929  1019  1444 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:21.929  3214  3214 D HeadsetService: Received stop request...Stopping profile...
08-16 17:58:21.929  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
,08-16 17:58:21.929  1019  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:21.929  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:21.929  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-16 17:58:21.929  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-16 17:58:21.929  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
08-16 17:58:21.929  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:21.929  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:21.929  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:21.929  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 17:58:21.929  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-16 17:58:21.929  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:21.929  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:58:21.929  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:21.929  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.929  4838  4838 D HeadsetProfile: Bluetooth service disconnected
,08-16 17:58:21.929  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:21.929  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:21.929  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:21.939  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:58:21.939  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:58:21.939  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:58:21.939  1019  1737 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:21.939  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.939  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:21.939  1019  1737 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:21.939  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:21.939  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-16 17:58:21.939  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:58:21.939  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:58:21.939  1019  1737 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:21.939  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.939  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:21.939  1019  1737 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:21.939  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:21.939  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:58:21.939  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:21.939  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:21.939  1019  1125 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:21.939  1019  1125 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.939  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:21.939  1019  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:21.939  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:21.949  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-16 17:58:21.949  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:58:21.949  3214  3292 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:58:21.949  1019  4459 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:21.949  1019  4459 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.949  1019  4459 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:21.949  1019  4459 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:21.949  1019  4459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:21.949  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:21.949  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:21.949  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:21.949  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:21.949  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:58:21.949  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:21.949  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:58:21.949  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:21.949  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:58:21.949  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:58:21.949  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:58:21.949  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:58:21.949  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-16 17:58:21.949  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:21.959  3214  3214 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 17:58:21.959  3214  3292 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-16 17:58:21.959  3214  3214 D A2dpService: Received stop request...Stopping profile...
,08-16 17:58:21.959  3214  7375 D A2dpStateMachine: Exit Disconnected: -1
,08-16 17:58:21.959  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:21.959  1019  1019 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:21.959  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 17:58:21.959  4838  4838 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:21.959  4838  4838 D A2dpProfile: Bluetooth service disconnected
,08-16 17:58:21.959  3214  3214 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:58:21.959  3214  3214 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 17:58:21.959  3214  3214 D HidService: Received stop request...Stopping profile...
08-16 17:58:21.969  3214  3214 D HidService: Stopping Bluetooth HidService
08-16 17:58:21.969  3214  3214 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:58:21.969  3214  3214 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 17:58:21.969  3214  3214 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:58:21.969  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:21.969  3214  3214 D HealthService: Received stop request...Stopping profile...
08-16 17:58:21.969  4838  4838 D BluetoothInputDevice: Proxy object disconnected
08-16 17:58:21.969  4838  4838 D HidProfile: Bluetooth service disconnected
,08-16 17:58:21.969  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:21.969  3214  3214 D PanService: Received stop request...Stopping profile...
08-16 17:58:21.969  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:21.969  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:58:21.969  4838  4838 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:58:21.969  4838  4838 D PanProfile: Bluetooth service disconnected
,08-16 17:58:21.969  3214  3214 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:21.979  3214  3214 D SapService: Received stop request...Stopping profile...
08-16 17:58:21.979  3214  3214 D SapService: Stopping Bluetooth SapService
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:21.979  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-16 17:58:21.979  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 17:58:21.979  3214  3214 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-16 17:58:21.979  4838  4838 D BluetoothMap: Proxy object disconnected
,08-16 17:58:21.979  3214  7376 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 17:58:21.979  3214  3214 I GKI_LINUX: GKI_exit_task 2 done
08-16 17:58:21.979  3214  3214 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 17:58:21.979  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 17:58:21.979  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:21.979  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-16 17:58:21.979  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:21.979  3214  3214 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:58:21.979  3214  3214 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:58:21.979  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 17:58:21.979  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:21.979  3214  3214 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:58:21.979  3214  3214 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:58:21.979  4838  4838 D MapProfile: Bluetooth service disconnected
,08-16 17:58:21.979  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-16 17:58:21.979  3214  3214 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-16 17:58:21.979  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-16 17:58:21.979  3214  3214 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-16 17:58:21.979  3214  3214 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 17:58:21.979  3214  3214 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-16 17:58:21.989  4838  4838 D Bluetoothsap: BluetoothSAP Proxy object disconnected,
08-16 17:58:21.989  4838  4838 D SapProfile: Bluetooth service disconnected
08-16 17:58:21.989  3214  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 17:58:21.989  3214  3292 D BluetoothAdapterProperties: Setting state to 10
08-16 17:58:21.989  3214  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 17:58:21.989  3214  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 17:58:21.989  3214  3292 D BluetoothAdapterService: updateAdapterState state is 10
08-16 17:58:21.989  3214  3292 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:21.989  3214  3292 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 17:58:21.989  3214  3292 I BluetoothAdapterState: Entering OffState
08-16 17:58:21.989  4838  5529 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 17:58:21.989  4838  4846 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 17:58:21.989  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:21.989  3214  3227 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:21.989  4838  5529 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:21.989  4838  5529 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:21.989  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:21.989  1019  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:21.989  4838  4850 D Bluetoothsap: onBluetoothStateChange: up=false
,08-16 17:58:21.989  4838  4850 D Bluetoothsap: Unbinding service...
,08-16 17:58:21.999  1470  1483 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:21.999  1470  1483 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:21.999  6880  6896 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:21.999  6880  6896 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:21.999  1446  1455 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:21.999  1446  1455 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:21.999  6547  6556 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:21.999  6547  6556 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:21.999  6547  6556 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-16 17:58:21.999  6547  6556 D BluetoothLeAdvertiser: Exit stop advertising
,08-16 17:58:21.999  6547  6556 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 17:58:21.999  6547  6556 D BluetoothLeScanner: Exiting stopAllScan
,08-16 17:58:21.999  4838  5529 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:21.999  1756  1765 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:21.999  1756  1765 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:21.999  1182  1898 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:21.999  1182  1898 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:21.999  1462  1480 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:21.999  1462  1480 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:21.999  4838  4846 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 17:58:22.009  3214  3349 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:22.009  3214  3349 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:22.009  2634  2644 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:22.009  2634  2644 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:22.009  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:22.009  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
08-16 17:58:22.009  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:58:22.009  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:58:22.019  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:22.019  1182  1182 D BluetoothTile:  getBluetoothState : 10
,08-16 17:58:22.019  1019  1444 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:22.019  1019  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:58:22.019  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:22.019  1879  1879 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:22.029  4838  4838 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:22.029  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:22.029  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:22.029  4838  4838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:22.029  1019  1499 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 17:58:22.029  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:22.029  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:22.029  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:22.029  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:22.039  4838  4838 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:22.039  2634  2634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:22.039  4838  4838 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:22.049  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:22.049  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 17:58:22.239   288   288 E SMD     : DCD OFF,
,08-16 17:58:23.179  1019  3382 D SSRM:n  : SIOP:: AP = 340
,08-16 17:58:23.859  1019  3411 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:58:24.269   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:24.629  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:24.629  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:25.249   288   288 E SMD     : DCD OFF
,08-16 17:58:25.269   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:26.269   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:26.299  1019  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:58:26.299  1019  1499 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-16 17:58:26.299  1019  1499 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-16 17:58:26.299  1019  1499 D BatteryService: stay LED for charging
,08-16 17:58:26.299  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:58:26.299  1019  1019 I MotionRecognitionService: Plugged
,08-16 17:58:26.299  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:58:26.309  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:58:26.309  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-16 17:58:26.309  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-16 17:58:26.309  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 17:58:26.329  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 17:58:26.329  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 17:58:26.329  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 17:58:26.329  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-16 17:58:26.329  1182  1182 D SViewCoverView: level :100 plugged : 2
,08-16 17:58:27.269   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:27.629  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:27.629  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@220ba3de added. We now have 6 listener(s)
,08-16 17:58:27.629  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:27.629  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:27.629  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@269699bf added. We now have 7 listener(s)
,08-16 17:58:27.629  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:27.629  6547  6683 I System.out: IsBluetoothEnabled
,08-16 17:58:27.639  6547  6683 D BluetoothAdapter: disable()
,08-16 17:58:27.639  1019  1125 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-16 17:58:27.639  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:27.649  6547  6683 D BluetoothAdapter: enable(),
,08-16 17:58:27.649  1019  1032 W ActivityManager: Permission Denial: getCurrentUser() from pid=6547, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:58:27.649  1019  1032 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 17:58:27.649  1019  1032 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6547, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:27.649  1019  1032 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 17:58:27.649  1019  1032 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-16 17:58:27.649  1019  1032 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-16 17:58:27.649  1019  1032 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-16 17:58:27.649  1019  1032 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:58:27.649  1019  1032 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:58:27.649  1019  1032 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:27.659  1019  1032 D SettingsProvider: name = bluetooth_on,
,08-16 17:58:27.669  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:58:27.669  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:27.669  1019  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 17:58:27.679  3214  3292 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-16 17:58:27.679  3214  3292 D BluetoothAdapterProperties: Setting state to 11
08-16 17:58:27.679  3214  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 17:58:27.679  3214  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:27.679  3214  3292 D BluetoothAdapterService: updateAdapterState state is 11
08-16 17:58:27.679  3214  3292 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:27.679  3214  3292 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-16 17:58:27.679  3214  3292 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-16 17:58:27.679  3214  3292 W BluetoothAdap,terService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:58:27.679  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:58:27.679  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-16 17:58:27.679  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:27.679  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
08-16 17:58:27.679  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:58:27.679  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:27.689  1182  1182 D BluetoothTile:  getBluetoothState : 11
,08-16 17:58:27.689  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:58:27.689  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:58:27.689  4838  4838 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:27.689  1879  1879 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:27.689  1019  4803 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:27.689  1019  4803 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.699  1019  4803 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:27.699  1019  4803 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:27.699  1019  4803 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.699  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:27.709  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:58:27.709  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:58:27.709  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:27.709  2634  2634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:58:27.709  1019  1032 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:58:27.709  3214  3214 D HeadsetService: Received start request. Starting profile...
08-16 17:58:27.709  1019  4459 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:27.709  3214  3214 D HeadsetService: start()
08-16 17:58:27.709  3214  3214 D HeadsetStateMachine: make
,08-16 17:58:27.709  1019  4459 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.709  3214  3214 E HeadsetStateMachine: # of Max HF connection is 2
08-16 17:58:27.709  1019  4459 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:27.709  1019  4459 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:27.709  1019  4459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.719  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-16 17:58:27.719  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:27.719  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:58:27.719  1019  1444 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:58:27.719  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:27.719  1019  1449 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-16 17:58:27.719  1019  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.719  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:27.719  1019  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:27.719  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:58:27.719  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:27.719  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.719  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:27.719  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:27.719  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.729  4838  4838 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:27.729  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:58:27.729  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:58:27.729  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:58:27.729  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:27.729  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.729  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:27.729  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:27.729  1019  1752 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-16 17:58:27.729  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:27.729  1019  1752 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.729  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-16 17:58:27.729  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:58:27.729  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:58:27.739  1019  1752 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:27.739  1019  1752 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:27.739  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:58:27.739  3214  3214 I bluedroid: get_profile_interface handsfree
,08-16 17:58:27.739  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:27.739  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-16 17:58:27.739  1019  4459 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:27.739  1019  4459 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.739  1019  4459 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:27.739  1019  4459 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:27.739  1019  4459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.749  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:58:27.749  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:27.749  3214  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:27.749  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-16 17:58:27.749  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-16 17:58:27.749  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:27.749  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:27.749  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.749  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:58:27.749  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:27.749  3214  3292 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:58:27.759  1019  1737 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:27.759  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.759  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:27.759  1019  1737 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:27.759  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.759  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:27.759  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:27.759  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:27.759  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:27.759  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:27.759  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:27.759  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:58:27.759  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:27.759  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:58:27.759  3214  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:58:27.759  3214  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:58:27.759  3214  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:58:27.759  3214  3292 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 17:58:27.759  3214  3214 E DualScoManager: Dual Sco Manager already instantiated
08-16 17:58:27.759  3214  3214 I DualScoManager: Set HeadsetServiceHelper
08-16 17:58:27.759  3214  3214 D BluetoothAtMessage: createCMTIContentObservers
,08-16 17:58:27.759  1019  1125 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-16 17:58:27.759  1019  1125 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:27.759  1019  1125 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:27.759  1019  1125 D SettingsProvider: selectionArgs: false
,08-16 17:58:27.759  1019  1125 D SettingsProvider: selectionArgs: 1002
08-16 17:58:27.759  1019  1125 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:27.759  1019  1125 D SettingsProvider: ret = -1
,08-16 17:58:27.759  3214  7402 D HeadsetStateMachine: Enter Disconnected: -2
08-16 17:58:27.759  3214  3214 D HeadsetService: mStartError = false
08-16 17:58:27.759  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:27.769  3214  3214 D A2dpService: Received start request. Starting profile...
,08-16 17:58:27.769  3214  3214 D A2dpService: start()
08-16 17:58:27.769  3214  3214 I bluedroid: get_profile_interface avrcp
,08-16 17:58:27.769  3214  7402 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-16 17:58:27.769  3214  7402 D HeadsetStateMachine: map size, before remove : 0
08-16 17:58:27.769  3214  7402 D HeadsetStateMachine: map size, after remove: 0
,08-16 17:58:27.769  3214  3214 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:58:27.769  3214  3214 D Avrcp   : Initialize Media Controller
08-16 17:58:27.769  3214  3214 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-16 17:58:27.769  3214  3214 E Avrcp   : getActiveSessions
,08-16 17:58:27.769  3214  3214 D Avrcp   : pick active media Controller
08-16 17:58:27.769  3214  3214 D Avrcp   : Get the active Media Controller 
,08-16 17:58:27.779  3214  3214 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 17:58:27.779  3214  7403 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 17:58:27.779  3214  3214 D A2dpStateMachine: make
,08-16 17:58:27.779  3214  3214 I bluedroid: get_profile_interface a2dp
,08-16 17:58:27.779  3214  7405 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 17:58:27.779  3214  3214 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 17:58:27.789  3214  3214 D A2dpService: mStartError = false
,08-16 17:58:27.789  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
08-16 17:58:27.789  3214  3214 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 17:58:27.789  3214  7404 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:58:27.789  1446  1457 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 17:58:27.789  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-16 17:58:27.789  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:58:27.789  1446  1457 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 17:58:27.789  3214  3214 D HidService: Received start request. Starting profile...
08-16 17:58:27.789  3214  3214 D HidService: start()
08-16 17:58:27.789  3214  3214 I bluedroid: get_profile_interface hidhost
08-16 17:58:27.789  3214  3214 D HidService: setHidService(): set to: null
08-16 17:58:27.789  3214  3214 D HidService: mStartError = false
08-16 17:58:27.789  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:27.789  3214  3214 D HealthService: Received start request. Starting profile...
08-16 17:58:27.789  3214  3214 D HealthService: start()
,08-16 17:58:27.799  3214  3214 I bluedroid: get_profile_interface health
08-16 17:58:27.799  3214  7403 D BluetoothMediaBrowser: no now playing list
08-16 17:58:27.799  3214  3214 D HealthService: mStartError = false
08-16 17:58:27.799  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:27.799  3214  3214 D HeadsetStateMachine: Proxy object connected
08-16 17:58:27.799  3214  3214 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 17:58:27.799  3214  7402 D HeadsetStateMachine: Disconnected process message: 11
08-16 17:58:27.799  3214  7403 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 17:58:27.799  3214  3214 D PanService: Received start request. Starting profile...
,08-16 17:58:27.799  3214  3214 D PanService: start()
08-16 17:58:27.799  3214  3214 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:58:27.799  3214  3214 I bluedroid: get_profile_interface pan
,08-16 17:58:27.799  3214  3214 D PanService: mStartError = false
08-16 17:58:27.799  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:27.799  3214  3214 D BluetoothMapService: Received start request. Starting profile...
,08-16 17:58:27.799  3214  3214 D BluetoothMapService: start()
,08-16 17:58:27.799  3214  3214 D BluetoothMapService: mStartError = false
,08-16 17:58:27.799  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:27.799  3214  3214 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-16 17:58:27.799  3214  3214 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-16 17:58:27.809  3214  7402 D HeadsetStateMachine: Disconnected process message: 18
08-16 17:58:27.809  3214  3214 D SapService: Received start request. Starting profile...
08-16 17:58:27.809  3214  3214 D SapService: start()
08-16 17:58:27.809  3214  3214 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 17:58:27.809  3214  3214 I bluedroid: get_profile_interface sap,
08-16 17:58:27.809  3214  3214 D SapService: mStartError = false
08-16 17:58:27.809  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
08-16 17:58:27.809  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 17:58:27.809  3214  3214 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-16 17:58:27.809  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 17:58:27.809  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 17:58:27.809  3214  7402 D HeadsetStateMachine: Disconnected process message: 10
08-16 17:58:27.809  3214  7402 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:58:27.809  3214  7402 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:58:27.809  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-16 17:58:27.809  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 17:58:27.819  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 17:58:27.819  3214  3214 E BluetoothAdapterService(104793583): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 17:58:27.829  3214  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-16 17:58:27.829  3214  3292 I bluedroid: enable,
08-16 17:58:27.829  3214  3295 E bt-btif : Calling BTA_HhEnable
08-16 17:58:27.829  3214  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-16 17:58:27.829  3214  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-16 17:58:27.829  3214  3295 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-16 17:58:27.829  3214  3295 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-16 17:58:27.829  3214  3295 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:58:27.829  3214  3295 I bluedroid: getModelRssiValues
08-16 17:58:27.829  3214  3295 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 17:58:27.829  3214  3295 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:58:27.829  1019  1019 D SettingsProvider: name = bluetooth_name
,08-16 17:58:27.829  3214  3295 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-16 17:58:27.839  3214  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:58:27.839  3214  3295 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:58:27.839  3214  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:58:27.839  3214  3295 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-16 17:58:27.839  3214  3295 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-16 17:58:27.839  3214  3295 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-16 17:58:27.839  3214  3295 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 17:58:27.839  3214  3295 E bt-btif : JVenable fails
,08-16 17:58:27.839  3214  3295 D bte_conf: Device ID record 1 : primary
08-16 17:58:27.839  3214  3295 D bte_conf:   vendorId            = 0075
08-16 17:58:27.839  3214  3295 D bte_conf:   vendorIdSource      = 0001
,08-16 17:58:27.839  3214  3295 D bte_conf:   product             = 0100
08-16 17:58:27.839  3214  3295 D bte_conf:   version             = 0200
08-16 17:58:27.839  3214  3295 D bte_conf:   clientExecutableURL = 
08-16 17:58:27.839  3214  3295 D bte_conf:   serviceDescription  = 
08-16 17:58:27.839  3214  3295 D bte_conf:   documentationURL    = 
08-16 17:58:27.839  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:27.839  3214  3295 D bte_conf: bte_load_did_conf no section named DID2.
08-16 17:58:27.839  3214  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-16 17:58:27.839  3214  3295 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 17:58:27.839  3214  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 17:58:27.839  3214  3292 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:58:27.839  3214  3292 D BluetoothAdapterProperties: State =  11
,08-16 17:58:27.839  1019  1032 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:58:27.839  3214  3292 D BluetoothAdapterProperties: Setting state to 12
,08-16 17:58:27.839  3214  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 17:58:27.849  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:27.849  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:27.849  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:27.849  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:27.849  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:27.849  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:27.849  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:27.849  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:27.849  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:27.849  3214  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 17:58:27.849  3214  3295 D BluetoothAdapterProperties: Scan Mode:21
,08-16 17:58:27.859  3214  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:58:27.859  1019  1444 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-16 17:58:27.859  1019  1444 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:58:27.859  1019  1444 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:27.859  1019  1444 D SettingsProvider: selectionArgs: false
08-16 17:58:27.859  1019  1444 D SettingsProvider: selectionArgs: 1002
,08-16 17:58:27.859  1019  1444 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:27.859  1019  1444 D SettingsProvider: ret = -1
,08-16 17:58:27.859  3214  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:27.859  3214  3292 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 17:58:27.859  1019  1737 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:27.859  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.859  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:27.859  1019  1737 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:27.859  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.859  3214  3292 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:27.859  4838  4846 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:58:27.859  3214  3292 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 17:58:27.859  3214  3292 D BluetoothAdapterService: starting service from this receiver
,08-16 17:58:27.869  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:27.869  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.869  3214  3214 I BluetoothPbapService: Handler(): got msg=1
,08-16 17:58:27.869  1019  1752 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:58:27.869  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:27.869  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:27.869  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.869  3214  3292 I BluetoothAdapterState: Entering On State from state = 11
,08-16 17:58:27.879  3214  3214 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 17:58:27.879  3214  7410 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 17:58:27.879  3214  7410 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 17:58:27.879  3214  7410 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:27.879  3214  7410 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-16 17:58:27.879  3214  7410 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:27.879  3214  7410 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-16 17:58:27.879  3214  7410 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ede82e3
,08-16 17:58:27.889  3214  7410 D BluetoothSocket: channel: 19
08-16 17:58:27.889  3214  7410 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 17:58:28.019  1019  1048 I art     : Explicit concurrent mark sweep GC freed 58838(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.297ms total 143.951ms
,08-16 17:58:28.019  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 17:58:28.019  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.019  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.019  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.019  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.019  4838  4850 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:58:28.019  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-16 17:58:28.019  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.019  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.019  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.019  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.029  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:28.029  1019  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-16 17:58:28.029  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:28.029  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.029  3214  3223 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:28.029  3214  3223 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.029  1019  1048 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:28.029  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.029  4838  4838 D BluetoothMap: Proxy object connected
08-16 17:58:28.029  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.029  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.029  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.029  4838  4838 D MapProfile: Bluetooth service connected
08-16 17:58:28.029  4838  4838 D BluetoothMap: getConnectedDevices()
,08-16 17:58:28.039  3214  3214 D BluetoothA2dp: Proxy object connected,
08-16 17:58:28.039  3214  3214 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-16 17:58:28.039  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:58:28.039  1446  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-16 17:58:28.039  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:58:28.039  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.039  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:28.039  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-16 17:58:28.039  1019  1019 D BluetoothA2dp: Proxy object connected
,08-16 17:58:28.039  1446  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.039  4838  4846 D BluetoothPan: Binding service...
,08-16 17:58:28.039  4838  4838 D BluetoothPbap: Proxy object connected
08-16 17:58:28.039  4838  4838 D PbapServerProfile: Bluetooth service connected
,08-16 17:58:28.039  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:58:28.039  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.049  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.049  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.049  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.049  4838  4838 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:58:28.049  4838  4838 D PanProfile: Bluetooth service connected
,08-16 17:58:28.049  1446  1455 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.049  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:28.049  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:28.049  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.049  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.049  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.049  1446  1455 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.049  4838  5529 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:58:28.049  4838  5529 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:28.049  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:58:28.049  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.049  4838  4846 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.049  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:58:28.059  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:28.059  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:28.059  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.059  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.059  4838  4838 D HeadsetProfile: Bluetooth service connected
,08-16 17:58:28.059  4838  4846 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.059  4838  5529 D Bluetoothsap: onBluetoothStateChange: up=true
08-16 17:58:28.059  4838  5529 D Bluetoothsap: Binding service...
,08-16 17:58:28.059  4838  5529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 17:58:28.059  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-16 17:58:28.059  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.059  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.059  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.059  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.059  4838  5529 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-16 17:58:28.059  1470  1483 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.059  1470  1483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.059  6880  6894 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.059  6880  6894 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:28.059  4838  4838 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 17:58:28.059  4838  4838 D SapProfile: Bluetooth service connected
08-16 17:58:28.059  4838  4838 D Bluetoothsap: getConnectedDevices()
,08-16 17:58:28.069  1446  6878 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.069  1446  6878 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.069  6547  6555 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.069  6547  6555 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.069  1019  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-16 17:58:28.069  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:28.069  1019  1048 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.069  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:58:28.069  4838  4846 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:28.069  4838  4846 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.069  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:28.069  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.069  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.069  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.069  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.069  4838  4838 D BluetoothA2dp: Proxy object connected
08-16 17:58:28.069  4838  4838 D A2dpProfile: Bluetooth service connected
08-16 17:58:28.069  1756  1775 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.069  1756  1775 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.069  1182  4030 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.069  1182  4030 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.069  1462  1767 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.069  1462  1767 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.069  4838  5529 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:58:28.069  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-16 17:58:28.069  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.079  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:28.079  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.079  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.079  4838  4838 D BluetoothInputDevice: Proxy object connected
08-16 17:58:28.079  4838  4838 D HidProfile: Bluetooth service connected
,08-16 17:58:28.079  3214  3349 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.079  3214  3349 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.079  1019  1048 D BluetoothPan: Binding service...
08-16 17:58:28.079  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:58:28.079  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.079  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:58:28.079  1470  2712 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.079  1019  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:28.079  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:28.079  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.079  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.079  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.079  1470  2712 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.089  1446  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.089  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:28.089  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:28.089  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.089  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.089  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.089  1446  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.089  2634  4572 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.089  2634  4572 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:28.089  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 17:58:28.089  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:58:28.089  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:28.089  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
08-16 17:58:28.089  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:58:28.099  1446  1446 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@13de3363, true
,08-16 17:58:28.099  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:58:28.099  1446  1446 D BluetoothHeadset: registerMessageListener
,08-16 17:58:28.099  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:58:28.099  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:58:28.099  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:28.099  1182  1182 D BluetoothTile:  getBluetoothState : 12
,08-16 17:58:28.099  1879  1879 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:28.099  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:28.099  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:28.109  4838  4838 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:28.109  1019  1499 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:28.109  3214  3223 D HeadsetService: registerMessageListener
,08-16 17:58:28.109  3214  3223 D HeadsetService: registerMessageListener
08-16 17:58:28.109  3214  7402 D HeadsetStateMachine: Disconnected process message: 70
,08-16 17:58:28.109  3214  7402 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2f429f0c
08-16 17:58:28.109  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:28.109  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-16 17:58:28.109  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
08-16 17:58:28.109  1019  1032 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-16 17:58:28.109  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:58:28.119  4838  4838 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-16 17:58:28.119  4838  4838 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.,
08-16 17:58:28.119  4838  4838 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 17:58:28.119  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 17:58:28.119  4838  4838 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-16 17:58:28.119  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-16 17:58:28.119  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 17:58:28.119  3214  7402 D HeadsetStateMachine: Disconnected process message: 9
,08-16 17:58:28.119  3214  7402 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 17:58:28.119  3214  7411 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 17:58:28.119   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-16 17:58:28.119   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 17:58:28.119   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-16 17:58:28.119   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 17:58:28.119   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 17:58:28.119   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 17:58:28.119   283   283 V audio_hw_primary: adev_set_parameters: exit
08-16 17:58:28.119  3214  7402 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 17:58:28.119  3214  7411 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:58:28.119  3214  7411 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:28.129  3214  7411 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-16 17:58:28.129  3214  7411 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:28.129  3214  7411 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-16 17:58:28.129  3214  7411 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b1b9055
,08-16 17:58:28.129  3214  7411 D BluetoothSocket: channel: 5
08-16 17:58:28.129  4838  4838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:28.129  1019  1752 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 17:58:28.129  1019  1752 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.129  1019  1752 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.129  1019  1752 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.129  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:28.139  2634  2634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:28.139  4838  4838 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:28.139  4838  4838 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:28.139  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:28.139  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 17:58:28.149  3214  3214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63f05ef
,08-16 17:58:28.149  3214  3214 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:58:28.149  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:28.149  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.149  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.149  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.149  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.159  1019  1499 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:58:28.169  3214  7416 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 17:58:28.169  3214  7416 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:28.169  3214  7416 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-16 17:58:28.169  3214  7416 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:28.169  3214  7416 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:28.169  3214  7416 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17d1dcd1
,08-16 17:58:28.179  3214  7416 D BluetoothSocket: channel: 12
08-16 17:58:28.179  3214  7416 I BtOppRfcommListener: Accept thread started.
,08-16 17:58:28.249   288   288 E SMD     : DCD OFF
,08-16 17:58:28.269   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:28.679  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-16 17:58:28.679  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:28.679  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:28.679  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:28.679  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:28.679  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:28.679  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:28.679  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
08-16 17:58:28.679  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:28.679  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:28.679  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39b1d88c added. We now have 8 listener(s)
08-16 17:58:28.679  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:28.679  1019  1032 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:58:28.679  1019  1032 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:58:28.679  1019  1032 D SecContentProvider2: mCursor = null
,08-16 17:58:28.689  1019  1032 D SettingsProvider: name = wifi_on,
08-16 17:58:28.689  1019  1032 D WifiService: setWifiEnabled: false pid=6547, uid=10170,
,08-16 17:58:28.689  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:28.689  1019  1491 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 17:58:28.699  1019  1491 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-16 17:58:28.699  1019  1491 D SecContentProvider2: mCursor = null
,08-16 17:58:28.699  1019  1491 D WifiService: setWifiEnabled: true pid=6547, uid=10170
,08-16 17:58:28.699  1019  1491 W ActivityManager: Permission Denial: getCurrentUser() from pid=6547, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:58:28.699  1019  1491 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:58:28.699  1019  1491 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6547, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:28.699  1019  1491 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 17:58:28.699  1019  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:58:28.699  1019  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:58:28.699  1019  1491 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:58:28.699  1019  1491 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:58:28.699  1019  1491 D SettingsProvider: name = wifi_on
,08-16 17:58:28.709  1019  1130 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 17:58:29.059  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-16 17:58:29.059  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:29.059  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:29.059  1019  1046 D Tethering: interfaceAdded wlan0
,08-16 17:58:29.069   278  1017 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-16 17:58:29.069   278  1017 D SoftapController: Softap fwReload - Ok
,08-16 17:58:29.069  1019  1046 D Tethering: interfaceAdded p2p0
,08-16 17:58:29.069   278  1017 D CommandListener: Setting iface cfg,
08-16 17:58:29.069   278  1017 D CommandListener: Trying to bring down wlan0
,08-16 17:58:29.069   278  1017 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:58:29.079  1019  1133 E Tethering: No numeric data
,08-16 17:58:29.079  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:58:29.079  1019  1133 D Tethering: clearTetheredNotification(),
08-16 17:58:29.079  1019  1046 D Tethering: p2p0 is not a tetherable iface, ignoring,
08-16 17:58:29.079  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:58:29.079  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:29.079  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:29.079  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:29.079  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:58:29.079  1182  1182 D HotspotTile: updateTetherState():false, false
,08-16 17:58:29.089  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:29.089  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:58:29.089  1019  1130 E WifiHW  : supplicant_name : p2p_supplicant
08-16 17:58:29.089  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:58:29.089  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:29.089  1019  1127 V NetworkStats: performPollLocked() took 11ms
08-16 17:58:29.099  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:29.099  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:29.139  7427  7427 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-16 17:58:29.139  7427  7427 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 17:58:29.139  7427  7427 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 17:58:29.149  7427  7427 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-16 17:58:29.149   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7427
08-16 17:58:29.149   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 17:58:29.149  7427  7427 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,08-16 17:58:29.149  7427  7427 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:29.149  7427  7427 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 17:58:29.149  7427  7427 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-16 17:58:29.149   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7427
,08-16 17:58:29.149   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-16 17:58:29.189  1019  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-16 17:58:29.209  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 17:58:29.209  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:29.209  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:29.209  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:58:29.209  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:29.209  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:29.209  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:29.209  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 17:58:29.209  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:29.219  1182  1182 D HotspotTile: onReceive : 2, 0
08-16 17:58:29.209  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:29.209  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-16 17:58:29.219  4838  4838 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:29.219  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:29.229  1019  1737 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:29.229  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:29.229  1019  1737 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:58:29.229  1019  1737 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:29.229  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:58:29.229  1646  1646 I Hs20UtilService: Starting #19
,08-16 17:58:29.229  1646  1684 I Hs20UtilService: Message received 5011
,08-16 17:58:29.239  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:29.239  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-16 17:58:29.239  6765  6765 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:58:29.239  6765  6765 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:29.269   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-16 17:58:29.339   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-16 17:58:29.339  7427  7427 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-16 17:58:29.379  7427  7427 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 17:58:29.379  7427  7427 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 17:58:29.389  7427  7427 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-16 17:58:29.389   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7427
08-16 17:58:29.389   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 17:58:29.389  7427  7427 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 17:58:29.389  7427  7427 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:29.389  7427  7427 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-16 17:58:29.399  7427  7427 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:29.399  7427  7427 E wpa_supplicant: SIM READ ERROR
08-16 17:58:29.399  7427  7427 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:29.399  7427  7427 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:29.399  7427  7427 E wpa_supplicant: SIM READ ERROR
,08-16 17:58:29.399  7427  7427 I wpa_supplicant: Blacklist: Clear (all) 
08-16 17:58:29.399  7427  7427 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:58:29.399  7427  7427 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:58:29.399  7427  7427 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:29.399  7427  7427 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,08-16 17:58:29.399  7427  7427 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:29.399  7427  7427 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-16 17:58:29.399  7427  7427 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 17:58:29.399  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 17:58:29.399  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:29.399  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:29.399  1019  1133 D Tethering: InitialState.processMessage what=4
,08-16 17:58:29.399  1019  1133 E Tethering: No numeric data
08-16 17:58:29.399  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:29.399  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:58:29.409  1182  1182 D HotspotTile: updateTetherState():false, false,
08-16 17:58:29.399  1019  1133 D Tethering: clearTetheredNotification()
08-16 17:58:29.409  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:29.409  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:29.409  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated,
,08-16 17:58:29.409  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:29.409  1019  1127 V NetworkStats: performPollLocked() took 3ms
08-16 17:58:29.409  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:29.409  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:29.409  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:29.529  7427  7427 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-16 17:58:29.669  7427  7427 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-16 17:58:29.669  7427  7427 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
08-16 17:58:29.679  7427  7427 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-16 17:58:29.679   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7427
08-16 17:58:29.679   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 17:58:29.679  7427  7427 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 17:58:29.679  7427  7427 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:29.679  7427  7427 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 17:58:29.689  7427  7427 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
08-16 17:58:29.699  7427  7427 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-16 17:58:29.699   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7427
08-16 17:58:29.699   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 17:58:29.699  7427  7427 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 17:58:29.699  7427  7427 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:29.699  7427  7427 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:29.699  7427  7427 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:29.699  7427  7427 E wpa_supplicant: SIM READ ERROR
08-16 17:58:29.699  7427  7427 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:58:29.699  7427  7427 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:58:29.699  7427  7427 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 17:58:29.699  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 17:58:29.699  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:58:29.709  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:58:29.709  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:29.709  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:29.709  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:58:29.859  7427  7427 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-16 17:58:29.859  7427  7427 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 17:58:29.939  7427  7427 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-16 17:58:29.939  7427  7427 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-16 17:58:29.939  7427  7427 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 17:58:29.949  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-16 17:58:29.949  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 17:58:29.949  7427  7427 I wpa_supplicant: HOTSPOT20_ENABLE called
08-16 17:58:29.949  7427  7427 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:29.949  7427  7427 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:29.949  7427  7427 E wpa_supplicant: SIM READ ERROR
08-16 17:58:29.949  7427  7427 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:58:29.969  7427  7427 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-16 17:58:29.979  7427  7427 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-16 17:58:29.989  1019  1130 D WifiConfigStore: Loading config and enabling all networks 
,08-16 17:58:29.989  4838  4838 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:29.999  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:29.999  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:29.999  1019  1444 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:29.999  1019  1444 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:58:29.999  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:29.999  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:29.999  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:29.999  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:29.999  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:29.999  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:29.999  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-16 17:58:29.999  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-16 17:58:29.999  1019  1444 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:29.999  1019  1444 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:29.999  1019  1444 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:29.999  1646  1646 I Hs20UtilService: Starting #20
,08-16 17:58:29.999  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:29.999  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:29.999  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:29.999  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:29.999  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:29.999  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:29.999  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:29.999  6547  6547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:29.999  1646  1684 I Hs20UtilService: Message received 5011
,08-16 17:58:29.999  1019  1130 E WifiConfigStore: Not a HS20
,08-16 17:58:29.999  6547  6547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:30.009  1182  1182 D HotspotTile: onReceive : 3, 0
08-16 17:58:30.009  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:58:30.009  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:30.009  1019  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
08-16 17:58:30.009  6765  6765 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:30.009  6765  6765 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:58:30.009  6765  6765 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:30.019  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-16 17:58:30.019  7427  7427 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 17:58:30.019  7427  7427 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 17:58:30.019  7427  7427 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:58:30.019  7427  7427 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:58:30.019  7427  7427 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 17:58:30.019  7427  7427 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 17:58:30.019  7427  7427 I wpa_supplicant: First Scan Start
08-16 17:58:30.019  7427  7427 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-16 17:58:30.019  1019  1130 D WifiNative-wlan0: Setting external_sim to 1
,08-16 17:58:30.019  1019  1130 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:58:30.019  1019  1130 I WifiNative-HAL: startHal
08-16 17:58:30.019  1019  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9ea0388c
08-16 17:58:30.019  1019  1130 I WifiNative-HAL: Could not start hal
,08-16 17:58:30.019  6943  6943 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:30.019  1019  1130 E WifiNative-wlan0: do suspend true
,08-16 17:58:30.019  1019  1129 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-16 17:58:30.029  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-16 17:58:30.029  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3,
08-16 17:58:30.029  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:30.029  1019  1129 D WifiP2pService: P2pEnablingState
08-16 17:58:30.029  1019  1153 I WifiNative-HAL: startHal
08-16 17:58:30.029  1019  1129 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 17:58:30.029  1019  1153 E wifi    : getStaticLongField sWifiHalHandle 0x990249bc
08-16 17:58:30.029  1019  1129 D WifiP2pService: P2p socket connection successful
08-16 17:58:30.029  1019  1153 I WifiNative-HAL: Could not start hal
08-16 17:58:30.029  1019  1129 D WifiP2pService: P2pEnabledState
08-16 17:58:30.029  1019  1153 E WifiScanningService: could not start HAL
08-16 17:58:30.029  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 17:58:30.029  1019  1019 D RttService: SCAN_AVAILABLE : 3
08-16 17:58:30.029  1019  1154 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:30.029   278  1017 D CommandListener: Setting iface cfg
08-16 17:58:30.029   278  1017 D CommandListener: Trying to bring up p2p0
08-16 17:58:30.029  1019  1129 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 17:58:30.029  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:58:30.029  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:58:30.029  1019  1130 E WifiNative-wlan0: invaild command id : 215
,08-16 17:58:30.029  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:58:30.029  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:58:30.029  1019  1130 E WifiNative-wlan0: invaild command id : 215
08-16 17:58:30.029  1019  1132 E ConnectivityService: updateNetworkInfo()
08-16 17:58:30.029  7427  7427 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-16 17:58:30.029  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 17:58:30.039  7427  7427 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:58:30.039  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 17:58:30.039  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:30.039  1019  1049 D WifiDisplayController: disconnect
08-16 17:58:30.039  1019  1049 D WifiDisplayController: updateConnection
08-16 17:58:30.039  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:30.039  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:58:30.039  7427  7427 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-16 17:58:30.039  1019  1130 E WifiStateMachine: Failed to set frequency band 0
,08-16 17:58:30.039  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:30.039  1019  1130 D SecContentProvider2: mCursor = null
08-16 17:58:30.039  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 17:58:30.039  1019  1317 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:58:30.039  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:58:30.039  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:58:30.039  1019  1130 D SecContentProvider2: mCursor = null,
,08-16 17:58:30.039  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,08-16 17:58:30.039  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
,08-16 17:58:30.039  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-16 17:58:30.039  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:58:30.049  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 17:58:30.049  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:58:30.049  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:58:30.049  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:58:30.049  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:30.049  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress
,08-16 17:58:30.049  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-16 17:58:30.049  1019  1129 D WifiP2pService: DeviceAddress: 0a:75:42
,08-16 17:58:30.049  1019  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  secondary type: null
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  wps: 0
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  grpcapab: 0
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  devcapab: 0
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  status: 3
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  wfdInfo: null
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  groupownerAddress: null
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  GOdeviceName: null
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  interfaceAddress: 
08-16 17:58:30.049  1019  1049 D WifiDisplayController:  SConnectInfo : null
,08-16 17:58:30.049  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:30.049  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:58:30.049  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:30.049  4838  4838 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:30.049  4838  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:30.059  7321  7321 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:30.059  7321  7321 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:58:30.059  7321  7321 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:58:30.069  6928  6928 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:30.079  1019  1129 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 17:58:30.079  1019  1129 D WifiP2pService: InactiveState
,08-16 17:58:30.079  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
,08-16 17:58:30.079  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:58:30.079  7427  7427 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 17:58:30.079  1019  1129 D WifiP2pService: InactiveState{ what=143376 },
,08-16 17:58:30.079  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:58:30.739  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:30.739  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:30.739  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:30.739  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:30.739  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:30.739  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:30.739  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:30.739  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:30.739  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:30.739  6547  6683 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 17:58:30.739  6547  6683 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 17:58:30.739  6547  6683 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@36891ff5 Bundle[{}]
,08-16 17:58:30.749  6547  6683 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 17:58:30.749  6547  6683 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 17:58:30.749  6547  6683 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:58:30.749  6547  6683 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 17:58:30.749  6547  6683 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 17:58:30.749  6547  6683 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:58:30.759  6547  6683 I System.out: Running OutgoingSocketThread,
,08-16 17:58:30.759  6547  7436 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1309)
,08-16 17:58:30.759  6547  7436 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 33625
,08-16 17:58:30.759  6547  7436 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 17:58:31.249   288   288 E SMD     : DCD OFF
,08-16 17:58:31.299  7427  7427 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
08-16 17:58:31.299  7427  7427 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 17:58:31.299  7427  7427 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-16 17:58:31.299  7427  7427 I wpa_supplicant: Trying to associate with  'G700'
08-16 17:58:31.299  7427  7427 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-16 17:58:31.299  7427  7427 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-16 17:58:31.299  1019  7433 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-16 17:58:31.309  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:31.309  1019  1130 D SecContentProvider2: mCursor = null
,08-16 17:58:31.409  7427  7427 E wpa_supplicant: Cmd 35605 not handled
,08-16 17:58:31.409  7427  7427 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:58:31.409  7427  7427 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-16 17:58:31.409  7427  7427 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-16 17:58:31.409  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:31.409  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:31.409  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:31.409  7427  7427 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-16 17:58:31.409  7427  7427 I wpa_supplicant: Associated with F4.99.3E
08-16 17:58:31.409  7427  7427 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:58:31.409  7427  7427 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-16 17:58:31.409  7427  7427 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-16 17:58:31.419  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:31.419  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:31.419  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:58:31.419  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 17:58:31.419  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:31.419  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:31.419  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:58:31.419  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
,08-16 17:58:31.419  7427  7427 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:58:31.419  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 17:58:31.419  7427  7427 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-16 17:58:31.419  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:31.419  1019  1130 D SecContentProvider2: mCursor = null
08-16 17:58:31.429  1019  1133 E Tethering: No numeric data
08-16 17:58:31.429  7427  7427 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-16 17:58:31.429  7427  7427 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-16 17:58:31.429  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:58:31.429  1019  1133 D Tethering: clearTetheredNotification()
08-16 17:58:31.429  7427  7427 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:58:31.429  7427  7427 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-16 17:58:31.429  7427  7427 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-16 17:58:31.429  7427  7427 I wpa_supplicant: Blacklist: Clear (temp) 
08-16 17:58:31.429  7427  7427 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-16 17:58:31.429  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:58:31.429  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
08-16 17:58:31.429  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-16 17:58:31.429  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:31.429  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:58:31.429  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:31.429  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:31.429  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:58:31.439  1182  1182 D HotspotTile: updateTetherState():false, false
,08-16 17:58:31.439  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:31.439  1019  1130 D SecContentProvider2: mCursor = null
,08-16 17:58:31.439  1019  1127 V NetworkStats: performPollLocked() took 10ms
,08-16 17:58:31.439  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:31.449  1019  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-16 17:58:31.449  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:31.449  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:31.449  1019  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 17:58:31.449  1019  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-16 17:58:31.449  1019  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-16 17:58:31.449  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-16 17:58:31.449  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 17:58:31.459  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:31.459  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:31.459  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:31.459  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:31.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:31.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:31.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:31.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:31.459  1019  1752 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:31.459  1019  1752 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:31.459  1019  1752 W ActivityManager: userId = 0, bbcId = -10000,
,08-16 17:58:31.459  1019  1752 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:31.459  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:31.469  1646  1646 I Hs20UtilService: Starting #21
,08-16 17:58:31.469  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:58:31.469  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:31.469  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:31.469  1646  1684 I Hs20UtilService: Message received 5007
,08-16 17:58:31.469  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:58:31.469  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 17:58:31.469  4838  4838 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:31.469  4838  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:31.479  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:31.489   278  1017 D CommandListener: Setting iface cfg
,08-16 17:58:31.489  1019  1130 E WifiStateMachine: Start Dhcp Watchdog 3
,08-16 17:58:31.489  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:58:31.489  1019  1130 D SecContentProvider2: mCursor = null
,08-16 17:58:31.499  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-16 17:58:31.499  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:31.499  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:58:31.509  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:31.509  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:31.509  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:31.509  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:31.509  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:58:31.509  1019  1130 D SecContentProvider2: mCursor = null
,08-16 17:58:31.509  1019  1130 E WifiNative-wlan0: do suspend false
,08-16 17:58:31.519  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:58:31.519  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-16 17:58:31.729  7440  7440 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-16 17:58:31.729  7440  7440 I dhcpcd  : version 5.5.6 starting
,08-16 17:58:31.739  7440  7440 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-16 17:58:31.759  6547  6683 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1310)
08-16 17:58:31.759  6547  6683 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1310)
08-16 17:58:31.759  6547  6683 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1315)
08-16 17:58:31.759  6547  6683 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 17:58:31.759  6547  6683 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1316)
,08-16 17:58:31.759  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:31.759  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fc0bd5 added. We now have 2 listener(s)
,08-16 17:58:31.769  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 17:58:31.769  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:31.769  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:31.769  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:31.769  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1aaa1fea added. We now have 9 listener(s)
,08-16 17:58:31.769  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:31.769  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:58:31.769  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:31.779  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:31.779  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:31.779  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:31.779  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:31.779  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-16 17:58:31.779  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:31.779  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:31.779  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:31.779  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:31.779  6547  6683 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:31.779  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:31.779  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20e9f178 added. We now have 3 listener(s)
08-16 17:58:31.789  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:31.789  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:31.789  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:31.799  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:31.799  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fe9051 added. We now have 10 listener(s)
,08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:31.799  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:31.799  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-16 17:58:31.799  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:31.799  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:58:31.799  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fc0bd5 removed from the list
08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:31.799  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1aaa1fea removed from the list
08-16 17:58:31.799  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:31.799  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:31.799  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1aaa1fea not in the list
08-16 17:58:31.799  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:31.799  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fe9051 removed from the list
08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:31.799  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:31.799  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:31.799  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20e9f178 removed from the list
08-16 17:58:31.799  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:31.799  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0250b6 added. We now have 2 listener(s)
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:31.799  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:31.799  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215801b7 added. We now have 9 listener(s)
08-16 17:58:31.799  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:31.809  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:31.809  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:31.809  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:31.809  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:31.809  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:31.809  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:31.809  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:31.809  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:31.809  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:31.809  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:31.819  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:31.819  6547  6683 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:31.819  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:31.819  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:31.819  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cae08d added. We now have 3 listener(s)
,08-16 17:58:31.819  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:31.819  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 17:58:31.819  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:31.819  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:31.819  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:31.819  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31dac242 added. We now have 10 listener(s)
08-16 17:58:31.819  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:31.819  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:31.819  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:58:31.819  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:31.819  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:31.819  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:31.829  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:58:31.839  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:31.839  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 17:58:31.839  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:58:31.839  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:31.839  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:58:31.849  7440  7440 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-16 17:58:31.849  7440  7440 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-16 17:58:31.849  7440  7440 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-16 17:58:31.849  7440  7440 I dhcpcd  : bssid match
08-16 17:58:31.849  7440  7440 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-16 17:58:31.849  3214  3349 D BtGatt.GattService: registerClient() - UUID=25622aca-9140-4476-b2f8-218505e23686
,08-16 17:58:31.899  3214  3295 D BtGatt.GattService: onClientRegistered() - UUID=25622aca-9140-4476-b2f8-218505e23686, clientIf=6
08-16 17:58:31.899  6547  6555 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-16 17:58:31.899  3214  3379 D BtGatt.GattService: start scan with filters
08-16 17:58:31.899  3214  3367 D BtGatt.ScanManager: handling starting scan
08-16 17:58:31.899  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:58:31.899  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:58:31.899  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:58:31.899  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:58:31.899  3214  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 17:58:31.899  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:31.899  3214  3367 D BtGatt.ScanManager: allow scan with filters
,08-16 17:58:31.899  3214  3367 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 17:58:31.899  3214  3367 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-16 17:58:31.909  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:58:31.909  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:31.909  3214  3367 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:31.909  3214  3367 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:58:31.909  3214  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 17:58:31.909  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:31.909  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:31.909  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:58:31.909  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:31.909  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:58:31.909  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:31.919  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:31.919  6547  6683 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:58:31.919  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:31.919  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 17:58:31.919  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:31.919  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:58:31.919  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 17:58:31.919  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:58:31.919  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:58:31.929  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:58:31.929  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 17:58:31.929  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:58:31.929  3214  7382 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:31.929  3214  3367 D BtGatt.ScanManager: filter size is 1
,08-16 17:58:31.929  3214  3367 D BtGatt.ScanManager: delete FilterIndex - 6
,08-16 17:58:31.939  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:58:31.939  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:31.939  3214  3367 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:31.939  3214  7384 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:58:31.939  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:58:31.939  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:31.939  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:31.939  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:31.939  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:31.939  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:31.939  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:58:31.939  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:31.939  3214  3367 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:58:31.939  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:58:31.939  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:31.939  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:58:31.939  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:31.949  3214  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-16 17:58:31.949  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:31.949  7440  7440 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-16 17:58:31.949  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:31.949  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:31.949  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:31.949  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:31.949  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:31.949  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:31.949  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:31.949  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:31.949  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0250b6 removed from the list
08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:31.949  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215801b7 removed from the list
08-16 17:58:31.949  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:31.949  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:31.949  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:31.949  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:31.949  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215801b7 not in the list
08-16 17:58:31.949  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:31.949  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:31.949  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31dac242 removed from the list
,08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:31.949  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:31.949  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:31.949  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:58:31.949  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cae08d removed from the list
08-16 17:58:31.959  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:31.959  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15d6c08e added. We now have 2 listener(s)
,08-16 17:58:31.959  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
,08-16 17:58:31.959  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:58:31.959  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:58:31.959  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:31.959  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ef70af added. We now have 9 listener(s)
,08-16 17:58:31.959  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:31.959  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:31.969  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:31.969  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:31.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:31.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:31.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:31.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:31.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:31.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:31.969  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:31.969  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:31.969  6547  6683 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:31.969  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:31.979  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:31.979  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12989445 added. We now have 3 listener(s)
,08-16 17:58:31.979  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:31.979  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-16 17:58:31.979  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:31.979  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:58:31.979  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:31.979  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a82579a added. We now have 10 listener(s)
08-16 17:58:31.979  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:31.979  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:31.979  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:31.979  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:58:31.979  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:31.979  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:31.979  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:31.989  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:58:31.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:31.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:31.989  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:58:31.999  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:31.999  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:58:31.999  3214  7384 D BtGatt.GattService: registerClient() - UUID=198a330a-097b-4e38-b55b-247c27f43521
,08-16 17:58:32.049  3214  3295 D BtGatt.GattService: onClientRegistered() - UUID=198a330a-097b-4e38-b55b-247c27f43521, clientIf=6,
08-16 17:58:32.049  6547  6556 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-16 17:58:32.049  3214  3223 D BtGatt.GattService: start scan with filters
08-16 17:58:32.049  3214  3367 D BtGatt.ScanManager: handling starting scan,
08-16 17:58:32.049  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-16 17:58:32.049  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:58:32.049  3214  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:58:32.049  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-16 17:58:32.049  3214  3367 D BtGatt.ScanManager: allow scan with filters
,08-16 17:58:32.049  3214  3367 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 17:58:32.049  3214  3367 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
08-16 17:58:32.049  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:32.049  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:58:32.049  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:32.049  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:58:32.049  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.049  3214  3367 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:32.049  3214  3367 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:32.049  3214  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 17:58:32.049  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.049  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:58:32.049  6547  6683 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 17:58:32.049  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-16 17:58:32.049  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.049  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:32.049  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:32.049  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.049  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.049  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:58:32.049  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15d6c08e removed from the list
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.049  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ef70af removed from the list
08-16 17:58:32.049  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:32.049  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:32.049  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.049  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-16 17:58:32.049  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.049  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:32.049  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ef70af not in the list
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:32.049  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:32.049  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:32.049  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
08-16 17:58:32.059  3214  3379 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:32.059  3214  3367 D BtGatt.ScanManager: filter size is 1
08-16 17:58:32.059  3214  3367 D BtGatt.ScanManager: delete FilterIndex - 7
,08-16 17:58:32.059  3214  3227 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:58:32.059  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:58:32.059  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.059  3214  3367 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:32.059  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:58:32.059  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:58:32.059  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 17:58:32.059  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 17:58:32.059  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:32.059  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 17:58:32.059  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.059  3214  3367 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:58:32.069  3214  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:58:32.069  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.069  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:32.069  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:58:32.069  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 17:58:32.069  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:58:32.069  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:32.069  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:32.069  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:32.069  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:32.069  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:32.069  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.069  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 17:58:32.069  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a82579a removed from the list
08-16 17:58:32.069  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.069  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.069  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:32.069  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.069  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12989445 removed from the list
08-16 17:58:32.069  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:32.069  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1e5366 added. We now have 2 listener(s)
08-16 17:58:32.069  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 17:58:32.069  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:32.069  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:32.069  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:32.069  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d36c6a7 added. We now have 9 listener(s)
08-16 17:58:32.069  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:32.069  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:58:32.079  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:32.079  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:32.079  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:32.079  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:32.079  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:32.079  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:32.079  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:32.079  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:32.079  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:32.079  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:32.079  6547  6683 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:32.079  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:32.079  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@268206fd added. We now have 3 listener(s)
08-16 17:58:32.079  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:32.089  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:32.089  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-16 17:58:32.089  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:32.089  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:32.089  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:32.089  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@282c3ff2 added. We now have 10 listener(s)
08-16 17:58:32.089  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:32.089  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:32.089  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:32.089  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:32.089  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:32.089  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:58:32.089  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:58:32.089  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:58:32.089  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 17:58:32.099  7440  7440 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
08-16 17:58:32.099  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:58:32.099  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:32.099  6547  6683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:58:32.099  3214  7382 D BtGatt.GattService: registerClient() - UUID=96a69438-f03c-485e-a51d-3f1047f7bfe7
,08-16 17:58:32.139  3214  3295 D BtGatt.GattService: onClientRegistered() - UUID=96a69438-f03c-485e-a51d-3f1047f7bfe7, clientIf=6
,08-16 17:58:32.149  6547  6556 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:58:32.149  3214  7384 D BtGatt.GattService: start scan with filters
,08-16 17:58:32.149  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:58:32.149  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:58:32.149  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:32.149  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:58:32.149  3214  3367 D BtGatt.ScanManager: handling starting scan
,08-16 17:58:32.149  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:32.149  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:58:32.149  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:32.149  3214  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:58:32.149  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.149  3214  3367 D BtGatt.ScanManager: allow scan with filters
08-16 17:58:32.149  3214  3367 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:58:32.149  3214  3367 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-16 17:58:32.159  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 17:58:32.159  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.159  3214  3367 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:32.159  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 17:58:32.159  3214  3367 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:58:32.159  3214  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 17:58:32.159  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.159  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:32.159  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:32.159  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:32.159  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.159  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.159  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:32.159  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.159  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1e5366 removed from the list
08-16 17:58:32.159  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.159  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d36c6a7 removed from the list
08-16 17:58:32.159  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:32.159  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:32.169  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.169  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 17:58:32.169  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.169  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 17:58:32.169  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.169  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:32.169  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.169  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:32.169  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.169  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d36c6a7 not in the list
08-16 17:58:32.169  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:32.169  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:32.169  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:32.169  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:32.169  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:58:32.169  3214  3349 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:32.179  3214  3367 D BtGatt.ScanManager: filter size is 1
08-16 17:58:32.179  3214  3367 D BtGatt.ScanManager: delete FilterIndex - 8
,08-16 17:58:32.179  3214  3223 D BtGatt.GattService: unregisterClient() - clientIf=6
08-16 17:58:32.179  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:58:32.179  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:32.179  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:32.179  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:32.179  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:58:32.179  3214  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:58:32.179  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.179  3214  3367 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:32.179  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:32.179  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:58:32.179  6547  6683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:32.179  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-16 17:58:32.179  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:32.179  3214  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:58:32.179  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.179  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:32.179  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.179  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.179  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@282c3ff2 removed from the list
08-16 17:58:32.179  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.179  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.179  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.179  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.179  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@268206fd removed from the list
08-16 17:58:32.179  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:32.179  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:32.179  6547  6547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:32.179  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:32.179  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30ba693e added. We now have 2 listener(s)
08-16 17:58:32.179  3214  3367 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:58:32.189  3214  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:58:32.189  3214  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.189  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-16 17:58:32.189  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:58:32.189  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:32.189  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:32.189  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f63e39f added. We now have 9 listener(s)
,08-16 17:58:32.189  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:32.189  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:32.199  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:32.199  6547  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:32.199  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:32.199  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:32.199  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-16 17:58:32.199  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:32.199  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:32.199  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:32.199  6547  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:32.209  6547  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:32.209  6547  6683 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:32.209  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:32.209  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@236018b5 added. We now have 3 listener(s)
,08-16 17:58:32.209  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:32.219  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-16 17:58:32.219  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:32.219  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:32.219  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:32.219  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@286fdb4a added. We now have 10 listener(s)
,08-16 17:58:32.219  6547  6683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:32.219  6547  6683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:32.219  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:32.219  6547  6683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.219  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.219  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.219  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30ba693e removed from the list
,08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.219  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f63e39f removed from the list
08-16 17:58:32.219  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:32.219  6547  6683 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:32.219  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.219  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.219  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.219  6547  6683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f63e39f not in the list,
08-16 17:58:32.219  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.219  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.219  6547  6683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@286fdb4a removed from the list
08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.219  6547  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.219  6547  6683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.219  6547  6683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.219  6547  6683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@236018b5 removed from the list
08-16 17:58:32.219  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 17:58:32.219  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 17:58:32.219  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 17:58:32.219  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:32.219  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 17:58:32.219  6547  6683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:32.229  6547  7467 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1323, name: My test thread name)
,08-16 17:58:32.229  6547  7467 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1323, thread name: My test thread name)
08-16 17:58:32.229  6547  7467 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1323, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:58:32.229  6547  7468 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1325, name: My test thread name)
08-16 17:58:32.229  6547  7468 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1325, thread name: My test thread name)
08-16 17:58:32.229  6547  7468 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1325, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:58:32.229  6547  6683 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-16 17:58:32.229  6547  6683 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 17:58:32.229  6547  6683 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 17:58:32.229  6547  6683 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 17:58:32.239  6547  6683 D com.test.thalitest.ThaliTestRunner: Total duration: 23272 ms
,08-16 17:58:32.239  6547  6683 I jxcore-log: Total number of executed tests:  80
08-16 17:58:32.239  6547  6683 I jxcore-log: 
,08-16 17:58:32.239  6547  6683 I jxcore-log: Number of passed tests:  80
08-16 17:58:32.239  6547  6683 I jxcore-log: 
08-16 17:58:32.239  6547  6683 I jxcore-log: Number of failed tests:  0
08-16 17:58:32.239  6547  6683 I jxcore-log: 
,08-16 17:58:32.239  6547  6683 I jxcore-log: Number of ignored tests:  0
08-16 17:58:32.239  6547  6683 I jxcore-log: 
08-16 17:58:32.239  6547  6683 I jxcore-log: Total duration:  23272,
08-16 17:58:32.239  6547  6683 I jxcore-log: 
,08-16 17:58:32.239  6547  6683 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 17:58:32.239  6547  6683 I jxcore-log: 
,08-16 17:58:32.239  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.239  6547  6683 I jxcore-log: 
08-16 17:58:32.239  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.239  6547  6683 I jxcore-log: 
08-16 17:58:32.249  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.249  6547  6683 I jxcore-log: 
08-16 17:58:32.249  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.249  6547  6683 I jxcore-log: 
08-16 17:58:32.249  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.249  6547  6683 I jxcore-log: 
08-16 17:58:32.249  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.249  6547  6683 I jxcore-log: 
08-16 17:58:32.249  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.249  6547  6683 I jxcore-log: 
08-16 17:58:32.259  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.259  6547  6683 I jxcore-log: 
08-16 17:58:32.259  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.259  6547  6683 I jxcore-log: 
08-16 17:58:32.259  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.259  6547  6683 I jxcore-log: 
08-16 17:58:32.259  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.259  6547  6683 I jxcore-log: 
08-16 17:58:32.259  6547  6547 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 17:58:32.259  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:32.259  6547  6683 I jxcore-log: 
08-16 17:58:32.259  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.259  6547  6683 I jxcore-log: 
,08-16 17:58:32.259  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.259  6547  6683 I jxcore-log: 
08-16 17:58:32.259  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.259  6547  6683 I jxcore-log: 
08-16 17:58:32.259  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.259  6547  6683 I jxcore-log: 
08-16 17:58:32.259  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.259  6547  6683 I jxcore-log: 
,08-16 17:58:32.269  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.269  6547  6683 I jxcore-log: 
,08-16 17:58:32.269  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-16 17:58:32.269  6547  6683 I jxcore-log: 
,08-16 17:58:32.269  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.269  6547  6683 I jxcore-log: 
,08-16 17:58:32.269  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.269  6547  6683 I jxcore-log: 
,08-16 17:58:32.269  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-16 17:58:32.269  6547  6683 I jxcore-log: 
,08-16 17:58:32.269  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.269  6547  6683 I jxcore-log: 
,08-16 17:58:32.269  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 17:58:32.269  6547  6683 I jxcore-log: 
,08-16 17:58:32.269  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 17:58:32.269  6547  6683 I jxcore-log: 
,08-16 17:58:32.269  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 17:58:32.269  6547  6683 I jxcore-log: 
,08-16 17:58:32.269  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,08-16 17:58:32.269  6547  6683 I jxcore-log: 
,08-16 17:58:32.279  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,08-16 17:58:32.279  6547  6683 I jxcore-log: 
,08-16 17:58:32.279  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.279  6547  6683 I jxcore-log: 
,08-16 17:58:32.319  1019  1130 E WifiNative-wlan0: do suspend true
,08-16 17:58:32.349  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
08-16 17:58:32.349  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-16 17:58:32.349  1019  1130 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 17:58:32.349  1019  1130 E WifiStateMachine: VerifyingLinkState enter
,08-16 17:58:32.359  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 17:58:32.359  1019  1132 E ConnectivityService: updateNetworkInfo()
08-16 17:58:32.359  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:32.359  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:32.359  1019  1132 D ConnectivityService: Adding iface wlan0 to network 504
08-16 17:58:32.359  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.359  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.359  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.359  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.359  1019  1132 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-16 17:58:32.359  1019  1147 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-16 17:58:32.359  1019  1147 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:58:32.359  1019  1147 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:58:32.359  1019  1147 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:58:32.359  1019  1147 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-16 17:58:32.379  1019  1130 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-16 17:58:32.379  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 17:58:32.379  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 17:58:32.379  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:58:32.379  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.379  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.379  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.379  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.379  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:58:32.389  1019  1132 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-16 17:58:32.389  1019  1132 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-16 17:58:32.389  1019  1132 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-16 17:58:32.389  1019  1132 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 17:58:32.389  1019  1132 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-16 17:58:32.389  1019  1737 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:32.389  1019  1130 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 17:58:32.389  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:32.389  1019  1130 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
08-16 17:58:32.389  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:32.389  1019  1132 D ConnectivityService: LTETest block dns file not exists
08-16 17:58:32.389  1019  1737 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:32.389  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:58:32.389  1646  1646 I Hs20UtilService: Starting #22
08-16 17:58:32.399  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 17:58:32.399  1019  1019 I WifiTrafficPoller: mBoosterFLAG : 0
08-16 17:58:32.399  1019  1019 I WifiTrafficPoller: current booster mode : FullMode
08-16 17:58:32.399  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 17:58:32.399  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:32.399  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:32.399  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.399  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.399  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.399  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.399  1646  1684 I Hs20UtilService: Message received 5007
,08-16 17:58:32.399  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:32.399  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 17:58:32.399  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.399  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.399  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.409  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.409  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:58:32.409  4838  4838 I NearbySettings: MountReceiver.onReceive - Keep current state
08-16 17:58:32.409  1019  1132 V NetworkStats: updateIfacesLocked()
08-16 17:58:32.409  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.409  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:32.409  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:32.409  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:32.419  1019  1132 V NetworkStats: performPollLocked() took 9ms
08-16 17:58:32.419  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:32.419  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.419  1019  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-16 17:58:32.419  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.419  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:58:32.419  1019  1132 E ConnectivityService: updateNetworkInfo()
08-16 17:58:32.419  1019  1132 E ConnectivityService: updateNetworkInfo()
08-16 17:58:32.419  1019  1132 V NetworkStats: updateIfacesLocked()
08-16 17:58:32.419  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.419  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:58:32.419  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:32.419  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:32.419  1019  1132 V NetworkStats: performPollLocked() took 3ms
08-16 17:58:32.419  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:32.419  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.419  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:32.419  1019  1132 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-16 17:58:32.429  1019  7437 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:32.429  1019  7437 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-16 17:58:32.429  1019  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-16 17:58:32.429  1019  7437 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:32.429  1019  1132 D ConnectivityService:    accepting network in place of null
08-16 17:58:32.429  1019  7437 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-16 17:58:32.429  1019  7437 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:58:32.429  1019  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 17:58:32.429  1019  1129 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-16 17:58:32.429   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 17:58:32.429   278  1011 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-16 17:58:32.429  1019  1132 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 17:58:32.429  1019  1132 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-16 17:58:32.429  1019  1449 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:32.429  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:32.429  1019  1449 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:58:32.429  1019  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:32.429  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:58:32.429  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:58:32.429  1470  1470 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 17:58:32.429  1470  1470 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 17:58:32.429  1019  1132 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} },
08-16 17:58:32.429  1019  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-16 17:58:32.429  1646  1646 I Hs20UtilService: Starting #23
08-16 17:58:32.439  1182  1662 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:58:32.439  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-16 17:58:32.439  1019  1133 D Tethering: MasterInitialState.processMessage what=3
08-16 17:58:32.439  1646  1684 I Hs20UtilService: Message received 5007
08-16 17:58:32.439  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.439  1019  1127 V NetworkStats: updateIfacesLocked()
08-16 17:58:32.439  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:58:32.439  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:32.439  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:32.439  1182  1182 D StatusBar.NetworkController: EthernetConnected: false,
08-16 17:58:32.439  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:58:32.439  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:58:32.439  1182  1182 D StatusBar.NetworkController: updateDataNetType()
08-16 17:58:32.439  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.439  1019  1127 V NetworkStats: performPollLocked() took 4ms
08-16 17:58:32.439  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.439  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.439  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.439  1019  1128 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 17:58:32.439  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:32.439  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:58:32.449  4838  4838 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
,08-16 17:58:32.449  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-16 17:58:32.449  6547  6547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:58:32.449  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:58:32.449  4838  4838 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-16 17:58:32.449  4838  4838 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 17:58:32.449  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.449  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:32.449  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 17:58:32.449  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-16 17:58:32.449  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:32.449  6547  6683 I jxcore-log: 
,08-16 17:58:32.449  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 17:58:32.449  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-16 17:58:32.449  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-16 17:58:32.449  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-16 17:58:32.459  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:32.459  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
08-16 17:58:32.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.459  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.459  1019  4803 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-16 17:58:32.459  1019  4803 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:32.459  1019  4803 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:32.459  1019  4803 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:32.459  1019  4803 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:58:32.459  1646  1646 I Hs20UtilService: Starting #24
,08-16 17:58:32.459  1646  1684 I Hs20UtilService: Message received 5007
,08-16 17:58:32.469  4838  4838 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:58:32.469  4838  4838 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 17:58:32.469  1019  1752 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
08-16 17:58:32.469  1019  1737 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-16 17:58:32.469  1019  1737 D SecContentProvider2: mCursor = null
,08-16 17:58:32.479  1019  4459 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-16 17:58:32.479  1019  4459 D SecContentProvider2: mCursor = null
08-16 17:58:32.479  1019  1444 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-16 17:58:32.479  1019  1444 D SecContentProvider2: mCursor = null
,08-16 17:58:32.479  1019  1031 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-16 17:58:32.479  1019  1031 D SecContentProvider2: mCursor = null
,08-16 17:58:32.479  1019  4803 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-16 17:58:32.479  1019  4803 D SecContentProvider2: mCursor = null
,08-16 17:58:32.479  1019  1449 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-16 17:58:32.479  1019  1449 D SecContentProvider2: mCursor = null
,08-16 17:58:32.509   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-16 17:58:32.509  1019  1752 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,08-16 17:58:32.519  1182  1182 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 17:58:32.519  7474  7474 D AndroidRuntime: ,
08-16 17:58:32.519  7474  7474 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 17:58:32.519  7474  7474 D AndroidRuntime: CheckJNI is OFF
,08-16 17:58:32.519  7474  7474 D AndroidRuntime: readGMSProperty: start
08-16 17:58:32.519  7474  7474 D AndroidRuntime: readGMSProperty: already setted!!
08-16 17:58:32.519  7474  7474 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 17:58:32.519  7474  7474 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 17:58:32.519  7474  7474 D AndroidRuntime: readGMSProperty: end
08-16 17:58:32.519  7474  7474 D AndroidRuntime: addProductProperty: start
08-16 17:58:32.519  1019  7437 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 17:58:32.569  6547  6547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:58:32.569  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:32.569  6547  6683 I jxcore-log: 
,08-16 17:58:32.589  1019  7437 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:58:32 GMT], X-Android-Received-Millis=[1471363112602], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471363112569]},
08-16 17:58:32.589  1019  7437 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 17:58:32.589  1019  1132 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-16 17:58:32.589  1019  7437 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-16 17:58:32.589  1019  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-16 17:58:32.589  1182  1662 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:58:32.589  1019  1132 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-16 17:58:32.589  1019  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
08-16 17:58:32.589  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: EthernetConnected: false,
08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE,
08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: updateDataNetType()
,08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-16 17:58:32.599  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:32.599  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.599  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.649  7474  7474 E AffinityControl: AffinityControl: registerfunction enter,
,08-16 17:58:32.669  7474  7474 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-16 17:58:32.679  6547  6547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:58:32.689  6547  6683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-16 17:58:32.689  6547  6683 I jxcore-log: 
,08-16 17:58:32.709  1019  1032 D PackageManager: START PACKAGE DELETE: observer{99079261}
08-16 17:58:32.709  1019  1032 D PackageManager: pkg{<packageName>}
08-16 17:58:32.709  1019  1032 D PackageManager: user{0}
08-16 17:58:32.709  1019  1032 D PackageManager: caller{2000}
08-16 17:58:32.709  1019  1032 D PackageManager: flags{2}
,08-16 17:58:32.709  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,08-16 17:58:32.709  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-16 17:58:32.709  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-16 17:58:32.709  1019  1032 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,08-16 17:58:32.709  1019  1032 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-16 17:58:32.709  1019  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-16 17:58:32.709  1019  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-16 17:58:32.709  1019  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-16 17:58:32.719  1019  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-16 17:58:32.719  1019  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-16 17:58:32.719  1019  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-16 17:58:32.779  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg,
08-16 17:58:32.779  1019  1044 I ActivityManager: Killing 6547:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-16 17:58:32.859  1019  1044 I ActivityManager:   Force finishing activity ActivityRecord{2efb4a92 u0 com.test.thalitest/.MainActivity t163}
,08-16 17:58:32.869  1019  1044 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 17:58:32.869  1019  1044 D InputDispatcher: Focus left window: 6547
,08-16 17:58:32.879   258   434 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-16 17:58:32.879   258  1099 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-16 17:58:32.899  1019  1044 D InputDispatcher: Focused application released,
,08-16 17:58:32.899  1019  1049 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 17:58:32.899  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 17:58:32.899  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:58:32.909  1019  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-16 17:58:32.929  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:32.929  1019  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-16 17:58:32.959  2866  2866 I art     : Explicit concurrent mark sweep GC freed 18008(1049KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.003ms total 40.054ms
,08-16 17:58:32.989  1019  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 17:58:32.989  1756  2005 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 17:58:32.999  1879  1879 E SamsungIME: mOCRHelper is null
,08-16 17:58:32.999  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,08-16 17:58:33.009  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-16 17:58:33.009  1470  1470 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 17:58:33.009  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-16 17:58:33.009  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-16 17:58:33.009  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-16 17:58:33.029  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,08-16 17:58:33.029  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-16 17:58:33.029  2850  2850 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 17:58:33 GMT+02:00 2016
,08-16 17:58:33.039  1019  1449 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 17:58:33.039  1019  1449 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.039  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.039  1019  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:33.039  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 17:58:33.049  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
08-16 17:58:33.049  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-16 17:58:33.049  1019  1043 W TextServicesManagerService: no available spell checker services found
,08-16 17:58:33.059  2850  2850 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-16 17:58:33.059  1019  1127 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-16 17:58:33.059  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:33.059  1019  1127 V NetworkStats: performPollLocked(flags=0x3)
,08-16 17:58:33.069  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:33.069  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:33.069  1019  1490 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-16 17:58:33.069  1019  1490 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-16 17:58:33.069  1462  1462 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:58:33.069  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:33.069  1019  1127 V NetworkStats: performPollLocked() took 11ms
,08-16 17:58:33.079  2850  2850 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-16 17:58:33.079  1019  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-16 17:58:33.079  2850  2850 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 17:58:33.089  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.089  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.089  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.089  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.099  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.099  7492  7492 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.099  7492  7492 I libpersona: KNOX_SDCARD checking this for 10090
08-16 17:58:33.099  7492  7492 E Zygote  : v2
08-16 17:58:33.099  7492  7492 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.109  7492  7492 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:33.109  7492  7492 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:33.109  1019  1490 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7492 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-16 17:58:33.109  1462  1462 D RegisteredServicesCache: empty dynamic service
08-16 17:58:33.109  2850  2850 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-16 17:58:33.109  7492  7492 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.119  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.129  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.139  2850  7490 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 17:58:33.139  2850  7490 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-16 17:58:33.139  2850  7490 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-16 17:58:33.139  1462  1462 D RegisteredComponentCache: Collect Tech packages for Knox
,08-16 17:58:33.139  2850  7490 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-16 17:58:33.139  1462  1462 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:58:33.139  1019  1752 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-16 17:58:33.139  1019  1752 D SecContentProvider2: mCursor = null
,08-16 17:58:33.149  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-16 17:58:33.149  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 17:58:33.149  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.159  7492  7492 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:33.159  7492  7492 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:33.159  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-16 17:58:33.159  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-16 17:58:33.159  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 17:58:33.159  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 17:58:33.159  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 17:58:33.159  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 17:58:33.159  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 17:58:33.159  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-16 17:58:33.169  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 17:58:33.169  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 17:58:33.169  1019  1019 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
08-16 17:58:33.169  1019  3382 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-16 17:58:33.169  1019  1164 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-16 17:58:33.179  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-16 17:58:33.179  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.179  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.179  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.179  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.199  7507  7507 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.199  7507  7507 E Zygote  : v2
08-16 17:58:33.199  7507  7507 I libpersona: KNOX_SDCARD checking this for 10052
08-16 17:58:33.199  7507  7507 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:33.199  7507  7507 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:58:33.199  7507  7507 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:33.199  7507  7507 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.199  1019  1044 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7507 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-16 17:58:33.209  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,08-16 17:58:33.209  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.209  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.209  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.209  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.219  1019  3382 D SSRM:n  : SIOP:: AP = 330
,08-16 17:58:33.229  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-16 17:58:33.229  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-16 17:58:33.229  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 17:58:33.229  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 17:58:33.229  7516  7516 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.229  7516  7516 E Zygote  : v2
08-16 17:58:33.229  7516  7516 I libpersona: KNOX_SDCARD checking this for 10098
08-16 17:58:33.229  7516  7516 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.229  7516  7516 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:33.229  7516  7516 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:33.229  7516  7516 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.239  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 17:58:33.239  1019  1044 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7516 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-16 17:58:33.239  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 17:58:33.239  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 17:58:33.239  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-16 17:58:33.239  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 17:58:33.239  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:33.239  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:33.249  1019  1752 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-16 17:58:33.259  7492  7492 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) },
08-16 17:58:33.259  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.259  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:58:33.259  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.259  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.259  7492  7492 D elm:15121: ELMEngine.ELMEngine( context ).
08-16 17:58:33.259  2850  7490 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-16 17:58:33.259  7492  7492 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-16 17:58:33.269  7516  7516 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:58:33.269  7516  7516 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:33.279  7507  7507 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:33.279  7536  7536 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.279  7536  7536 E Zygote  : v2
08-16 17:58:33.279  7536  7536 I libpersona: KNOX_SDCARD checking this for 10032
08-16 17:58:33.279  7507  7507 D ActivityThread: Added TimaKeyStore provider
08-16 17:58:33.279  7536  7536 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.279  7536  7536 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:58:33.279  7536  7536 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:33.279  7536  7536 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.289  1019  1752 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7536 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:58:33.289  1019  1737 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-16 17:58:33.289  1019  1737 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.299  1019  1737 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.299  1019  1737 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:33.299  1019  1737 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-16 17:58:33.299  1019  1058 I art     : Explicit concurrent mark sweep GC freed 72886(4MB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 23MB/35MB, paused 6.919ms total 263.686ms
,08-16 17:58:33.299  7492  7492 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-16 17:58:33.309  2850  7490 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-16 17:58:33.309  2850  7490 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-16 17:58:33.309  7492  7492 D elm:15121: ElmAgentService : onCreate()
,08-16 17:58:33.309  7492  7549 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-16 17:58:33.309  7492  7549 D elm:15121: MainReceiver.listeningToPackageRemoved()
,08-16 17:58:33.309  7492  7549 D elm:15121: MDMBridge.getInstance()
,08-16 17:58:33.319  7492  7549 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 17:58:33.319   307   307 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.543ms total 30.485ms
,08-16 17:58:33.329  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-16 17:58:33.329  7536  7536 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:58:33.329  7536  7536 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:33.329  1019  1132 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:58:33.329  1019  1132 V NetworkStats: updateIfacesLocked()
08-16 17:58:33.329  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:33.329  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:58:33.329  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:33.329  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:33.329  7492  7549 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 17:58:33.339  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:33.339  1019  1132 V NetworkStats: performPollLocked() took 6ms
,08-16 17:58:33.339   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 17.361ms
,08-16 17:58:33.349  2850  2850 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-16 17:58:33.359   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 18.559ms
,08-16 17:58:33.359  1019  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-16 17:58:33.359  1182  1662 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 17:58:33.359  1019  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-16 17:58:33.359  1182  1662 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295,
08-16 17:58:33.359  1019  1752 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast,
08-16 17:58:33.369  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.369  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.369  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.369  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.379  7555  7555 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.379  7555  7555 E Zygote  : v2
08-16 17:58:33.379  7555  7555 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:58:33.379  7555  7555 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.379  7555  7555 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:33.389  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-16 17:58:33.389  7555  7555 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:33.389  7555  7555 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.399  1019  1752 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7555 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 17:58:33.399  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.399  1019  1752 I ActivityManager: Killing 7003:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-16 17:58:33.409  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:33.409  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:33.409  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.409  2634  2634 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-16 17:58:33.409  2634  2634 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
08-16 17:58:33.409  7492  7492 D elm:15121: ElmAgentService : onDestroy().
,08-16 17:58:33.419  1019  1752 I ActivityManager: Killing 7018:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-16 17:58:33.439  1019  1132 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-16 17:58:33.439  1019  1449 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:33.439  7555  7555 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:33.439  7555  7555 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:33.439  1019  1449 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.439  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.439  1019  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:33.439  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:33.449  7033  7570 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-16 17:58:33.449  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.469  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:58:33.469  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:58:33.469  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:58:33.479  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.479  7536  7571 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-16 17:58:33.479  7033  7570 D AccountUtils: Clearing selected account for com.test.thalitest
,08-16 17:58:33.489  7536  7571 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-16 17:58:33.489  1019  1058 D PackageManager: delete codoeFile: 
,08-16 17:58:33.499  1019  1449 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-16 17:58:33.499  1019  1449 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.499  1019  1449 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.499  1019  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:33.499  1019  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-16 17:58:33.499  1019  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,08-16 17:58:33.509  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-16 17:58:33.509  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.509  7536  7571 D SPPClientService: PushLog.txt file is not deleted.
,08-16 17:58:33.509  7536  7571 D SPPClientService: PushLog.txt file is not deleted.
,08-16 17:58:33.509  7536  7571 D SPPClientService: ============PushLog. stop!
,08-16 17:58:33.509  1019  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-16 17:58:33.509  1019  1058 D PackageManager: result of delete: 1{99079261},
,08-16 17:58:33.519  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.519  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:33.519  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-16 17:58:33.519  1019  1317 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:33.519  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:33.519  1019  1317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:33.519  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:33.519  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.519  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.529  7474  7474 D AndroidRuntime: Shutting down VM
,08-16 17:58:33.529  1019  1752 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-16 17:58:33.529  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:58:33.529  1019  1752 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
08-16 17:58:33.529  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:58:33.529  1019  1752 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.529  1019  1752 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:33.529  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-16 17:58:33.529  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.529  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:58:33.529  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:58:33.539  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:58:33.539  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:58:33.539  1019  4459 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:33.539  1019  4459 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:33.539  1019  4459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:33.539  1019  4459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:58:33.539  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.539  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-16 17:58:33.549  1019  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-16 17:58:33.549  1019  1058 D PackageManager: userId{-1}
08-16 17:58:33.549  1019  1058 D PackageManager: andCode{true}
,08-16 17:58:33.549  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-16 17:58:33.549  1019  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:33.549  1019  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:33.549  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.549  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:33.549  1019  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:33.549  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:33.559  1019  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.579  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.579  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.579  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.579  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.589  7583  7583 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.589  7583  7583 E Zygote  : v2
08-16 17:58:33.589  7583  7583 I libpersona: KNOX_SDCARD checking this for 10003
08-16 17:58:33.589  7583  7583 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.589  7583  7583 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:33.589  1019  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7583 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-16 17:58:33.589  7583  7583 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:33.589  1019  1752 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-16 17:58:33.589  7583  7583 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.589  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.589  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.589  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.589  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.609  7593  7593 E Zygote  : MountEmulatedStorage()
,08-16 17:58:33.609  7593  7593 E Zygote  : v2
08-16 17:58:33.609  7593  7593 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:58:33.609  7593  7593 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.609  7593  7593 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:33.609  7593  7593 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 17:58:33.609  7033  7570 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-16 17:58:33.619  1019  1752 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7593 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 17:58:33.619  7593  7593 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.619  1019  1752 I ActivityManager: Killing 7060:com.sec.android.soagent/u0a31 (adj 15): empty #21,
,08-16 17:58:33.619  7033  7581 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
08-16 17:58:33.619  7033  7581 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,08-16 17:58:33.629  7033  7581 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
08-16 17:58:33.629  7033  7581 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,08-16 17:58:33.629  1019  1752 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-16 17:58:33.629  7033  7033 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-16 17:58:33.629  7033  7033 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
,08-16 17:58:33.629  7583  7583 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-16 17:58:33.629  7583  7583 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:33.629  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.629  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.639  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.639  1019  1752 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.639  7033  7581 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
08-16 17:58:33.639  7033  7581 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,08-16 17:58:33.639  7033  7581 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,08-16 17:58:33.649  7033  7581 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
08-16 17:58:33.649  7033  7581 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,08-16 17:58:33.649  7593  7593 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:33.649  7033  7581 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
08-16 17:58:33.649  7033  7581 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
08-16 17:58:33.649  7033  7581 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,08-16 17:58:33.649  7033  7581 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,08-16 17:58:33.659  7611  7611 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.659  7611  7611 E Zygote  : v2
08-16 17:58:33.659  7611  7611 I libpersona: KNOX_SDCARD checking this for 10039
08-16 17:58:33.659  7593  7593 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:33.659  7611  7611 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:33.659  7611  7611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:58:33.659  1019  1752 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7611 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-16 17:58:33.659  7611  7611 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:33.669  6847  6847 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-16 17:58:33.669  7611  7611 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.679  1019  1490 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 17:58:33.679  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.679  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.679  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:33.679  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:33.689  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-16 17:58:33.689  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.689  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.689  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.689  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.709  7629  7629 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.709  7629  7629 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:58:33.709  7629  7629 E Zygote  : v2
08-16 17:58:33.709  7629  7629 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.709  7629  7629 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:33.709  7611  7611 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:33.709  7629  7629 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:33.709  7611  7611 D ActivityThread: Added TimaKeyStore provider
08-16 17:58:33.709  7629  7629 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.719  1019  1031 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7629 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 17:58:33.729  7593  7593 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,08-16 17:58:33.729  1019  4803 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:33.739  7474  7474 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 17:58:33.739  7629  7629 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:33.739  1019  4803 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.739  1019  4803 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:33.739  1019  4803 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:58:33.739  7629  7629 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:33.749  1019  1031 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-16 17:58:33.749  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.749  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.749  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:33.749  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,08-16 17:58:33.749  1019  1125 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:33.749  1019  1125 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.749  1019  1125 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.749  1019  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:33.749  1019  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:33.759  7611  7611 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 17:58:33.759  7611  7611 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:58:33.759  7611  7611 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:58:33.759  7611  7611 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-16 17:58:33.759  7611  7611 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 17:58:33.759  7611  7611 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 17:58:33.759  7611  7611 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 17:58:33.759  1019  1317 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-16 17:58:33.759  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.759  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.769  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.769  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.779  7649  7649 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.779  7649  7649 E Zygote  : v2
08-16 17:58:33.779  7649  7649 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:58:33.779  7649  7649 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.779  7649  7649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:33.789  7649  7649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:58:33.789  7649  7649 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.789  1019  1317 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7649 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 17:58:33.799  1019  1737 I ActivityManager: Killing 7094:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-16 17:58:33.799  7629  7629 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:58:33.809  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-16 17:58:33.809  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-16 17:58:33.819  7649  7649 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:33.829  7649  7649 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:33.849  3214  3293 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-16 17:58:33.859  1019  1448 I ActivityManager: Killing 7117:com.android.chrome/u0a77 (adj 15): empty #21
,08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-16 17:58:33.859  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-16 17:58:33.869  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,08-16 17:58:33.869  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
,08-16 17:58:33.879  1019  1490 D LocationManagerService: getProviders()=[passive, gps]
,08-16 17:58:33.879  7649  7666 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
08-16 17:58:33.879  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,08-16 17:58:33.879  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-16 17:58:33.879  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-16 17:58:33.879  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-16 17:58:33.879  7649  7666 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
08-16 17:58:33.879  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-16 17:58:33.879  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-16 17:58:33.879  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,08-16 17:58:33.879  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
08-16 17:58:33.889  1019  1752 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-16 17:58:33.889  1019  1752 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.889  1019  1752 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:33.889  1019  1752 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:33.889  1019  1752 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-16 17:58:33.899  1019  1448 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink,
08-16 17:58:33.899  1019  1448 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.909  1019  1448 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.909  1019  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:33.909  1019  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-16 17:58:33.919  7649  7649 D AcmsService: Enter Oncreate
08-16 17:58:33.919  7649  7649 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-16 17:58:33.919  7649  7649 D AcmsService: creating AcmsCore
,08-16 17:58:33.919  7649  7649 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-16 17:58:33.919  7649  7649 D AcmsCore: AcmsCore
,08-16 17:58:33.919  6847  6847 D BluetoothAdapter: cancelDiscovery,
,08-16 17:58:33.929  7629  7629 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
,08-16 17:58:33.929  7649  7649 D AcmsCore: init
08-16 17:58:33.929  1019  4459 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
08-16 17:58:33.929  7649  7649 D AcmsCore: Looper handler is not null
08-16 17:58:33.929  7649  7649 D AcmsCore: Post to AcmsCoreHandler
08-16 17:58:33.929  7649  7649 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-16 17:58:33.929  7649  7649 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-16 17:58:33.929  7649  7649 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,08-16 17:58:33.939  7629  7629 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:33.939  7629  7629 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 17:58:33.939  7629  7629 D AndroidRuntime: Shutting down VM
,08-16 17:58:33.939  7629  7629 E AndroidRuntime: FATAL EXCEPTION: main
08-16 17:58:33.939  7629  7629 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7629
08-16 17:58:33.939  7629  7629 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125),
08-16 17:58:33.939  7629  7629 E AndroidRuntime: 	... 9 more
08-16 17:58:33.939  7649  7671 D AcmsCertificateMngr: AcmsCertificateMngr
,08-16 17:58:33.939  7649  7671 D AcmsRevocationMngr: AcmsRevocationMngr,
,08-16 17:58:33.939  7649  7649 D AcmsService: onStartCommand
08-16 17:58:33.939  7649  7649 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
08-16 17:58:33.939  7649  7649 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-16 17:58:33.939  7649  7649 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-16 17:58:33.939  7649  7649 D AcmsService: Incremented Counter Value : onStartCommand
,08-16 17:58:33.939  1019  4459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.939  1019  4459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.939  1019  4459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.939  1019  4459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.959  7672  7672 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.959  7672  7672 I libpersona: KNOX_SDCARD checking this for 10014
,08-16 17:58:33.959  7672  7672 E Zygote  : v2
08-16 17:58:33.959  7672  7672 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.959  7672  7672 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:58:33.969  7672  7672 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:58:33.969  1019  4459 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7672 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,08-16 17:58:33.969  7672  7672 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 17:58:33.969  1019  1125 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,08-16 17:58:33.969  3214  7384 D BluetoothAdapterProperties: mDiscovering is false
08-16 17:58:33.969  3214  7384 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
08-16 17:58:33.969  6847  6847 D BluetoothAdapter: cancelDiscovery = true
08-16 17:58:33.969  6847  6847 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-16 17:58:33.969  7649  7671 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,08-16 17:58:33.969  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-16 17:58:33.969  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.969  1019  1491 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,08-16 17:58:33.979  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.979  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:33.979  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-16 17:58:33.979  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-16 17:58:33.989  7649  7671 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,08-16 17:58:33.989  6847  6847 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-16 17:58:33.999  1019  7685 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop191.tmp: open failed: EROFS (Read-only file system)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 17:58:33.999  1019  7685 E DropBoxManagerService: 	... 5 more

```
