#### Test 821470465fdde63_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-22 10:49:56.949  6579  6579 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-22 10:49:56.949  6579  6579 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-22 10:49:56.949  6788  6788 E Zygote  : MountEmulatedStorage()
08-22 10:49:56.949  6788  6788 E Zygote  : v2
08-22 10:49:56.949  6788  6788 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
--------- beginning of system
08-22 10:49:56.949  6788  6788 I libpersona: KNOX_SDCARD checking this for 10068
08-22 10:49:56.949  6788  6788 I libpersona: KNOX_SDCARD not a persona
08-22 10:49:56.959  6788  6788 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:49:56.959  6788  6788 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-22 10:49:56.959  6579  6579 D Mms/MethodReflector: getSubId is called
08-22 10:49:56.959  6579  6579 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-22 10:49:56.959  6579  6785 D Mms/Synchronizer: [end]    doSync consume time = 35.459323
08-22 10:49:56.959  6579  6579 D Mms/MethodReflector: getTelephonyProperty is called
08-22 10:49:56.959  6579  6579 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-22 10:49:56.959  6579  6579 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-22 10:49:56.959  6579  6579 D Mms/DownloadManager: auto download without roaming -> true
08-22 10:49:56.959  6579  6579 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-22 10:49:56.959  6579  6579 D Mms/DownloadManager: mAutoDownload ------> true
08-22 10:49:56.959  1015  1459 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6788 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-22 10:49:56.969  6579  6723 D Mms/ArtClassLoader: init [DONE] art
08-22 10:49:56.979  6579  6784 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 17.018855
08-22 10:49:56.989  6788  6788 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:49:56.989  6788  6788 D ActivityThread: Added TimaKeyStore provider
08-22 10:49:56.989  6579  6579 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-22 10:49:56.999  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:49:56.999  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:49:56.999  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-22 10:49:56.999  1015  1485 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-22 10:49:56.999  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-22 10:49:57.009  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-22 10:49:57.009  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.009  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.009  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.009  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.019  1015  1027 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6805 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,08-22 10:49:57.029  6805  6805 E Zygote  : MountEmulatedStorage()
08-22 10:49:57.029  6805  6805 I libpersona: KNOX_SDCARD checking this for 10042
08-22 10:49:57.029  6805  6805 E Zygote  : v2
08-22 10:49:57.029  6805  6805 I libpersona: KNOX_SDCARD not a persona
08-22 10:49:57.029  6805  6805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:49:57.029  6805  6805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:49:57.029  6805  6805 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-22 10:49:57.059  6805  6805 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:49:57.059  6805  6805 D ActivityThread: Added TimaKeyStore provider
08-22 10:49:57.069  6579  6814 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-22 10:49:57.069  6579  6814 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-22 10:49:57.069  1015  1027 I ActivityManager: Killing 6396:com.android.defcontainer/u0a3 (adj 15): empty #21
08-22 10:49:57.069  1015  1027 I ActivityManager: Killing 6358:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #22
08-22 10:49:57.079  6788  6788 D BadgeProvider: onCreate
08-22 10:49:57.079  6788  6788 D BadgeProvider: DatabaseHelper
08-22 10:49:57.119  6579  6783 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-22 10:49:57.119  6805  6805 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 10:49:57.119  6805  6805 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 10:49:57.119  6805  6805 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 10:49:57.239  6805  6805 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-22 10:49:57.249  1015  1028 I ActivityManager: Killing 6032:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-22 10:49:57.249   287   287 E SMD     : DCD OFF
08-22 10:49:57.259  1015  1055 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-22 10:49:57.259  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-22 10:49:57.259  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.259  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.259  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.259  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.289  1015  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6823 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-22 10:49:57.289  6823  6823 E Zygote  : MountEmulatedStorage()
08-22 10:49:57.289  1015  3418 I art     : Explicit concurrent mark sweep GC freed 139293(7MB) AllocSpace objects, 4(1863KB) LOS objects, 33% free, 22MB/34MB, paused 5.008ms total 170.479ms
08-22 10:49:57.289  6823  6823 E Zygote  : v2
08-22 10:49:57.289  6823  6823 I libpersona: KNOX_SDCARD checking this for 10003
08-22 10:49:57.289  6823  6823 I libpersona: KNOX_SDCARD not a persona
08-22 10:49:57.289  6823  6823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:49:57.299  6823  6823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:49:57.299  6823  6823 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 10:49:57.309  1462  1665 D TP/SmsProvider: query,matched:26, calling pid = 6579
08-22 10:49:57.309  6821  6821 D AndroidRuntime: 
08-22 10:49:57.309  6821  6821 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 10:49:57.309  6821  6821 D AndroidRuntime: CheckJNI is OFF
08-22 10:49:57.309  6821  6821 D AndroidRuntime: readGMSProperty: start
08-22 10:49:57.309  6821  6821 D AndroidRuntime: readGMSProperty: already setted!!
08-22 10:49:57.309  6821  6821 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 10:49:57.309  6821  6821 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 10:49:57.309  6821  6821 D AndroidRuntime: readGMSProperty: end
08-22 10:49:57.309  6821  6821 D AndroidRuntime: addProductProperty: start
08-22 10:49:57.319  1462  1665 D TP/SmsProvider: match 26:Elapsed time : 6.791 ms
08-22 10:49:57.339  6823  6823 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:49:57.339  6823  6823 D ActivityThread: Added TimaKeyStore provider
08-22 10:49:57.349  1462  1478 D TP/MmsSmsProvider: query,matched:6, calling pid = 6579
08-22 10:49:57.349  1015  1378 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-22 10:49:57.369  1462  1478 D TP/MmsSmsProvider: match 6:Elapsed time : 20.051 ms
08-22 10:49:57.379   283   283 E installd: system dir 0 : /system/app/
08-22 10:49:57.379   283   283 E installd: system dir 1 : /system/priv-app/
08-22 10:49:57.379   283   283 E installd: system dir 2 : /vendor/app/
08-22 10:49:57.379   283   283 E installd: system dir 3 : /oem/app/
08-22 10:49:57.379  1015  1438 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-22 10:49:57.379  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.379  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.379  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.379  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.399  6845  6845 E Zygote  : MountEmulatedStorage()
08-22 10:49:57.399  6845  6845 E Zygote  : v2
08-22 10:49:57.399  6845  6845 I libpersona: KNOX_SDCARD checking this for 10023
08-22 10:49:57.399  6845  6845 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:49:57.399  6845  6845 I libpersona: KNOX_SDCARD not a persona
08-22 10:49:57.399  6845  6845 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:49:57.399  6845  6845 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 10:49:57.399  1015  1438 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6845 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-22 10:49:57.409  1015  1055 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-22 10:49:57.419  6845  6845 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:49:57.419  6845  6845 D ActivityThread: Added TimaKeyStore provider
08-22 10:49:57.439  1015  1467 I ActivityManager: Killing 6479:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-22 10:49:57.479  6821  6821 E AffinityControl: AffinityControl: registerfunction enter
08-22 10:49:57.509  6821  6821 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-22 10:49:57.509  6845  6845 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-22 10:49:57.539  6579  6783 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-22 10:49:57.549  1015  1459 E PersonaManagerService: inState():  stateMachine is null !!
08-22 10:49:57.559  1015  1459 I PersonaManagerService: PersonaId don't exist
08-22 10:49:57.559  1015  1459 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-22 10:49:57.559  1015  1459 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 10:49:57.579  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-22 10:49:57.579  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-22 10:49:57.579  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-22 10:49:57.579  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-22 10:49:57.579  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-22 10:49:57.589  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-22 10:49:57.589  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-22 10:49:57.589  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-22 10:49:57.589  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-22 10:49:57.589  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-22 10:49:57.589  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-22 10:49:57.589  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-22 10:49:57.599  6845  6845 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-22 10:49:57.599  6646  6772 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-22 10:49:57.599  6646  6772 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 10:49:57.599  6646  6772 I GAv4    :   adb logcat -s GAv4
08-22 10:49:57.599  1015  1459 W ActivityManager: mDVFSHelper.acquire()
08-22 10:49:57.599  1015  1459 D FocusedStackFrame: Set to : 0
08-22 10:49:57.609  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 10:49:57.609  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-22 10:49:57.619  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.619  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.619  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.619  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.629  6869  6869 E Zygote  : MountEmulatedStorage()
08-22 10:49:57.629  6869  6869 E Zygote  : v2
08-22 10:49:57.629  6869  6869 I libpersona: KNOX_SDCARD checking this for 10170
08-22 10:49:57.629  6869  6869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:49:57.629  6869  6869 I libpersona: KNOX_SDCARD not a persona
08-22 10:49:57.629  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 10:49:57.629  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-22 10:49:57.639   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-22 10:49:57.639  1015  1459 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6869 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 10:49:57.639  1015  1459 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-22 10:49:57.639  1015  1459 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 10:49:57.639  6869  6869 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:49:57.639  6869  6869 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-22 10:49:57.649  1015  1459 D InputDispatcher: Focused application set to: xxxx
08-22 10:49:57.649  1015  1459 D InputDispatcher: Focus left window: 1486
08-22 10:49:57.659  6821  6821 D AndroidRuntime: Shutting down VM
08-22 10:49:57.659   303   303 I art     : Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 20.283ms
08-22 10:49:57.659  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 10:49:57.659  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 10:49:57.669  6869  6869 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:49:57.669  6869  6869 D ActivityThread: Added TimaKeyStore provider
08-22 10:49:57.669  1015  1467 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-22 10:49:57.669  1015  1015 V ActivityManager: Display changed displayId=0
08-22 10:49:57.679  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-22 10:49:57.679   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.788ms
08-22 10:49:57.699   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 648us total 17.100ms
08-22 10:49:57.709  6646  6772 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-22 10:49:57.709  1015  1438 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-22 10:49:57.709  1015  1467 D PersonaManager: isKioskContainerExistOnDevice
08-22 10:49:57.719  1486  1486 V ActivityThread: updateVisibility : ActivityRecord{2de89d0e token=android.os.BinderProxy@7422a08 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-22 10:49:57.729  1486  1486 D Launcher: onTrimMemory. Level: 20
08-22 10:49:57.729  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-22 10:49:57.739   257   440 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-22 10:49:57.739   257   444 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-22 10:49:57.759  6646  6659 W art     : Suspending all threads took: 12.162ms
08-22 10:49:57.769  6646  6772 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-22 10:49:57.799  6646  6772 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-22 10:49:57.799  6646  6887 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-22 10:49:57.849  6869  6869 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-22 10:49:57.859  6821  6821 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 10:49:57.869  6869  6869 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 4704-4707)
08-22 10:49:57.869  6869  6869 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-22 10:49:57.879  1850  3291 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-22 10:49:57.909  1850  3291 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-22 10:49:57.929  6869  6869 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cf35a44}
08-22 10:49:57.929  6869  6869 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-22 10:49:57.939  1015  1459 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-22 10:49:57.939  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.939  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.939  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.939  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:49:57.939  6869  6869 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 10:49:57.959  6895  6895 E Zygote  : MountEmulatedStorage()
08-22 10:49:57.959  6895  6895 E Zygote  : v2
08-22 10:49:57.959  6895  6895 I libpersona: KNOX_SDCARD checking this for 1000
08-22 10:49:57.959  6895  6895 I libpersona: KNOX_SDCARD not a persona
08-22 10:49:57.959  6895  6895 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:49:57.959  6895  6895 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:49:57.959  1015  1459 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6895 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 10:49:57.959  6895  6895 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 10:49:57.979  6895  6895 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:49:57.979  6895  6895 D ActivityThread: Added TimaKeyStore provider
08-22 10:49:57.999  1850  3291 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-22 10:49:57.999  1015  1502 I ActivityManager: Killing 6505:com.sec.spp.push/u0a32 (adj 15): empty #21
08-22 10:49:58.009  6895  6895 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-22 10:49:58.009  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-22 10:49:58.009  1015  1479 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-22 10:49:58.009  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-22 10:49:58.009  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:49:58.009  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:49:58.009  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-22 10:49:58.019  1015  1378 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-22 10:49:58.019  6869  6869 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-22 10:49:58.029  6869  6869 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 10:49:58.029  6895  6895 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-22 10:49:58.029  6869  6869 E SysUtils: ApplicationContext is null in ApplicationStatus
08-22 10:49:58.039  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-22 10:49:58.039  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:49:58.039  1015  3418 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:49:58.039  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 10:49:58.039  6646  6893 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-22 10:49:58.039  6646  6893 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-22 10:49:58.049  6895  6911 E FilterInstaller: installFilters
08-22 10:49:58.049  6895  6911 E FilterInstaller: There is no requred permission
08-22 10:49:58.059  1015  1479 I ActivityManager: Killing 4757:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-22 10:49:58.059  6869  6869 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 10:49:58.059  6869  6869 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 10:49:58.059  6869  6869 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 10:49:58.059  6869  6869 I Adreno-EGL: Local Branch: 
08-22 10:49:58.059  6869  6869 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 10:49:58.059  6869  6869 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 10:49:58.059  6869  6869 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-22 10:49:58.079  6646  6893 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-22 10:49:58.129  6869  6869 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 10:49:58.139  6869  6869 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-22 10:49:58.139  6869  6869 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-22 10:49:58.139  6646  6893 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-22 10:49:58.139  6646  6893 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2dbcf7da: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-22 10:49:58.139  6646  6893 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-22 10:49:58.149  6869  6869 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-22 10:49:58.149  6869  6869 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-22 10:49:58.219  1015  1041 W ActivityManager: Activity pause timeout for ActivityRecord{3fbf91e4 u0 com.test.thalitest/.MainActivity t163}
08-22 10:49:58.249  6869  6869 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 10:49:58.259  6869  6869 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-22 10:49:58.269  6869  6869 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 10:49:58.269  6869  6869 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-22 10:49:58.279  6869  6869 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-22 10:49:58.279  6869  6869 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 10:49:58.289  6869  6869 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 10:49:58.409  6869  6934 D OpenGLRenderer: Render dirty regions requested: true
08-22 10:49:58.409  1015  1467 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-22 10:49:58.409  1015  1467 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 10:49:58.409  1015  1467 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-22 10:49:58.409  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-22 10:49:58.409  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-22 10:49:58.419  6869  6921 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-22 10:49:58.419  6869  6869 V ActivityThread: updateVisibility : ActivityRecord{12114aa4 token=android.os.BinderProxy@9ca7d1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-22 10:49:58.429  6869  6869 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 10:49:58.429  6869  6869 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-22 10:49:58.439   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-22 10:49:58.449  1015  1378 D InputDispatcher: Focus entered window: 6869
08-22 10:49:58.449  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 10:49:58.449  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 10:49:58.459  6869  6869 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-22 10:49:58.459  6869  6934 I OpenGLRenderer: Initialized EGL, version 1.4
08-22 10:49:58.459  6869  6934 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-22 10:49:58.459  6869  6934 D OpenGLRenderer: Enabling debug mode 0
08-22 10:49:58.489  1015  1479 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-22 10:49:58.489  1175  1175 D PanelView: There is/are notification(s) 
08-22 10:49:58.499  1015  6939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-22 10:49:58.509  1015  1046 I ActivityManager: Displayed Component not be shown by security: +786ms (total +891ms)
08-22 10:49:58.509  1015  1046 W ActivityManager: mDVFSHelper.release()
08-22 10:49:58.509  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3fbf91e4 u0 com.test.thalitest/.MainActivity t163} time:105341
08-22 10:49:58.509   257   444 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-22 10:49:58.509   257  1101 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-22 10:49:58.519  6869  6869 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-22 10:49:58.519  1860  1860 I SamsungIME: getCurrentCandidateView
08-22 10:49:58.529  6869  6869 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9ca7d1 time:105360
08-22 10:49:58.559  6869  6869 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6869
,08-22 10:49:58.609  1860  1860 D SamsungIME: Dismiss ExpandCandiate
,08-22 10:49:58.759  1860  1860 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 10:49:58.769  6869  6869 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 10:49:58.789  1860  1860 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 10:49:58.809  1860  1860 I SamsungIME: KeybaordView init() : load resources
,08-22 10:49:58.839  1860  1860 I SamsungIME: getCurrentKeyboard
,08-22 10:49:58.839  1860  1860 I SamsungIME: getTextKeyboard
,08-22 10:49:58.859  1860  1860 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-22 10:49:58.869  6869  6938 D jxcore_app_log: JniHelper::setJavaVM(0xb803c2b0), pthread_self() = -1201896600
,08-22 10:49:58.869  6869  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 10:49:58.869  6869  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 10:49:58.869  6869  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 10:49:58.869  6869  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 10:49:58.869  6869  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-22 10:49:58.869  6869  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b73a11a added. We now have 1 listener(s)
,08-22 10:49:58.879  6869  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-22 10:49:58.879  6869  6938 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 10:49:58.879  6869  6938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:49:58.879  6869  6938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-22 10:49:58.889  6869  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33c62741 added. We now have 1 listener(s)
08-22 10:49:58.889  6869  6938 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:49:58.889  6869  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 10:49:58.889  6869  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-22 10:49:58.889  6869  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 10:49:58.889  6869  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 10:49:58.889  6869  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 10:49:58.899  6869  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:49:58.899  6869  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-22 10:49:58.899  6869  6938 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-22 10:49:58.909  6869  6938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:49:58.909  6869  6938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:49:58.909  6869  6938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:49:58.909  6869  6938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:49:58.909  6869  6938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:49:58.909  6869  6938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:49:58.909  6869  6938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:49:58.909  6869  6938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 10:49:58.909  6869  6938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-22 10:49:58.909  6869  6938 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:49:58.909  6869  6938 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 10:49:58.909  6579  6579 I Mms/MmsApp:  start initViewCache mms
08-22 10:49:58.909  6579  6579 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1935.301197
08-22 10:49:58.909  6579  6579 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-22 10:49:58.919  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:49:58.919  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:49:58.939  6869  6869 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 10:49:59.059  6579  6579 D AbsListView: Get MotionRecognitionManager
,08-22 10:49:59.059  1015  1378 D MotionRecognitionService:  ssp status : false
,08-22 10:49:59.059  6579  6579 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 150.099895
,08-22 10:49:59.109  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 10:49:59.109  1015  1479 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4222, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-22 10:49:59.109  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-22 10:49:59.109  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 10:49:59.109  1015  1015 I MotionRecognitionService: Plugged
,08-22 10:49:59.109  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 10:49:59.119  1015  1479 D BatteryService: stay LED for charging
,08-22 10:49:59.119  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-22 10:49:59.119  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 10:49:59.119  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-22 10:49:59.119  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 10:49:59.129  2793  2793 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-22 10:49:59.129  2793  3037 D HeadsetStateMachine: Disconnected process message: 10
,08-22 10:49:59.139  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 10:49:59.139  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 10:49:59.139  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 10:49:59.149  6579  6579 D Mms/BubbleViewCache: fillCache bubble = 1
,08-22 10:49:59.499  6869  6947 W jxcore-log: Initializing JXcore engine
08-22 10:49:59.499  6869  6947 W jxcore-log: JXcore engine is ready
,08-22 10:49:59.569  1959  1959 E audit   : type=1400 msg=audit(1471855799.569:205): avc:  denied  { ioctl } for  pid=6947 comm="Thread-1241" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-22 10:49:59.569  1959  1959 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:49:59.569  1959  1959 E audit   : type=1300 msg=audit(1471855799.569:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f8fb8f8 items=0 ppid=303 ppcomm=main pid=6947 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1241" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-22 10:49:59.569  1959  1959 E audit   : type=1320 msg=audit(1471855799.569:205): 
,08-22 10:49:59.579  6869  6947 W jxcore-log: Starting JXcore engine
,08-22 10:49:59.689  6869  6947 W jxcore-log: Platform android
08-22 10:49:59.689  6869  6947 W jxcore-log: 
08-22 10:49:59.689  6869  6947 W jxcore-log: Process ARCH arm
08-22 10:49:59.689  6869  6947 W jxcore-log: 
,08-22 10:49:59.889  6869  6947 I jxcore-log: JXcore Cordova bridge is ready!,
08-22 10:49:59.889  6869  6947 I jxcore-log: 
08-22 10:49:59.889  6869  6947 W jxcore-log: JXcore engine is started
,08-22 10:49:59.889  6869  6938 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,08-22 10:49:59.899  6869  6869 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 10:49:59.989  1015  1093 V AlarmManager: waitForAlarm result :8,
,08-22 10:50:00.249   287   287 E SMD     : DCD OFF,
,08-22 10:50:01.279  1015  1093 V AlarmManager: waitForAlarm result :4
,08-22 10:50:01.289  1015  1388 D NtpTrustedTime: forceRefresh() from cache miss
,08-22 10:50:01.289   277   981 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 10:50:01.289   277   981 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,08-22 10:50:01.289  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-22 10:50:01.299  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-22 10:50:01.299  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-22 10:50:01.299  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-22 10:50:01.299  1175  1175 D KeyguardUpdateMonitor: handleTimeUpdate
,08-22 10:50:01.309  1175  1175 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-22 10:50:01.309  1175  1175 D SecKeyguardClockView: HomeTimezone(): 1
,08-22 10:50:01.309  1015  1015 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-22 10:50:01.309  1015  1015 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,08-22 10:50:01.329  1015  1015 I BackgroundCompactionService: onStart. jobID=801
,08-22 10:50:01.329  1175  1175 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 10:50:01.329  1015  1015 I BackgroundCompactionService: onStart done. jobID=801
,08-22 10:50:01.329  1015  6952 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-22 10:50:01.329  1175  1175 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-22 10:50:01.329  1175  1175 I KeyguardEffectViewController: *** don't update sliding image ***
,08-22 10:50:01.339  1015  6952 I BackgroundCompactionService: compact_memory command done
,08-22 10:50:01.349  1015  1388 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1471855801562 mCachedNtpElapsedRealtime : 108188 mCachedNtpCertainty : 9
,08-22 10:50:01.349  1015  1388 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:01.359  1015  1388 D AlarmManagerService: Setting time of day to sec=1471855801
,08-22 10:50:01.359  1015  1388 D AlarmManagerService: Trying to open a file
,08-22 10:50:01.359  1015  1388 D AlarmManagerService: File Open Success
08-22 10:50:01.359  1015  1388 D AlarmManagerService: File Close Success
08-22 10:50:01.359  1015  1388 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
08-22 10:50:01.567  1015  1093 V AlarmManager: waitForAlarm result :65536
08-22 10:50:01.567  1015  1388 W AlarmManagerService: Unable to set rtc to 1471855801: Invalid argument
,08-22 10:50:01.567  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-22 10:50:01.567  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-22 10:50:01.567  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:01.567  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:01.567  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 10:50:01.576  1015  1093 V AlarmManager: No more alarm at this time.nowELAPSED=108216 batch.start=118239
,08-22 10:50:01.596  1015  1015 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1471855801609
,08-22 10:50:01.606  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 10:50:01.606  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
,08-22 10:50:01.616  1175  1175 D KeyguardUpdateMonitor: handleTimeUpdate
,08-22 10:50:01.616  1015  1015 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,08-22 10:50:01.616  1015  1015 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,08-22 10:50:01.626  1175  1175 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-22 10:50:01.636  1015  1048 I PowerManagerService: [PWL] Off : 30s ago
,08-22 10:50:01.636  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-22 10:50:01.636  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-22 10:50:01.636  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'Config Service fetch' (uid=10011, pid=1850, ws=WorkSource{10170 com.test.thalitest}) (elapsedTime=5658)
08-22 10:50:01.636  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1015, ws=WorkSource{1000}) (elapsedTime=159)
,08-22 10:50:01.636  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10011, pid=1683, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=122)
08-22 10:50:01.636  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10011, pid=1683, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=93)
,08-22 10:50:01.646  1175  1175 D SecKeyguardClockView: HomeTimezone(): 1
,08-22 10:50:01.656  1015  2872 D SSRM:n  : SIOP:: AP = 400
,08-22 10:50:01.656  1015  1015 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 10:50:01.656  1175  1175 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-22 10:50:01.656  1175  1175 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,08-22 10:50:01.666  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 10:50:01.676  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 10:50:01.676  1015  1467 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-22 10:50:01.676  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,08-22 10:50:01.676  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:01.676  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:01.676  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 10:50:01.676  1015  1015 I DrmEventService:  no response from SecureClock 
,08-22 10:50:01.676  1015  1015 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
,08-22 10:50:01.676  1015  1015 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
,08-22 10:50:01.676  1015  1015 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
,08-22 10:50:01.686  1015  1015 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
,08-22 10:50:01.686  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 10:50:01.696  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-22 10:50:01.696  1175  1175 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
08-22 10:50:01.696  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:01.696  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:01.696  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:01.696  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:01.696  1015  1479 D SettingsProvider: name = lockscreen_zoom_panning_effect
08-22 10:50:01.696  1015  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 10:50:01.696  1015  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 10:50:01.696  1015  1479 D SettingsProvider: selectionArgs: false
08-22 10:50:01.696  1015  1479 D SettingsProvider: selectionArgs: 10049
08-22 10:50:01.696  1015  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 10:50:01.696  1015  1479 D SettingsProvider: ret = -1
,08-22 10:50:01.706  1175  1175 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false,
,08-22 10:50:01.716  6957  6957 E Zygote  : MountEmulatedStorage()
08-22 10:50:01.716  1015  1015 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6957 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 10:50:01.716  6957  6957 E Zygote  : v2
08-22 10:50:01.716  6957  6957 I libpersona: KNOX_SDCARD checking this for 10008
08-22 10:50:01.716  6957  6957 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:01.716  1175  1175 D KeyguardEffectViewController: isPreloadedWallpaper=true
,08-22 10:50:01.716  1175  1175 I GeometricMosaic_Keyguard: update
,08-22 10:50:01.716  1683  6963 I VacuumService: Vacuum at: now=1471855801726 tag=VacuumService
,08-22 10:50:01.716  6957  6957 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:01.726  6957  6957 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:01.726  1175  1175 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
08-22 10:50:01.726  6957  6957 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 10:50:01.756  6957  6957 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:01.756  6957  6957 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:01.806  1175  1175 I KeyguardEffectViewUtil: set current wallpaper info
,08-22 10:50:01.806  1015  1485 D SettingsProvider: name = keyguard_current_wallpaper_type
,08-22 10:50:01.806  1015  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 10:50:01.806  1015  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 10:50:01.806  1015  1485 D SettingsProvider: selectionArgs: false
08-22 10:50:01.816  1015  1485 D SettingsProvider: selectionArgs: 10049
08-22 10:50:01.816  1015  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 10:50:01.816  1015  1485 D SettingsProvider: ret = -1
,08-22 10:50:01.816  1015  1467 D SettingsProvider: name = keyguard_current_wallpaper_file_path
08-22 10:50:01.816  1015  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 10:50:01.816  1015  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 10:50:01.816  1015  1467 D SettingsProvider: selectionArgs: false
08-22 10:50:01.816  1015  1467 D SettingsProvider: selectionArgs: 10049
08-22 10:50:01.816  1015  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 10:50:01.816  1015  1467 D SettingsProvider: ret = -1
,08-22 10:50:01.816  1015  1438 D SettingsProvider: name = keyguard_current_wallpaper_res_id
08-22 10:50:01.816  1015  1438 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 10:50:01.816  1015  1438 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 10:50:01.816  1015  1438 D SettingsProvider: selectionArgs: false
08-22 10:50:01.816  1015  1438 D SettingsProvider: selectionArgs: 10049
08-22 10:50:01.816  1015  1438 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 10:50:01.816  1015  1438 D SettingsProvider: ret = -1
,08-22 10:50:01.876  1015  1320 E Watchdog: !@Sync 3
,08-22 10:50:01.896  6957  6957 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-22 10:50:01.896  1175  1652 D TEST    : run!!!
,08-22 10:50:01.896  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 10:50:01.906  1175  1652 I GeometricMosaic_Renderer: setBackgroundBitmap
,08-22 10:50:01.916  6957  6957 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-22 10:50:01.916  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 10:50:01.916  1015  1502 I ActivityManager: Killing 6494:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-22 10:50:01.936  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-22 10:50:01.956  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 10:50:01.956  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,08-22 10:50:01.956  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:01.956  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:01.956  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:01.996  1015  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 10:50:01.996  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,08-22 10:50:01.996  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:01.996  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 10:50:02.006  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:02.016  2927  2927 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Aug 22 10:50:02 GMT+02:00 2016
,08-22 10:50:02.016  1015  1211 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-22 10:50:02.016  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-22 10:50:02.016  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:02.016  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:02.016  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-22 10:50:02.026  2927  2927 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-22 10:50:02.026  1015  1467 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-22 10:50:02.026  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.026  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.026  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.026  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.036  2927  2927 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-22 10:50:02.036  2927  2927 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 10:50:02.036  2927  2927 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 10:50:02.036  2927  6975 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-22 10:50:02.036  2927  6975 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-22 10:50:02.046  2927  6975 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Mon Aug 22 10:50:02 GMT+02:00 2016
,08-22 10:50:02.046  6977  6977 E Zygote  : MountEmulatedStorage()
,08-22 10:50:02.046  6977  6977 E Zygote  : v2
08-22 10:50:02.046  6977  6977 I libpersona: KNOX_SDCARD checking this for 10036
08-22 10:50:02.046  6977  6977 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:02.046  6977  6977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:02.056  1015  1467 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6977 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-22 10:50:02.056  6977  6977 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:02.056  6977  6977 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-22 10:50:02.066  2927  6975 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,08-22 10:50:02.066  2927  2927 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-22 10:50:02.076  6977  6977 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:02.076  6977  6977 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:02.116  6977  6977 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@2d481ac
,08-22 10:50:02.126  6977  6977 I SA      : [SSP] onCreated
,08-22 10:50:02.136  6977  6977 I SA      : [TPM] There is no property file
,08-22 10:50:02.136  6977  6977 I SA      : [SCU] isHaveSA() - false
,08-22 10:50:02.136  6977  6977 I SA      : [TPM] getModelProperty : null
,08-22 10:50:02.146  6977  6977 I SA      : [TPM] getCSCProperty : null
08-22 10:50:02.146  6977  6977 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-22 10:50:02.146  6977  6977 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-22 10:50:02.146  6977  6977 I SA      : [DM] TFT FEATURE: false
,08-22 10:50:02.146  6977  6977 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-22 10:50:02.146  6977  6977 I SA      : [DM] init START
,08-22 10:50:02.156  6977  6977 I SA      : [DM] This device is not a Vodafone
,08-22 10:50:02.156  6977  6977 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-22 10:50:02.156  6977  6977 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-22 10:50:02.156  6977  6977 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-22 10:50:02.156  6977  6977 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-22 10:50:02.166  6977  6977 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-22 10:50:02.166  6977  6977 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-22 10:50:02.166  6977  6977 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-22 10:50:02.166  6977  6977 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 10:50:02.166  6977  6977 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-22 10:50:02.166  6977  6977 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-22 10:50:02.166  6977  6977 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-22 10:50:02.166  6977  6977 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-22 10:50:02.166  6977  6977 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-22 10:50:02.166  6977  6977 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-22 10:50:02.166  6977  6977 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-22 10:50:02.176  6977  6977 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
08-22 10:50:02.176  6977  6977 I SA      : [SCU] isHaveSA() - false
08-22 10:50:02.176  6977  6977 I SA      : support phone number id : false
08-22 10:50:02.176  6977  6977 I SA      : [DM] Supports Ref Jpn : true
08-22 10:50:02.186  6977  6977 I SA      : [DM] init END
,08-22 10:50:02.216  1015  1211 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-22 10:50:02.216  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.216  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.216  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.216  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.226  6996  6996 E Zygote  : MountEmulatedStorage()
08-22 10:50:02.226  6996  6996 I libpersona: KNOX_SDCARD checking this for 10058
08-22 10:50:02.226  6996  6996 E Zygote  : v2
08-22 10:50:02.226  6996  6996 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:02.226  6996  6996 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:02.226  6996  6996 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:02.236  6996  6996 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:02.236  1015  1211 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6996 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 10:50:02.236  1015  1211 I ActivityManager: Killing 6526:com.samsung.helphub/1000 (adj 15): empty #21
,08-22 10:50:02.266  6996  6996 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:02.266  6996  6996 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:02.316  6996  6996 I ExternalOEMControlProvider: onCreate
,08-22 10:50:02.336  1015  1211 I ActivityManager: Killing 5760:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-22 10:50:02.336  1792  1792 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-22 10:50:02.336  6996  7011 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-22 10:50:02.336  1792  1792 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-22 10:50:02.336  1015  1378 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-22 10:50:02.346  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.346  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.346  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.346  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.356  7012  7012 E Zygote  : MountEmulatedStorage()
,08-22 10:50:02.356  7012  7012 E Zygote  : v2
08-22 10:50:02.356  7012  7012 I libpersona: KNOX_SDCARD checking this for 10081
08-22 10:50:02.356  7012  7012 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:02.356  1015  1378 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7012 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-22 10:50:02.356  7012  7012 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:02.366  7012  7012 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 10:50:02.366  7012  7012 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:02.376  7012  7012 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:02.376  7012  7012 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:02.386  6562  6600 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-22 10:50:02.396  7012  7012 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-22 10:50:02.396  7012  7012 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-22 10:50:02.396  7012  7012 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 10:50:02.396  7012  7012 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 10:50:02.396  7012  7012 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-22 10:50:02.416  6562  6600 I AcmsKeyStoreHelper: Key Store exist
08-22 10:50:02.416  6562  6600 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-22 10:50:02.446   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-22 10:50:02.446   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-22 10:50:02.456  1015  1485 D SettingsProvider: name = next_alarm_formatted
08-22 10:50:02.456  1015  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 10:50:02.456  1015  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 10:50:02.456  1015  1485 D SettingsProvider: selectionArgs: false
08-22 10:50:02.456  1015  1485 D SettingsProvider: selectionArgs: 10081
08-22 10:50:02.456  1015  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 10:50:02.456  1015  1485 D SettingsProvider: ret = -1
,08-22 10:50:02.496  6562  6600 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
,08-22 10:50:02.496  6562  6600 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-22 10:50:02.496  6562  6600 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-22 10:50:02.496  6562  6600 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 10:50:02.506  6562  6600 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-22 10:50:02.506  6562  6600 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-22 10:50:02.506  6562  6600 D AcmsCore: This is NOT a valid MirrorLink app
08-22 10:50:02.506  6562  6600 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-22 10:50:02.506  6562  6600 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 10:50:02.506  6562  6600 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-22 10:50:02.506  6562  6600 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-22 10:50:02.506  6562  6562 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-22 10:50:02.506  6562  6562 D AcmsService: Enter onDestroy
,08-22 10:50:02.506  6562  6562 I AcmsService: cleanUp(): inside service clean up
08-22 10:50:02.506  6562  6562 D AcmsCore: AcmsCore: inside DeInit
,08-22 10:50:02.506  6562  6562 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,08-22 10:50:02.506  6562  6562 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,08-22 10:50:02.506  6562  6562 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-22 10:50:02.506  6562  6562 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-22 10:50:02.506  6562  6562 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-22 10:50:02.506  6562  6562 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-22 10:50:02.506  6562  6562 D AcmsService: killing acms process
,08-22 10:50:02.506  6562  6562 I Process : Sending signal. PID: 6562 SIG: 9
,08-22 10:50:02.556  1015  3420 I ActivityManager: Process ACMS.Process (pid 6562)(adj 0) has died(29,752)
,08-22 10:50:02.576  7012  7012 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 111.221ms
,08-22 10:50:02.676  1015  1378 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-22 10:50:02.686  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.686  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.686  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.686  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.696  1015  1378 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7028 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-22 10:50:02.696  1015  1378 I ActivityManager: Killing 6544:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-22 10:50:02.696  7028  7028 E Zygote  : MountEmulatedStorage()
08-22 10:50:02.696  7028  7028 I libpersona: KNOX_SDCARD checking this for 10090
08-22 10:50:02.696  7028  7028 E Zygote  : v2
08-22 10:50:02.696  7028  7028 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:02.696  7028  7028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:02.706  7028  7028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:02.706  7028  7028 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:02.716  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:02.716  7028  7028 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:02.746  7028  7028 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-22 10:50:02.746  7028  7028 D elm:15121: ELMEngine.ELMEngine( context ).
,08-22 10:50:02.746  7028  7028 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-22 10:50:02.746  1015  1467 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-22 10:50:02.746  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-22 10:50:02.746  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:02.746  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:02.746  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-22 10:50:02.756  7028  7028 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-22 10:50:02.756  1015  1502 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-22 10:50:02.756  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.756  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.756  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.756  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.756  7028  7028 D elm:15121: ElmAgentService : onCreate()
08-22 10:50:02.756  7028  7043 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,08-22 10:50:02.766  7028  7043 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,08-22 10:50:02.776  7028  7028 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,08-22 10:50:02.776  7028  7028 D elm:15121: ModuleBase.ModifySetAlarm()
08-22 10:50:02.776  7028  7028 D elm:15121: MDMBridge.getInstance()
08-22 10:50:02.776  7028  7028 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 10:50:02.776  7045  7045 E Zygote  : MountEmulatedStorage()
08-22 10:50:02.776  7045  7045 E Zygote  : v2
08-22 10:50:02.776  7045  7045 I libpersona: KNOX_SDCARD checking this for 10130
08-22 10:50:02.776  7045  7045 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:02.776  7045  7045 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:02.776  7045  7045 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:02.776  1015  1502 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7045 uid=10130 gids={50130, 9997} abi=armeabi-v7a,
08-22 10:50:02.776  7045  7045 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-22 10:50:02.786  7028  7028 D elm:15121: ElmAgentService : onDestroy().
,08-22 10:50:02.786  1015  1211 I ActivityManager: Killing 6054:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-22 10:50:02.806  7045  7045 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:02.806  7045  7045 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:02.826  7045  7045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 10:50:02.826  7045  7045 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-22 10:50:02.836  1015  3420 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-22 10:50:02.846  1015  3420 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.846  1015  3420 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.846  1015  3420 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.846  1015  3420 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.856  7060  7060 E Zygote  : MountEmulatedStorage()
,08-22 10:50:02.856  7060  7060 E Zygote  : v2
08-22 10:50:02.856  7060  7060 I libpersona: KNOX_SDCARD checking this for 10131
08-22 10:50:02.856  7060  7060 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:02.856  7060  7060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:02.856  1015  3420 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7060 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,08-22 10:50:02.856  1015  3420 I ActivityManager: Killing 6626:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-22 10:50:02.856  7060  7060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:02.856  7060  7060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:02.886  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:02.886  7060  7060 D ActivityThread: Added TimaKeyStore provider,
,08-22 10:50:02.896  7060  7060 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-22 10:50:02.896  7060  7060 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 10:50:02.896  7060  7060 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 10:50:02.946  2690  2702 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-22 10:50:02.956  1015  1378 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-22 10:50:02.956  1015  1378 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-22 10:50:02.956  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:02.956  1015  1378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:02.956  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-22 10:50:02.976  1015  1485 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-22 10:50:02.976  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-22 10:50:02.976  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:02.976  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:02.976  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-22 10:50:02.976  1015  1459 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-22 10:50:02.976  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.976  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.976  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:02.976  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:02.996  7081  7081 E Zygote  : MountEmulatedStorage(),
08-22 10:50:02.996  7081  7081 E Zygote  : v2
08-22 10:50:02.996  7081  7081 I libpersona: KNOX_SDCARD checking this for 1000
08-22 10:50:02.996  7081  7081 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:02.996  7081  7081 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:02.996  7081  7081 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:02.996  1015  1459 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7081 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 10:50:03.006  1015  1211 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-22 10:50:03.006  7081  7081 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:03.006  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:03.006  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:03.006  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:03.006  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:03.016  7090  7090 E Zygote  : MountEmulatedStorage()
,08-22 10:50:03.016  7090  7090 E Zygote  : v2
08-22 10:50:03.016  7090  7090 I libpersona: KNOX_SDCARD checking this for 10037
08-22 10:50:03.016  7090  7090 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:03.016  7090  7090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:03.016  1015  1211 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7090 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-22 10:50:03.026  7090  7090 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:03.026  7090  7090 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 10:50:03.036  7081  7081 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:50:03.036  7081  7081 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:03.046  7090  7090 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:03.046  7090  7090 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:03.066  7090  7090 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-22 10:50:03.076  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 10:50:03.076  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 10:50:03.076  7081  7081 D SecurityLogAgent: StateMachine : Current State = 1
,08-22 10:50:03.076  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-22 10:50:03.086  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:03.086  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:03.086  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:03.086  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:03.096  7090  7090 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-22 10:50:03.096  7112  7112 E Zygote  : MountEmulatedStorage()
,08-22 10:50:03.096  7112  7112 E Zygote  : v2
08-22 10:50:03.096  7112  7112 I libpersona: KNOX_SDCARD checking this for 10153
08-22 10:50:03.096  7112  7112 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:03.096  7112  7112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:03.106  1015  1027 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7112 uid=10153 gids={50153, 9997} abi=armeabi-v7a,
,08-22 10:50:03.106  1015  1027 I ActivityManager: Killing 6610:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21,
,08-22 10:50:03.106  7112  7112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 10:50:03.106  7112  7112 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:03.126   303   303 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 22.558ms
,08-22 10:50:03.136   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.658ms
,08-22 10:50:03.146  7112  7112 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:03.146  7112  7112 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:03.156   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.535ms
,08-22 10:50:03.256  1015  1485 I art     : Explicit concurrent mark sweep GC freed 21738(1206KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 22MB/34MB, paused 2.437ms total 145.538ms
,08-22 10:50:03.276  7112  7112 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 10:50:03.296  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-22 10:50:03.296  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:03.296  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:03.296  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:03.296  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:03.316  7128  7128 E Zygote  : MountEmulatedStorage()
,08-22 10:50:03.316  7128  7128 E Zygote  : v2
08-22 10:50:03.316  7128  7128 I libpersona: KNOX_SDCARD checking this for 1000
08-22 10:50:03.316  7128  7128 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:03.316  7128  7128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:03.316  1015  1028 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7128 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 10:50:03.316  1015  1028 I ActivityManager: Killing 6646:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-22 10:50:03.316  7128  7128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:03.316  7128  7128 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:03.336  7128  7128 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:03.336  7128  7128 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:03.346  1015  1438 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,08-22 10:50:03.346  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-22 10:50:03.356  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:03.356  1015  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 10:50:03.356  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-22 10:50:03.376  7128  7128 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1471855803384
08-22 10:50:03.376  7128  7128 D         : TimeServiceNative: User Time to be set is 1471855803384
08-22 10:50:03.376  7128  7128 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-22 10:50:03.376  7128  7128 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-22 10:50:03.376  7128  7128 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1471855803384
,08-22 10:50:03.376   319   552 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-22 10:50:03.376  7128  7128 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-22 10:50:03.376   319  7147 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1471855803384
08-22 10:50:03.376   319  7147 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1471855803384, operation = 0
08-22 10:50:03.386   319  7147 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/17/71 2:32:56
08-22 10:50:03.386   319  7147 D QC-time-services: Daemon:Value read from RTC seconds = 35605976000
08-22 10:50:03.386   319  7147 D QC-time-services: Daemon:new time 1471855803384 
08-22 10:50:03.386   319  7147 D QC-time-services: Daemon: delta 1436249827384 genoff 1436249827384 
08-22 10:50:03.386   319  7147 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249827384 to memory
08-22 10:50:03.386   319  7147 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-22 10:50:03.386   319  7147 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-22 10:50:03.396   319  7147 D QC-time-services: Updating the TOD offset
08-22 10:50:03.396   319  7147 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249827384 to memory
08-22 10:50:03.396   319  7147 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-22 10:50:03.396   319  7147 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-22 10:50:03.396   319  7147 E QC-time-services: Daemon:Update to modem bit set
08-22 10:50:03.396   319  7147 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-22 10:50:03.396   319  7147 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285027384
,08-22 10:50:03.396  7128  7128 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-22 10:50:03.396   319   550 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-22 10:50:03.396  1015  1479 I ActivityManager: Killing 6678:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-22 10:50:03.396   319   552 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-22 10:50:03.406  2690  2690 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-22 10:50:03.406  2690  2690 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-22 10:50:03.406  2690  2690 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-22 10:50:03.416  2690  2690 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-22 10:50:03.416  2690  2690 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-22 10:50:03.416  1015  1027 I ActivityManager: Killing 6703:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-22 10:50:03.426  2690  2690 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-22 10:50:03.426  2690  2690 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-22 10:50:03.426  2690  2690 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
08-22 10:50:03.426  2690  2690 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-22 10:50:03.426  2690  2690 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-22 10:50:03.426  2690  2690 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-22 10:50:03.426  2690  2690 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-22 10:50:03.426  2690  2690 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-22 10:50:03.426  2690  2690 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-22 10:50:03.426  2690  2690 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-22 10:50:03.436  2690  2690 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-22 10:50:03.436  2690  2690 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-22 10:50:03.436  2690  2690 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-22 10:50:03.446  2690  2690 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-22 10:50:03.446  2690  2690 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-22 10:50:03.446   287   287 E SMD     : DCD OFF,
,08-22 10:50:04.356  7090  7090 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-22 10:50:04.366  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:04.366  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:04.366  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-22 10:50:04.366  1015  3420 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:04.366  1015  3420 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:04.366  1015  3420 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-22 10:50:04.376  1015  1255 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-22 10:50:04.376  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:04.376  1015  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:04.376  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-22 10:50:04.376  1015  3418 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-22 10:50:04.376  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-22 10:50:04.386  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:04.386  1015  3418 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:04.386  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-22 10:50:04.386  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:04.386  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:04.386  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-22 10:50:04.396  1015  1438 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-22 10:50:04.396  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-22 10:50:04.406  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:04.406  1015  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:04.406  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-22 10:50:04.416  1015  1485 I ActivityManager: Killing 6662:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-22 10:50:06.106  1850  6607 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XMW_ZbNRfm4d4CVMYXJD9vET-qIBARGJ_8dsGVX82kCisGrLrgDhnlePbEzKHfC-Bm_zs3Jiv32CrbFDkHKLh9sRWMSCml9Pcwj9s91zrKw3DA0vXg5ss4EZDPeO_vu5w6pD5cuFN8b6yYi6aef1Sw8vD2dP2FN1jzo39sv2QJhLXxJLVUaoL480yali9Ux2UnfqJoT5MHk6ohNSBeGjWD-Jicj7JO_qG_NfCtp9qM9f7NxCY
,08-22 10:50:06.116  1850  6607 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-22 10:50:06.116  1015  1485 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-22 10:50:06.116  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-22 10:50:06.116  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:06.116  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:06.116  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:06.126  1850  6607 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 10:50:06.126   277   981 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 10:50:06.126   277   981 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-22 10:50:06.136  1850  6607 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-22 10:50:06.136  1850  6607 I qtaguid : Tagging socket 108 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1850, getuid(): 10011
,08-22 10:50:06.176  1850  6607 I qtaguid : Tagging socket 111 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1850, getuid(): 10011
,08-22 10:50:06.346  1850  6607 I qtaguid : Untagging socket 108
,08-22 10:50:06.346  1850  1850 I ConfigFetchService: fetch service done; releasing wakelock
,08-22 10:50:06.346  1850  1850 I ConfigFetchService: stopping self
,08-22 10:50:06.356  1015  1467 I ActivityManager: Killing 6740:com.sec.pcw.device/1000 (adj 15): empty #21
,08-22 10:50:06.446   287   287 E SMD     : DCD OFF
,08-22 10:50:07.446   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 10:50:07.656  1015  1055 D PackageManager: [MSG] MCS_UNBIND
,08-22 10:50:07.656  1015  1479 I ActivityManager: Killing 6756:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-22 10:50:07.816  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-22 10:50:08.446   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 10:50:09.346  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 10:50:09.346  1015  1479 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4250, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 10:50:09.346  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-22 10:50:09.346  1015  1479 D BatteryService: stay LED for charging
08-22 10:50:09.346  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 10:50:09.356  1015  1015 I MotionRecognitionService: Plugged,
08-22 10:50:09.356  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 10:50:09.356  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 10:50:09.356  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 10:50:09.356  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 10:50:09.356  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 10:50:09.366  2793  2793 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-22 10:50:09.376  2793  3037 D HeadsetStateMachine: Disconnected process message: 10
,08-22 10:50:09.386  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 10:50:09.386  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-22 10:50:09.386  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 10:50:09.446   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 10:50:09.456   287   287 E SMD     : DCD OFF,
,08-22 10:50:09.536  1015  2891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-22 10:50:10.446   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 10:50:10.766  1015  1041 I ActivityManager: Waited long enough for: ServiceRecord{3ef22124 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,08-22 10:50:11.356  1683  1683 I ConfigService: onDestroy,
,08-22 10:50:11.446   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 10:50:11.596  1015  1093 V AlarmManager: waitForAlarm result :4
08-22 10:50:11.596  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-22 10:50:11.686  1015  2872 D SSRM:n  : SIOP:: AP = 360
,08-22 10:50:11.726  6098  6098 D FactoryTest: Not factory mode
,08-22 10:50:11.726  6098  6098 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-22 10:50:11.726  6098  6098 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-22 10:50:11.726  6098  6098 D MTPRx   : still no open session command from host, so toast
,08-22 10:50:11.726  6098  6098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-22 10:50:11.726  6098  6098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-22 10:50:11.726  6098  6098 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118368
,08-22 10:50:11.736  1015  1378 E PersonaManagerService: inState():  stateMachine is null !!
,08-22 10:50:11.736  1015  1378 I PersonaManagerService: PersonaId don't exist
,08-22 10:50:11.736  1015  1378 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-22 10:50:11.736  1015  1378 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 10:50:11.736  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:11.736  1015  1378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:11.736  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-22 10:50:11.746  1015  1378 W ActivityManager: mDVFSHelper.acquire()
,08-22 10:50:11.766  1015  1378 D PersonaManager: isKioskContainerExistOnDevice
,08-22 10:50:11.766  1015  1378 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 10:50:11.766  1015  1378 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 10:50:11.766  1015  1378 D InputDispatcher: Focused application set to: xxxx
08-22 10:50:11.766  1015  1378 D InputDispatcher: Focus left window: 6869
,08-22 10:50:11.766  6098  6098 E MTPRx   : started activity for popup
,08-22 10:50:11.776  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 10:50:11.776  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 10:50:11.806  6098  6098 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-22 10:50:11.806  6098  6098 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-22 10:50:11.806  6098  6098 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-22 10:50:11.806  6098  6098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 10:50:11.806  6098  6098 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 10:50:11.806  6098  6098 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 10:50:11.836  6098  6098 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-22 10:50:11.846  1015  1255 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-22 10:50:11.846  1015  1255 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-22 10:50:11.846  1015  1255 D InputDispatcher: Focused application set to: xxxx
,08-22 10:50:11.846  1015  1255 D InputDispatcher: Focus entered window: 6869
,08-22 10:50:11.846  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 10:50:11.846  1015  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 10:50:11.846  1015  1027 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1fbdaf1f attribute=null, token = android.os.BinderProxy@3d0d129
,08-22 10:50:11.846  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 10:50:11.896  6098  6098 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-22 10:50:11.906  6098  6098 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-22 10:50:11.906  6098  6098 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-22 10:50:11.926  6869  6869 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-22 10:50:11.926  6869  6869 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-22 10:50:11.936  6869  6869 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-22 10:50:11.936  6869  6869 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-22 10:50:11.936  1015  3418 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-22 10:50:11.936  1015  3418 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 10:50:11.936  1015  3418 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-22 10:50:11.936  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-22 10:50:11.936  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-22 10:50:11.946  6412  6445 D Finsky  : [1129] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-22 10:50:11.946  6412  6412 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-22 10:50:11.956  6869  6869 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 10:50:11.956  6869  6869 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-22 10:50:11.956  6869  6869 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9ca7d1 time:118592
,08-22 10:50:11.956  6869  6869 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1c08659d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2d8cb1ba, 16908290=android.view.AbsSavedState$1@2d8cb1ba}, android:focusedViewId=100}]}]
,08-22 10:50:11.956  6869  6869 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-22 10:50:11.956  6869  6869 V ActivityThread: updateVisibility : ActivityRecord{12114aa4 token=android.os.BinderProxy@9ca7d1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-22 10:50:11.956  6869  6869 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-22 10:50:11.956  6869  6869 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-22 10:50:11.966  1015  1255 D PersonaManager: isKioskContainerExistOnDevice
,08-22 10:50:12.446   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-22 10:50:12.456   287   287 E SMD     : DCD OFF
,08-22 10:50:13.006  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 10:50:13.006  6869  6947 I jxcore-log: 
,08-22 10:50:13.016  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 10:50:13.016  6869  6947 I jxcore-log: 
,08-22 10:50:13.016  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:13.016  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:13.016  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:13.016  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:13.016  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:13.016  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:13.016  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:13.016  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:13.016  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 10:50:13.026  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 10:50:13.026  6869  6947 I jxcore-log: 
,08-22 10:50:13.026  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 10:50:13.026  6869  6947 I jxcore-log: 
,08-22 10:50:13.666  6869  6947 D ExecuteNativeTests: Running unit tests
,08-22 10:50:13.756  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:13.756  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b added. We now have 2 listener(s)
,08-22 10:50:13.756  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-22 10:50:13.756  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:13.756  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:13.756  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:13.756  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 added. We now have 2 listener(s)
08-22 10:50:13.756  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:13.756  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:13.756  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:13.766  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:13.766  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:13.766  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:13.766  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:13.766  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:13.766  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:13.766  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:13.766  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:13.766  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 10:50:13.766  6869  6947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:13.766  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:13.766  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 10:50:13.766  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 10:50:13.766  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-22 10:50:13.766  6869  6947 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-22 10:50:13.766  6869  6947 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 10:50:13.766  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 10:50:13.766  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 10:50:13.766  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 10:50:13.766  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:13.766  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:13.766  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:13.766  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:13.766  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:13.766  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:13.776  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:13.776  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b removed from the list
08-22 10:50:13.776  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:13.776  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 removed from the list
,08-22 10:50:13.776  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:13.776  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:13.776  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:13.776  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:13.776  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:13.776  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 10:50:13.776  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:13.776  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:13.776  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:13.776  6869  6947 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-22 10:50:13.776  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:13.786  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:13.786  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:13.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:13.786  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:13.786  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:13.786  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:13.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:13.786  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:13.786  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:13.786  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:13.786  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:13.786  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:13.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:13.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:13.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:13.786  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 10:50:13.786  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:13.786  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:13.786  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:13.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:13.786  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:13.786  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:13.786  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:13.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:13.786  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:13.786  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:13.786  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:13.786  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:13.786  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:13.786  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:13.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:13.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:13.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:13.786  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:13.786  6869  6947 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 10:50:13.796  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:13.796  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:13.796  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:13.796  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:13.796  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:13.796  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:13.796  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:13.796  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:13.796  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 10:50:13.796  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:13.796  6869  6947 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:50:13.796  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 10:50:13.796  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:13.796  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 10:50:13.796  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:13.796  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 10:50:13.796  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 10:50:13.796  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:13.806  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:13.806  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 10:50:13.816  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 10:50:13.816  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-22 10:50:13.816  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-22 10:50:13.816  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 10:50:13.816  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 10:50:13.816  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 10:50:13.836  2793  2803 D BtGatt.GattService: registerClient() - UUID=f5d245ed-b7ad-403c-9e6e-e3853a670570
,08-22 10:50:13.876  2793  2856 D BtGatt.GattService: onClientRegistered() - UUID=f5d245ed-b7ad-403c-9e6e-e3853a670570, clientIf=6
,08-22 10:50:13.886  6869  6879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 10:50:13.886  2793  2857 D BtGatt.GattService: start scan with filters
,08-22 10:50:13.886  2793  3034 D BtGatt.ScanManager: handling starting scan
,08-22 10:50:13.886  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 10:50:13.886  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 10:50:13.886  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-22 10:50:13.886  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 10:50:13.886  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 10:50:13.896  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
08-22 10:50:13.896  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,08-22 10:50:13.896  2793  3034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
08-22 10:50:13.896  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 10:50:13.906  6869  6947 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 10:50:13.906  2793  2856 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 10:50:13.906  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:13.906  2793  3034 D BtGatt.ScanManager: allow scan with filters
08-22 10:50:13.906  2793  3034 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-22 10:50:13.906  2793  3034 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-22 10:50:13.906  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:13.906  6869  6947 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 10:50:13.906  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:13.906  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 10:50:13.906  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:13.906  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 10:50:13.906  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 10:50:13.906  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 10:50:13.906  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:13.906  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 10:50:13.916  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 10:50:13.916  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 10:50:13.916  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-22 10:50:13.916  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:13.916  2793  3034 D BtGatt.ScanManager: Starting BLE batch scan
08-22 10:50:13.916  2793  3034 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 10:50:13.916  2793  2809 D BtGatt.GattService: stopScan() - queue size =1
,08-22 10:50:13.916  2793  2857 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 10:50:13.916  2793  2856 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-22 10:50:13.916  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:13.916  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 10:50:13.926  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 10:50:13.926  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 10:50:13.926  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:13.926  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 10:50:13.926  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:13.926  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 10:50:13.926  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:13.926  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 10:50:13.926  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 10:50:13.926  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:13.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:13.936  2793  3034 D BtGatt.ScanManager: filter size is 1
,08-22 10:50:13.936  2793  3034 D BtGatt.ScanManager: delete FilterIndex - 3
,08-22 10:50:13.936  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 10:50:13.936  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 10:50:13.936  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:13.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 10:50:13.936  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:13.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:13.936  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:13.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:13.936  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:13.946  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 10:50:13.946  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 10:50:13.946  2793  3034 D BtGatt.ScanManager: stopping BLe Batch
,08-22 10:50:13.946  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 10:50:13.946  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:13.946  6869  6947 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 10:50:13.946  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:13.946  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 10:50:13.946  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:13.956  2793  3034 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 10:50:13.956  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:13.956  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:13.956  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:13.956  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:13.956  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:13.956  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:13.956  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:13.956  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:13.956  2793  2856 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-22 10:50:13.956  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:13.956  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 10:50:13.956  6869  6947 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:50:13.956  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 10:50:13.956  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:13.956  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 10:50:13.956  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:13.956  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 10:50:13.966  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:13.966  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 10:50:13.966  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:13.966  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 10:50:13.966  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 10:50:13.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 10:50:13.976  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 10:50:13.976  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 10:50:13.976  2793  2803 D BtGatt.GattService: registerClient() - UUID=7d286ecc-7880-451e-82b3-08806f5da7c3
,08-22 10:50:14.016  2793  2856 D BtGatt.GattService: onClientRegistered() - UUID=7d286ecc-7880-451e-82b3-08806f5da7c3, clientIf=6
,08-22 10:50:14.016  6869  6881 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-22 10:50:14.016  2793  2809 D BtGatt.GattService: start scan with filters
,08-22 10:50:14.026  2793  3034 D BtGatt.ScanManager: handling starting scan
08-22 10:50:14.026  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 10:50:14.026  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 10:50:14.026  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:14.026  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 10:50:14.026  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 10:50:14.026  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 10:50:14.026  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 10:50:14.026  2793  2856 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 10:50:14.026  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.026  2793  3034 D BtGatt.ScanManager: allow scan with filters
,08-22 10:50:14.036  2793  3034 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 10:50:14.036  2793  3034 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-22 10:50:14.036  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 10:50:14.036  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 10:50:14.036  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.036  2793  3034 D BtGatt.ScanManager: Starting BLE batch scan
08-22 10:50:14.036  2793  3034 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 10:50:14.046  6869  6947 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 10:50:14.046  2793  2856 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 10:50:14.046  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.046  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:14.046  6869  6947 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-22 10:50:14.046  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.046  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 10:50:14.056  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.056  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 10:50:14.056  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 10:50:14.056  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 10:50:14.056  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:14.056  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:14.056  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 10:50:14.056  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 10:50:14.056  2793  2857 D BtGatt.GattService: stopScan() - queue size =1
,08-22 10:50:14.056  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 10:50:14.056  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.056  2793  2803 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 10:50:14.056  2793  3034 D BtGatt.ScanManager: filter size is 1
,08-22 10:50:14.056  2793  3034 D BtGatt.ScanManager: delete FilterIndex - 4
,08-22 10:50:14.066  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 10:50:14.066  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.066  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 10:50:14.066  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 10:50:14.066  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 10:50:14.066  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:14.066  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 10:50:14.066  2793  3034 D BtGatt.ScanManager: stopping BLe Batch
08-22 10:50:14.066  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:14.066  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 10:50:14.066  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:14.066  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 10:50:14.066  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:14.066  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 10:50:14.066  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:14.066  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:14.076  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.076  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.076  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:14.076  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.076  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.076  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.076  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.076  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.076  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.076  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.076  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-22 10:50:14.076  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 10:50:14.076  2793  3034 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 10:50:14.076  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.076  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.076  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.076  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.076  6869  6947 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 10:50:14.076  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:14.076  2793  2856 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-22 10:50:14.076  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.086  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:14.086  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:14.086  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:14.086  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:14.086  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:14.086  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:14.086  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:14.086  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:14.086  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 10:50:14.086  6869  6947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:14.086  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:14.086  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:14.096  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 10:50:14.096  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:14.096  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-22 10:50:14.096  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:14.096  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 10:50:14.096  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 10:50:14.096  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 10:50:14.096  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 10:50:14.106  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 10:50:14.106  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 10:50:14.106  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 10:50:14.106  2793  2809 D BtGatt.GattService: registerClient() - UUID=9fbbafa8-672d-4a5f-a174-26121b1f0bff
,08-22 10:50:14.146  2793  2856 D BtGatt.GattService: onClientRegistered() - UUID=9fbbafa8-672d-4a5f-a174-26121b1f0bff, clientIf=6
,08-22 10:50:14.146  6869  6884 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 10:50:14.146  2793  2803 D BtGatt.GattService: start scan with filters
,08-22 10:50:14.156  2793  3034 D BtGatt.ScanManager: handling starting scan
,08-22 10:50:14.156  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 10:50:14.156  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 10:50:14.156  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:14.156  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 10:50:14.156  2793  2856 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 10:50:14.156  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.156  2793  3034 D BtGatt.ScanManager: allow scan with filters
,08-22 10:50:14.156  2793  3034 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-22 10:50:14.166  2793  3034 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-22 10:50:14.166  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:14.166  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 10:50:14.166  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 10:50:14.166  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 10:50:14.166  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 10:50:14.166  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.166  2793  3034 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 10:50:14.166  2793  3034 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 10:50:14.176  6869  6947 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 10:50:14.176  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.176  6869  6947 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 10:50:14.176  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.176  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 10:50:14.176  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.176  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 10:50:14.176  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 10:50:14.176  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 10:50:14.176  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:14.176  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:14.176  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 10:50:14.176  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 10:50:14.176  2793  2857 D BtGatt.GattService: stopScan() - queue size =1
,08-22 10:50:14.176  2793  2809 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 10:50:14.176  2793  2856 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 10:50:14.176  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.186  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 10:50:14.186  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 10:50:14.186  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-22 10:50:14.186  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:14.186  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 10:50:14.186  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:14.186  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 10:50:14.186  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.196  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 10:50:14.196  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 10:50:14.196  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:14.196  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 10:50:14.196  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.196  6869  6947 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 10:50:14.196  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.196  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.196  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.196  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:14.196  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.196  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.196  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.196  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.196  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:14.196  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:14.196  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.196  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.196  2793  3034 D BtGatt.ScanManager: filter size is 1
,08-22 10:50:14.196  2793  3034 D BtGatt.ScanManager: delete FilterIndex - 5
08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.196  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.196  6869  6947 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-22 10:50:14.196  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.196  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.196  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.196  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:14.196  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.196  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.196  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.196  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 10:50:14.196  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.196  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.196  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.196  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.196  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:14.196  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.206  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 10:50:14.206  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.206  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-22 10:50:14.206  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.206  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.206  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.206  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.206  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.206  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 10:50:14.206  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.206  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.206  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:14.206  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.206  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.206  6869  6947 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-22 10:50:14.206  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:14.206  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.206  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.206  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.206  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-22 10:50:14.206  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.206  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.206  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.206  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.206  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.206  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.206  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.206  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 10:50:14.206  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 10:50:14.206  2793  3034 D BtGatt.ScanManager: stopping BLe Batch
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.206  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.206  6869  6947 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-22 10:50:14.206  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.206  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.206  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.206  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.206  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.206  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.206  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.206  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.206  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.206  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.206  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.206  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.206  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 10:50:14.206  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 10:50:14.206  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-22 10:50:14.206  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 10:50:14.206  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 10:50:14.206  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.216  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 10:50:14.216  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.216  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.216  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:14.216  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.216  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.216  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.216  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 10:50:14.216  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.216  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.216  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.216  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.216  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-22 10:50:14.216  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 10:50:14.216  2793  3034 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-22 10:50:14.216  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.216  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.216  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.216  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.216  6869  6947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 10:50:14.216  6869  6947 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-22 10:50:14.216  2793  2856 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 10:50:14.216  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:14.216  6869  6947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 10:50:14.216  6869  6947 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 10:50:14.216  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 10:50:14.226  6869  6947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-22 10:50:14.226  6869  6947 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 10:50:14.226  6869  6947 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-22 10:50:14.226  6869  6947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 10:50:14.226  6869  6947 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 10:50:14.226  6869  6947 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-22 10:50:14.226  6869  6947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 10:50:14.226  6869  6947 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 10:50:14.226  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-22 10:50:14.226  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-22 10:50:14.226  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-22 10:50:14.226  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-22 10:50:14.226  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-22 10:50:14.226  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-22 10:50:14.226  6869  6947 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-22 10:50:14.226  6869  6947 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 10:50:14.226  6869  6947 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-22 10:50:14.226  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:14.226  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.226  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.226  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.226  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.226  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.226  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-22 10:50:14.226  6869  7161 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1305)
08-22 10:50:14.226  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.226  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.226  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.226  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.226  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.226  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.226  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.226  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.236  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.236  6869  6947 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-22 10:50:14.236  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.236  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.236  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.236  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.236  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.236  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.236  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.236  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.236  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.236  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.236  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.236  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.236  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.236  6869  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1305
08-22 10:50:14.236  6869  6947 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-22 10:50:14.236  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.236  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.236  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.236  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.236  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.236  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.236  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.236  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.236  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.236  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.236  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.236  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.236  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.236  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.236  6869  6947 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-22 10:50:14.236  6869  6947 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-22 10:50:14.236  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 10:50:14.236  6869  6947 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-22 10:50:14.236  6869  6947 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 10:50:14.236  6869  6947 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-22 10:50:14.236  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-22 10:50:14.246  6869  6947 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-22 10:50:14.246  6869  6947 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 10:50:14.246  6869  6947 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-22 10:50:14.246  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 10:50:14.246  6869  6947 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-22 10:50:14.246  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.246  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.246  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 10:50:14.246  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.246  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.246  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.246  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.246  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.246  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:14.246  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.246  6869  7161 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.246  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.246  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.246  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.246  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 10:50:14.246  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.246  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.246  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.246  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
,08-22 10:50:14.246  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.246  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.246  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.246  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.246  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.246  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.246  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.246  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.246  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:14.246  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:14.246  6869  7161 D BluetoothSocket: connect(): myUserId = 0
08-22 10:50:14.246  6869  7161 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 10:50:14.246  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-22 10:50:14.246  6869  6947 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-22 10:50:14.256  6869  6869 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-22 10:50:14.256  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.256  6869  6869 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:14.256  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.256  6869  7163 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-22 10:50:14.256  6869  7163 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-22 10:50:14.256  2793  2803 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:14.256  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:14.256  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:14.256  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:14.256  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.256  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.256  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.256  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.256  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.256  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.256  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.256  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.256  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.256  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.256  6869  6869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-22 10:50:14.256  6869  7161 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.256  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.256  6869  6947 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-22 10:50:14.256  6869  6947 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 10:50:14.256  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 10:50:14.256  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.256  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.256  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.256  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.256  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.256  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.256  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.256  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.256  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.256  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.256  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.266  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.266  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.266  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.266  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.266  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.266  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.266  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.266  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.266  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.266  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.266  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.266  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.266  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.266  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
,08-22 10:50:14.266  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:14.266  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:14.266  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:14.266  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.266  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.266  6869  6947 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3162625b not in the list
08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.266  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.266  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:14.266  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.266  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:14.266  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:14.266  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:14.266  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:14.266  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3dcaf8 not in the list
08-22 10:50:14.266  6869  6947 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-22 10:50:14.266  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 10:50:14.266  6869  6947 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-22 10:50:14.266  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 10:50:14.266  6869  6947 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-22 10:50:14.266  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-22 10:50:14.276  6869  6947 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 10:50:14.276  6869  6947 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 10:50:14.276  6869  6947 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-22 10:50:14.276  6869  6947 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-22 10:50:14.276  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:14.276  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35f951a added. We now have 2 listener(s)
08-22 10:50:14.276  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:14.276  6869  6947 D BluetoothAdapter: enable()
,08-22 10:50:14.276  6869  6947 D BluetoothAdapter: enable(): BT is already enabled..!,
,08-22 10:50:14.286  1015  1255 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-22 10:50:14.286  1015  1255 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 10:50:14.286  1015  1255 D SecContentProvider2: mCursor = null
,08-22 10:50:14.286  1015  1255 D WifiService: setWifiEnabled: true pid=6869, uid=10170
,08-22 10:50:14.286  1015  1255 W ActivityManager: Permission Denial: getCurrentUser() from pid=6869, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-22 10:50:14.286  1015  1255 W WifiService: Failed getting userId using ActivityManagerNative
08-22 10:50:14.286  1015  1255 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6869, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 10:50:14.286  1015  1255 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 10:50:14.286  1015  1255 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 10:50:14.286  1015  1255 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 10:50:14.286  1015  1255 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 10:50:14.286  1015  1255 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 10:50:14.286  1015  1255 D SettingsProvider: name = wifi_on
,08-22 10:50:14.296  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:14.296  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b3c984b added. We now have 3 listener(s)
08-22 10:50:14.296  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:14.296  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:14.296  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@435e228 added. We now have 4 listener(s)
08-22 10:50:14.296  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:14.296  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:14.296  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c9ab41 added. We now have 5 listener(s)
08-22 10:50:14.296  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:14.306  1015  1438 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 10:50:14.306  1015  1438 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-22 10:50:14.306  1015  1438 D SecContentProvider2: mCursor = null
,08-22 10:50:14.306  1015  1438 D WifiService: setWifiEnabled: false pid=6869, uid=10170
,08-22 10:50:14.306  1015  1438 D SettingsProvider: name = wifi_on
,08-22 10:50:14.316  6869  6947 D BluetoothAdapter: disable()
,08-22 10:50:14.316  1015  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-22 10:50:14.316  1387  1387 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 10:50:14.316  1387  1387 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-22 10:50:14.316  1015  1459 D SettingsProvider: name = bluetooth_on
08-22 10:50:14.316  1387  1387 I wpa_supplicant: P2P: Current p2p state = IDLE
08-22 10:50:14.316  1387  1387 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-22 10:50:14.326  2793  2853 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-22 10:50:14.326  2793  2853 D BluetoothAdapterProperties: Setting state to 13
08-22 10:50:14.326  2793  2853 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-22 10:50:14.326  2793  2853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-22 10:50:14.326  2793  2853 D BluetoothAdapterService: updateAdapterState state is 13
,08-22 10:50:14.326  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:14.326  1015  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:14.326  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 10:50:14.326  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:14.326  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:14.326  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:14.326  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:14.326  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:14.326  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:14.326  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:14.326  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:14.326  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:14.326  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:14.326  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.326  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:14.326  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:14.326  6869  6947 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:50:14.326  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:14.336  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:14.336  2793  2793 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-22 10:50:14.336  2793  2853 D BluetoothAdapterService: Autoconnection is available 
08-22 10:50:14.336  2793  2853 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-22 10:50:14.336  2793  2853 D BluetoothAdapterService: terminating service from this receiver
08-22 10:50:14.336  2793  2793 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@349b0b17, channel: 19, state: LISTENING
08-22 10:50:14.336  2793  2793 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@349b0b17, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@40e61c3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e2eeb04mSocket: android.net.LocalSocket@1ead78ed impl:android.net.LocalSocketImpl@1f02e322 fd:FileDescriptor[80]
08-22 10:50:14.336  2793  2793 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1ead78ed impl:android.net.LocalSocketImpl@1f02e322 fd:FileDescriptor[80]
,08-22 10:50:14.336  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:14.336  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
08-22 10:50:14.336  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:14.336  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:14.346  1860  1860 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-22 10:50:14.346  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-22 10:50:14.346  1387  1387 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
,08-22 10:50:14.346  1015  1125 E WifiNative-wlan0: do suspend true
,08-22 10:50:14.346  1015  1124 D WifiP2pService: InactiveState{ what=147461 }
08-22 10:50:14.346  1015  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
08-22 10:50:14.346  1015  1124 D WifiP2pService: DefaultState{ what=147461 }
,08-22 10:50:14.346  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 10:50:14.356  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:14.356  1175  1175 D BluetoothTile:  getBluetoothState : 13
,08-22 10:50:14.356  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 10:50:14.356  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 10:50:14.356  4558  4558 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:14.356  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 10:50:14.356  1015  3420 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 10:50:14.366  1015  3420 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:14.366  1015  3420 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.366  1015  3420 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 10:50:14.366  1015  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:14.366  1015  1502 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-22 10:50:14.366  2793  2853 D BluetoothAdapterProperties: onBluetoothDisable()
,08-22 10:50:14.366  2793  2853 D BluetoothAdapterProperties: mDiscovering is false
,08-22 10:50:14.366  1015  1479 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 10:50:14.366  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:14.366  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:14.366  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:14.366  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:14.366  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:14.366  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:14.366  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:14.366  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:14.366  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:14.366  2793  2853 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-22 10:50:14.366  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-22 10:50:14.366  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:14.366  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 10:50:14.376  4558  4558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 10:50:14.376  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-22 10:50:14.376  2793  2856 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 10:50:14.376  2793  2856 D BluetoothAdapterProperties: Scan Mode:20
,08-22 10:50:14.376  1015  1485 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-22 10:50:14.376  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 10:50:14.376  1015  1485 W ActivityManager: userId = 0, bbcId = -10000,
08-22 10:50:14.376  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.376  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-22 10:50:14.376  2793  2853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-22 10:50:14.376  4558  4558 D BluetoothPbap: Proxy object disconnected
08-22 10:50:14.376  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:14.376  4558  4558 D PbapServerProfile: Bluetooth service disconnected
08-22 10:50:14.376  2793  2853 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-22 10:50:14.376  2793  2853 E bt-btif : cmd socket is not created
08-22 10:50:14.376  2793  5467 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-22 10:50:14.376  2793  2858 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-22 10:50:14.386  2793  2853 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,08-22 10:50:14.386  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:14.386  2793  2793 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23bb41b3, channel: 5, state: LISTENING
08-22 10:50:14.386  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 10:50:14.386  2793  2793 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@23bb41b3, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@126b571f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@831b370mSocket: android.net.LocalSocket@1a75b6e9 impl:android.net.LocalSocketImpl@3100f6e fd:FileDescriptor[82]
08-22 10:50:14.386  2793  2793 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a75b6e9 impl:android.net.LocalSocketImpl@3100f6e fd:FileDescriptor[82]
,08-22 10:50:14.386  4558  4558 D DockEventReceiver: finishStartingService: stopping service
,08-22 10:50:14.396  2793  2793 I BtOppRfcommListener: stopping Accept Thread
,08-22 10:50:14.396  2793  2793 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f9e460f, channel: 12, state: LISTENING
08-22 10:50:14.396  2793  2793 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f9e460f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36702396, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e56969cmSocket: android.net.LocalSocket@2569d8a5 impl:android.net.LocalSocketImpl@22b1b47a fd:FileDescriptor[86]
08-22 10:50:14.396  2793  2793 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2569d8a5 impl:android.net.LocalSocketImpl@22b1b47a fd:FileDescriptor[86]
,08-22 10:50:14.396  2793  5467 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-22 10:50:14.396  2793  2858 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-22 10:50:14.396  2793  2858 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-22 10:50:14.396  2793  2858 W bt-btif : invalid rfc slot id: 4
,08-22 10:50:14.396  2793  2793 V BluetoothOppManager: cleanUp...
,08-22 10:50:14.396  4558  4558 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 10:50:14.406  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:14.406  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-22 10:50:14.406  6869  7161 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20ba6e27, channel: -1, state: INIT
08-22 10:50:14.406  6869  7161 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@20ba6e27, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@161af8d4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2944ba7dmSocket: android.net.LocalSocket@3cc3ad72 impl:android.net.LocalSocketImpl@1655c5c3 fd:FileDescriptor[105]
08-22 10:50:14.406  6869  7161 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3cc3ad72 impl:android.net.LocalSocketImpl@1655c5c3 fd:FileDescriptor[105]
,08-22 10:50:14.406  6869  7161 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1305)
,08-22 10:50:14.406  1015  1467 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-22 10:50:14.406  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:14.406  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:14.406  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:14.406  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:14.416  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-22 10:50:14.416  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 10:50:14.426  2793  2858 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-22 10:50:14.426  2793  2858 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
,08-22 10:50:14.426  2793  2858 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 10:50:14.426  7170  7170 I libpersona: KNOX_SDCARD checking this for 10055
08-22 10:50:14.426  2793  2858 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-22 10:50:14.426  7170  7170 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:14.426  2793  2858 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 10:50:14.426  2793  2858 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 10:50:14.426  7170  7170 E Zygote  : MountEmulatedStorage()
08-22 10:50:14.426  7170  7170 E Zygote  : v2
,08-22 10:50:14.426  7170  7170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:14.426  7170  7170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:14.436  1015  1467 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7170 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-22 10:50:14.436  7170  7170 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:14.436   277   985 D CommandListener: Clearing all IP addresses on wlan0
,08-22 10:50:14.436  1683  2555 V NativeCrypto: Read error: ssl=0xb8564290: I/O error during system call, Connection timed out
,08-22 10:50:14.446  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:14.446  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 10:50:14.446  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.446  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.446  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 10:50:14.446  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.446  1683  2555 V NativeCrypto: SSL shutdown failed: ssl=0xb8564290: I/O error during system call, Broken pipe
,08-22 10:50:14.446  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:14.446  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 10:50:14.446  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:14.446  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,08-22 10:50:14.446  1015  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-22 10:50:14.446  1015  1378 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-22 10:50:14.446  1015  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-22 10:50:14.446  1015  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-22 10:50:14.446  1015  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-22 10:50:14.446  1015  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-22 10:50:14.446  1015  1781 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 10:50:14.446  1015  1781 I qtaguid : Tagging socket 359 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
,08-22 10:50:14.456  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 10:50:14.476  7170  7170 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:50:14.476  7170  7170 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:14.476  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
08-22 10:50:14.476  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-22 10:50:14.476  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1,
08-22 10:50:14.476  1015  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-22 10:50:14.476  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-22 10:50:14.486  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-22 10:50:14.486  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 10:50:14.486  1015  1781 I qtaguid : Untagging socket 359,
08-22 10:50:14.486  1015  1781 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 10:50:14.486  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:14.486  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 10:50:14.486  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:14.486  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 10:50:14.486  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:14.496  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer,
08-22 10:50:14.486  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:14.496  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 10:50:14.496  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.496  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-22 10:50:14.496  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.496  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:14.506  1015  1124 D WifiP2pService: P2pDisablingState
,08-22 10:50:14.506  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-22 10:50:14.506  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-22 10:50:14.516  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-22 10:50:14.516  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 10:50:14.516  1015  1046 D WifiDisplayController: disconnect
08-22 10:50:14.516  1015  1046 D WifiDisplayController: updateConnection
08-22 10:50:14.516  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 10:50:14.516  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 10:50:14.516  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 10:50:14.516  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 10:50:14.516  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 10:50:14.516  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-22 10:50:14.516  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-22 10:50:14.526  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-22 10:50:14.526  1015  1124 D WifiP2pService: p2p socket connection lost
,08-22 10:50:14.526  1015  1124 D WifiP2pService: P2pDisabledState
08-22 10:50:14.526  1015  1125 E WifiNative-wlan0: do suspend true
,08-22 10:50:14.526  7170  7170 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-22 10:50:14.546  1015  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-22 10:50:14.546  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 10:50:14.556  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 },
,08-22 10:50:14.556  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-22 10:50:14.556  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-22 10:50:14.556  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-22 10:50:14.556  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:14.556  7170  7170 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-22 10:50:14.556  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 10:50:14.556  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.556  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 10:50:14.556  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.556  7170  7170 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-22 10:50:14.556  7170  7170 D UserAnalysis: Create SecureDbHelper
,08-22 10:50:14.566  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:14.566  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-22 10:50:14.566  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:14.566  1015  1127 V NetworkStats: updateIfacesLocked()
08-22 10:50:14.566  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-22 10:50:14.566  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-22 10:50:14.566   277   981 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 10:50:14.566   277   981 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-22 10:50:14.566   277   985 D CommandListener: Clearing all IP addresses on wlan0
08-22 10:50:14.566  7170  7170 D IntelligenceServiceApplication: onCreate()
08-22 10:50:14.566  1015  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-22 10:50:14.566  1015  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-22 10:50:14.566  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:14.566  1015  1127 V NetworkStats: performPollLocked() took 6ms
,08-22 10:50:14.576  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-22 10:50:14.576  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-22 10:50:14.576  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:14.576  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 10:50:14.576  1387  1387 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-22 10:50:14.576  1175  1741 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-22 10:50:14.576  1015  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 10:50:14.576  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-22 10:50:14.576  1015  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 10:50:14.576  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-22 10:50:14.576  1462  1462 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-22 10:50:14.576  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-22 10:50:14.576  1462  1462 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 10:50:14.576  1015  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-22 10:50:14.576  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-22 10:50:14.586  7170  7170 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-22 10:50:14.586  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-22 10:50:14.586  1015  1128 D Tethering: MasterInitialState.processMessage what=3
08-22 10:50:14.586  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-22 10:50:14.596  1015  1122 V NetworkStats: updateIfacesLocked()
08-22 10:50:14.596  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:14.596  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-22 10:50:14.596  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-22 10:50:14.596  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 10:50:14.596  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-22 10:50:14.596  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:14.596  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:14.596  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 10:50:14.596  1015  1125 D SecContentProvider2: mCursor = null
08-22 10:50:14.596  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-22 10:50:14.596  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 10:50:14.596  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:14.596  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-22 10:50:14.596  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:14.596  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:14.596  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-22 10:50:14.596  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:14.596  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:14.596  1015  1122 V NetworkStats: performPollLocked() took 7ms
08-22 10:50:14.596  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:14.596  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:14.596  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-22 10:50:14.606  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-22 10:50:14.606  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-22 10:50:14.606  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-22 10:50:14.606  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-22 10:50:14.606  4558  4558 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 10:50:14.606  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:14.606  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:14.606  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:14.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:14.606  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:14.606  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:14.606  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:14.606  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:14.606  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:14.606  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,08-22 10:50:14.606  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:14.606  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:14.606  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:14.606  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:14.606  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:14.616  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:14.616  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:14.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:14.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:14.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:14.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:14.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:14.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:14.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:14.616  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:14.616  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:14.616  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-22 10:50:14.616  1015  3418 I ActivityManager: Killing 6788:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-22 10:50:14.616  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:14.616  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 10:50:14.616  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.616  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.616  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.616  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:14.616  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:14.616  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-22 10:50:14.616  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:14.616  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 10:50:14.616  1175  1175 D HotspotTile: onReceive : 0, 0
08-22 10:50:14.616  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-22 10:50:14.616  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-22 10:50:14.626  1015  3418 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-22 10:50:14.626  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:14.626  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:14.626  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:14.626  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:14.626  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,08-22 10:50:14.646  7192  7192 E Zygote  : MountEmulatedStorage()
,08-22 10:50:14.646  7192  7192 E Zygote  : v2
08-22 10:50:14.646  7192  7192 I libpersona: KNOX_SDCARD checking this for 10105
08-22 10:50:14.646  7192  7192 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:14.646  1015  3418 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7192 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-22 10:50:14.646  7192  7192 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:14.646  7192  7192 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:14.646  7192  7192 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 10:50:14.656  2793  2853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-22 10:50:14.656  2793  2853 D BtConfig.SecureMode: isSecureModeOn:false
08-22 10:50:14.656  2793  2853 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-22 10:50:14.656  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-22 10:50:14.656  2793  2853 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-22 10:50:14.656  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 10:50:14.656  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 10:50:14.656  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-22 10:50:14.656  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:14.656  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:14.656  1015  1502 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:14.656  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 10:50:14.656  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:14.656  1015  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.656  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:14.666  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-22 10:50:14.666  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService,
08-22 10:50:14.666  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-22 10:50:14.666  2793  2793 D HeadsetService: Received stop request...Stopping profile...
,08-22 10:50:14.666  1015  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:14.666  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 10:50:14.666  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:14.666  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.666  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:14.666  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
08-22 10:50:14.666  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-22 10:50:14.666  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-22 10:50:14.666  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-22 10:50:14.666  1015  3418 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:14.666  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-22 10:50:14.666  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 10:50:14.676  2793  2793 D A2dpService: Received stop request...Stopping profile...
08-22 10:50:14.676  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:14.676  1015  3418 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.676  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 10:50:14.676  2793  3074 D A2dpStateMachine: Exit Disconnected: -1
08-22 10:50:14.676  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-22 10:50:14.676  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 10:50:14.676  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 10:50:14.676  4558  4558 D HeadsetProfile: Bluetooth service disconnected
,08-22 10:50:14.676  7192  7192 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:14.686  7192  7192 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:14.686  1015  3418 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:14.686  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-22 10:50:14.686  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:14.686  1015  3418 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.686  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:14.686  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-22 10:50:14.686  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 10:50:14.686  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-22 10:50:14.686  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:14.696  1015  1438 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:14.696  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-22 10:50:14.696  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:14.696  1015  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.696  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:14.696  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService,
08-22 10:50:14.696  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:14.696  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-22 10:50:14.696  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-22 10:50:14.696  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-22 10:50:14.696  4558  4558 D BluetoothA2dp: Proxy object disconnected
08-22 10:50:14.696  4558  4558 D A2dpProfile: Bluetooth service disconnected
,08-22 10:50:14.696  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:14.696  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 10:50:14.706  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:14.706  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.706  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 10:50:14.706  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-22 10:50:14.706  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-22 10:50:14.706  2793  2853 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 10:50:14.706  1015  3418 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:14.706  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 10:50:14.706  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:14.706  1015  3418 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.706  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 10:50:14.706  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:14.706  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:14.706  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:14.706  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:14.706  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-22 10:50:14.706  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService,
08-22 10:50:14.706  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 10:50:14.706  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 10:50:14.706  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 10:50:14.706  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-22 10:50:14.706  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 10:50:14.706  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 10:50:14.706  2793  2853 D BluetoothAdapterState: Stopping profile services that were post enabled
08-22 10:50:14.706  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-22 10:50:14.706  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 10:50:14.716  2793  2793 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-22 10:50:14.716  2793  2793 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 10:50:14.716  2793  2793 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 10:50:14.716  2793  2793 D HidService: Received stop request...Stopping profile...
08-22 10:50:14.716  2793  2793 D HidService: Stopping Bluetooth HidService
08-22 10:50:14.716  2793  2793 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 10:50:14.716  2793  2793 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-22 10:50:14.716  2793  2793 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 10:50:14.716  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:14.716  2793  2793 D HealthService: Received stop request...Stopping profile...
08-22 10:50:14.716  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:14.716  4558  4558 D BluetoothInputDevice: Proxy object disconnected
08-22 10:50:14.716  4558  4558 D HidProfile: Bluetooth service disconnected
,08-22 10:50:14.726  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-22 10:50:14.726  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 10:50:14.726  2793  2793 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-22 10:50:14.726  2793  2793 D PanService: Received stop request...Stopping profile...
08-22 10:50:14.726  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
08-22 10:50:14.726  1387  1387 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 10:50:14.726  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 10:50:14.726  2793  2793 D BluetoothA2dp: Proxy object disconnected
08-22 10:50:14.726  2793  2793 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-22 10:50:14.726  2793  3075 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-22 10:50:14.726  2793  2793 I GKI_LINUX: GKI_exit_task 2 done
08-22 10:50:14.726  4558  4558 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 10:50:14.726  4558  4558 D PanProfile: Bluetooth service disconnected
,08-22 10:50:14.726  2793  2793 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-22 10:50:14.726  2793  2793 D BluetoothMapService: Received stop request...Stopping profile...
,08-22 10:50:14.736  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:14.736  4558  4558 D BluetoothMap: Proxy object disconnected
08-22 10:50:14.736  4558  4558 D MapProfile: Bluetooth service disconnected
,08-22 10:50:14.736  2793  2793 D SapService: Received stop request...Stopping profile...
08-22 10:50:14.736  2793  2793 D SapService: Stopping Bluetooth SapService
,08-22 10:50:14.736  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:14.736  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-22 10:50:14.736  2793  2793 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 10:50:14.736  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:14.736  2793  2793 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:14.736  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-22 10:50:14.736  2793  2793 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 10:50:14.736  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:14.736  2793  2793 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:14.736  2793  2793 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-22 10:50:14.736  2793  2793 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 10:50:14.736  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-22 10:50:14.736  2793  2793 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 10:50:14.746  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:14.746  2793  2793 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:14.746  2793  2793 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 10:50:14.746  2793  2793 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-22 10:50:14.746  4558  4558 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-22 10:50:14.746  4558  4558 D SapProfile: Bluetooth service disconnected
,08-22 10:50:14.746  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-22 10:50:14.746  2793  2793 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 10:50:14.746  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 10:50:14.746  2793  2793 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-22 10:50:14.746  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-22 10:50:14.746  2793  2793 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-22 10:50:14.746  2793  2793 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-22 10:50:14.746  2793  2793 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-22 10:50:14.746  1015  1041 W ActivityManager: mDVFSHelper.release()
,08-22 10:50:14.746  2793  2853 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-22 10:50:14.746  2793  2853 D BluetoothAdapterProperties: Setting state to 10
,08-22 10:50:14.746  2793  2853 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-22 10:50:14.746  2793  2853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 10:50:14.746  2793  2853 D BluetoothAdapterService: updateAdapterState state is 10
08-22 10:50:14.746  2793  2853 D BluetoothAdapterService: Autoconnection is available 
08-22 10:50:14.746  2793  2853 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-22 10:50:14.746  2793  2853 I BluetoothAdapterState: Entering OffState
08-22 10:50:14.746  4558  4566 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:14.746  4558  4566 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:14.746  4558  4567 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 10:50:14.756  1450  1769 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 10:50:14.756  6869  6869 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-22 10:50:14.756  1450  1769 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:14.756  1742  2303 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:14.756  1742  2303 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 10:50:14.756  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:14.756  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 10:50:14.756  1462  1665 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:14.756  1462  1665 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:14.756  4558  4566 D BluetoothMap: onBluetoothStateChange: up=false
,08-22 10:50:14.766  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 10:50:14.766  1387  1387 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
08-22 10:50:14.766  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 10:50:14.766  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 10:50:14.766  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 10:50:14.766  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 10:50:14.766  4558  4567 D Bluetoothsap: onBluetoothStateChange: up=false,
08-22 10:50:14.766  4558  4567 D Bluetoothsap: Unbinding service...
,08-22 10:50:14.766  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 10:50:14.766  4558  4566 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 10:50:14.766  6869  6881 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 10:50:14.766  6869  6881 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 10:50:14.766  6869  6881 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-22 10:50:14.766  6869  6881 D BluetoothLeAdvertiser: Exit stop advertising
08-22 10:50:14.766  6869  6881 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-22 10:50:14.766  6869  6881 D BluetoothLeScanner: Exiting stopAllScan
08-22 10:50:14.766  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 10:50:14.766  1683  1767 D BluetoothAdapter: onBluetoothStateChange: up=false,
,08-22 10:50:14.766  1683  1767 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 10:50:14.766  1427  1440 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:14.766  1427  1440 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:14.776  2793  2857 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 10:50:14.776  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 10:50:14.776  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 10:50:14.776  2793  2809 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:14.776  2793  2809 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 10:50:14.776  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 10:50:14.776  4558  4567 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 10:50:14.776  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 10:50:14.776  1175  2851 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:14.776  1175  2851 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 10:50:14.776  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 10:50:14.776  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 10:50:14.776  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:14.776  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-22 10:50:14.776  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 10:50:14.776  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 10:50:14.786  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 10:50:14.786  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 10:50:14.786  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:14.786  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 10:50:14.786  1175  1175 D BluetoothTile:  getBluetoothState : 10
,08-22 10:50:14.786  1860  1860 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-22 10:50:14.786  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 10:50:14.786  1015  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:14.786  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 10:50:14.786  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 10:50:14.786  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 10:50:14.796  4558  4558 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:14.796  1387  1387 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-22 10:50:14.796  1387  1387 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-22 10:50:14.796  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:14.796  1387  1387 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-22 10:50:14.796  1387  1387 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-22 10:50:14.796  1387  1387 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-22 10:50:14.796  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:14.796  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:14.796  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:14.796  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:14.796  1015  1128 D Tethering: InitialState.processMessage what=4
08-22 10:50:14.796  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:14.796  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:14.796  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:14.796  1015  1128 E Tethering: No numeric data
,08-22 10:50:14.796  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 10:50:14.796  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:14.796  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 10:50:14.796  1015  1128 D Tethering: clearTetheredNotification()
08-22 10:50:14.796  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 10:50:14.796  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:14.796  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 10:50:14.796  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 10:50:14.796  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 10:50:14.806  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 10:50:14.806  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-22 10:50:14.806  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:14.806  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:14.806  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 10:50:14.806  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-22 10:50:14.806  1015  1122 V NetworkStats: performPollLocked() took 4ms
,08-22 10:50:14.806  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:14.806  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 10:50:14.806  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:14.806  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:14.806  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 10:50:14.806  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 10:50:14.816  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 10:50:14.816  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 10:50:14.816  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-22 10:50:14.816  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 10:50:14.816  1175  1175 D HotspotTile: updateTetherState():false, false
,08-22 10:50:14.816  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 10:50:14.816  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 10:50:14.816  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 10:50:14.816  1462  1462 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 10:50:14.816  1462  1462 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 10:50:14.836   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 10:50:14.836   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 10:50:14.836  7192  7221 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 10:50:14.846   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 10:50:14.846   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 10:50:14.846  7192  7221 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 10:50:14.936  1387  1387 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 10:50:14.976  7192  7192 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 10:50:14.976  7192  7192 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 10:50:14.976  7192  7192 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 10:50:14.976  7192  7192 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 10:50:14.976  7192  7192 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.k.d(PG:583)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 10:50:14.976  7192  7192 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 10:50:14.986  1015  1378 I ActivityManager: Killing 6805:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
08-22 10:50:14.976  7192  7192 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 10:50:14.986  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:14.976  7192  7192 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 10:50:14.976  7192  7192 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 10:50:14.976  1387  1387 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-22 10:50:14.986  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:14.986  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:14.986  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 10:50:14.986  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 10:50:14.986  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:14.986  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:14.986  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 10:50:14.996  1628  1628 I Hs20UtilService: Starting #8
08-22 10:50:14.996  1628  1657 I Hs20UtilService: Message received 5007
08-22 10:50:14.996  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 10:50:14.996  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 10:50:14.996  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-22 10:50:14.996  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 10:50:14.996  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:14.996  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 10:50:14.996  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 10:50:15.006  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:15.006  1015  1378 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:15.006  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-22 10:50:15.006  1015  1378 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-22 10:50:15.006  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.006  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.006  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.006  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.016  7237  7237 E Zygote  : MountEmulatedStorage()
,08-22 10:50:15.016  7237  7237 E Zygote  : v2
08-22 10:50:15.016  7237  7237 I libpersona: KNOX_SDCARD checking this for 10102
08-22 10:50:15.016  7237  7237 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:15.016  7237  7237 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:15.016  1015  1378 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7237 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-22 10:50:15.026  7237  7237 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:15.026  7237  7237 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-22 10:50:15.046  7192  7222 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-22 10:50:15.046  7237  7237 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:50:15.046  7237  7237 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:15.066  7237  7237 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-22 10:50:15.086  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-22 10:50:15.086  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-22 10:50:15.086  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-22 10:50:15.096  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-22 10:50:15.106  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:15.106  1015  3420 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 10:50:15.116  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:15.116  1015  3420 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:15.116  1015  3420 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:15.116  1015  3420 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-22 10:50:15.116  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:15.116  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 10:50:15.116  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:15.116  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 10:50:15.116  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:15.116  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:15.116  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:15.116  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:15.116  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:15.116  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:15.116  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-22 10:50:15.126  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 10:50:15.126  1175  1175 D HotspotTile: onReceive : 1, 0
,08-22 10:50:15.126  4558  4558 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 10:50:15.126  1742  2198 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 10:50:15.126  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:15.136  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:15.316  7237  7259 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-22 10:50:15.316  7237  7259 I Babel_SMS: MmsConfig.loadMmsSettings
08-22 10:50:15.316  7237  7259 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-22 10:50:15.316  7237  7259 I Babel_SMS: MmsConfig.loadFromDatabase
,08-22 10:50:15.336  7237  7259 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-22 10:50:15.336  7237  7259 I Babel_SMS: MmsConfig.loadFromResources
,08-22 10:50:15.336  7237  7259 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-22 10:50:15.336  7237  7259 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-22 10:50:15.356  1015  1502 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-22 10:50:15.356  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-22 10:50:15.366  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.366  1015  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:15.366  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 10:50:15.386  7237  7237 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 10:50:15.386  7237  7237 I Babel_Crash: startup - clean
,08-22 10:50:15.416  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-22 10:50:15.416  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 10:50:15.416  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 10:50:15.426  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 10:50:15.426  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:15.426  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 10:50:15.426  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 10:50:15.426  1015  1459 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-22 10:50:15.426  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.426  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.426  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.426  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:15.436  7237  7237 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-22 10:50:15.436  7262  7262 E Zygote  : MountEmulatedStorage()
08-22 10:50:15.436  7262  7262 I libpersona: KNOX_SDCARD checking this for 10064
08-22 10:50:15.436  7262  7262 E Zygote  : v2
08-22 10:50:15.436  7262  7262 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:15.436  7262  7262 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:15.436  7262  7262 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:15.446  1015  1459 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7262 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 10:50:15.446  7262  7262 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:15.446  7237  7237 W AudioCapabilities: Unsupported mime audio/evrc
,08-22 10:50:15.456   287   287 E SMD     : DCD OFF
,08-22 10:50:15.466  7262  7262 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:15.466  7237  7237 W AudioCapabilities: Unsupported mime audio/qcelp
,08-22 10:50:15.466  7262  7262 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:15.466  7237  7237 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-22 10:50:15.466  7237  7237 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-22 10:50:15.476  7237  7237 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-22 10:50:15.476  7237  7237 W AudioCapabilities: Unsupported mime audio/x-ima
,08-22 10:50:15.476  7237  7237 W AudioCapabilities: Unsupported mime audio/qcelp
,08-22 10:50:15.486  7237  7237 W AudioCapabilities: Unsupported mime audio/evrc
,08-22 10:50:15.486  7262  7262 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-22 10:50:15.496  7237  7237 W VideoCapabilities: Unsupported mime video/wvc1
,08-22 10:50:15.496  7237  7237 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-22 10:50:15.506  7262  7262 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 10:50:15.506  7262  7262 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-22 10:50:15.506  7237  7237 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-22 10:50:15.506  7237  7237 W VideoCapabilities: Unsupported mime video/wvc1
,08-22 10:50:15.516  7237  7237 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-22 10:50:15.516  7237  7237 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-22 10:50:15.516  7237  7237 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-22 10:50:15.516  7237  7237 W VideoCapabilities: Unsupported mime video/mp43
,08-22 10:50:15.516  7237  7237 W VideoCapabilities: Unsupported mime video/sorenson
,08-22 10:50:15.526  7237  7237 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-22 10:50:15.536  7237  7237 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-22 10:50:15.546  7262  7262 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 10:50:15.546  1015  1378 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-22 10:50:15.546  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:15.556  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.556  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.556  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:15.566  7277  7277 E Zygote  : MountEmulatedStorage()
,08-22 10:50:15.566  7277  7277 E Zygote  : v2
08-22 10:50:15.566  7277  7277 I libpersona: KNOX_SDCARD checking this for 10065
08-22 10:50:15.566  7277  7277 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:15.566  7277  7277 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 10:50:15.566  1015  1378 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7277 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 10:50:15.566  1015  1378 I ActivityManager: Killing 6845:com.wsomacp/u0a23 (adj 15): empty #21
,08-22 10:50:15.566  7277  7277 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:15.566  7237  7237 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 10:50:15.576  7277  7277 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 10:50:15.576  7237  7237 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 10:50:15.576  7237  7237 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 10:50:15.576  7237  7237 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 10:50:15.586  1015  3420 I ActivityManager: Killing 6895:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-22 10:50:15.586  7237  7237 I vclib   : onServiceConnected
,08-22 10:50:15.586  7277  7277 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:15.586  7277  7277 D ActivityThread: Added TimaKeyStore provider,
,08-22 10:50:15.606  1015  1043 D Tethering: interfaceRemoved wlan0
,08-22 10:50:15.606  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-22 10:50:15.616  7277  7277 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 10:50:15.626  1015  1502 I ActivityManager: Killing 6957:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-22 10:50:15.636  1015  1378 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 10:50:15.636  1015  1378 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 10:50:15.636  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:15.636  1015  1378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.636  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 10:50:15.636  1628  1628 I Hs20UtilService: Starting #9
,08-22 10:50:15.636  1628  1657 I Hs20UtilService: Message received 5007
,08-22 10:50:15.636  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 10:50:15.636  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 10:50:15.636  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 10:50:15.636  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 10:50:15.636  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:15.636  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 10:50:15.636  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 10:50:15.646  1015  1467 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 10:50:15.646  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 10:50:15.646  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.646  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.646  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 10:50:15.656  1628  1628 I Hs20UtilService: Starting #10
,08-22 10:50:15.656  1628  1657 I Hs20UtilService: Message received 5011
,08-22 10:50:15.656  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 10:50:15.656  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 10:50:15.656  7081  7081 D SecurityLogAgent: StateMachine : Current State = 1
,08-22 10:50:15.656  7081  7081 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 10:50:15.666  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.666  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.666  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.666  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.666  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.666  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.666  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.666  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.666  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.676  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.676  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.676  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.676  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.676  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.676  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.676  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.676  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.676  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.686  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.686  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.686  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.686  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.686  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.686  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.686  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.686  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.686  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.686  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.686  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.686  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.696  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:15.696  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-22 10:50:15.696  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.696  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.696  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.696  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.696  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:15.696  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.696  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.696  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:15.696  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.696  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.706  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.706  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.706  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 10:50:15.716  4558  4558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 10:50:15.716  1015  1378 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 10:50:15.716  1015  1378 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 10:50:15.716  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:15.716  1015  1378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:15.716  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 10:50:15.726  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:15.736  4558  4558 D DockEventReceiver: finishStartingService: stopping service
,08-22 10:50:15.736  4558  4558 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 10:50:15.736  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:15.736  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-22 10:50:15.756  1015  1485 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-22 10:50:15.756  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:15.756  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.756  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.756  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:15.776  7294  7294 E Zygote  : MountEmulatedStorage()
08-22 10:50:15.776  7294  7294 E Zygote  : v2
08-22 10:50:15.776  7294  7294 I libpersona: KNOX_SDCARD checking this for 1000
08-22 10:50:15.776  7294  7294 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:15.776  7294  7294 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:15.776  7294  7294 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:15.776  1015  1485 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7294 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 10:50:15.776  7294  7294 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:15.806  7294  7294 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:15.806  7294  7294 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:15.826  7294  7294 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-22 10:50:15.836  7294  7294 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-22 10:50:15.836  7294  7294 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-22 10:50:15.836  1015  1043 D Tethering: interfaceRemoved p2p0
,08-22 10:50:15.836  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-22 10:50:15.846  7294  7294 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-22 10:50:15.846  7294  7294 I PCWCLIENTTRACE_PushUtil: sales region : global
08-22 10:50:15.846  7294  7294 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-22 10:50:15.846  7294  7294 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:15.856  1015  1485 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-22 10:50:15.856  1015  1485 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-22 10:50:15.856  1015  1485 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-22 10:50:15.856  1015  1485 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-22 10:50:15.856  1015  1485 I ActivityManager: Killing 1850:com.google.android.gms/u0a11 (adj 15): empty #21
,08-22 10:50:15.856  7294  7309 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-22 10:50:15.856  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-22 10:50:15.866  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.866  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.866  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.866  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:15.876  7311  7311 E Zygote  : MountEmulatedStorage()
,08-22 10:50:15.876  7311  7311 E Zygote  : v2,
08-22 10:50:15.876  7311  7311 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:15.876  7311  7311 I libpersona: KNOX_SDCARD checking this for 10001
08-22 10:50:15.876  7311  7311 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:15.876  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7311 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 10:50:15.886  7311  7311 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:15.886  7311  7311 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-22 10:50:15.896  7311  7311 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:15.896  7311  7311 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:15.946  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-22 10:50:15.956  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.956  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.956  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:15.956  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:15.986  7329  7329 E Zygote  : MountEmulatedStorage(),
08-22 10:50:15.986  7329  7329 E Zygote  : v2
,08-22 10:50:15.986  7329  7329 I libpersona: KNOX_SDCARD checking this for 1000
08-22 10:50:15.986  7329  7329 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:15.986  1015  1027 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7329 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 10:50:15.986  7329  7329 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-22 10:50:15.996  1015  1027 I ActivityManager: Killing 6977:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-22 10:50:15.996  7329  7329 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:15.996  7329  7329 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:16.036  7329  7329 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:16.036  7329  7329 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:16.086  7329  7329 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-22 10:50:16.216  7329  7329 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-22 10:50:16.226  7329  7329 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-22 10:50:16.226  7329  7329 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:16.226  7329  7329 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-22 10:50:16.226  7329  7329 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-22 10:50:16.236  7329  7329 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-22 10:50:16.236  1015  1502 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-22 10:50:16.236  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:16.236  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.236  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.236  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:16.246  1015  1502 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7345 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 10:50:16.256  7345  7345 E Zygote  : MountEmulatedStorage()
08-22 10:50:16.256  7345  7345 E Zygote  : v2
08-22 10:50:16.256  7345  7345 I libpersona: KNOX_SDCARD checking this for 10008
08-22 10:50:16.256  7345  7345 I libpersona: KNOX_SDCARD not a persona,
08-22 10:50:16.256  7345  7345 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:16.256  1015  1502 I ActivityManager: Killing 6579:com.android.mms/u0a41 (adj 15): empty #21,
,08-22 10:50:16.256  7345  7345 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:16.256  7345  7345 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 10:50:16.266  7345  7345 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-22 10:50:16.276  7345  7345 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:16.326  1015  1467 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gms, hostingType: broadcast
,08-22 10:50:16.326  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:16.336  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.336  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.336  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:16.336  1015  1485 D CountryDetector: No listener is left
,08-22 10:50:16.346  1015  1467 I ActivityManager: Start proc com.google.android.gms for broadcast com.google.android.gms/.gcm.gmsproc.GmsAutoStarter: pid=7360 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
08-22 10:50:16.346  7360  7360 E Zygote  : MountEmulatedStorage()
08-22 10:50:16.346  7360  7360 E Zygote  : v2,
08-22 10:50:16.346  1015  1467 I ActivityManager: Killing 6996:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-22 10:50:16.346  7360  7360 I libpersona: KNOX_SDCARD checking this for 10011
08-22 10:50:16.346  7360  7360 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:16.346  7360  7360 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:16.356  7360  7360 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:16.356  7360  7360 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 10:50:16.376   303   303 I art     : Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 638us total 30.569ms
,08-22 10:50:16.386  7360  7360 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:16.386  7360  7360 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:16.406   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.474ms total 22.008ms
,08-22 10:50:16.416  7360  7360 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-22 10:50:16.416  7360  7360 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-22 10:50:16.426   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 688us total 21.351ms
,08-22 10:50:16.456  7360  7360 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-22 10:50:16.456  7360  7360 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>,
,08-22 10:50:16.466  7360  7360 I MultiDex: VM with version 2.1.0 has multidex support
,08-22 10:50:16.466  7360  7360 I MultiDex: install
08-22 10:50:16.466  7360  7360 I MultiDex: VM has multidex support, MultiDex support library is disabled.,
,08-22 10:50:16.566  7360  7360 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-22 10:50:16.626  7360  7360 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-22 10:50:16.626  7360  7360 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1590d8a0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-22 10:50:16.626  7360  7360 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-22 10:50:16.646  1015  1027 I ActivityManager: Killing 6137:com.samsung.android.sm/1000 (adj 15): empty #21
,08-22 10:50:16.646  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-22 10:50:16.646  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-22 10:50:16.646  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-22 10:50:16.646  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:16.646  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:16.646  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 10:50:16.686  7360  7378 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-22 10:50:16.706  7360  7374 W art     : Suspending all threads took: 6.737ms
,08-22 10:50:16.716  7360  7382 I iu.SyncManager: SYNC; picasa accounts
,08-22 10:50:16.736  7360  7360 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-22 10:50:16.756  1015  1467 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 10:50:16.756  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-22 10:50:16.756  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:16.756  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:16.756  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:16.776  7360  7360 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 10:50:16.786  7360  7360 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-22 10:50:16.786  2927  2927 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 22 10:50:16 GMT+02:00 2016
,08-22 10:50:16.786  1015  1502 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-22 10:50:16.796  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-22 10:50:16.796  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:16.796  1015  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:16.796  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-22 10:50:16.796  2927  2927 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-22 10:50:16.806  1015  3418 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-22 10:50:16.806  2927  2927 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-22 10:50:16.806  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.806  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.806  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.806  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:16.806  2927  2927 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 10:50:16.816  7387  7387 E Zygote  : MountEmulatedStorage(),
08-22 10:50:16.816  7387  7387 E Zygote  : v2
08-22 10:50:16.816  7387  7387 I libpersona: KNOX_SDCARD checking this for 10031
08-22 10:50:16.816  7387  7387 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:16.816  7387  7387 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 10:50:16.816  1015  3418 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7387 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-22 10:50:16.826  2927  2927 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 10:50:16.826  2927  7386 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-22 10:50:16.826  7387  7387 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:16.826  2927  7386 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-22 10:50:16.826  7387  7387 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-22 10:50:16.836  2927  7386 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-22 10:50:16.836  2927  7386 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-22 10:50:16.846  2927  2927 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-22 10:50:16.846  7387  7387 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:16.846  7387  7387 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:16.876  7387  7387 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-22 10:50:16.876  1015  1027 I ActivityManager: Killing 7012:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-22 10:50:16.896  1015  1378 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-22 10:50:16.896  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.896  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.896  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.896  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:16.896  3570  7402 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-22 10:50:16.896  3570  7402 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-22 10:50:16.906  3570  7402 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-22 10:50:16.906  3570  7402 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-22 10:50:16.906  1015  1378 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7403 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 10:50:16.906  7403  7403 E Zygote  : MountEmulatedStorage(),
08-22 10:50:16.906  7403  7403 E Zygote  : v2
08-22 10:50:16.906  3570  7402 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-22 10:50:16.906  7403  7403 I libpersona: KNOX_SDCARD checking this for 10032
08-22 10:50:16.906  7403  7403 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:16.906  7403  7403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:16.916  7403  7403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 10:50:16.916  7403  7403 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-22 10:50:16.946  7403  7403 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:16.946  7403  7403 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:16.996  7403  7418 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-22 10:50:16.996  7403  7418 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-22 10:50:16.996  7403  7403 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-22 10:50:16.996  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-22 10:50:16.996  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:16.996  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.996  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:16.996  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:17.016  7420  7420 E Zygote  : MountEmulatedStorage(),
08-22 10:50:17.016  7420  7420 E Zygote  : v2
08-22 10:50:17.016  7420  7420 I libpersona: KNOX_SDCARD checking this for 10036
08-22 10:50:17.016  7420  7420 I libpersona: KNOX_SDCARD not a persona,
08-22 10:50:17.016  7420  7420 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:17.016  7420  7420 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-22 10:50:17.016  1015  1028 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7420 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 10:50:17.016  7420  7420 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-22 10:50:17.016  7403  7418 D SPPClientService: PushLog.txt file is not deleted.
,08-22 10:50:17.016  7403  7418 D SPPClientService: PushLog.txt file is not deleted.
08-22 10:50:17.016  7403  7418 D SPPClientService: ============PushLog. stop!
,08-22 10:50:17.016  1015  1028 I ActivityManager: Killing 7028:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-22 10:50:17.026  1015  3418 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-22 10:50:17.026  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-22 10:50:17.026  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:17.026  1015  3418 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-22 10:50:17.026  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-22 10:50:17.036  7420  7420 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:17.036  7420  7420 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:17.056  7403  7429 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-22 10:50:17.076  7420  7420 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@2d481ac
,08-22 10:50:17.086  7420  7420 I SA      : [SSP] onCreated
,08-22 10:50:17.096  7420  7420 I SA      : [TPM] There is no property file
,08-22 10:50:17.096  7420  7420 I SA      : [SCU] isHaveSA() - false
,08-22 10:50:17.096  7420  7420 I SA      : [TPM] getModelProperty : null
,08-22 10:50:17.096  7420  7420 I SA      : [TPM] getCSCProperty : null
,08-22 10:50:17.106  7420  7420 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-22 10:50:17.106  7420  7420 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-22 10:50:17.106  7420  7420 I SA      : [DM] TFT FEATURE: false
,08-22 10:50:17.106  7420  7420 I SA      : [DM] init START
,08-22 10:50:17.106  7420  7420 I SA      : [DM] This device is not a Vodafone
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-22 10:50:17.116  7420  7420 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-22 10:50:17.116  7420  7420 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75),
08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-22 10:50:17.126  7420  7420 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-22 10:50:17.126  7420  7420 I SA      : [SCU] isHaveSA() - false,
08-22 10:50:17.126  7420  7420 I SA      : support phone number id : false
08-22 10:50:17.126  7420  7420 I SA      : [DM] Supports Ref Jpn : true
08-22 10:50:17.126  7420  7420 I SA      : [DM] init END
08-22 10:50:17.126  7420  7420 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-22 10:50:17.136  7420  7420 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-22 10:50:17.136  7420  7420 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-22 10:50:17.136  7420  7420 I SA      : [SLFUCHKMGR] constructor called
,08-22 10:50:17.136  7420  7420 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-22 10:50:17.136  7420  7420 I SA      : [OR] == isSIMCardReady false ==
,08-22 10:50:17.136  7420  7420 I SA      : [SCU] == networkStateCheck == false
08-22 10:50:17.136  7420  7420 I SA      : [OR] onReceive END
,08-22 10:50:17.136  1015  1485 I ActivityManager: Killing 7112:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-22 10:50:17.146  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:17.156  1792  1792 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-22 10:50:17.166  2690  2702 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-22 10:50:17.166  1792  1792 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1,
08-22 10:50:17.166  1792  1792 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-22 10:50:17.166  1792  1792 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-22 10:50:17.166  1792  1792 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-22 10:50:17.166  1792  1792 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-22 10:50:17.166  1792  1792 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-22 10:50:17.176  1015  1378 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-22 10:50:17.176  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:17.176  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:17.176  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:17.176  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:17.186  1015  1378 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7442 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 10:50:17.186  7442  7442 E Zygote  : MountEmulatedStorage()
,08-22 10:50:17.196  7442  7442 E Zygote  : v2
08-22 10:50:17.196  7442  7442 I libpersona: KNOX_SDCARD checking this for 10077
08-22 10:50:17.196  7442  7442 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:17.196  7442  7442 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:17.196  7442  7442 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 10:50:17.196  7442  7442 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-22 10:50:17.216  7442  7442 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:17.226  7442  7442 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:17.336  1015  1479 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 10:50:17.336  1015  1479 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 10:50:17.336  1015  1479 D SecContentProvider2: mCursor = null
,08-22 10:50:17.336  1015  1479 D WifiService: setWifiEnabled: true pid=6869, uid=10170
08-22 10:50:17.336  1015  1479 W ActivityManager: Permission Denial: getCurrentUser() from pid=6869, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-22 10:50:17.336  1015  1479 W WifiService: Failed getting userId using ActivityManagerNative
08-22 10:50:17.336  1015  1479 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6869, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 10:50:17.336  1015  1479 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 10:50:17.336  1015  1479 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 10:50:17.336  1015  1479 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 10:50:17.336  1015  1479 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 10:50:17.336  1015  1479 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-22 10:50:17.336  1015  1479 D SettingsProvider: name = wifi_on
,08-22 10:50:17.346  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-22 10:50:17.376  1015  1485 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-22 10:50:17.376  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-22 10:50:17.376  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:17.376  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:17.376  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 10:50:17.386  1015  1459 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-22 10:50:17.386  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-22 10:50:17.386  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:17.386  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:17.386  1015  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:17.406  7461  7461 E Zygote  : MountEmulatedStorage()
08-22 10:50:17.406  7461  7461 E Zygote  : v2
08-22 10:50:17.406  7461  7461 I libpersona: KNOX_SDCARD checking this for 10110
08-22 10:50:17.406  7461  7461 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:17.406  1015  1459 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7461 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 10:50:17.406  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:17.406  1015  1438 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-22 10:50:17.406  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-22 10:50:17.406  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:17.406  1015  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:17.406  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 10:50:17.406  7237  7460 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-22 10:50:17.416  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 10:50:17.416  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-22 10:50:17.426  1015  1028 I ActivityManager: Killing 7128:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-22 10:50:17.446  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:17.446  7461  7461 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:17.456   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 10:50:17.496  1015  1485 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 10:50:17.566   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-22 10:50:17.566   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 10:50:17.566  7461  7479 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-22 10:50:17.576   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-22 10:50:17.576   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 10:50:17.576  7461  7479 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-22 10:50:17.576  7461  7461 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-22 10:50:17.576  7461  7461 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 10:50:17.576  7461  7461 I GAv4    :   adb logcat -s GAv4
,08-22 10:50:17.586   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-22 10:50:17.586   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 10:50:17.586  7461  7480 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-22 10:50:17.596   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-22 10:50:17.596   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 10:50:17.596  7461  7480 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-22 10:50:17.606  7461  7461 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 10:50:17.606  1015  1485 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 10:50:17.616  7461  7461 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 10:50:17.616  7461  7488 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 10:50:17.746  1015  1043 D Tethering: interfaceAdded wlan0
,08-22 10:50:17.756  1015  1128 E Tethering: No numeric data
,08-22 10:50:17.756  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-22 10:50:17.756  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:17.756  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:17.756  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 10:50:17.756  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 10:50:17.756  1175  1175 D HotspotTile: updateTetherState():false, false
08-22 10:50:17.756  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 10:50:17.756  1015  1128 D Tethering: clearTetheredNotification()
,08-22 10:50:17.766  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:17.766  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:17.766  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:17.766  1015  1122 V NetworkStats: performPollLocked() took 7ms
08-22 10:50:17.766  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:17.766  1015  1128 D Tethering: InitialState.processMessage what=4
,08-22 10:50:17.766  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:17.766  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:17.766  1015  1128 E Tethering: No numeric data
08-22 10:50:17.766  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 10:50:17.766  1015  1128 D Tethering: clearTetheredNotification()
,08-22 10:50:17.766  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-22 10:50:17.766  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:17.766  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 10:50:17.766  1175  1175 D HotspotTile: updateTetherState():false, false
,08-22 10:50:17.766  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-22 10:50:17.776  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 10:50:17.776  1015  1043 D Tethering: interfaceAdded p2p0
,08-22 10:50:17.776  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-22 10:50:17.776  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:17.776  1015  1122 V NetworkStats: performPollLocked() took 6ms
,08-22 10:50:17.776  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 10:50:17.776  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 10:50:17.776  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:17.776  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:17.776   277   985 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-22 10:50:17.776   277   985 D SoftapController: Softap fwReload - Ok
,08-22 10:50:17.776  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 10:50:17.786   277   985 D CommandListener: Setting iface cfg
08-22 10:50:17.786   277   985 D CommandListener: Trying to bring down wlan0
,08-22 10:50:17.786   277   985 D CommandListener: Clearing all IP addresses on wlan0
,08-22 10:50:17.786  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-22 10:50:17.806  1015  1211 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 10:50:17.816  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:17.816  1015  1211 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 10:50:17.816  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-22 10:50:17.846  7461  7461 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-22 10:50:17.846  7504  7504 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-22 10:50:17.846  7504  7504 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-22 10:50:17.846  7504  7504 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-22 10:50:17.856  7504  7504 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-22 10:50:17.866   363   363 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7504
08-22 10:50:17.866   363   363 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C,
08-22 10:50:17.866  7504  7504 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-22 10:50:17.866  7504  7504 I wpa_supplicant: ssSupport state is = 1
08-22 10:50:17.866  7504  7504 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-22 10:50:17.866  7504  7504 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-22 10:50:17.866   363   363 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7504
08-22 10:50:17.866   363   363 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-22 10:50:17.886  7461  7461 I cr.library_loader: Time to load native libraries: 12 ms (timestamps 4508-4520),
08-22 10:50:17.886  7461  7461 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 10:50:17.886  7461  7461 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {349b0b17}
,08-22 10:50:17.886  7461  7461 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 10:50:17.886  7461  7461 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 10:50:17.886  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-22 10:50:17.906  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-22 10:50:17.906  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:17.906  4558  4558 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-22 10:50:17.906  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 10:50:17.906  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:17.906  1175  1175 D HotspotTile: onReceive : 2, 0
08-22 10:50:17.906  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 10:50:17.906  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:17.906  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:17.906  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:17.906  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:17.906  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:17.906  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-22 10:50:17.906  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:17.906  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:17.916  7461  7461 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-22 10:50:17.916  7461  7461 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-22 10:50:17.916  7461  7461 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-22 10:50:17.936  7461  7461 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 10:50:17.936  7461  7461 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 10:50:17.936  7461  7461 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 10:50:17.936  7461  7461 I Adreno-EGL: Local Branch: 
08-22 10:50:17.936  7461  7461 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 10:50:17.936  7461  7461 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 10:50:17.936  7461  7461 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 10:50:18.036   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-22 10:50:18.036  7504  7504 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-22 10:50:18.056  7461  7519 W cr.media: Requires BLUETOOTH permission
,08-22 10:50:18.066  7461  7461 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 10:50:18.076  7461  7461 I NSApplication: Starting up...
,08-22 10:50:18.076  1015  1467 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 10:50:18.086  1015  1502 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 10:50:18.086  1015  3418 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-22 10:50:18.086  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:18.086  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:18.086  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:18.086  1015  3418 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:18.096  7504  7504 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-22 10:50:18.096  7504  7504 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 10:50:18.106  1015  3418 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7525 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-22 10:50:18.106  7504  7504 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-22 10:50:18.106   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7504
08-22 10:50:18.116  1015  3418 I ActivityManager: Killing 7090:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-22 10:50:18.106   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-22 10:50:18.116  7525  7525 I libpersona: KNOX_SDCARD checking this for 10117
08-22 10:50:18.106  7504  7504 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 10:50:18.116  7525  7525 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:18.106  7504  7504 I wpa_supplicant: ssSupport state is = 1
08-22 10:50:18.116  7525  7525 E Zygote  : MountEmulatedStorage()
08-22 10:50:18.116  7525  7525 E Zygote  : v2
08-22 10:50:18.116  7504  7504 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 10:50:18.116  7525  7525 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:18.116  7504  7504 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 10:50:18.116  7504  7504 E wpa_supplicant: SIM READ ERROR
08-22 10:50:18.116  7504  7504 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 10:50:18.116  7504  7504 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 10:50:18.116  7504  7504 E wpa_supplicant: SIM READ ERROR
08-22 10:50:18.116  7504  7504 I wpa_supplicant: Blacklist: Clear (all) 
08-22 10:50:18.116  7504  7504 I wpa_supplicant: wpa_default_ap_write_once
08-22 10:50:18.116  7504  7504 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 10:50:18.116  7504  7504 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 10:50:18.116  7504  7504 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-22 10:50:18.116  7504  7504 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 10:50:18.116  7504  7504 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 10:50:18.116  7525  7525 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:18.116  7504  7504 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-22 10:50:18.116  7525  7525 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-22 10:50:18.116  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:18.116  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 10:50:18.126  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 10:50:18.136  7525  7525 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:18.136  7525  7525 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:18.156  7525  7525 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 10:50:18.196  7504  7504 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-22 10:50:18.206  1015  1093 V AlarmManager: waitForAlarm result :4
,08-22 10:50:18.356  7504  7504 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-22 10:50:18.356  7504  7504 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 10:50:18.376  7504  7504 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-22 10:50:18.376   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7504
08-22 10:50:18.376   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-22 10:50:18.376  7504  7504 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 10:50:18.376  7504  7504 I wpa_supplicant: ssSupport state is = 1
,08-22 10:50:18.376  7504  7504 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-22 10:50:18.376  7504  7504 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 10:50:18.386  7504  7504 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-22 10:50:18.396   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7504
08-22 10:50:18.396   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-22 10:50:18.396  7504  7504 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 10:50:18.396  7504  7504 I wpa_supplicant: ssSupport state is = 1
08-22 10:50:18.396  7504  7504 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-22 10:50:18.396  7504  7504 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 10:50:18.396  7504  7504 E wpa_supplicant: SIM READ ERROR
08-22 10:50:18.396  7504  7504 I wpa_supplicant: wpa_default_ap_write_once
08-22 10:50:18.396  7504  7504 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-22 10:50:18.396  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 10:50:18.396  7504  7504 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-22 10:50:18.396  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 10:50:18.396  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 10:50:18.396  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-22 10:50:18.396  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 10:50:18.396  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 10:50:18.456   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 10:50:18.456   287   287 E SMD     : DCD OFF,
,08-22 10:50:18.466  1015  1378 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-22 10:50:18.466  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:18.466  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:18.466  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:18.466  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:18.476  7549  7549 E Zygote  : MountEmulatedStorage(),
,08-22 10:50:18.476  1015  1378 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7549 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
08-22 10:50:18.476  1015  1378 I ActivityManager: Killing 7045:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-22 10:50:18.486  7549  7549 E Zygote  : v2
08-22 10:50:18.486  7549  7549 I libpersona: KNOX_SDCARD checking this for 10121
08-22 10:50:18.486  7549  7549 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:18.486  7549  7549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:18.486  7504  7504 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-22 10:50:18.486  7504  7504 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
08-22 10:50:18.486  7549  7549 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:18.486  7549  7549 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:18.506  7549  7549 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:18.506  7549  7549 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:18.516  7549  7549 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 10:50:18.516  7549  7549 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 10:50:18.516  7549  7549 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 10:50:18.526  7549  7549 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:18.526  7549  7549 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-22 10:50:18.536  7549  7549 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-22 10:50:18.536  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
08-22 10:50:18.536  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:18.536  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:18.536  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:18.536  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:18.546  7504  7504 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-22 10:50:18.546  7504  7504 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-22 10:50:18.546  7504  7504 I wpa_supplicant: Skip scan - bUseNetwork false
,08-22 10:50:18.556  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-22 10:50:18.556  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-22 10:50:18.556  7504  7504 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-22 10:50:18.556  7504  7504 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 10:50:18.556  7504  7504 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 10:50:18.556  7504  7504 E wpa_supplicant: SIM READ ERROR
08-22 10:50:18.556  7504  7504 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 10:50:18.566  1015  1027 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7569 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-22 10:50:18.566  7569  7569 E Zygote  : MountEmulatedStorage()
08-22 10:50:18.566  7569  7569 I libpersona: KNOX_SDCARD checking this for 10141
08-22 10:50:18.566  7569  7569 E Zygote  : v2
08-22 10:50:18.566  7569  7569 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:18.566  7569  7569 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:18.566  1015  1027 I ActivityManager: Killing 7060:com.android.calendar/u0a131 (adj 15): empty #21
,08-22 10:50:18.566  7569  7569 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:18.566  7569  7569 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:18.576  7504  7504 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-22 10:50:18.586  7569  7569 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:50:18.586  7569  7569 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:18.596  7504  7504 I wpa_supplicant: Skip scan - bUseNetwork false
,08-22 10:50:18.596  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-22 10:50:18.606  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:18.606  7569  7569 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-22 10:50:18.606  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:18.606  7569  7569 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 10:50:18.606  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:18.606  7569  7569 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 10:50:18.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:18.606  7569  7569 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 10:50:18.606  4558  4558 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:18.606  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:18.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:18.606  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 10:50:18.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:18.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:18.606  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:18.606  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-22 10:50:18.606  1175  1175 D HotspotTile: onReceive : 3, 0
,08-22 10:50:18.616  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:18.616  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:18.616  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:18.616  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:18.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:18.616  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:18.616  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:18.616  1015  1125 E WifiConfigStore: Not a HS20
,08-22 10:50:18.626  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-22 10:50:18.626  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-22 10:50:18.626  7504  7504 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-22 10:50:18.626  7504  7504 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-22 10:50:18.626  7504  7504 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 10:50:18.626  7504  7504 I wpa_supplicant: P2P: Current p2p state = IDLE
08-22 10:50:18.626  7504  7504 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-22 10:50:18.626  7504  7504 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-22 10:50:18.626  7504  7504 I wpa_supplicant: First Scan Start
,08-22 10:50:18.626  7504  7504 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-22 10:50:18.626  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
08-22 10:50:18.626  7237  7237 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 10:50:18.636  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 10:50:18.636  1015  1125 I WifiNative-HAL: startHal
08-22 10:50:18.636  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9e6f488c
08-22 10:50:18.636  1015  1125 I WifiNative-HAL: Could not start hal
,08-22 10:50:18.636  1015  1125 E WifiNative-wlan0: do suspend true
,08-22 10:50:18.636  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-22 10:50:18.636  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-22 10:50:18.636  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-22 10:50:18.636   277   985 D CommandListener: Setting iface cfg
08-22 10:50:18.636   277   985 D CommandListener: Trying to bring up p2p0
,08-22 10:50:18.636  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-22 10:50:18.636  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 10:50:18.636  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 10:50:18.636  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-22 10:50:18.636  1015  1148 I WifiNative-HAL: startHal
08-22 10:50:18.636  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x98fd19bc
08-22 10:50:18.636  1015  1148 I WifiNative-HAL: Could not start hal
08-22 10:50:18.636  1015  1148 E WifiScanningService: could not start HAL
08-22 10:50:18.636  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-22 10:50:18.646  1015  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 10:50:18.646  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 10:50:18.646  7504  7504 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-22 10:50:18.646  1015  1124 D WifiP2pService: P2pEnablingState
08-22 10:50:18.646  7504  7504 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-22 10:50:18.646  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-22 10:50:18.646  7504  7504 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-22 10:50:18.646  1015  1124 D WifiP2pService: P2p socket connection successful
08-22 10:50:18.646  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:18.646  1015  1124 D WifiP2pService: P2pEnabledState
,08-22 10:50:18.646  1015  1125 E WifiStateMachine: Failed to set frequency band 0
08-22 10:50:18.646  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-22 10:50:18.646  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 10:50:18.646  1015  1125 D SecContentProvider2: mCursor = null
08-22 10:50:18.646  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-22 10:50:18.646  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-22 10:50:18.646  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 10:50:18.646  1015  1046 D WifiDisplayController: disconnect
08-22 10:50:18.646  1015  1046 D WifiDisplayController: updateConnection
08-22 10:50:18.646  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 10:50:18.646  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 10:50:18.646  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-22 10:50:18.646  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 10:50:18.646  1015  1438 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 10:50:18.646  1015  1125 D SecContentProvider2: mCursor = null,
08-22 10:50:18.646  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 10:50:18.656  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-22 10:50:18.656  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 10:50:18.656  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
08-22 10:50:18.656  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-22 10:50:18.656  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 10:50:18.656  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-22 10:50:18.656  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  secondary type: null
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  wps: 0
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  grpcapab: 0
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  devcapab: 0
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  status: 3
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  wfdInfo: null
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-22 10:50:18.656  1015  1046 D WifiDisplayController:  SConnectInfo : null
,08-22 10:50:18.656  1015  1124 D WifiP2pService: DeviceAddress: 0a:75:42
,08-22 10:50:18.666  1015  1467 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 10:50:18.676  1015  1459 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 10:50:18.686  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-22 10:50:18.686  1015  1124 D WifiP2pService: InactiveState
08-22 10:50:18.686  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-22 10:50:18.686  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 },
,08-22 10:50:18.686  7504  7504 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 10:50:18.686  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-22 10:50:18.686  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 10:50:18.706  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 10:50:18.716  1015  3418 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 10:50:18.756  1015  3420 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-22 10:50:18.756  1015  3420 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:18.756  1015  3420 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:18.756  1015  3420 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:18.756  1015  3420 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:18.766  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 10:50:18.766  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 10:50:18.766  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 10:50:18.766  1015  1485 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 10:50:18.766  7593  7593 E Zygote  : MountEmulatedStorage()
08-22 10:50:18.766  7593  7593 I libpersona: KNOX_SDCARD checking this for 10068
08-22 10:50:18.766  7593  7593 E Zygote  : v2
08-22 10:50:18.766  7593  7593 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:18.766  7593  7593 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:18.776  1015  3420 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7593 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-22 10:50:18.776  7593  7593 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:18.776  1015  1502 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 10:50:18.776  7593  7593 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 10:50:18.796  7593  7593 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:18.796  7593  7593 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:18.806  1015  1378 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 10:50:18.806  1015  1255 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-22 10:50:18.806  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:18.806  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:18.806  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:18.806  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:18.816  7593  7593 D BadgeProvider: onCreate
,08-22 10:50:18.816  7593  7593 D BadgeProvider: DatabaseHelper,
,08-22 10:50:18.826  7609  7609 E Zygote  : MountEmulatedStorage()
08-22 10:50:18.826  1015  1255 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7609 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-22 10:50:18.826  7609  7609 E Zygote  : v2
08-22 10:50:18.826  7609  7609 I libpersona: KNOX_SDCARD checking this for 10009
08-22 10:50:18.826  7609  7609 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:18.826  7609  7609 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:18.826  1015  1255 I ActivityManager: Killing 6412:com.android.vending/u0a26 (adj 15): empty #21
,08-22 10:50:18.826  1015  1255 I ActivityManager: Killing 6823:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-22 10:50:18.836  7609  7609 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:18.836  7609  7609 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-22 10:50:18.856  7609  7609 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:18.866  7609  7609 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:18.916  1015  1459 I ActivityManager: Killing 7262:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-22 10:50:18.926  1015  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 10:50:18.926  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 10:50:18.936  1015  1485 W ActivityManager: userId = 0, bbcId = -10000,
08-22 10:50:18.936  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:18.936  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 10:50:18.936  1628  1628 I Hs20UtilService: Starting #11
08-22 10:50:18.936  1628  1657 I Hs20UtilService: Message received 5011
,08-22 10:50:18.936  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 10:50:18.936  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 10:50:18.936  7081  7081 D SecurityLogAgent: StateMachine : Current State = 1
08-22 10:50:18.936  7081  7081 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 10:50:18.946  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:18.946  1015  3418 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:18.946  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:18.956  1015  1502 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-22 10:50:18.956  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-22 10:50:18.956  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:18.956  1015  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:18.956  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 10:50:18.956  1015  1028 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-22 10:50:18.956  1015  1028 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-22 10:50:18.956  1015  1028 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-22 10:50:18.956  1015  1028 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-22 10:50:18.956  1683  2542 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-22 10:50:18.956  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:18.956  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:18.956  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:18.986  1015  3420 I art     : Explicit concurrent mark sweep GC freed 75470(4MB) AllocSpace objects, 9(192KB) LOS objects, 33% free, 22MB/34MB, paused 2.776ms total 155.514ms
,08-22 10:50:18.996  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:18.996  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:18.996  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:18.996  7593  7602 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-22 10:50:18.996  1683  1683 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-22 10:50:19.006  1015  1485 W ActivityManager: userId = 0, bbcId = -10000,
,08-22 10:50:19.006  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.006  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.016  1015  1378 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-22 10:50:19.016  1015  1378 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-22 10:50:19.016  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.016  1015  1378 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.016  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.016  7593  7602 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-22 10:50:19.016  7593  7602 D BadgeProvider: sendNotify, [notify] : null
08-22 10:50:19.016  7593  7602 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-22 10:50:19.016  7593  7602 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-22 10:50:19.016  7593  7602 D BadgeProvider: update, [UpdateCount] : 1
,08-22 10:50:19.016  1486  1486 D Launcher.Model: reloadBadges entered.
,08-22 10:50:19.026  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-22 10:50:19.026  1015  1211 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-22 10:50:19.026  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.026  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.026  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.026  1683  1683 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:19.026  1683  1683 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:19.036  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.036  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.036  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.036  7360  7360 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
08-22 10:50:19.036  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-22 10:50:19.036  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-22 10:50:19.046  1015  1502 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 10:50:19.046  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-22 10:50:19.046  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.046  1015  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 10:50:19.046  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.056  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.056  1015  1459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.056  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.056  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.056  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.056  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.066  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.066  1015  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.066  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.076  1015  1255 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 10:50:19.076  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.076  1015  1255 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.076  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.076  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:19.076  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:19.076  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:19.076  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:19.086  7628  7628 E Zygote  : MountEmulatedStorage()
,08-22 10:50:19.086  7628  7628 E Zygote  : v2
08-22 10:50:19.086  7628  7628 I libpersona: KNOX_SDCARD checking this for 10011
08-22 10:50:19.086  7628  7628 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:19.086  7628  7628 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:19.086  1015  1255 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7628 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-22 10:50:19.086  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.086  1015  3418 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.086  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.096  7628  7628 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:19.096  7628  7628 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-22 10:50:19.096  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.096  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.096  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.116   303   303 I art     : Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 24.935ms
,08-22 10:50:19.126  7628  7628 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-22 10:50:19.126  7628  7628 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:19.126   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 17.131ms
,08-22 10:50:19.136  7628  7628 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-22 10:50:19.136  7628  7628 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-22 10:50:19.146   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 685us total 17.285ms
,08-22 10:50:19.166  1462  1680 D TP/SmsProvider: query,matched:0, calling pid = 7360
,08-22 10:50:19.166  1462  1680 D TP/SmsProvider: match 0:Elapsed time : 2.628 ms,
,08-22 10:50:19.176  7628  7628 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-22 10:50:19.176  7628  7628 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-22 10:50:19.176  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.176  1015  1459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.176  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.176  7628  7628 I MultiDex: VM with version 2.1.0 has multidex support
08-22 10:50:19.176  7628  7628 I MultiDex: install
08-22 10:50:19.176  7628  7628 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-22 10:50:19.186  1462  1473 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7360
,08-22 10:50:19.186  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.186  1015  1459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.186  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.196  1015  1438 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 10:50:19.196  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.196  1015  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.196  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.196  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.196  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.196  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.206  1015  3418 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 10:50:19.206  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 10:50:19.206  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.206  1015  3418 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:19.206  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 10:50:19.206  7628  7628 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-22 10:50:19.216  1628  1628 I Hs20UtilService: Starting #12
,08-22 10:50:19.216  1628  1657 I Hs20UtilService: Message received 5011
,08-22 10:50:19.216  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 10:50:19.216  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 10:50:19.216  7081  7081 D SecurityLogAgent: StateMachine : Current State = 1
08-22 10:50:19.216  7081  7081 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 10:50:19.216  1015  1459 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 10:50:19.216  1015  1459 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-22 10:50:19.216  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.216  1015  1459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 10:50:19.216  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.226  1462  1680 D TP/SmsProvider: query,matched:0, calling pid = 7360
08-22 10:50:19.226  7360  7647 D LocationInitializer: Restart initialization of location
,08-22 10:50:19.226  1462  1680 D TP/SmsProvider: match 0:Elapsed time : 1.986 ms
,08-22 10:50:19.236  1015  3420 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 10:50:19.236  1015  3420 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-22 10:50:19.236  1015  3420 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.236  1015  3420 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.236  1015  3420 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.246  1015  1502 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 10:50:19.246  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 10:50:19.246   277   981 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 10:50:19.246   277   981 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-22 10:50:19.246  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.246  1015  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:19.246  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 10:50:19.246  1015  1467 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 10:50:19.246  1628  1628 I Hs20UtilService: Starting #13
08-22 10:50:19.246  1462  1473 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7360
,08-22 10:50:19.246  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.246  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.256  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.256  1628  1657 I Hs20UtilService: Message received 5011
,08-22 10:50:19.256  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 10:50:19.256  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 10:50:19.256  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-22 10:50:19.266  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 10:50:19.266  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 10:50:19.266  7081  7081 D SecurityLogAgent: StateMachine : Current State = 1
08-22 10:50:19.266  7081  7081 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 10:50:19.276  7628  7628 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb3a40: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-22 10:50:19.276  7628  7628 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-22 10:50:19.276  7628  7628 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-22 10:50:19.276  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-22 10:50:19.276  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 10:50:19.286  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 10:50:19.286  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 10:50:19.286  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:19.286  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 10:50:19.286  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 10:50:19.286  1015  1438 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-22 10:50:19.286  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:19.286  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:19.286  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:19.286  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:19.306  7651  7651 E Zygote  : MountEmulatedStorage()
08-22 10:50:19.306  7651  7651 E Zygote  : v2
08-22 10:50:19.306  7651  7651 I libpersona: KNOX_SDCARD checking this for 10064
08-22 10:50:19.306  7651  7651 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:19.306  7651  7651 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:19.306  7651  7651 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:19.306  7651  7651 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 10:50:19.306  1015  1438 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7651 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 10:50:19.326  7628  7628 D WearableService: callingUid 10011, callindPid: 7628
,08-22 10:50:19.336  7651  7651 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:19.346  7651  7651 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:19.346  7628  7658 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-22 10:50:19.356  7360  7374 I art     : Background partial concurrent mark sweep GC freed 3874(398KB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 7MB/11MB, paused 5.544ms total 38.187ms
,08-22 10:50:19.376  1742  4813 E MDM     : [189] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-22 10:50:19.386  7651  7651 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-22 10:50:19.406  1015  3420 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-22 10:50:19.406  1015  3420 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4227, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 10:50:19.406  1015  3420 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 10:50:19.406  7651  7651 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-22 10:50:19.406  1015  3420 D BatteryService: stay LED for charging,
08-22 10:50:19.406  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-22 10:50:19.406  1015  1015 I MotionRecognitionService: Plugged
08-22 10:50:19.406  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false,
,08-22 10:50:19.406  7651  7651 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-22 10:50:19.426  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 10:50:19.426  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 10:50:19.426  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 10:50:19.436  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-22 10:50:19.446  7651  7651 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 10:50:19.446  7277  7277 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 10:50:19.456  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.456  1015  1211 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.456  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-22 10:50:19.456   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 10:50:19.456  1683  7649 I art     : Explicit concurrent mark sweep GC freed 18976(936KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/14MB, paused 1.079ms total 59.788ms
,08-22 10:50:19.456  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 10:50:19.456  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-22 10:50:19.456  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 10:50:19.456  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.456  1015  1378 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.456  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.466  1015  3420 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-22 10:50:19.466  1015  3420 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-22 10:50:19.466  1015  3420 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.466  1015  3420 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.466  1015  3420 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.476  1683  2729 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-22 10:50:19.476  1015  1378 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-22 10:50:19.476  1015  1378 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-22 10:50:19.476  1015  1378 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-22 10:50:19.476  1015  1378 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-22 10:50:19.476  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.476  1015  1378 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.476  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.476  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.476  1015  3418 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.476  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.476  1683  1683 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-22 10:50:19.486  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.486  1015  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.486  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.486  1015  1485 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-22 10:50:19.486  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-22 10:50:19.486  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.486  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 10:50:19.486  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.496  1683  1683 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:19.496  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.496  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 10:50:19.496  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.496  1683  1683 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:19.506  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.506  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.506  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.506  7360  7360 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-22 10:50:19.506  1015  1459 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 10:50:19.506  1015  1459 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-22 10:50:19.506  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.506  1015  1459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.506  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.516  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.516  1015  1255 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.516  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.516  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.516  1015  1255 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 10:50:19.516  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.526  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.526  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.526  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.526  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.526  1015  3418 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 10:50:19.526  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.536  1742  5394 E MDM     : [191] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-22 10:50:19.536  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.536  1015  3418 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.536  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.546  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.546  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 10:50:19.546  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.546  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.546  1015  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.546  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.556  1015  1378 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 10:50:19.556  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.556  1015  1378 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.556  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.556  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.556  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.556  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.566  1015  1459 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 10:50:19.566  1015  1459 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-22 10:50:19.566  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.566  1015  1459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.566  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.566  7360  7671 D LocationInitializer: Restart initialization of location
,08-22 10:50:19.566  1015  3418 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 10:50:19.566  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-22 10:50:19.566  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:19.566  1015  3418 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:19.566  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:19.746  7504  7504 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
08-22 10:50:19.746  7504  7504 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-22 10:50:19.746  7504  7504 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-22 10:50:19.746  7504  7504 I wpa_supplicant: Trying to associate with  'G700'
08-22 10:50:19.746  7504  7504 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-22 10:50:19.746  7504  7504 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-22 10:50:19.756  1015  7568 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-22 10:50:19.766  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 10:50:19.766  1015  1125 D SecContentProvider2: mCursor = null
,08-22 10:50:19.856  7504  7504 E wpa_supplicant: Cmd 35605 not handled
,08-22 10:50:19.856  7504  7504 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 10:50:19.856  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:19.856  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 10:50:19.856  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:19.856  7504  7504 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-22 10:50:19.856  7504  7504 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-22 10:50:19.866  7504  7504 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-22 10:50:19.866  7504  7504 I wpa_supplicant: Associated with F4.99.3E
08-22 10:50:19.866  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:19.866  7504  7504 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 10:50:19.866  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:19.866  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:19.866  7504  7504 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-22 10:50:19.866  7504  7504 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030,
08-22 10:50:19.866  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:19.866  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:19.866  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:19.866  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 10:50:19.866  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-22 10:50:19.866  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-22 10:50:19.876  1015  1128 E Tethering: No numeric data
08-22 10:50:19.876  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-22 10:50:19.876  1015  1125 D SecContentProvider2: mCursor = null,
08-22 10:50:19.876  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-22 10:50:19.876  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 10:50:19.876  1015  1128 D Tethering: clearTetheredNotification()
08-22 10:50:19.876  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 10:50:19.876  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:19.876  1175  1175 D HotspotTile: updateTetherState():false, false
08-22 10:50:19.876  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:19.876  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 10:50:19.876  7504  7504 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 10:50:19.876  7504  7504 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-22 10:50:19.876  7504  7504 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-22 10:50:19.886  7504  7504 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-22 10:50:19.886  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 10:50:19.886  1015  1125 D SecContentProvider2: mCursor = null
,08-22 10:50:19.886  7504  7504 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 10:50:19.886  1015  1122 V NetworkStats: performPollLocked() took 11ms
08-22 10:50:19.886  7504  7504 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-22 10:50:19.886  7504  7504 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-22 10:50:19.886  7504  7504 I wpa_supplicant: Blacklist: Clear (temp) 
,08-22 10:50:19.886  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 10:50:19.886  7504  7504 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-22 10:50:19.886  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:19.886  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 10:50:19.886  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-22 10:50:19.886  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:19.886  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:19.896  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50],
,08-22 10:50:19.896  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-22 10:50:19.906  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-22 10:50:19.906  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-22 10:50:19.906  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:19.906  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-22 10:50:19.906  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:19.906  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 10:50:19.906  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:19.906  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 10:50:19.906  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:19.906  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 10:50:19.906  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:19.906  1628  1628 I Hs20UtilService: Starting #14
08-22 10:50:19.906  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:19.906  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:19.906  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:19.906  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:19.906  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:19.906  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:19.906  1628  1657 I Hs20UtilService: Message received 5007
,08-22 10:50:19.916  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 10:50:19.916  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 10:50:19.916  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
08-22 10:50:19.916  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 10:50:19.916  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:19.916  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 10:50:19.916  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 10:50:19.916  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:19.936   277   985 D CommandListener: Setting iface cfg,
,08-22 10:50:19.936  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,08-22 10:50:19.936  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 10:50:19.936  1015  1125 D SecContentProvider2: mCursor = null
,08-22 10:50:19.946  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 10:50:19.946  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 10:50:19.946  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 10:50:19.956  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:19.956  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:19.956  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:19.956  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 10:50:19.956  1015  1125 D SecContentProvider2: mCursor = null
,08-22 10:50:19.956  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:19.956  1015  1125 E WifiNative-wlan0: do suspend false
,08-22 10:50:19.956  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-22 10:50:19.956  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 10:50:20.176  7676  7676 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-22 10:50:20.176  7676  7676 I dhcpcd  : version 5.5.6 starting,
,08-22 10:50:20.186  7676  7676 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-22 10:50:20.246  7676  7676 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-22 10:50:20.246  7676  7676 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-22 10:50:20.246  7676  7676 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,08-22 10:50:20.246  7676  7676 I dhcpcd  : bssid match
,08-22 10:50:20.246  7676  7676 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-22 10:50:20.306  7676  7676 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-22 10:50:20.356  1015  1485 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-22 10:50:20.356  1015  1485 D WifiService: setWifiEnabled: false pid=6869, uid=10170,
,08-22 10:50:20.356  1015  1485 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
08-22 10:50:20.356  1015  1485 D SecContentProvider2: mCursor = null
08-22 10:50:20.356  1015  1485 D SettingsProvider: name = wifi_on,
,08-22 10:50:20.366  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:20.366  7676  7676 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-22 10:50:20.376  1015  1125 E WifiNative-wlan0: do suspend true,
,08-22 10:50:20.396  1015  1124 D WifiP2pService: InactiveState{ what=143375 },
08-22 10:50:20.396  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 10:50:20.406   277   985 D CommandListener: Clearing all IP addresses on wlan0,
,08-22 10:50:20.406  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:20.406  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 10:50:20.406  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:20.406  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.406  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.406  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.406  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.416  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:20.416  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 10:50:20.416  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:20.416  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-22 10:50:20.416   277   985 E Netd    : no such netId 503
,08-22 10:50:20.416  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 10:50:20.416  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:20.416  1015  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-22 10:50:20.416  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:20.416  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-22 10:50:20.416  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 10:50:20.416  1015  1127 V NetworkStats: updateIfacesLocked()
,08-22 10:50:20.416  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-22 10:50:20.426  1015  1127 V NetworkStats: performPollLocked() took 8ms
,08-22 10:50:20.426  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:20.426  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:20.426  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:20.426  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:20.426  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.426  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.426  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.426  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:20.436  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
,08-22 10:50:20.436  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-22 10:50:20.436  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-22 10:50:20.436  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-22 10:50:20.436  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 10:50:20.436  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-22 10:50:20.436  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-22 10:50:20.436  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-22 10:50:20.436  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 10:50:20.436  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 10:50:20.436  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:20.436  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:20.436  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 10:50:20.436  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-22 10:50:20.436  1015  7674 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-22 10:50:20.436  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-22 10:50:20.436  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-22 10:50:20.436  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-22 10:50:20.436  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:20.436  1628  1628 I Hs20UtilService: Starting #15
08-22 10:50:20.436  1628  1657 I Hs20UtilService: Message received 5007
,08-22 10:50:20.446  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:20.446  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:20.446  1015  7674 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-22 10:50:20.446  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 10:50:20.446  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 10:50:20.446  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 10:50:20.446  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-22 10:50:20.446  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-22 10:50:20.446  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-22 10:50:20.446  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-22 10:50:20.446  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-22 10:50:20.446  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 10:50:20.446  1015  1046 D WifiDisplayController: disconnect
08-22 10:50:20.446  1015  1046 D WifiDisplayController: updateConnection
08-22 10:50:20.446  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 10:50:20.446  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 10:50:20.446  1015  1124 D WifiP2pService: P2pDisablingState
08-22 10:50:20.446  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-22 10:50:20.446  1015  1124 D WifiP2pService: p2p socket connection lost
08-22 10:50:20.446  1015  1124 D WifiP2pService: P2pDisabledState
08-22 10:50:20.446  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 10:50:20.446  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 10:50:20.446  1015  1125 E WifiNative-wlan0: do suspend true
08-22 10:50:20.446  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 10:50:20.446  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-22 10:50:20.446  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-22 10:50:20.446  1015  3418 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 10:50:20.456  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 10:50:20.456   314   314 I ServiceManager: Waiting for service AtCmdFwd...
08-22 10:50:20.456  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 10:50:20.456  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 10:50:20.456  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 10:50:20.456  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 10:50:20.456  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:20.456  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 10:50:20.456  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 10:50:20.466  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-22 10:50:20.466  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 10:50:20.466  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 10:50:20.466  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 10:50:20.466  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:20.466  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 10:50:20.466  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 10:50:20.466  7651  7651 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-22 10:50:20.476  7651  7651 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-22 10:50:20.476  7651  7651 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 10:50:20.476  7277  7277 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 10:50:20.486   277   985 D CommandListener: Clearing all IP addresses on wlan0
08-22 10:50:20.486  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
08-22 10:50:20.486  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-22 10:50:20.486  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 10:50:20.486  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:20.486  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:20.486  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.486  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.486  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.486  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:20.496  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 10:50:20.496  7504  7504 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-22 10:50:20.506  1015  1502 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 10:50:20.506  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 10:50:20.506  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:20.506  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:20.506  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:20.506  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:20.506  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.506  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.506  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.506  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:20.506  1015  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:20.506  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 10:50:20.506  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 10:50:20.506  1015  1125 D SecContentProvider2: mCursor = null
,08-22 10:50:20.506  1628  1628 I Hs20UtilService: Starting #16
,08-22 10:50:20.506  1628  1657 I Hs20UtilService: Message received 5007
,08-22 10:50:20.516  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-22 10:50:20.516  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:20.516  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:20.516  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 10:50:20.516  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 10:50:20.516  1175  1175 D HotspotTile: onReceive : 0, 0
08-22 10:50:20.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:20.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:20.516  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:20.516  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-22 10:50:20.516  4558  4558 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 10:50:20.526  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 10:50:20.526  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 10:50:20.526  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 10:50:20.526  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 10:50:20.526  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:20.526  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 10:50:20.526  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:20.526  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 10:50:20.526  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:20.526  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:20.526  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:20.526  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:20.526  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:20.526  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:20.526  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:20.526  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:20.536  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:20.536  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:20.536  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:20.536  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:20.536  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:20.536  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:20.536  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:20.536  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:20.536  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:20.536  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:20.536  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:20.536  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:20.536  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:20.536  1015  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 10:50:20.536  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-22 10:50:20.546  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:20.546  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:20.546  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 10:50:20.546  1628  1628 I Hs20UtilService: Starting #17
08-22 10:50:20.546  1628  1657 I Hs20UtilService: Message received 5011
08-22 10:50:20.546  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 10:50:20.546  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 10:50:20.546  7081  7081 D SecurityLogAgent: StateMachine : Current State = 1
08-22 10:50:20.546  7081  7081 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 10:50:20.646  7504  7504 I wpa_supplicant: Blacklist: Clear (all) ,
,08-22 10:50:20.786  7504  7504 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-22 10:50:20.786  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 10:50:20.786  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 10:50:20.786  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 10:50:20.806  7504  7504 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-22 10:50:20.806  7504  7504 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED,
,08-22 10:50:20.806  7504  7504 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-22 10:50:20.806  7504  7504 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-22 10:50:20.806  7504  7504 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-22 10:50:20.816  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 10:50:20.816  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:20.816  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:20.816  1015  1128 D Tethering: InitialState.processMessage what=4
,08-22 10:50:20.816  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 10:50:20.816  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:20.816  1015  1128 E Tethering: No numeric data
08-22 10:50:20.816  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 10:50:20.816  1015  1128 D Tethering: clearTetheredNotification()
08-22 10:50:20.816  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 10:50:20.816  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:20.816  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:20.826  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 10:50:20.826  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:20.826  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 10:50:20.826  1175  1175 D HotspotTile: updateTetherState():false, false
,08-22 10:50:20.826  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-22 10:50:20.826  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-22 10:50:20.826  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 10:50:20.826  1015  1122 V NetworkStats: performPollLocked() took 5ms
08-22 10:50:20.826  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:20.836  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:20.836  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:20.856  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-22 10:50:20.856  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:20.856  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 10:50:21.016  7504  7504 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 10:50:21.056  7504  7504 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-22 10:50:21.056  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:21.056  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:21.066  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 10:50:21.066  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-22 10:50:21.066  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-22 10:50:21.076  7237  7237 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 10:50:21.076  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 10:50:21.086  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:21.086  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 10:50:21.086  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:21.086  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:21.086  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:21.086  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:21.086  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:21.086  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:21.086  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-22 10:50:21.086  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 10:50:21.086  1175  1175 D HotspotTile: onReceive : 1, 0
,08-22 10:50:21.086  4558  4558 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:21.086  1742  2198 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 10:50:21.086  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:21.086  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:21.096  1015  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 10:50:21.096  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 10:50:21.096  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:21.096  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:21.096  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 10:50:21.106  1628  1628 I Hs20UtilService: Starting #18
08-22 10:50:21.106  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 10:50:21.106  1628  1657 I Hs20UtilService: Message received 5011
08-22 10:50:21.106  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 10:50:21.106  7081  7081 D SecurityLogAgent: StateMachine : Current State = 1
08-22 10:50:21.106  7081  7081 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 10:50:21.456   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 10:50:21.456   287   287 E SMD     : DCD OFF,
,08-22 10:50:21.636  1015  1048 I PowerManagerService: [PWL] Off : 50s ago
,08-22 10:50:21.636  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-22 10:50:21.636  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-22 10:50:21.636  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=7049)
,08-22 10:50:21.706  1015  2872 D SSRM:n  : SIOP:: AP = 360
,08-22 10:50:21.826  1015  1043 D Tethering: interfaceRemoved wlan0
,08-22 10:50:21.826  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-22 10:50:22.006  1015  1043 D Tethering: interfaceRemoved p2p0
,08-22 10:50:22.006  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-22 10:50:22.456   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-22 10:50:22.616  1015  1093 V AlarmManager: waitForAlarm result :4,
,08-22 10:50:22.616   277   981 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-22 10:50:22.616   277   981 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-22 10:50:22.636  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:22.636  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 10:50:22.636  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-22 10:50:22.816  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-22 10:50:23.366  6869  6947 D BluetoothAdapter: enable()
,08-22 10:50:23.366  1015  1467 W ActivityManager: Permission Denial: getCurrentUser() from pid=6869, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-22 10:50:23.376  1015  1467 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-22 10:50:23.376  1015  1467 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6869, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 10:50:23.376  1015  1467 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 10:50:23.376  1015  1467 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-22 10:50:23.376  1015  1467 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-22 10:50:23.376  1015  1467 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-22 10:50:23.376  1015  1467 W BluetoothManagerService: ,	at android.os.Binder.execTransact(Binder.java:446)
08-22 10:50:23.376  1015  1467 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 10:50:23.376  1015  1467 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 10:50:23.376  1015  1467 D SettingsProvider: name = bluetooth_on
,08-22 10:50:23.386  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-22 10:50:23.386  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 10:50:23.386  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-22 10:50:23.386  2793  2853 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-22 10:50:23.386  2793  2853 D BluetoothAdapterProperties: Setting state to 11
08-22 10:50:23.386  2793  2853 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-22 10:50:23.386  2793  2853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-22 10:50:23.386  2793  2853 D BluetoothAdapterService: updateAdapterState state is 11
,08-22 10:50:23.396  2793  2853 D BluetoothAdapterService: Autoconnection is available 
08-22 10:50:23.396  2793  2853 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-22 10:50:23.396  2793  2853 D BtConfig.SecureMode: isSecureModeOn:false
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
,08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 10:50:23.396  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 10:50:23.396  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
08-22 10:50:23.406  1015  1438 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:23.406  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.406  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.406  1015  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.406  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.406  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-22 10:50:23.406  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 10:50:23.406  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-22 10:50:23.406  1015  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:23.406  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 10:50:23.406  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.406  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.406  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.416  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-22 10:50:23.416  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 10:50:23.416  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 10:50:23.416  2793  2793 D HeadsetService: Received start request. Starting profile...
08-22 10:50:23.416  2793  2793 D HeadsetService: start()
08-22 10:50:23.416  2793  2793 D HeadsetStateMachine: make
08-22 10:50:23.416  1015  1255 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:23.416  1015  1255 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-22 10:50:23.416  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.416  1015  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.416  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.416  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-22 10:50:23.416  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 10:50:23.416  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 10:50:23.416  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:23.416  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-22 10:50:23.416  2793  2793 E HeadsetStateMachine: # of Max HF connection is 2
,08-22 10:50:23.426  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.426  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.426  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.426  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService,
08-22 10:50:23.426  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 10:50:23.436  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:23.426  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-22 10:50:23.436  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-22 10:50:23.446  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 10:50:23.446  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:23.446  1175  1175 D BluetoothTile:  getBluetoothState : 11
,08-22 10:50:23.446  1860  1860 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 10:50:23.446  4558  4558 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:23.456  1015  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:23.456  1015  1459 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-22 10:50:23.456  1015  1459 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.456  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.456  1015  1459 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.456  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-22 10:50:23.456  1015  1502 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:23.456  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.456  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 10:50:23.456  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:23.456  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 10:50:23.456  1015  1378 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-22 10:50:23.456  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.456  1015  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.456  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.456  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:23.456  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:23.456  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:23.456  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:23.466  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-22 10:50:23.466  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:23.466  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:23.466  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-22 10:50:23.466  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.466  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.466  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 10:50:23.466  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-22 10:50:23.466  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 10:50:23.466  2793  2853 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-22 10:50:23.476  1015  3418 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:23.476  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-22 10:50:23.476  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.476  1015  3418 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.476  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 10:50:23.476  1015  1459 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-22 10:50:23.476  1015  1459 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.476  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.476  1015  1459 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.476  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-22 10:50:23.476  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-22 10:50:23.476  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:23.476  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:23.476  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:23.476  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:23.476  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:23.476  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:23.476  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 10:50:23.476  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 10:50:23.476  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 10:50:23.476  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-22 10:50:23.476  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 10:50:23.476  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 10:50:23.476  2793  2853 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-22 10:50:23.476  2793  2793 I bluedroid: get_profile_interface handsfree
,08-22 10:50:23.486  4558  4558 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 10:50:23.496  2793  2793 E DualScoManager: Dual Sco Manager already instantiated
,08-22 10:50:23.496  2793  2793 I DualScoManager: Set HeadsetServiceHelper
08-22 10:50:23.496  2793  2793 D BluetoothAtMessage: createCMTIContentObservers
08-22 10:50:23.496  1015  1438 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-22 10:50:23.496  1015  1438 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 10:50:23.496  1015  1438 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 10:50:23.496  1015  1438 D SettingsProvider: selectionArgs: false
08-22 10:50:23.496  1015  1438 D SettingsProvider: selectionArgs: 1002
08-22 10:50:23.496  1015  1438 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 10:50:23.496  1015  1438 D SettingsProvider: ret = -1
,08-22 10:50:23.496  2793  7709 D HeadsetStateMachine: Enter Disconnected: -2
08-22 10:50:23.496  2793  2793 D HeadsetService: mStartError = false
08-22 10:50:23.496  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:23.496  2793  2793 D A2dpService: Received start request. Starting profile...
,08-22 10:50:23.496  2793  2793 D A2dpService: start()
08-22 10:50:23.496  2793  2793 I bluedroid: get_profile_interface avrcp
,08-22 10:50:23.496  2793  7709 D HeadsetStateMachine: Clear mHeadsetBrsf
08-22 10:50:23.496  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:23.496  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-22 10:50:23.496  2793  7709 D HeadsetStateMachine: map size, before remove : 0
08-22 10:50:23.496  2793  7709 D HeadsetStateMachine: map size, after remove: 0
,08-22 10:50:23.506  2793  2793 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-22 10:50:23.506  2793  2793 D Avrcp   : Initialize Media Controller
08-22 10:50:23.506  2793  2793 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-22 10:50:23.506  2793  2793 E Avrcp   : getActiveSessions
08-22 10:50:23.506  2793  2793 D Avrcp   : pick active media Controller
08-22 10:50:23.506  2793  2793 D Avrcp   : Get the active Media Controller 
,08-22 10:50:23.516  2793  2793 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-22 10:50:23.516  2793  7710 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-22 10:50:23.516  2793  2793 D A2dpStateMachine: make
,08-22 10:50:23.516  2793  2793 I bluedroid: get_profile_interface a2dp
,08-22 10:50:23.516  2793  7712 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-22 10:50:23.516  2793  2793 E bt-btif : warning : media task started media_task_refcnt 1 
08-22 10:50:23.516  2793  2793 D A2dpService: mStartError = false
08-22 10:50:23.516  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
08-22 10:50:23.516  2793  7711 D A2dpStateMachine: Enter Disconnected: -2
,08-22 10:50:23.516  2793  2793 D HidService: Received start request. Starting profile...
08-22 10:50:23.516  2793  2793 D HidService: start()
08-22 10:50:23.516  2793  2793 I bluedroid: get_profile_interface hidhost
08-22 10:50:23.516  2793  2793 D HidService: setHidService(): set to: null
08-22 10:50:23.516  2793  2793 D HidService: mStartError = false
08-22 10:50:23.516  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
08-22 10:50:23.516  2793  2793 D HealthService: Received start request. Starting profile...
,08-22 10:50:23.526  2793  2793 D HealthService: start()
,08-22 10:50:23.526  2793  2793 I bluedroid: get_profile_interface health
08-22 10:50:23.526  2793  2793 D HealthService: mStartError = false
08-22 10:50:23.526  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:23.526  2793  2793 D HeadsetStateMachine: Try to query the phonestate on bind
,08-22 10:50:23.526  1427  1449 I Telecom : BluetoothPhoneService: queryPhoneState
08-22 10:50:23.526  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-22 10:50:23.526  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 10:50:23.526  1427  1449 I Telecom : BluetoothPhoneService: Result of Message : true
,08-22 10:50:23.526  2793  2793 D PanService: Received start request. Starting profile...
08-22 10:50:23.526  2793  2793 D PanService: start()
08-22 10:50:23.526  2793  2793 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 10:50:23.526  2793  2793 I bluedroid: get_profile_interface pan
08-22 10:50:23.536  2793  2793 D PanService: mStartError = false
08-22 10:50:23.536  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:23.536  2793  2793 D BluetoothMapService: Received start request. Starting profile...
08-22 10:50:23.536  2793  2793 D BluetoothMapService: start()
,08-22 10:50:23.536  2793  2793 D BluetoothMapService: mStartError = false
,08-22 10:50:23.536  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:23.536  2793  2793 D HeadsetStateMachine: Proxy object connected
08-22 10:50:23.536  2793  2793 D SapService: Received start request. Starting profile...
08-22 10:50:23.536  2793  7710 D BluetoothMediaBrowser: no now playing list
08-22 10:50:23.536  2793  2793 D SapService: start()
08-22 10:50:23.536  2793  7710 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-22 10:50:23.536  2793  2793 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-22 10:50:23.536  2793  2793 I bluedroid: get_profile_interface sap
08-22 10:50:23.536  2793  2793 D SapService: mStartError = false
08-22 10:50:23.536  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
08-22 10:50:23.536  2793  2793 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-22 10:50:23.536  2793  2793 D HeadsetPhoneState: sendDeviceDataStateChanged
08-22 10:50:23.536  2793  2793 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-22 10:50:23.536  2793  7709 D HeadsetStateMachine: Disconnected process message: 11
08-22 10:50:23.536  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-22 10:50:23.536  2793  2793 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 10:50:23.536  2793  7709 D HeadsetStateMachine: Disconnected process message: 18
,08-22 10:50:23.536  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-22 10:50:23.536  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-22 10:50:23.536  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-22 10:50:23.536  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-22 10:50:23.536  2793  7709 D HeadsetStateMachine: Disconnected process message: 10
,08-22 10:50:23.536  2793  7709 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 10:50:23.536  2793  7709 D HeadsetStateMachine: Disconnected process message: 11
,08-22 10:50:23.556  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-22 10:50:23.556  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-22 10:50:23.556  2793  2853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-22 10:50:23.556  2793  2853 I bluedroid: enable
,08-22 10:50:23.566  2793  2856 E bt-btif : Calling BTA_HhEnable
08-22 10:50:23.566  2793  2856 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-22 10:50:23.566  2793  2856 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-22 10:50:23.566  2793  2856 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-22 10:50:23.566  2793  2856 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-22 10:50:23.566  2793  2856 E BluetoothServiceJni: populateRssiValuesNative
08-22 10:50:23.566  2793  2856 I bluedroid: getModelRssiValues
08-22 10:50:23.566  2793  2856 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-22 10:50:23.566  2793  2856 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 10:50:23.566  1015  1015 D SettingsProvider: name = bluetooth_name
,08-22 10:50:23.566  2793  2856 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-22 10:50:23.566  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:23.576  2793  2856 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 10:50:23.576  2793  2856 D BluetoothAdapterProperties: Scan Mode:20
08-22 10:50:23.576  2793  2856 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 10:50:23.576  2793  2856 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-22 10:50:23.576  2793  2856 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-22 10:50:23.576  2793  2856 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-22 10:50:23.576  2793  2856 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-22 10:50:23.576  2793  2856 E bt-btif : JVenable fails
,08-22 10:50:23.576  2793  2856 D bte_conf: Device ID record 1 : primary
08-22 10:50:23.576  2793  2856 D bte_conf:   vendorId            = 0075
08-22 10:50:23.576  2793  2856 D bte_conf:   vendorIdSource      = 0001
08-22 10:50:23.576  2793  2856 D bte_conf:   product             = 0100
08-22 10:50:23.576  2793  2856 D bte_conf:   version             = 0200
08-22 10:50:23.576  2793  2856 D bte_conf:   clientExecutableURL = 
08-22 10:50:23.576  2793  2856 D bte_conf:   serviceDescription  = 
08-22 10:50:23.576  2793  2856 D bte_conf:   documentationURL    = 
08-22 10:50:23.576  2793  2856 D bte_conf: bte_load_did_conf no section named DID2.
,08-22 10:50:23.576  2793  2856 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-22 10:50:23.576  2793  2856 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 10:50:23.576  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:23.576  2793  2853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-22 10:50:23.576  2793  2853 D BluetoothAdapterProperties: ScanMode =  20
08-22 10:50:23.576  2793  2853 D BluetoothAdapterProperties: State =  11
08-22 10:50:23.576  1015  1502 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 10:50:23.576  2793  2853 D BluetoothAdapterProperties: Setting state to 12
08-22 10:50:23.576  2793  2853 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 10:50:23.586  2793  2856 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-22 10:50:23.586  2793  2856 D BluetoothAdapterProperties: Scan Mode:21
,08-22 10:50:23.586  1015  3420 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-22 10:50:23.586  1015  3420 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 10:50:23.586  1015  3420 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 10:50:23.586  1015  3420 D SettingsProvider: selectionArgs: false
08-22 10:50:23.586  1015  3420 D SettingsProvider: selectionArgs: 1002
08-22 10:50:23.586  1015  3420 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 10:50:23.586  1015  3420 D SettingsProvider: ret = -1
08-22 10:50:23.586  2793  2856 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 10:50:23.586  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:23.586  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:23.586  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:23.586  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:23.586  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:23.586  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:23.586  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:23.586  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:23.586  2793  2853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 10:50:23.586  2793  2853 D BluetoothAdapterService: updateAdapterState state is 12
,08-22 10:50:23.586  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:23.586  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.586  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.586  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.586  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.586  2793  2853 D BluetoothAdapterService: Autoconnection is available 
08-22 10:50:23.586  2793  2853 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-22 10:50:23.586  2793  2853 D BluetoothAdapterService: starting service from this receiver
08-22 10:50:23.586  4558  4567 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:23.586  4558  4567 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:23.586  4558  7626 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 10:50:23.586  1015  1255 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:23.596  1015  1255 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-22 10:50:23.596  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.596  1015  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.596  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.596  4558  7626 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:23.596  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 10:50:23.596  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 10:50:23.596  2793  2853 I BluetoothAdapterState: Entering On State from state = 11
,08-22 10:50:23.596  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:23.596  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.596  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.596  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-22 10:50:23.596  2793  2793 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-22 10:50:23.596  1462  1478 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:23.596  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 10:50:23.596  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 10:50:23.596  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.596  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.596  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.596  1462  1478 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 10:50:23.606  7192  7202 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 10:50:23.606  7192  7202 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:23.606  1450  1461 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 10:50:23.606  1450  1461 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:23.606  1742  2303 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 10:50:23.606  1742  2303 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:23.606  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-22 10:50:23.606  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:23.606  1462  1680 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:23.606  1462  1680 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 10:50:23.606  4558  4566 D BluetoothMap: onBluetoothStateChange: up=true
08-22 10:50:23.606  2793  2793 I BluetoothPbapService: Handler(): got msg=1
,08-22 10:50:23.606  1015  3420 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 10:50:23.616  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-22 10:50:23.616  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.616  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.616  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 10:50:23.616  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.616  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:23.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:23.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:23.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:23.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:23.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:23.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:23.616  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:23.616  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 10:50:23.616  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:23.616  4558  4558 D BluetoothA2dp: Proxy object connected
08-22 10:50:23.616  4558  4558 D A2dpProfile: Bluetooth service connected
,08-22 10:50:23.616  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-22 10:50:23.616  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 10:50:23.616  1015  1015 D BluetoothA2dp: Proxy object connected
,08-22 10:50:23.616  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:23.616  2793  7717 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-22 10:50:23.616  1427  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-22 10:50:23.616  4558  4558 D BluetoothMap: Proxy object connected
,08-22 10:50:23.616  4558  4558 D MapProfile: Bluetooth service connected
08-22 10:50:23.626  4558  4558 D BluetoothMap: getConnectedDevices()
08-22 10:50:23.626  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 10:50:23.626  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 10:50:23.626  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.626  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.626  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-22 10:50:23.626  1427  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 10:50:23.626  4558  4567 D Bluetoothsap: onBluetoothStateChange: up=true
08-22 10:50:23.626  4558  4567 D Bluetoothsap: Binding service...
08-22 10:50:23.626  2793  7717 D BluetoothSocket: bindListen(): myUserId = 0
08-22 10:50:23.626  2793  7717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:23.626  2793  7717 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-22 10:50:23.626  2793  7717 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 10:50:23.626  2793  7717 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 10:50:23.626  2793  7717 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fd52700
,08-22 10:50:23.626  2793  7717 D BluetoothSocket: channel: 19,
08-22 10:50:23.626  2793  7717 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-22 10:50:23.626  4558  4567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-22 10:50:23.626  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-22 10:50:23.626  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.636  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.636  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.636  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.636  4558  4567 D Bluetoothsap: bindService called to Bluetooth SAP Service,
08-22 10:50:23.636  4558  4558 D Bluetoothsap: BluetoothSAP Proxy object connected
08-22 10:50:23.636  4558  4558 D SapProfile: Bluetooth service connected
08-22 10:50:23.636  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 10:50:23.636  4558  4558 D Bluetoothsap: getConnectedDevices()
08-22 10:50:23.636  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 10:50:23.636  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-22 10:50:23.636  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-22 10:50:23.636  4558  7626 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 10:50:23.636  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-22 10:50:23.636  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.636  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.636  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.636  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.636  6869  6879 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:23.636  6869  6879 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:23.636  4558  4558 D BluetoothPbap: Proxy object connected
08-22 10:50:23.636  1683  2551 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:23.636  1683  2551 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 10:50:23.636  4558  4558 D PbapServerProfile: Bluetooth service connected
,08-22 10:50:23.636  1427  1449 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:23.646  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 10:50:23.646  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 10:50:23.646  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.646  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.646  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.646  1427  1449 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 10:50:23.646  4558  7626 D BluetoothPan: Binding service...
,08-22 10:50:23.646  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-22 10:50:23.646  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.646  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.646  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.646  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.646  4558  4558 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 10:50:23.646  4558  4558 D PanProfile: Bluetooth service connected
,08-22 10:50:23.656  1427  1440 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:23.656  1427  1440 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:23.656  2793  7216 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 10:50:23.656  2793  7216 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:23.656  1015  1045 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-22 10:50:23.656  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.656  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.656  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.656  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.656  2793  2793 D BluetoothA2dp: Proxy object connected
08-22 10:50:23.656  2793  2793 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-22 10:50:23.656  1015  1045 D BluetoothPan: Binding service...
,08-22 10:50:23.656  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-22 10:50:23.656  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-22 10:50:23.656  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 10:50:23.656  4558  4567 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:23.656  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 10:50:23.656  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 10:50:23.666  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:23.666  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.666  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.666  4558  4567 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 10:50:23.666  4558  4558 D HeadsetProfile: Bluetooth service connected
,08-22 10:50:23.666  1427  3036 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:23.666  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 10:50:23.666  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 10:50:23.666  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.666  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.666  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.666  1427  3036 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 10:50:23.666  2793  7166 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:23.666  2793  7166 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:23.666  4558  7626 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 10:50:23.666  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-22 10:50:23.666  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.666  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.676  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:23.676  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.676  4558  4558 D BluetoothInputDevice: Proxy object connected
,08-22 10:50:23.676  4558  4558 D HidProfile: Bluetooth service connected
,08-22 10:50:23.676  1175  2850 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 10:50:23.676  1175  2850 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 10:50:23.676  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-22 10:50:23.676  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 10:50:23.676  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:23.676  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-22 10:50:23.676  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 10:50:23.686  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-22 10:50:23.686  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2b73a11a, true
,08-22 10:50:23.686  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 10:50:23.686  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:23.686  1175  1175 D BluetoothTile:  getBluetoothState : 12
08-22 10:50:23.686  1427  1427 D BluetoothHeadset: registerMessageListener
,08-22 10:50:23.686  1860  1860 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 10:50:23.686  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 10:50:23.696  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 10:50:23.696  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:23.696  2793  2857 D HeadsetService: registerMessageListener
,08-22 10:50:23.696  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:23.696  2793  2857 D HeadsetService: registerMessageListener
08-22 10:50:23.696  1015  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:23.696  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-22 10:50:23.696  1015  1467 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-22 10:50:23.696  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 10:50:23.696  2793  7709 D HeadsetStateMachine: Disconnected process message: 70
,08-22 10:50:23.696  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
08-22 10:50:23.706  2793  7709 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@29a3cb39
,08-22 10:50:23.706  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:23.706  4558  4558 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:23.706  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-22 10:50:23.706  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-22 10:50:23.706  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-22 10:50:23.706  2793  7709 D HeadsetStateMachine: Disconnected process message: 9
08-22 10:50:23.706  2793  7709 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-22 10:50:23.706  4558  4558 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-22 10:50:23.706  4558  4558 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-22 10:50:23.706  4558  4558 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-22 10:50:23.706  4558  4558 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-22 10:50:23.706   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-22 10:50:23.706   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-22 10:50:23.706   282   282 V voice   : voice_set_parameters: exit with code(-2)
08-22 10:50:23.706   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-22 10:50:23.706   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-22 10:50:23.706   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-22 10:50:23.716   282   282 V audio_hw_primary: adev_set_parameters: exit
,08-22 10:50:23.716  2793  7718 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-22 10:50:23.716  2793  7709 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-22 10:50:23.716  2793  7718 D BluetoothSocket: bindListen(): myUserId = 0
08-22 10:50:23.716  2793  7718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:23.716  2793  7718 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-22 10:50:23.716  2793  7718 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 10:50:23.716  2793  7718 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 10:50:23.716  2793  7718 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9bf157e
,08-22 10:50:23.716  2793  7718 D BluetoothSocket: channel: 5
,08-22 10:50:23.716  4558  4558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 10:50:23.716  1015  3420 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 10:50:23.716  1015  3420 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.726  1015  3420 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.726  1015  3420 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 10:50:23.726  1015  3420 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 10:50:23.726  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:23.736  4558  4558 D DockEventReceiver: finishStartingService: stopping service
,08-22 10:50:23.736  4558  4558 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 10:50:23.736  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-22 10:50:23.736  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-22 10:50:23.746  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:23.746  2793  2793 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 10:50:23.746  1015  1255 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:23.746  1015  1255 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-22 10:50:23.746  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:23.746  1015  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 10:50:23.746  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:23.756  1015  1211 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 10:50:23.776  2793  7724 D BluetoothSocket: bindListen(): myUserId = 0
08-22 10:50:23.776  2793  7724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:23.776  2793  7724 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[88]}
08-22 10:50:23.776  2793  7724 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 10:50:23.776  2793  7724 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 10:50:23.776  2793  7724 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cb30b8a
,08-22 10:50:23.776  2793  7724 D BluetoothSocket: channel: 12
08-22 10:50:23.776  2793  7724 I BtOppRfcommListener: Accept thread started.
,08-22 10:50:24.456   287   287 E SMD     : DCD OFF,
,08-22 10:50:24.546  1015  1211 I ActivityManager: Killing 7294:com.sec.pcw.device/1000 (adj 15): empty #21
,08-22 10:50:24.586  1015  3418 I ActivityManager: Killing 7311:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-22 10:50:26.386  6869  6947 D BluetoothAdapter: disable(),
08-22 10:50:26.386  1015  1485 D SettingsProvider: name = bluetooth_on
,08-22 10:50:26.396  2793  2853 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-22 10:50:26.396  2793  2853 D BluetoothAdapterProperties: Setting state to 13
08-22 10:50:26.396  2793  2853 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-22 10:50:26.396  2793  2853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 10:50:26.396  2793  2853 D BluetoothAdapterService: updateAdapterState state is 13
08-22 10:50:26.396  1015  1438 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:26.396  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 10:50:26.396  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:26.396  1015  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:26.396  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-22 10:50:26.406  2793  2853 D BluetoothAdapterService: Autoconnection is available 
,08-22 10:50:26.406  2793  2853 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-22 10:50:26.406  2793  2853 D BluetoothAdapterService: terminating service from this receiver
,08-22 10:50:26.406  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 10:50:26.406  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:26.406  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 10:50:26.406  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:26.406  2793  2853 D BluetoothAdapterProperties: onBluetoothDisable(),
08-22 10:50:26.406  2793  2853 D BluetoothAdapterProperties: mDiscovering is false
,08-22 10:50:26.406  1015  1502 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
08-22 10:50:26.416  2793  2793 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-22 10:50:26.416  2793  2853 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-22 10:50:26.416  2793  2793 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c7c25fb, channel: 19, state: LISTENING
08-22 10:50:26.416  2793  2793 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@c7c25fb, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fd52700, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f90d618mSocket: android.net.LocalSocket@2076a871 impl:android.net.LocalSocketImpl@323e5656 fd:FileDescriptor[80]
08-22 10:50:26.416  2793  2793 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2076a871 impl:android.net.LocalSocketImpl@323e5656 fd:FileDescriptor[80]
,08-22 10:50:26.416  2793  2856 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 10:50:26.416  2793  2856 D BluetoothAdapterProperties: Scan Mode:20
,08-22 10:50:26.426  2793  2853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-22 10:50:26.426  2793  2853 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-22 10:50:26.426  2793  2853 E bt-btif : BTM_SEC_CLR[17]: id 
08-22 10:50:26.426  2793  2858 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-22 10:50:26.426  2793  2853 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-22 10:50:26.426  4558  4558 D BluetoothPbap: Proxy object disconnected
08-22 10:50:26.426  4558  4558 D PbapServerProfile: Bluetooth service disconnected
,08-22 10:50:26.426  2793  7724 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-22 10:50:26.426  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:26.426  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:26.426  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:26.426  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:26.426  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:26.426  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:26.426  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:26.426  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:26.426  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:26.436  2793  2858 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 10:50:26.436  2793  2858 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 10:50:26.436  2793  2858 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 10:50:26.436  2793  2858 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 10:50:26.436  2793  2858 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 10:50:26.436  2793  2858 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-22 10:50:26.436  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:26.436  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:26.446  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:26.446  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:26.446  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:26.446  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:26.446  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:26.446  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:26.446  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:26.446  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:26.446  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:26.446  6869  6869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:26.446  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:26.446  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:26.456  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-22 10:50:26.456  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-22 10:50:26.456  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 10:50:26.456  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:26.456  1175  1175 D BluetoothTile:  getBluetoothState : 13
,08-22 10:50:26.456  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 10:50:26.466  1860  1860 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 10:50:26.466  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 10:50:26.466  4558  4558 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:26.466  2793  2793 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3dc93bc4, channel: 5, state: LISTENING
08-22 10:50:26.466  2793  2793 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3dc93bc4, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9bf157e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c7c5aadmSocket: android.net.LocalSocket@136181e2 impl:android.net.LocalSocketImpl@ce35973 fd:FileDescriptor[82]
08-22 10:50:26.466  2793  2793 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@136181e2 impl:android.net.LocalSocketImpl@ce35973 fd:FileDescriptor[82]
,08-22 10:50:26.466  2793  2793 I BtOppRfcommListener: stopping Accept Thread
08-22 10:50:26.466  2793  2793 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24005030, channel: 12, state: LISTENING
08-22 10:50:26.466  2793  2793 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24005030, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cb30b8a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@21b0f4a9mSocket: android.net.LocalSocket@2699da2e impl:android.net.LocalSocketImpl@3d9019cf fd:FileDescriptor[88]
08-22 10:50:26.466  2793  2793 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2699da2e impl:android.net.LocalSocketImpl@3d9019cf fd:FileDescriptor[88]
,08-22 10:50:26.466  2793  7724 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-22 10:50:26.476  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:26.476  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:26.476  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 10:50:26.476  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:26.476  1015  3420 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 10:50:26.476  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 10:50:26.476  2793  2793 V BluetoothOppManager: cleanUp...
,08-22 10:50:26.486  4558  4558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 10:50:26.486  1015  1459 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 10:50:26.486  1015  1459 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 10:50:26.486  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:26.486  1015  1459 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:26.486  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 10:50:26.496  4558  4558 D DockEventReceiver: finishStartingService: stopping service
,08-22 10:50:26.496  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:26.496  4558  4558 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 10:50:26.506  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:26.506  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-22 10:50:26.626  2793  2853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-22 10:50:26.626  2793  2853 D BtConfig.SecureMode: isSecureModeOn:false
08-22 10:50:26.626  2793  2853 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-22 10:50:26.626  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-22 10:50:26.626  2793  2853 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-22 10:50:26.626  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 10:50:26.626  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 10:50:26.626  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:26.626  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-22 10:50:26.626  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 10:50:26.626  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:26.626  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:26.626  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:26.626  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 10:50:26.626  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 10:50:26.626  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-22 10:50:26.626  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:26.626  1015  3418 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-22 10:50:26.626  1015  3418 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:26.626  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 10:50:26.626  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 10:50:26.626  2793  2793 D HeadsetService: Received stop request...Stopping profile...
,08-22 10:50:26.636  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:26.636  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-22 10:50:26.636  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 10:50:26.636  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 10:50:26.636  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:26.636  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-22 10:50:26.636  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 10:50:26.636  4558  4558 D HeadsetProfile: Bluetooth service disconnected
,08-22 10:50:26.636  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:26.636  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:26.636  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:26.636  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-22 10:50:26.636  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 10:50:26.636  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 10:50:26.646  1015  3420 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:26.646  1015  3420 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-22 10:50:26.646  1015  3420 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:26.646  1015  3420 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:26.646  1015  3420 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:26.646  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-22 10:50:26.646  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 10:50:26.646  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-22 10:50:26.646  1015  1438 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:26.646  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 10:50:26.646  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:26.646  1015  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:26.646  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:26.646  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:26.646  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:26.646  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:26.646  1015  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:26.646  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 10:50:26.646  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:26.646  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:26.646  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:26.656  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-22 10:50:26.656  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 10:50:26.656  2793  2853 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 10:50:26.656  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:26.656  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 10:50:26.656  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:26.656  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:26.656  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:26.656  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:26.656  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:26.656  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:26.656  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:26.656  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:26.656  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:26.656  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 10:50:26.656  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 10:50:26.656  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 10:50:26.656  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-22 10:50:26.656  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 10:50:26.656  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 10:50:26.656  2793  2853 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-22 10:50:26.656  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-22 10:50:26.656  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 10:50:26.656  2793  2793 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-22 10:50:26.656  2793  2793 D A2dpService: Received stop request...Stopping profile...
,08-22 10:50:26.656  2793  7711 D A2dpStateMachine: Exit Disconnected: -1
,08-22 10:50:26.656  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:26.656  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-22 10:50:26.656  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-22 10:50:26.666  4558  4558 D BluetoothA2dp: Proxy object disconnected
08-22 10:50:26.666  4558  4558 D A2dpProfile: Bluetooth service disconnected
,08-22 10:50:26.666  2793  2793 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-22 10:50:26.666  2793  2793 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-22 10:50:26.666  2793  2793 D HidService: Received stop request...Stopping profile...
,08-22 10:50:26.666  2793  2793 D HidService: Stopping Bluetooth HidService
08-22 10:50:26.666  2793  2793 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-22 10:50:26.666  2793  2793 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-22 10:50:26.666  2793  2793 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-22 10:50:26.666  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:26.666  2793  2793 D HealthService: Received stop request...Stopping profile...
08-22 10:50:26.666  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:26.666  4558  4558 D BluetoothInputDevice: Proxy object disconnected
,08-22 10:50:26.666  2793  2793 D PanService: Received stop request...Stopping profile...
08-22 10:50:26.666  4558  4558 D HidProfile: Bluetooth service disconnected
08-22 10:50:26.666  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:26.676  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 10:50:26.676  4558  4558 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 10:50:26.676  4558  4558 D PanProfile: Bluetooth service disconnected
,08-22 10:50:26.676  2793  2793 D BluetoothMapService: Received stop request...Stopping profile...
,08-22 10:50:26.676  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:26.676  2793  2793 D SapService: Received stop request...Stopping profile...
,08-22 10:50:26.676  2793  2793 D SapService: Stopping Bluetooth SapService
08-22 10:50:26.676  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:26.676  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-22 10:50:26.676  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 10:50:26.676  2793  2793 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-22 10:50:26.676  2793  2793 D BluetoothA2dp: Proxy object disconnected
08-22 10:50:26.676  2793  2793 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-22 10:50:26.686  2793  7712 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-22 10:50:26.686  2793  2793 I GKI_LINUX: GKI_exit_task 2 done
08-22 10:50:26.686  2793  2793 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-22 10:50:26.686  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-22 10:50:26.686  2793  2793 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 10:50:26.686  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:26.686  2793  2793 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:26.686  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-22 10:50:26.686  2793  2793 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 10:50:26.686  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:26.686  2793  2793 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:26.686  2793  2793 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-22 10:50:26.686  2793  2793 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 10:50:26.686  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-22 10:50:26.686  2793  2793 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 10:50:26.686  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:26.686  2793  2793 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:26.686  2793  2793 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 10:50:26.686  2793  2793 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-22 10:50:26.686  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-22 10:50:26.686  2793  2793 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 10:50:26.686  2793  2793 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 10:50:26.686  2793  2793 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-22 10:50:26.686  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-22 10:50:26.686  2793  2793 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. ,
,08-22 10:50:26.686  2793  2793 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-22 10:50:26.686  2793  2793 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-22 10:50:26.686  4558  4558 D BluetoothMap: Proxy object disconnected
08-22 10:50:26.686  4558  4558 D MapProfile: Bluetooth service disconnected
08-22 10:50:26.686  4558  4558 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-22 10:50:26.686  4558  4558 D SapProfile: Bluetooth service disconnected
,08-22 10:50:26.686  2793  2853 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-22 10:50:26.686  2793  2853 D BluetoothAdapterProperties: Setting state to 10
08-22 10:50:26.686  2793  2853 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-22 10:50:26.686  2793  2853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 10:50:26.686  2793  2853 D BluetoothAdapterService: updateAdapterState state is 10
,08-22 10:50:26.696  2793  2853 D BluetoothAdapterService: Autoconnection is available 
,08-22 10:50:26.696  2793  2853 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-22 10:50:26.696  2793  2853 I BluetoothAdapterState: Entering OffState
,08-22 10:50:26.696  4558  4567 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 10:50:26.696  4558  4567 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:26.696  4558  7626 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 10:50:26.696  7192  7200 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:26.696  7192  7200 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:26.696  1450  1769 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:26.696  1450  1769 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:26.696  1742  1751 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 10:50:26.696  1742  1751 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 10:50:26.696  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 10:50:26.696  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:26.696  1462  1478 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:26.696  1462  1478 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:26.696  4558  4566 D BluetoothMap: onBluetoothStateChange: up=false
,08-22 10:50:26.696  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 10:50:26.706  4558  4567 D Bluetoothsap: onBluetoothStateChange: up=false
,08-22 10:50:26.706  4558  4567 D Bluetoothsap: Unbinding service...
,08-22 10:50:26.706  4558  7626 D BluetoothPbap: onBluetoothStateChange: up=false
,08-22 10:50:26.706  6869  6881 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 10:50:26.706  6869  6881 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 10:50:26.706  6869  6881 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-22 10:50:26.706  6869  6881 D BluetoothLeAdvertiser: Exit stop advertising
08-22 10:50:26.706  6869  6881 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-22 10:50:26.706  6869  6881 D BluetoothLeScanner: Exiting stopAllScan
,08-22 10:50:26.706  1683  1701 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 10:50:26.706  1683  1701 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:26.706  1427  1449 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 10:50:26.706  1427  1449 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:26.706  2793  2809 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 10:50:26.716  2793  2857 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 10:50:26.716  2793  2857 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:26.716  4558  7626 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-22 10:50:26.716  1175  1192 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 10:50:26.716  1175  1192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 10:50:26.716  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:26.716  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
,08-22 10:50:26.716  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 10:50:26.726  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 10:50:26.726  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:26.726  1175  1175 D BluetoothTile:  getBluetoothState : 10
,08-22 10:50:26.726  1860  1860 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 10:50:26.736  1015  1211 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:26.736  1015  3418 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 10:50:26.736  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 10:50:26.736  4558  4558 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:26.736  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:26.736  4558  4558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 10:50:26.736  1015  1467 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 10:50:26.736  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 10:50:26.746  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:26.746  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:26.746  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:26.746  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 10:50:26.746  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:26.756  4558  4558 D DockEventReceiver: finishStartingService: stopping service
,08-22 10:50:26.756  4558  4558 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 10:50:26.756  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:26.756  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-22 10:50:27.466   287   287 E SMD     : DCD OFF
,08-22 10:50:29.346  1015  1093 V AlarmManager: waitForAlarm result :4
,08-22 10:50:29.356   277   981 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 10:50:29.356   277   981 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-22 10:50:29.376  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:29.376  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:29.376  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-22 10:50:29.396  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:29.396  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:29.456  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-22 10:50:29.456  1015  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-22 10:50:29.456  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
08-22 10:50:29.456  1015  1467 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 10:50:29.456  1015  1467 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 10:50:29.456  1015  1467 D BatteryService: stay LED for charging
08-22 10:50:29.456  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-22 10:50:29.456  1015  1015 I MotionRecognitionService: Plugged
08-22 10:50:29.456  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 10:50:29.456  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-22 10:50:29.456  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 10:50:29.486  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 10:50:29.486  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-22 10:50:29.486  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 10:50:29.536  1015  2891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 10:50:30.466   287   287 E SMD     : DCD OFF
,08-22 10:50:31.726  1015  2872 D SSRM:n  : SIOP:: AP = 320,
,08-22 10:50:31.876  1015  1320 E Watchdog: !@Sync 4
,08-22 10:50:32.396  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-22 10:50:32.396  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c98ce40 added. We now have 6 listener(s)
08-22 10:50:32.396  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:32.396  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:32.396  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1678179 added. We now have 7 listener(s)
,08-22 10:50:32.406  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:32.406  6869  6947 I System.out: IsBluetoothEnabled
08-22 10:50:32.406  6869  6947 D BluetoothAdapter: disable()
08-22 10:50:32.406  1015  1467 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,08-22 10:50:32.416  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:32.416  6869  6947 D BluetoothAdapter: enable()
,08-22 10:50:32.416  1015  1479 W ActivityManager: Permission Denial: getCurrentUser() from pid=6869, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-22 10:50:32.416  1015  1479 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-22 10:50:32.416  1015  1479 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6869, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 10:50:32.416  1015  1479 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 10:50:32.416  1015  1479 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-22 10:50:32.416  1015  1479 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-22 10:50:32.416  1015  1479 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-22 10:50:32.416  1015  1479 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 10:50:32.416  1015  1479 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 10:50:32.416  1015  1479 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 10:50:32.426  1015  1479 D SettingsProvider: name = bluetooth_on
,08-22 10:50:32.426  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-22 10:50:32.426  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 10:50:32.436  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-22 10:50:32.436  2793  2853 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-22 10:50:32.436  2793  2853 D BluetoothAdapterProperties: Setting state to 11
,08-22 10:50:32.436  2793  2853 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-22 10:50:32.436  2793  2853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 10:50:32.436  2793  2853 D BluetoothAdapterService: updateAdapterState state is 11
,08-22 10:50:32.436  2793  2853 D BluetoothAdapterService: Autoconnection is available 
,08-22 10:50:32.436  2793  2853 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-22 10:50:32.436  2793  2853 D BtConfig.SecureMode: isSecureModeOn:false,
,08-22 10:50:32.436  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-22 10:50:32.436  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-22 10:50:32.436  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 10:50:32.436  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-22 10:50:32.436  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService,
08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
,08-22 10:50:32.446  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
,08-22 10:50:32.446  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
,08-22 10:50:32.446  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-22 10:50:32.446  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-22 10:50:32.446  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-22 10:50:32.446  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:32.446  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:32.446  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-22 10:50:32.446  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService,
08-22 10:50:32.446  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:32.446  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 10:50:32.446  1015  1015 I InputMethodManagerService: [BT Setting State] State =11,
08-22 10:50:32.446  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-22 10:50:32.456  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 10:50:32.456   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 10:50:32.456  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:32.456  1175  1175 D BluetoothTile:  getBluetoothState : 11
,08-22 10:50:32.456  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 10:50:32.456  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 10:50:32.466  1860  1860 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 10:50:32.466  4558  4558 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:32.466  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:32.466  1015  1485 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 10:50:32.466  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
,08-22 10:50:32.466  1015  1255 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:32.466  1015  1255 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.476  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:32.476  1015  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.476  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.476  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:32.476  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 10:50:32.476  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 10:50:32.476  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-22 10:50:32.476  2793  2793 D HeadsetService: Received start request. Starting profile...
08-22 10:50:32.476  2793  2793 D HeadsetService: start()
08-22 10:50:32.476  2793  2793 D HeadsetStateMachine: make
,08-22 10:50:32.476  2793  2793 E HeadsetStateMachine: # of Max HF connection is 2
,08-22 10:50:32.486  1015  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:32.486  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.486  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 10:50:32.486  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.486  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.486  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.486  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-22 10:50:32.486  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 10:50:32.486  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 10:50:32.486  1015  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:32.496  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.496  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:32.496  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.496  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.496  1015  1479 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-22 10:50:32.496  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.496  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:32.496  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.496  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-22 10:50:32.496  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 10:50:32.496  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-22 10:50:32.496  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-22 10:50:32.496  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:32.496  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.496  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:32.496  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.496  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.506  1015  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-22 10:50:32.506  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.506  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService,
08-22 10:50:32.506  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 10:50:32.506  1015  3420 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:32.506  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-22 10:50:32.506  1015  3420 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-22 10:50:32.506  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:32.506  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.506  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-22 10:50:32.506  2793  2793 I bluedroid: get_profile_interface handsfree
08-22 10:50:32.506  1015  3420 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:32.506  1015  3420 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.506  1015  3420 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 10:50:32.506  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-22 10:50:32.506  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 10:50:32.506  2793  2853 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 10:50:32.506  4558  4558 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 10:50:32.506  1015  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-22 10:50:32.506  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.516  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.516  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 10:50:32.516  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.516  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-22 10:50:32.516  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 10:50:32.516  2793  2853 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 10:50:32.526  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:32.526  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-22 10:50:32.526  1015  1459 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:32.526  1015  1459 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-22 10:50:32.526  2793  2793 E DualScoManager: Dual Sco Manager already instantiated
08-22 10:50:32.526  2793  2793 I DualScoManager: Set HeadsetServiceHelper
08-22 10:50:32.526  2793  2793 D BluetoothAtMessage: createCMTIContentObservers
08-22 10:50:32.526  1015  1378 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-22 10:50:32.526  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.526  1015  1459 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.526  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 10:50:32.526  1015  1378 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 10:50:32.526  1015  1378 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 10:50:32.526  1015  1378 D SettingsProvider: selectionArgs: false
08-22 10:50:32.526  1015  1378 D SettingsProvider: selectionArgs: 1002
08-22 10:50:32.526  1015  1378 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 10:50:32.526  1015  1378 D SettingsProvider: ret = -1
08-22 10:50:32.526  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:32.526  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:32.526  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 10:50:32.526  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:32.526  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:32.526  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 10:50:32.526  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 10:50:32.526  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 10:50:32.526  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 10:50:32.526  2793  2853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-22 10:50:32.526  2793  2853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 10:50:32.526  2793  2853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 10:50:32.526  2793  2853 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-22 10:50:32.526  2793  7739 D HeadsetStateMachine: Enter Disconnected: -2
,08-22 10:50:32.536  2793  2793 D HeadsetService: mStartError = false
08-22 10:50:32.536  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:32.536  2793  2793 D A2dpService: Received start request. Starting profile...
,08-22 10:50:32.536  2793  2793 D A2dpService: start()
08-22 10:50:32.536  2793  2793 I bluedroid: get_profile_interface avrcp
,08-22 10:50:32.536  2793  7739 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-22 10:50:32.536  2793  7739 D HeadsetStateMachine: map size, before remove : 0
08-22 10:50:32.536  2793  7739 D HeadsetStateMachine: map size, after remove: 0
,08-22 10:50:32.536  2793  2793 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-22 10:50:32.536  2793  2793 D Avrcp   : Initialize Media Controller
08-22 10:50:32.536  2793  2793 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-22 10:50:32.546  2793  2793 E Avrcp   : getActiveSessions
08-22 10:50:32.546  2793  2793 D Avrcp   : pick active media Controller
08-22 10:50:32.546  2793  2793 D Avrcp   : Get the active Media Controller 
,08-22 10:50:32.546  2793  2793 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-22 10:50:32.546  2793  2793 D A2dpStateMachine: make
08-22 10:50:32.546  2793  7740 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-22 10:50:32.556  2793  2793 I bluedroid: get_profile_interface a2dp
,08-22 10:50:32.556  2793  7742 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-22 10:50:32.556  2793  2793 E bt-btif : warning : media task started media_task_refcnt 1 
,08-22 10:50:32.556  2793  2793 D A2dpService: mStartError = false
08-22 10:50:32.556  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:32.556  2793  7741 D A2dpStateMachine: Enter Disconnected: -2
,08-22 10:50:32.556  2793  2793 D HidService: Received start request. Starting profile...
08-22 10:50:32.556  2793  2793 D HidService: start()
08-22 10:50:32.556  2793  2793 I bluedroid: get_profile_interface hidhost
08-22 10:50:32.556  2793  2793 D HidService: setHidService(): set to: null
08-22 10:50:32.556  2793  2793 D HidService: mStartError = false
08-22 10:50:32.556  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
08-22 10:50:32.556  2793  2793 D HeadsetStateMachine: Try to query the phonestate on bind
,08-22 10:50:32.556  1427  1440 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 10:50:32.556  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-22 10:50:32.556  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 10:50:32.556  1427  1440 I Telecom : BluetoothPhoneService: Result of Message : true
,08-22 10:50:32.556  2793  2793 D HeadsetStateMachine: Proxy object connected
,08-22 10:50:32.556  2793  2793 D HealthService: Received start request. Starting profile...
08-22 10:50:32.556  2793  2793 D HealthService: start()
,08-22 10:50:32.566  2793  2793 I bluedroid: get_profile_interface health
,08-22 10:50:32.566  2793  2793 D HealthService: mStartError = false
08-22 10:50:32.566  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
08-22 10:50:32.566  2793  2793 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-22 10:50:32.566  2793  7739 D HeadsetStateMachine: Disconnected process message: 11
08-22 10:50:32.566  2793  2793 D PanService: Received start request. Starting profile...
08-22 10:50:32.566  2793  2793 D PanService: start()
08-22 10:50:32.566  2793  2793 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 10:50:32.566  2793  2793 I bluedroid: get_profile_interface pan
08-22 10:50:32.566  2793  2793 D PanService: mStartError = false
08-22 10:50:32.566  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:32.566  2793  2793 D BluetoothMapService: Received start request. Starting profile...
08-22 10:50:32.566  2793  2793 D BluetoothMapService: start()
,08-22 10:50:32.566  2793  2793 D BluetoothMapService: mStartError = false
,08-22 10:50:32.566  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
08-22 10:50:32.566  2793  2793 D HeadsetPhoneState: sendDeviceDataStateChanged
08-22 10:50:32.566  2793  2793 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-22 10:50:32.566  2793  7739 D HeadsetStateMachine: Disconnected process message: 18
,08-22 10:50:32.566  2793  2793 D SapService: Received start request. Starting profile...
08-22 10:50:32.566  2793  2793 D SapService: start()
08-22 10:50:32.566  2793  2793 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-22 10:50:32.566  2793  2793 I bluedroid: get_profile_interface sap
08-22 10:50:32.566  2793  2793 D SapService: mStartError = false
08-22 10:50:32.566  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
08-22 10:50:32.566  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-22 10:50:32.566  2793  2793 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 10:50:32.566  2793  7739 D HeadsetStateMachine: Disconnected process message: 10
08-22 10:50:32.566  2793  7739 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 10:50:32.566  2793  7739 D HeadsetStateMachine: Disconnected process message: 11
08-22 10:50:32.566  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-22 10:50:32.566  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-22 10:50:32.566  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-22 10:50:32.566  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-22 10:50:32.566  2793  7740 D BluetoothMediaBrowser: no now playing list
08-22 10:50:32.566  2793  7740 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-22 10:50:32.586  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-22 10:50:32.586  2793  2793 E BluetoothAdapterService(796569431): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-22 10:50:32.586  2793  2853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-22 10:50:32.586  2793  2853 I bluedroid: enable
,08-22 10:50:32.586  2793  2856 E bt-btif : Calling BTA_HhEnable
,08-22 10:50:32.596  2793  2856 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-22 10:50:32.596  2793  2856 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-22 10:50:32.596  2793  2856 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-22 10:50:32.596  2793  2856 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-22 10:50:32.596  2793  2856 E BluetoothServiceJni: populateRssiValuesNative
08-22 10:50:32.596  2793  2856 I bluedroid: getModelRssiValues
08-22 10:50:32.596  2793  2856 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-22 10:50:32.596  2793  2856 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 10:50:32.596  1015  1015 D SettingsProvider: name = bluetooth_name
,08-22 10:50:32.596  2793  2856 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-22 10:50:32.596  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:32.596  2793  2856 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-22 10:50:32.596  2793  2856 D BluetoothAdapterProperties: Scan Mode:20
08-22 10:50:32.596  2793  2856 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 10:50:32.606  2793  2856 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-22 10:50:32.606  2793  2856 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-22 10:50:32.606  2793  2856 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-22 10:50:32.606  2793  2856 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-22 10:50:32.606  2793  2856 E bt-btif : JVenable fails
,08-22 10:50:32.606  2793  2856 D bte_conf: Device ID record 1 : primary
08-22 10:50:32.606  2793  2856 D bte_conf:   vendorId            = 0075
08-22 10:50:32.606  2793  2856 D bte_conf:   vendorIdSource      = 0001
08-22 10:50:32.606  2793  2856 D bte_conf:   product             = 0100
08-22 10:50:32.606  2793  2856 D bte_conf:   version             = 0200
08-22 10:50:32.606  2793  2856 D bte_conf:   clientExecutableURL = 
08-22 10:50:32.606  2793  2856 D bte_conf:   serviceDescription  = 
08-22 10:50:32.606  2793  2856 D bte_conf:   documentationURL    = 
08-22 10:50:32.606  2793  2856 D bte_conf: bte_load_did_conf no section named DID2.
,08-22 10:50:32.606  2793  2856 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-22 10:50:32.606  2793  2856 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-22 10:50:32.606  2793  2853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-22 10:50:32.606  2793  2853 D BluetoothAdapterProperties: ScanMode =  20
08-22 10:50:32.606  2793  2853 D BluetoothAdapterProperties: State =  11
,08-22 10:50:32.606  1015  3420 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 10:50:32.606  2793  2853 D BluetoothAdapterProperties: Setting state to 12
08-22 10:50:32.606  2793  2853 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 10:50:32.606  1015  1459 D SettingsProvider: name = bluetooth_a2dp_sink_mode,
08-22 10:50:32.606  1015  1459 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 10:50:32.606  1015  1459 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 10:50:32.606  1015  1459 D SettingsProvider: selectionArgs: false
08-22 10:50:32.606  1015  1459 D SettingsProvider: selectionArgs: 1002
,08-22 10:50:32.606  1015  1459 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 10:50:32.606  1015  1459 D SettingsProvider: ret = -1
,08-22 10:50:32.606  2793  2853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 10:50:32.606  2793  2853 D BluetoothAdapterService: updateAdapterState state is 12
08-22 10:50:32.606  1015  1378 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 10:50:32.606  1015  1378 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.606  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.606  1015  1378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.606  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.616  2793  2853 D BluetoothAdapterService: Autoconnection is available 
08-22 10:50:32.616  2793  2853 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-22 10:50:32.616  2793  2853 D BluetoothAdapterService: starting service from this receiver
,08-22 10:50:32.616  4558  4567 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 10:50:32.616  1015  3418 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:32.616  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-22 10:50:32.616  4558  4567 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:32.616  2793  2793 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-22 10:50:32.616  2793  2856 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 10:50:32.616  2793  2856 D BluetoothAdapterProperties: Scan Mode:21
08-22 10:50:32.616  2793  2856 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 10:50:32.626  2793  2793 I BluetoothPbapService: Handler(): got msg=1
,08-22 10:50:32.626  4558  7626 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 10:50:32.626  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.626  1015  3418 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.626  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 10:50:32.626  1015  3420 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-22 10:50:32.626  4558  7626 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:32.626  2793  2853 I BluetoothAdapterState: Entering On State from state = 11
,08-22 10:50:32.646  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:32.646  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:32.646  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:32.646  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:32.646  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:32.646  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:32.646  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:32.646  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:32.646  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:32.646  2793  7747 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-22 10:50:32.656  2793  7747 D BluetoothSocket: bindListen(): myUserId = 0
,08-22 10:50:32.656  2793  7747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:32.656  2793  7747 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-22 10:50:32.656  2793  7747 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 10:50:32.656  2793  7747 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 10:50:32.656  2793  7747 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@199453cb
,08-22 10:50:32.656  2793  7747 D BluetoothSocket: channel: 19
08-22 10:50:32.656  2793  7747 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-22 10:50:32.786  1015  1045 I art     : Explicit concurrent mark sweep GC freed 58209(3MB) AllocSpace objects, 8(129KB) LOS objects, 33% free, 22MB/34MB, paused 2.321ms total 156.269ms
08-22 10:50:32.786  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 10:50:32.786  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.786  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.786  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.786  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.786  1462  1665 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:32.786  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 10:50:32.786  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 10:50:32.786  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.786  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.786  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.796  1462  1665 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 10:50:32.796  4558  4558 D BluetoothA2dp: Proxy object connected
08-22 10:50:32.796  4558  4558 D A2dpProfile: Bluetooth service connected
,08-22 10:50:32.796  7192  7202 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:32.796  7192  7202 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:32.796  1450  1769 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 10:50:32.796  1450  1769 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:32.796  1742  1753 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 10:50:32.796  1742  1753 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
,08-22 10:50:32.796  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:32.796  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 10:50:32.796  1462  1665 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 10:50:32.796  1462  1665 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 10:50:32.796  4558  4567 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 10:50:32.796  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-22 10:50:32.796  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0,
08-22 10:50:32.796  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.796  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.796  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.806  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 10:50:32.806  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-22 10:50:32.806  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 10:50:32.806  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.806  1015  1015 D BluetoothA2dp: Proxy object connected
,08-22 10:50:32.806  4558  4558 D BluetoothMap: Proxy object connected
08-22 10:50:32.806  4558  4558 D MapProfile: Bluetooth service connected
08-22 10:50:32.806  4558  4558 D BluetoothMap: getConnectedDevices()
,08-22 10:50:32.806  1427  1449 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:32.806  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 10:50:32.806  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 10:50:32.806  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.806  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.806  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.806  1427  1449 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 10:50:32.806  4558  7626 D Bluetoothsap: onBluetoothStateChange: up=true
,08-22 10:50:32.806  4558  7626 D Bluetoothsap: Binding service...
,08-22 10:50:32.806  4558  7626 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-22 10:50:32.806  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-22 10:50:32.806  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.806  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.806  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.806  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-22 10:50:32.816  4558  7626 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-22 10:50:32.816  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:32.816  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 10:50:32.816  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-22 10:50:32.816  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 10:50:32.816  4558  4567 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 10:50:32.816  4558  4558 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-22 10:50:32.816  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-22 10:50:32.816  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-22 10:50:32.816  4558  4558 D SapProfile: Bluetooth service connected
08-22 10:50:32.816  4558  4558 D Bluetoothsap: getConnectedDevices()
,08-22 10:50:32.816  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.816  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.816  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.816  6869  6879 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 10:50:32.816  6869  6879 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 10:50:32.816  4558  4558 D BluetoothPbap: Proxy object connected
08-22 10:50:32.816  4558  4558 D PbapServerProfile: Bluetooth service connected
08-22 10:50:32.816  1683  1701 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 10:50:32.816  1683  1701 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:32.816  1427  3036 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:32.816  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 10:50:32.816  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 10:50:32.826  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.826  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.826  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.826  1427  3036 E BluetoothHeadset: BluetoothHeadset service is binded
08-22 10:50:32.826  4558  4567 D BluetoothPan: Binding service...
,08-22 10:50:32.826  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-22 10:50:32.826  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.826  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:32.826  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.826  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.826  4558  4558 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 10:50:32.826  4558  4558 D PanProfile: Bluetooth service connected
08-22 10:50:32.826  1427  1440 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:32.826  1427  1440 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 10:50:32.826  2793  2857 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 10:50:32.826  2793  2857 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:32.826  1015  1045 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 10:50:32.826  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.826  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.826  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.826  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.836  1015  1045 D BluetoothPan: Binding service...
08-22 10:50:32.836  2793  2793 D BluetoothA2dp: Proxy object connected
08-22 10:50:32.836  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-22 10:50:32.836  2793  2793 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-22 10:50:32.836  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.836  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 10:50:32.836  4558  4566 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:32.836  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 10:50:32.836  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 10:50:32.836  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.836  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.836  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.836  4558  4566 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 10:50:32.836  4558  4558 D HeadsetProfile: Bluetooth service connected
,08-22 10:50:32.836  1427  1449 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 10:50:32.836  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 10:50:32.836  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 10:50:32.836  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.836  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.836  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.836  1427  1449 E BluetoothHeadset: BluetoothHeadset service is binded,
08-22 10:50:32.836  2793  2803 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:32.836  2793  2803 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 10:50:32.836  4558  4567 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 10:50:32.846  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-22 10:50:32.846  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:32.846  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-22 10:50:32.846  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.846  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.846  1175  1200 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 10:50:32.846  1175  1200 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 10:50:32.846  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-22 10:50:32.846  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 10:50:32.846  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:32.846  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
,08-22 10:50:32.846  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 10:50:32.846  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2f6db44b, true
,08-22 10:50:32.846  1427  1427 D BluetoothHeadset: registerMessageListener
,08-22 10:50:32.856  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-22 10:50:32.856  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 10:50:32.856  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 10:50:32.856  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 10:50:32.866  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 10:50:32.866  1175  1175 D BluetoothTile:  getBluetoothState : 12
,08-22 10:50:32.866  1860  1860 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 10:50:32.866  1175  1762 D BluetoothTile:  handleUpdatestate:false name:null,
,08-22 10:50:32.866  1015  3418 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:32.866  1015  1255 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-22 10:50:32.866  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 10:50:32.866  4558  4558 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:32.876  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:32.876  2793  7719 D HeadsetService: registerMessageListener
,08-22 10:50:32.876  2793  7719 D HeadsetService: registerMessageListener
08-22 10:50:32.876  4558  4558 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-22 10:50:32.876  4558  4558 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-22 10:50:32.876  4558  4558 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-22 10:50:32.876  4558  4558 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-22 10:50:32.876  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-22 10:50:32.876  2793  7739 D HeadsetStateMachine: Disconnected process message: 70
08-22 10:50:32.876  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-22 10:50:32.876  2793  7739 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@293ea654
,08-22 10:50:32.876  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-22 10:50:32.876  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-22 10:50:32.876  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-22 10:50:32.876  2793  7739 D HeadsetStateMachine: Disconnected process message: 9
08-22 10:50:32.876  2793  7739 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-22 10:50:32.876  4558  4558 D BluetoothInputDevice: Proxy object connected
08-22 10:50:32.876  2793  7749 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-22 10:50:32.876  4558  4558 D HidProfile: Bluetooth service connected
,08-22 10:50:32.886   282   701 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false,
,08-22 10:50:32.886   282   701 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-22 10:50:32.886   282   701 V voice   : voice_set_parameters: exit with code(-2)
,08-22 10:50:32.886   282   701 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-22 10:50:32.886   282   701 V msm8974_platform: platform_set_parameters: exit with code(-2),
08-22 10:50:32.886   282   701 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-22 10:50:32.886   282   701 V audio_hw_primary: adev_set_parameters: exit
,08-22 10:50:32.886  2793  7739 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-22 10:50:32.886  2793  7749 D BluetoothSocket: bindListen(): myUserId = 0
,08-22 10:50:32.886  2793  7749 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 10:50:32.886  2793  7749 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-22 10:50:32.886  2793  7749 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 10:50:32.886  2793  7749 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-22 10:50:32.886  2793  7749 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f5299fd
08-22 10:50:32.886  2793  7749 D BluetoothSocket: channel: 5
,08-22 10:50:32.886  4558  4558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 10:50:32.886  1015  1459 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 10:50:32.886  1015  1459 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.896  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:32.896  1015  1459 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.896  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 10:50:32.896  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:32.896  4558  4558 D DockEventReceiver: finishStartingService: stopping service
,08-22 10:50:32.906  4558  4558 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 10:50:32.906  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:32.906  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-22 10:50:32.916  2793  2793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7aaf57
,08-22 10:50:32.916  2793  2793 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 10:50:32.916  1015  1255 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 10:50:32.916  1015  1255 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-22 10:50:32.916  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:32.916  1015  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:32.916  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 10:50:32.936  1015  1027 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 10:50:32.946  2793  7754 D BluetoothSocket: bindListen(): myUserId = 0
08-22 10:50:32.946  2793  7754 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:32.946  2793  7754 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
08-22 10:50:32.946  2793  7754 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 10:50:32.946  2793  7754 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 10:50:32.946  2793  7754 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3733d8f9
,08-22 10:50:32.946  2793  7754 D BluetoothSocket: channel: 12
,08-22 10:50:32.946  2793  7754 I BtOppRfcommListener: Accept thread started.
,08-22 10:50:33.436  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:33.436  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:33.436  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:33.436  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:33.436  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:33.436  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:33.436  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:33.436  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:33.436  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:33.446  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-22 10:50:33.446  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f1b2ebe added. We now have 8 listener(s)
,08-22 10:50:33.446  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:33.446  1015  1211 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 10:50:33.446  1015  1211 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-22 10:50:33.446  1015  1211 D SecContentProvider2: mCursor = null
,08-22 10:50:33.446  1015  1211 D WifiService: setWifiEnabled: false pid=6869, uid=10170
,08-22 10:50:33.446  1015  1211 D SettingsProvider: name = wifi_on
,08-22 10:50:33.456  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:33.456  1015  1459 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 10:50:33.456  1015  1459 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-22 10:50:33.456  1015  1459 D SecContentProvider2: mCursor = null
08-22 10:50:33.456   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 10:50:33.456  1015  1459 D WifiService: setWifiEnabled: true pid=6869, uid=10170
,08-22 10:50:33.456  1015  1459 W ActivityManager: Permission Denial: getCurrentUser() from pid=6869, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-22 10:50:33.456  1015  1459 W WifiService: Failed getting userId using ActivityManagerNative
08-22 10:50:33.456  1015  1459 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6869, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 10:50:33.456  1015  1459 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 10:50:33.456  1015  1459 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 10:50:33.456  1015  1459 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 10:50:33.456  1015  1459 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 10:50:33.456  1015  1459 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 10:50:33.456  1015  1459 D SettingsProvider: name = wifi_on
,08-22 10:50:33.466   287   287 E SMD     : DCD OFF
,08-22 10:50:33.466  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-22 10:50:33.786  1015  1043 D Tethering: interfaceAdded wlan0
,08-22 10:50:33.796  1015  1128 E Tethering: No numeric data
,08-22 10:50:33.796  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-22 10:50:33.796  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 10:50:33.796  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 10:50:33.806  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 10:50:33.806  1015  1128 D Tethering: clearTetheredNotification(),
08-22 10:50:33.806  1015  1128 D Tethering: InitialState.processMessage what=4
,08-22 10:50:33.806  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-22 10:50:33.806  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:33.806  1015  1128 E Tethering: No numeric data
08-22 10:50:33.806  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 10:50:33.806  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:33.806  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 10:50:33.806  1175  1175 D HotspotTile: updateTetherState():false, false
,08-22 10:50:33.816  1015  1043 D Tethering: interfaceAdded p2p0
,08-22 10:50:33.816  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring,
08-22 10:50:33.816  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 10:50:33.816  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 10:50:33.816  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-22 10:50:33.816  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 10:50:33.816  1015  1128 D Tethering: clearTetheredNotification()
,08-22 10:50:33.826   277   985 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-22 10:50:33.826  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 10:50:33.826   277   985 D SoftapController: Softap fwReload - Ok
08-22 10:50:33.826  1175  1175 D HotspotTile: updateTetherState():false, false
08-22 10:50:33.826  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:33.826  1015  1122 V NetworkStats: performPollLocked() took 18ms
,08-22 10:50:33.826  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:33.826  1015  1122 V NetworkStats: performPollLocked(flags=0x1),
08-22 10:50:33.826  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:33.826  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:33.826   277   985 D CommandListener: Setting iface cfg
08-22 10:50:33.826  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-22 10:50:33.826   277   985 D CommandListener: Trying to bring down wlan0
08-22 10:50:33.826  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 10:50:33.826   277   985 D CommandListener: Clearing all IP addresses on wlan0
,08-22 10:50:33.836  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:33.836  1015  1122 V NetworkStats: performPollLocked() took 6ms
,08-22 10:50:33.836  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-22 10:50:33.836  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:33.836  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-22 10:50:33.886  7765  7765 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-22 10:50:33.886  7765  7765 I wpa_supplicant: Successfully initialized wpa_supplicant
08-22 10:50:33.886  7765  7765 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,08-22 10:50:33.896  7765  7765 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-22 10:50:33.896   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7765
08-22 10:50:33.896   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-22 10:50:33.896  7765  7765 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-22 10:50:33.896  7765  7765 I wpa_supplicant: ssSupport state is = 1
,08-22 10:50:33.896  7765  7765 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-22 10:50:33.896  7765  7765 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-22 10:50:33.896   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7765
08-22 10:50:33.896   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106,
,08-22 10:50:33.936  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-22 10:50:33.956  4558  4558 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 10:50:33.956  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 10:50:33.956  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:33.956  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 10:50:33.956  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:33.956  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:33.956  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:33.956  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:33.956  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:33.956  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:33.956  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-22 10:50:33.956  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-22 10:50:33.956  1175  1175 D HotspotTile: onReceive : 2, 0
08-22 10:50:33.956  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:33.966  1015  1467 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,08-22 10:50:33.966  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:33.966  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 10:50:33.966  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:33.966  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 10:50:33.966  1628  1628 I Hs20UtilService: Starting #19
08-22 10:50:33.966  1628  1657 I Hs20UtilService: Message received 5011
,08-22 10:50:33.966  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 10:50:33.966  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 10:50:33.966  7081  7081 D SecurityLogAgent: StateMachine : Current State = 1
08-22 10:50:33.966  7081  7081 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 10:50:34.066   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-22 10:50:34.066  7765  7765 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-22 10:50:34.116  7765  7765 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-22 10:50:34.116  7765  7765 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-22 10:50:34.126  7765  7765 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-22 10:50:34.126   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7765
08-22 10:50:34.126   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-22 10:50:34.126  7765  7765 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-22 10:50:34.126  7765  7765 I wpa_supplicant: ssSupport state is = 1
08-22 10:50:34.126  7765  7765 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-22 10:50:34.126  7765  7765 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 10:50:34.126  7765  7765 E wpa_supplicant: SIM READ ERROR
08-22 10:50:34.126  7765  7765 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 10:50:34.126  7765  7765 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 10:50:34.126  7765  7765 E wpa_supplicant: SIM READ ERROR
,08-22 10:50:34.126  7765  7765 I wpa_supplicant: Blacklist: Clear (all) 
08-22 10:50:34.126  7765  7765 I wpa_supplicant: wpa_default_ap_write_once
08-22 10:50:34.126  7765  7765 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 10:50:34.126  7765  7765 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 10:50:34.126  7765  7765 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-22 10:50:34.126  7765  7765 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 10:50:34.126  7765  7765 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 10:50:34.126  7765  7765 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-22 10:50:34.126  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:34.136  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:34.126  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 10:50:34.206  7765  7765 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-22 10:50:34.396  7765  7765 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-22 10:50:34.396  7765  7765 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-22 10:50:34.406  7765  7765 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-22 10:50:34.406   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7765
08-22 10:50:34.406   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-22 10:50:34.406  7765  7765 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-22 10:50:34.406  7765  7765 I wpa_supplicant: ssSupport state is = 1
08-22 10:50:34.406  7765  7765 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-22 10:50:34.416  7765  7765 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-22 10:50:34.426  7765  7765 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-22 10:50:34.426   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7765
08-22 10:50:34.426   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-22 10:50:34.426  7765  7765 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-22 10:50:34.426  7765  7765 I wpa_supplicant: ssSupport state is = 1,
08-22 10:50:34.426  7765  7765 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 10:50:34.426  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-22 10:50:34.426  7765  7765 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 10:50:34.426  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 10:50:34.426  7765  7765 E wpa_supplicant: SIM READ ERROR
,08-22 10:50:34.426  7765  7765 I wpa_supplicant: wpa_default_ap_write_once
08-22 10:50:34.426  7765  7765 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 10:50:34.426  7765  7765 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-22 10:50:34.426  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 10:50:34.426  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-22 10:50:34.426  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 10:50:34.426  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 10:50:34.456   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 10:50:34.516  7765  7765 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-22 10:50:34.516  7765  7765 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-22 10:50:34.596  7765  7765 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-22 10:50:34.596  7765  7765 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-22 10:50:34.596  7765  7765 I wpa_supplicant: Skip scan - bUseNetwork false
,08-22 10:50:34.606  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-22 10:50:34.606  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-22 10:50:34.606  7765  7765 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-22 10:50:34.616  7765  7765 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-22 10:50:34.616  7765  7765 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 10:50:34.616  7765  7765 E wpa_supplicant: SIM READ ERROR,
08-22 10:50:34.616  7765  7765 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 10:50:34.636  7765  7765 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-22 10:50:34.646  7765  7765 I wpa_supplicant: Skip scan - bUseNetwork false
,08-22 10:50:34.646  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-22 10:50:34.656  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:34.656  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:34.656  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:34.656  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:34.656  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:34.656  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:34.656  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 10:50:34.656  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:34.656  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-22 10:50:34.656  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 10:50:34.656  1175  1762 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 10:50:34.656  1175  1175 D HotspotTile: onReceive : 3, 0
,08-22 10:50:34.656  4558  4558 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 10:50:34.666  1015  1502 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-22 10:50:34.666  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 10:50:34.666  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:34.666  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:34.666  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:34.666  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:34.666  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:34.666  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:34.666  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:34.666  6869  6869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:34.666  1015  1502 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:34.666  1015  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:34.666  1015  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 10:50:34.666  1015  1125 E WifiConfigStore: Not a HS20
,08-22 10:50:34.666  1628  1628 I Hs20UtilService: Starting #20
08-22 10:50:34.666  1628  1657 I Hs20UtilService: Message received 5011
,08-22 10:50:34.666  6869  6869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:34.676  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-22 10:50:34.676  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-22 10:50:34.676  7765  7765 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-22 10:50:34.676  7765  7765 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-22 10:50:34.676  7765  7765 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 10:50:34.676  7765  7765 I wpa_supplicant: P2P: Current p2p state = IDLE
08-22 10:50:34.676  7765  7765 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-22 10:50:34.676  7765  7765 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-22 10:50:34.676  7765  7765 I wpa_supplicant: First Scan Start
08-22 10:50:34.676  7765  7765 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-22 10:50:34.676  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-22 10:50:34.676  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 10:50:34.676  1015  1125 I WifiNative-HAL: startHal
,08-22 10:50:34.676  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9e6f488c
08-22 10:50:34.676  1015  1125 I WifiNative-HAL: Could not start hal
,08-22 10:50:34.676  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 10:50:34.676  7081  7081 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 10:50:34.676  7081  7081 D SecurityLogAgent: StateMachine : Current State = 1
08-22 10:50:34.676  7081  7081 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 10:50:34.686  7237  7237 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 10:50:34.686  1015  1125 E WifiNative-wlan0: do suspend true
,08-22 10:50:34.686  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-22 10:50:34.686   277   985 D CommandListener: Setting iface cfg
08-22 10:50:34.686   277   985 D CommandListener: Trying to bring up p2p0
,08-22 10:50:34.686  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 10:50:34.686  1015  1124 D WifiP2pService: P2pEnablingState
,08-22 10:50:34.686  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-22 10:50:34.686  1015  1124 D WifiP2pService: P2p socket connection successful
,08-22 10:50:34.686  1015  1124 D WifiP2pService: P2pEnabledState
,08-22 10:50:34.696  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-22 10:50:34.696  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-22 10:50:34.696  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-22 10:50:34.696  1015  1148 I WifiNative-HAL: startHal
08-22 10:50:34.696  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x98fd19bc
08-22 10:50:34.696  1015  1148 I WifiNative-HAL: Could not start hal
08-22 10:50:34.696  1015  1148 E WifiScanningService: could not start HAL
,08-22 10:50:34.696  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-22 10:50:34.696  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 10:50:34.696  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-22 10:50:34.696  1015  1015 D RttService: SCAN_AVAILABLE : 3
,08-22 10:50:34.696  1015  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 10:50:34.696  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 10:50:34.696  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-22 10:50:34.696  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-22 10:50:34.696  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-22 10:50:34.696  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-22 10:50:34.696  7765  7765 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 10:50:34.696  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-22 10:50:34.696  7765  7765 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 10:50:34.706  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
,08-22 10:50:34.706  7765  7765 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-22 10:50:34.706  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-22 10:50:34.706  1015  1125 E WifiStateMachine: Failed to set frequency band 0
08-22 10:50:34.706  1015  1046 D WifiDisplayController: disconnect,
08-22 10:50:34.706  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 10:50:34.706  1015  1046 D WifiDisplayController: updateConnection
08-22 10:50:34.706  1015  1125 D SecContentProvider2: mCursor = null
08-22 10:50:34.706  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-22 10:50:34.706  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 10:50:34.706  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
08-22 10:50:34.706  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-22 10:50:34.706  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 10:50:34.706  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 10:50:34.706  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 10:50:34.706  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 10:50:34.706  1015  1124 D WifiP2pService: DeviceAddress: 0a:75:42
,08-22 10:50:34.706  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 10:50:34.706  1015  1125 D SecContentProvider2: mCursor = null
,08-22 10:50:34.716  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-22 10:50:34.716  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 10:50:34.716  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-22 10:50:34.716  1015  1378 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 10:50:34.716  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 10:50:34.716  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  secondary type: null
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  wps: 0
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  grpcapab: 0
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  devcapab: 0
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  status: 3
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  wfdInfo: null
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-22 10:50:34.716  1015  1046 D WifiDisplayController:  SConnectInfo : null
,08-22 10:50:34.716  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 10:50:34.716  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 10:50:34.716  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:34.716  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 10:50:34.716  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 10:50:34.716  7651  7651 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 10:50:34.716  7651  7651 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-22 10:50:34.716  7651  7651 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 10:50:34.726  7277  7277 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,08-22 10:50:34.736  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-22 10:50:34.736  1015  1124 D WifiP2pService: InactiveState
,08-22 10:50:34.736  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-22 10:50:34.736  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 10:50:34.736  7765  7765 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 10:50:34.736  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-22 10:50:34.736  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 10:50:34.796  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-22 10:50:34.796  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 10:50:34.796  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-22 10:50:35.456   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 10:50:35.476  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:35.476  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:35.476  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:35.476  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:35.476  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:35.476  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:35.476  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:35.476  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:35.476  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 10:50:35.486  6869  6947 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-22 10:50:35.486  6869  6947 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-22 10:50:35.486  6869  6947 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1c08659d Bundle[{}]
08-22 10:50:35.486  6869  6947 I io.jxcore.node.LifeCycleMonitor: start: OK
08-22 10:50:35.486  6869  6947 I io.jxcore.node.LifeCycleMonitor: stop: OK,
08-22 10:50:35.486  6869  6947 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-22 10:50:35.486  6869  6947 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 10:50:35.486  6869  6947 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-22 10:50:35.486  6869  6947 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
,08-22 10:50:35.496  6869  6947 I System.out: Running OutgoingSocketThread
,08-22 10:50:35.496  6869  7775 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1335)
,08-22 10:50:35.506  6869  7775 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57995
,08-22 10:50:35.506  6869  7775 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-22 10:50:35.916  7765  7765 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
,08-22 10:50:35.926  7765  7765 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-22 10:50:35.926  1015  7771 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
08-22 10:50:35.926  7765  7765 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-22 10:50:35.926  7765  7765 I wpa_supplicant: Trying to associate with  'G700'
,08-22 10:50:35.926  7765  7765 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-22 10:50:35.926  7765  7765 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-22 10:50:35.946  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 10:50:35.946  1015  1125 D SecContentProvider2: mCursor = null
,08-22 10:50:36.036  7765  7765 E wpa_supplicant: Cmd 35605 not handled
,08-22 10:50:36.036  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:36.036  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:36.036  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:36.036  7765  7765 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-22 10:50:36.036  7765  7765 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-22 10:50:36.036  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 10:50:36.036  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:36.036  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:36.036  7765  7765 I wpa_supplicant: Associated with F4.99.3E,
,08-22 10:50:36.036  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 10:50:36.036  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 10:50:36.036  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 10:50:36.036  7765  7765 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 10:50:36.036  7765  7765 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-22 10:50:36.036  7765  7765 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-22 10:50:36.046  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-22 10:50:36.046  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-22 10:50:36.046  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-22 10:50:36.046  1015  1128 E Tethering: No numeric data
,08-22 10:50:36.046  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-22 10:50:36.046  1015  1128 D Tethering: clearTetheredNotification()
,08-22 10:50:36.046  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:36.046  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-22 10:50:36.046  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-22 10:50:36.046  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 10:50:36.046  1015  1125 D SecContentProvider2: mCursor = null
08-22 10:50:36.046  1175  1175 D HotspotTile: updateTetherState():false, false
,08-22 10:50:36.046  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:36.056  1015  1122 V NetworkStats: performPollLocked() took 5ms
08-22 10:50:36.046  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 10:50:36.056  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:36.056  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:36.056  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:36.056  7765  7765 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 10:50:36.056  7765  7765 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-22 10:50:36.056  7765  7765 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-22 10:50:36.056  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 10:50:36.056  7765  7765 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-22 10:50:36.056  1015  1125 D SecContentProvider2: mCursor = null
,08-22 10:50:36.056  7765  7765 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 10:50:36.056  7765  7765 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-22 10:50:36.056  7765  7765 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-22 10:50:36.066  7765  7765 I wpa_supplicant: Blacklist: Clear (temp) 
,08-22 10:50:36.066  7765  7765 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-22 10:50:36.066  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 10:50:36.066  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 10:50:36.066  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-22 10:50:36.066  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50],
,08-22 10:50:36.066  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-22 10:50:36.066  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-22 10:50:36.066  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-22 10:50:36.066  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-22 10:50:36.066  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-22 10:50:36.076  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 10:50:36.076  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 10:50:36.076  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:36.076  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:36.076  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:36.076  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:36.076  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:36.086  1015  2016 V SAMP_SPCM_test: CSC File load.. 
,08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application,
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
,08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location,
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-22 10:50:36.096  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time,
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security,
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location,
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings,
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-22 10:50:36.136  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account,
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-22 10:50:36.146  1015  1378 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-22 10:50:36.146  1015  1378 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account,
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email,
08-22 10:50:36.156  1015  2016 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-22 10:50:36.156  1015  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-22 10:50:36.156  1015  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-22 10:50:36.156  1015  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-22 10:50:36.156  1015  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-22 10:50:36.146  1015  2016 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-22 10:50:36.146  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 10:50:36.156  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:36.156  1015  1378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:36.156  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 10:50:36.156  1628  1628 I Hs20UtilService: Starting #21
08-22 10:50:36.156  1628  1657 I Hs20UtilService: Message received 5007
,08-22 10:50:36.176  7778  7778 E Zygote  : MountEmulatedStorage()
,08-22 10:50:36.176  7778  7778 E Zygote  : v2
08-22 10:50:36.176  7778  7778 I libpersona: KNOX_SDCARD checking this for 1000
08-22 10:50:36.176  7778  7778 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:36.176  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:36.176  1015  2016 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7778 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 10:50:36.176  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 10:50:36.176  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 10:50:36.176  7778  7778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:36.176  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 10:50:36.186  7778  7778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-22 10:50:36.186  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 10:50:36.186  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:36.186  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 10:50:36.186  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 10:50:36.186  7778  7778 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:36.196   277   985 D CommandListener: Setting iface cfg
,08-22 10:50:36.196  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 3
08-22 10:50:36.196  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 10:50:36.196  1015  1125 D SecContentProvider2: mCursor = null
,08-22 10:50:36.216  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 10:50:36.216  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:36.216  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:36.216  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:36.216  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:36.216  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:36.216  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:36.216  7778  7778 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:50:36.216  1015  1125 E WifiNative-wlan0: do suspend false
,08-22 10:50:36.216  7778  7778 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:36.216  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 10:50:36.216  1015  1125 D SecContentProvider2: mCursor = null
,08-22 10:50:36.226  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
08-22 10:50:36.226  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 10:50:36.226  7778  7778 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 10:50:36.266  1015  2016 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
08-22 10:50:36.266  1015  1015 I ActivityManager: Killing 7329:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-22 10:50:36.436  7795  7795 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-22 10:50:36.436  7795  7795 I dhcpcd  : version 5.5.6 starting
,08-22 10:50:36.446  7795  7795 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-22 10:50:36.456   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 10:50:36.466   287   287 E SMD     : DCD OFF,
,08-22 10:50:36.486  7795  7795 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-22 10:50:36.486  7795  7795 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-22 10:50:36.486  7795  7795 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-22 10:50:36.486  7795  7795 I dhcpcd  : bssid match,
08-22 10:50:36.486  7795  7795 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-22 10:50:36.496  6869  6947 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1336),
08-22 10:50:36.496  6869  6947 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1336)
,08-22 10:50:36.506  6869  6947 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1341)
08-22 10:50:36.506  6869  6947 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-22 10:50:36.506  6869  6947 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1342)
08-22 10:50:36.506  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-22 10:50:36.506  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc4fb1f added. We now have 2 listener(s)
,08-22 10:50:36.506  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-22 10:50:36.506  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:50:36.506  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:36.506  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:36.516  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205c8e6c added. We now have 9 listener(s)
08-22 10:50:36.516  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:36.516  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:36.516  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:36.516  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:36.516  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:36.516  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:36.516  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:36.516  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:36.516  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:36.516  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:36.516  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:36.526  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:36.526  6869  6947 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:50:36.526  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:36.526  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd778ca added. We now have 3 listener(s)
,08-22 10:50:36.526  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:36.526  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:36.526  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 10:50:36.526  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:36.526  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 10:50:36.526  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:36.526  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc82a3b added. We now have 10 listener(s)
,08-22 10:50:36.526  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:36.536  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:36.536  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:36.536  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:36.536  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:36.536  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:36.536  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc4fb1f removed from the list
08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:36.536  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205c8e6c removed from the list
08-22 10:50:36.536  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 10:50:36.536  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:36.536  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.536  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:36.536  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205c8e6c not in the list
08-22 10:50:36.536  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.536  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:36.536  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc82a3b removed from the list,
08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:36.536  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.536  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 10:50:36.536  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd778ca removed from the list
08-22 10:50:36.536  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:36.536  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25ba2558 added. We now have 2 listener(s)
08-22 10:50:36.536  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-22 10:50:36.536  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:36.536  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 10:50:36.536  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:36.536  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2e6b1 added. We now have 9 listener(s)
08-22 10:50:36.536  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:36.536  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:36.546  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:36.546  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:36.546  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:36.546  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:36.546  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:36.546  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:36.546  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:36.546  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:36.546  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:36.546  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:36.546  6869  6947 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:50:36.546  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:36.546  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3052f17 added. We now have 3 listener(s)
,08-22 10:50:36.556  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-22 10:50:36.556  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:36.556  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 10:50:36.556  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:36.556  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:36.556  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:36.556  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20583f04 added. We now have 10 listener(s)
,08-22 10:50:36.556  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-22 10:50:36.556  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-22 10:50:36.556  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:36.556  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 10:50:36.556  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:36.556  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 10:50:36.556  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-22 10:50:36.566  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-22 10:50:36.566  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 10:50:36.566  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-22 10:50:36.566  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 10:50:36.566  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 10:50:36.576  2793  2809 D BtGatt.GattService: registerClient() - UUID=da9ee0c5-722a-4993-a1e2-166193a6a6da,
,08-22 10:50:36.596  7795  7795 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-22 10:50:36.616  2793  2856 D BtGatt.GattService: onClientRegistered() - UUID=da9ee0c5-722a-4993-a1e2-166193a6a6da, clientIf=6
,08-22 10:50:36.616  6869  6881 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 10:50:36.616  2793  7719 D BtGatt.GattService: start scan with filters
,08-22 10:50:36.616  2793  3034 D BtGatt.ScanManager: handling starting scan
,08-22 10:50:36.626  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 10:50:36.626  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 10:50:36.626  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:36.626  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 10:50:36.626  2793  2856 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 10:50:36.626  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.626  2793  3034 D BtGatt.ScanManager: allow scan with filters
,08-22 10:50:36.626  2793  3034 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-22 10:50:36.626  2793  3034 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-22 10:50:36.626  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 10:50:36.626  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.636  2793  3034 D BtGatt.ScanManager: Starting BLE batch scan,
08-22 10:50:36.636  2793  3034 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,08-22 10:50:36.636  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:36.636  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 10:50:36.636  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:36.636  2793  2856 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-22 10:50:36.636  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.636  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 10:50:36.636  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 10:50:36.636  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.646  6869  6947 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-22 10:50:36.646  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 10:50:36.646  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-22 10:50:36.646  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:36.646  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-22 10:50:36.646  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 10:50:36.646  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 10:50:36.646  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:36.646  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 10:50:36.646  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 10:50:36.646  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 10:50:36.656  2793  2803 D BtGatt.GattService: stopScan() - queue size =1
08-22 10:50:36.656  2793  3034 D BtGatt.ScanManager: filter size is 1
08-22 10:50:36.656  2793  3034 D BtGatt.ScanManager: delete FilterIndex - 6
,08-22 10:50:36.656  2793  7166 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-22 10:50:36.656  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 10:50:36.656  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 10:50:36.656  2793  3034 D BtGatt.ScanManager: stopping BLe Batch,
08-22 10:50:36.656  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 10:50:36.656  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 10:50:36.656  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 10:50:36.656  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:36.656  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 10:50:36.656  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 10:50:36.656  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 10:50:36.656  2793  3034 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-22 10:50:36.656  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:36.666  2793  2856 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-22 10:50:36.666  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.666  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 10:50:36.666  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-22 10:50:36.666  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 10:50:36.666  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:36.666  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 10:50:36.666  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 10:50:36.666  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:36.676  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:36.676  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 10:50:36.676  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 10:50:36.676  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 10:50:36.676  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:36.676  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:36.676  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:36.676  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25ba2558 removed from the list
,08-22 10:50:36.676  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:36.676  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2e6b1 removed from the list
08-22 10:50:36.676  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:36.676  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:36.676  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.676  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:36.676  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 10:50:36.686  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 10:50:36.686  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:36.686  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2e6b1 not in the list
,08-22 10:50:36.686  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.686  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:36.686  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 10:50:36.686  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:36.686  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:36.686  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20583f04 removed from the list
08-22 10:50:36.686  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:36.686  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.686  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:36.686  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:36.686  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3052f17 removed from the list
,08-22 10:50:36.686  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 10:50:36.686  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@359c4770 added. We now have 2 listener(s)
,08-22 10:50:36.686  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 10:50:36.686  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:50:36.696  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 10:50:36.696  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:36.696  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21eebae9 added. We now have 9 listener(s)
,08-22 10:50:36.696  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:36.696  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:36.696  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:36.706  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:36.706  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:36.706  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:36.706  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:36.706  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:36.706  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:36.706  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:36.706  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:36.706  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:36.706  6869  6947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:36.706  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:36.706  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:36.706  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 10:50:36.706  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34a8ea0f added. We now have 3 listener(s)
,08-22 10:50:36.716  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 10:50:36.716  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:50:36.716  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 10:50:36.716  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:36.716  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39d66a9c added. We now have 10 listener(s)
,08-22 10:50:36.716  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:36.716  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 10:50:36.716  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 10:50:36.716  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:36.716  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 10:50:36.716  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:36.716  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 10:50:36.716  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 10:50:36.726  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 10:50:36.726  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 10:50:36.726  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 10:50:36.726  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 10:50:36.726  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 10:50:36.736  2793  7166 D BtGatt.GattService: registerClient() - UUID=f143eadd-8a26-44f4-a0f0-0dbfe7befeb9,
08-22 10:50:36.736  7795  7795 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-22 10:50:36.776  2793  2856 D BtGatt.GattService: onClientRegistered() - UUID=f143eadd-8a26-44f4-a0f0-0dbfe7befeb9, clientIf=6,
08-22 10:50:36.776  6869  6881 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 10:50:36.786  2793  2857 D BtGatt.GattService: start scan with filters,
08-22 10:50:36.786  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 10:50:36.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 10:50:36.786  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:36.786  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 10:50:36.786  2793  3034 D BtGatt.ScanManager: handling starting scan
,08-22 10:50:36.786  2793  2856 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 10:50:36.786  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.786  2793  3034 D BtGatt.ScanManager: allow scan with filters
08-22 10:50:36.786  2793  3034 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 10:50:36.786  2793  3034 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-22 10:50:36.786  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:36.786  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 10:50:36.786  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:36.796  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-22 10:50:36.796  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 10:50:36.796  2793  3034 D BtGatt.ScanManager: Starting BLE batch scan
08-22 10:50:36.796  2793  3034 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 10:50:36.796  2793  2856 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-22 10:50:36.796  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.796  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-22 10:50:36.796  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-22 10:50:36.796  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.806  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 10:50:36.806  6869  6947 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-22 10:50:36.806  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:36.806  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:36.806  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 10:50:36.806  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:36.806  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.806  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 10:50:36.806  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 10:50:36.806  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@359c4770 removed from the list
08-22 10:50:36.806  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:36.806  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21eebae9 removed from the list
08-22 10:50:36.806  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:36.806  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:36.806  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.806  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 10:50:36.806  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.806  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:36.806  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 10:50:36.806  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:36.806  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:36.806  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21eebae9 not in the list
08-22 10:50:36.806  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 10:50:36.816  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:36.816  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:36.816  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-22 10:50:36.816  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 10:50:36.816  2793  7216 D BtGatt.GattService: stopScan() - queue size =1
,08-22 10:50:36.816  2793  3034 D BtGatt.ScanManager: filter size is 1
,08-22 10:50:36.816  2793  3034 D BtGatt.ScanManager: delete FilterIndex - 7
08-22 10:50:36.816  2793  2803 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 10:50:36.816  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 10:50:36.816  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 10:50:36.816  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 10:50:36.816  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:36.816  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 10:50:36.816  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:36.816  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 10:50:36.816  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 10:50:36.816  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 10:50:36.816  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:36.816  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 10:50:36.816  2793  3034 D BtGatt.ScanManager: stopping BLe Batch
08-22 10:50:36.816  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:36.826  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 10:50:36.826  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.826  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:36.826  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:36.826  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:36.826  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39d66a9c removed from the list
08-22 10:50:36.826  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:36.826  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.826  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:36.826  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:36.826  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34a8ea0f removed from the list
08-22 10:50:36.826  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:36.826  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@142d9488 added. We now have 2 listener(s)
,08-22 10:50:36.826  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:36.826  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:36.826  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:36.826  2793  3034 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 10:50:36.836  2793  2856 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 10:50:36.836  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.836  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-22 10:50:36.836  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:36.836  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:36.836  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:36.836  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d9de21 added. We now have 9 listener(s)
08-22 10:50:36.836  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:36.836  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:36.836  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:36.836  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:36.836  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:36.836  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:36.836  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:36.836  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:36.836  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:36.836  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:36.836  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:36.846  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:36.846  6869  6947 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:50:36.846  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:36.846  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aba0c07 added. We now have 3 listener(s),
,08-22 10:50:36.846  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-22 10:50:36.846  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:36.846  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:36.846  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:36.846  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@354b7134 added. We now have 10 listener(s)
08-22 10:50:36.846  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:36.846  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 10:50:36.846  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:36.846  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 10:50:36.846  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:36.846  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:36.846  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 10:50:36.846  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:36.856  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 10:50:36.866  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 10:50:36.866  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 10:50:36.866  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 10:50:36.866  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 10:50:36.866  6869  6947 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 10:50:36.876  2793  2857 D BtGatt.GattService: registerClient() - UUID=83ece263-5a79-4367-906b-2f0479a941ca
,08-22 10:50:36.916  2793  2856 D BtGatt.GattService: onClientRegistered() - UUID=83ece263-5a79-4367-906b-2f0479a941ca, clientIf=6
08-22 10:50:36.916  6869  6881 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 10:50:36.916  2793  2809 D BtGatt.GattService: start scan with filters
08-22 10:50:36.916  2793  3034 D BtGatt.ScanManager: handling starting scan
08-22 10:50:36.916  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 10:50:36.916  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 10:50:36.916  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:36.916  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 10:50:36.916  2793  2856 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 10:50:36.916  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 10:50:36.916  2793  3034 D BtGatt.ScanManager: allow scan with filters
08-22 10:50:36.916  2793  3034 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 10:50:36.916  2793  3034 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6,
,08-22 10:50:36.916  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 10:50:36.916  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:36.916  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-22 10:50:36.916  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-22 10:50:36.916  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 10:50:36.916  2793  3034 D BtGatt.ScanManager: Starting BLE batch scan
08-22 10:50:36.916  2793  3034 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 10:50:36.926  2793  2856 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 10:50:36.926  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.926  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 10:50:36.926  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-22 10:50:36.926  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.936  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:36.936  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:36.936  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:36.936  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:36.936  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@142d9488 removed from the list
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:36.936  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d9de21 removed from the list
08-22 10:50:36.936  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:36.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:36.936  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 10:50:36.936  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:36.936  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d9de21 not in the list
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 10:50:36.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:36.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 10:50:36.936  2793  2857 D BtGatt.GattService: stopScan() - queue size =1
,08-22 10:50:36.936  2793  3034 D BtGatt.ScanManager: filter size is 1
08-22 10:50:36.936  2793  3034 D BtGatt.ScanManager: delete FilterIndex - 8
,08-22 10:50:36.936  2793  2809 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 10:50:36.936  2793  2856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 10:50:36.936  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.936  2793  3034 D BtGatt.ScanManager: stopping BLe Batch
,08-22 10:50:36.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 10:50:36.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 10:50:36.936  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:36.936  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 10:50:36.946  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:36.946  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 10:50:36.946  6869  6947 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:36.946  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 10:50:36.946  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:36.946  2793  2856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 10:50:36.946  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.946  2793  3034 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 10:50:36.946  2793  2856 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-22 10:50:36.946  2793  2856 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 10:50:36.946  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 10:50:36.946  6869  6869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 10:50:36.946  6869  6869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:36.946  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:36.946  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 10:50:36.946  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:36.946  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@354b7134 removed from the list
08-22 10:50:36.946  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:36.946  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:36.946  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:36.946  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:36.946  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aba0c07 removed from the list
,08-22 10:50:36.956  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 10:50:36.956  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc86ca0 added. We now have 2 listener(s)
,08-22 10:50:36.956  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 10:50:36.956  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:50:36.956  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 10:50:36.956  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:36.956  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262f3059 added. We now have 9 listener(s)
08-22 10:50:36.956  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:36.956  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:36.956  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:36.966  6869  6947 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:36.966  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:36.966  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:36.966  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:36.966  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:36.966  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:36.966  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:36.966  6869  6947 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:36.966  6869  6947 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:36.966  6869  6947 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:36.966  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:36.966  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a9e74ff added. We now have 3 listener(s)
,08-22 10:50:36.966  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:36.966  6869  6869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:36.966  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 10:50:36.976  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:50:36.976  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 10:50:36.976  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:36.976  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2957b2cc added. We now have 10 listener(s)
08-22 10:50:36.976  6869  6947 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:36.976  6869  6947 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:36.976  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 10:50:36.976  6869  6947 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:36.976  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.976  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:36.976  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc86ca0 removed from the list
,08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:36.976  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262f3059 removed from the list
08-22 10:50:36.976  6869  6947 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:36.976  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:36.976  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.976  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:36.976  6869  6947 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@262f3059 not in the list
08-22 10:50:36.976  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.976  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:36.976  6869  6947 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2957b2cc removed from the list
08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 10:50:36.976  6869  6947 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:36.976  6869  6947 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:36.976  6869  6947 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:36.976  6869  6947 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a9e74ff removed from the list
,08-22 10:50:36.976  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-22 10:50:36.976  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-22 10:50:36.976  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-22 10:50:36.976  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 10:50:36.976  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-22 10:50:36.976  6869  6947 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 10:50:36.986  6869  7826 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1349, name: My test thread name)
,08-22 10:50:36.986  6869  7826 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1349, thread name: My test thread name)
,08-22 10:50:36.986  6869  7826 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1349, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 10:50:36.986  6869  7827 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1351, name: My test thread name)
,08-22 10:50:36.986  6869  7827 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1351, thread name: My test thread name)
08-22 10:50:36.986  6869  7827 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1351, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 10:50:36.996  6869  6947 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-22 10:50:36.996  6869  6947 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-22 10:50:36.996  6869  6947 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-22 10:50:36.996  6869  6947 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-22 10:50:36.996  6869  6947 D com.test.thalitest.ThaliTestRunner: Total duration: 23243 ms
,08-22 10:50:36.996  6869  6947 I jxcore-log: Total number of executed tests:  80
08-22 10:50:36.996  6869  6947 I jxcore-log: 
,08-22 10:50:36.996  6869  6947 I jxcore-log: Number of passed tests:  80
08-22 10:50:36.996  6869  6947 I jxcore-log: 
08-22 10:50:36.996  6869  6947 I jxcore-log: Number of failed tests:  0
08-22 10:50:36.996  6869  6947 I jxcore-log: 
,08-22 10:50:36.996  6869  6947 I jxcore-log: Number of ignored tests:  0
08-22 10:50:36.996  6869  6947 I jxcore-log: 
,08-22 10:50:36.996  6869  6947 I jxcore-log: Total duration:  23243
08-22 10:50:36.996  6869  6947 I jxcore-log: 
,08-22 10:50:36.996  6869  6947 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-22 10:50:36.996  6869  6947 I jxcore-log: 
,08-22 10:50:37.006  6869  6869 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68),
,08-22 10:50:37.006  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:37.006  6869  6947 I jxcore-log: 
08-22 10:50:37.006  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:37.006  6869  6947 I jxcore-log: 
08-22 10:50:37.016  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:37.016  6869  6947 I jxcore-log: 
,08-22 10:50:37.016  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:37.016  6869  6947 I jxcore-log: 
,08-22 10:50:37.016  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:37.016  6869  6947 I jxcore-log: 
,08-22 10:50:37.016  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:37.016  6869  6947 I jxcore-log: 
,08-22 10:50:37.016  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:37.016  6869  6947 I jxcore-log: 
,08-22 10:50:37.026  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:37.026  6869  6947 I jxcore-log: 
,08-22 10:50:37.026  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:37.026  6869  6947 I jxcore-log: 
,08-22 10:50:37.026  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 10:50:37.026  6869  6947 I jxcore-log: 
,08-22 10:50:37.026  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 10:50:37.026  6869  6947 I jxcore-log: 
,08-22 10:50:37.026  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 10:50:37.026  6869  6947 I jxcore-log: 
,08-22 10:50:37.036  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:37.036  6869  6947 I jxcore-log: 
,08-22 10:50:37.036  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-22 10:50:37.036  6869  6947 I jxcore-log: 
,08-22 10:50:37.036  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 10:50:37.036  6869  6947 I jxcore-log: 
,08-22 10:50:37.036  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 10:50:37.036  6869  6947 I jxcore-log: 
,08-22 10:50:37.036  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:37.036  6869  6947 I jxcore-log: 
08-22 10:50:37.036  1015  1125 E WifiNative-wlan0: do suspend true
,08-22 10:50:37.036  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:37.036  6869  6947 I jxcore-log: 
08-22 10:50:37.036  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 10:50:37.036  6869  6947 I jxcore-log: 
,08-22 10:50:37.036  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 10:50:37.036  6869  6947 I jxcore-log: 
,08-22 10:50:37.036  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:37.036  6869  6947 I jxcore-log: 
,08-22 10:50:37.036  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:37.036  6869  6947 I jxcore-log: 
,08-22 10:50:37.046  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:37.046  6869  6947 I jxcore-log: 
,08-22 10:50:37.046  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:37.046  6869  6947 I jxcore-log: 
,08-22 10:50:37.046  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:37.046  6869  6947 I jxcore-log: 
,08-22 10:50:37.046  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:37.046  6869  6947 I jxcore-log: 
,08-22 10:50:37.046  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:37.046  6869  6947 I jxcore-log: 
,08-22 10:50:37.066  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
08-22 10:50:37.066  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 10:50:37.066  1015  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-22 10:50:37.066  1015  1125 E WifiStateMachine: VerifyingLinkState enter
,08-22 10:50:37.076  1015  1127 E ConnectivityService: updateNetworkInfo(),
,08-22 10:50:37.076  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-22 10:50:37.076  1015  1127 D ConnectivityService: Adding iface wlan0 to network 504
,08-22 10:50:37.086  1015  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
08-22 10:50:37.086  1015  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-22 10:50:37.086  1015  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-22 10:50:37.086  1015  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-22 10:50:37.086  1015  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-22 10:50:37.086  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 10:50:37.086  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:37.086  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:37.086  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.086  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:37.086  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-22 10:50:37.086  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-22 10:50:37.106  1015  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 10:50:37.106  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 10:50:37.106  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:37.106  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 10:50:37.116  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 10:50:37.116  1628  1628 I Hs20UtilService: Starting #22
08-22 10:50:37.116  1628  1657 I Hs20UtilService: Message received 5007
08-22 10:50:37.116  1015  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-22 10:50:37.126  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 10:50:37.126  4558  4558 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-22 10:50:37.126  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 10:50:37.136  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:37.136  1015  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-22 10:50:37.136  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:37.136  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.136  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.136  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.136  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.136  1015  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-22 10:50:37.136  1015  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-22 10:50:37.146  1015  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0,
08-22 10:50:37.146  1015  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-22 10:50:37.146  1015  1127 D ConnectivityService: LTETest block dns file not exists
08-22 10:50:37.146  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 10:50:37.156  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:37.156  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:37.156  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 10:50:37.156  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.156  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.156  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.156  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:37.156  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-22 10:50:37.156  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 10:50:37.156  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 10:50:37.156  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-22 10:50:37.156  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-22 10:50:37.166  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.166  1015  1127 V NetworkStats: updateIfacesLocked()
08-22 10:50:37.166  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:37.166  1015  1467 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 10:50:37.166  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 10:50:37.166  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-22 10:50:37.166  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.166  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 10:50:37.166  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:37.166  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 10:50:37.176  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:37.176  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:37.176  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 10:50:37.176  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.176  6869  6869 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 10:50:37.176  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.176  1015  1127 V NetworkStats: performPollLocked() took 6ms
08-22 10:50:37.176  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 10:50:37.176  6869  6947 I jxcore-log: 
,08-22 10:50:37.176  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.176  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:37.186  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:37.186  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-22 10:50:37.186  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 10:50:37.186  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 10:50:37.186  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.186  1015  1127 V NetworkStats: updateIfacesLocked()
,08-22 10:50:37.186  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.186  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-22 10:50:37.186  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.186  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:37.186  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 10:50:37.186  1628  1628 I Hs20UtilService: Starting #23
,08-22 10:50:37.196  1628  1657 I Hs20UtilService: Message received 5007
,08-22 10:50:37.196  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 10:50:37.196  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.196  1015  1127 V NetworkStats: performPollLocked() took 9ms
08-22 10:50:37.196  4558  4558 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 10:50:37.196  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 10:50:37.196  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.196  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:37.196  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 10:50:37.196  4558  4558 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 10:50:37.196  1015  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-22 10:50:37.196  4558  4558 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 10:50:37.196  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-22 10:50:37.196  1015  7777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-22 10:50:37.196  1015  7777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
,08-22 10:50:37.196  1015  7777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-22 10:50:37.196  4558  4623 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 10:50:37.196  1015  7777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-22 10:50:37.196  1015  7777 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 10:50:37.196  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-22 10:50:37.196  1015  1127 D ConnectivityService:    accepting network in place of null,
08-22 10:50:37.196  1462  1462 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-22 10:50:37.196  1462  1462 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 10:50:37.196  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-22 10:50:37.206   277   981 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 10:50:37.206   277   981 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-22 10:50:37.206  1015  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-22 10:50:37.206  1015  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-22 10:50:37.206  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-22 10:50:37.206  1015  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-22 10:50:37.206  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-22 10:50:37.206  1015  1128 D Tethering: MasterInitialState.processMessage what=3
08-22 10:50:37.206  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-22 10:50:37.206  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-22 10:50:37.206  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.206  1015  1122 V NetworkStats: updateIfacesLocked()
08-22 10:50:37.206  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-22 10:50:37.206  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:37.206  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 10:50:37.206  1175  1741 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
,08-22 10:50:37.216  1015  1122 V NetworkStats: performPollLocked() took 5ms
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-22 10:50:37.216  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-22 10:50:37.216  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.216  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.216  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.216  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.216  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 10:50:37.216  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 10:50:37.216  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.216  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:37.226  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.226  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:37.226  1015  1378 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 10:50:37.226  1015  1378 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-22 10:50:37.226  1015  1378 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:37.226  1015  1378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:37.226  1015  1378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 10:50:37.226  1628  1628 I Hs20UtilService: Starting #24
,08-22 10:50:37.226  1628  1657 I Hs20UtilService: Message received 5007
08-22 10:50:37.226  4558  4558 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 10:50:37.226  4558  4558 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-22 10:50:37.236  1015  1028 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
08-22 10:50:37.236  1015  3418 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-22 10:50:37.236  1015  3418 D SecContentProvider2: mCursor = null
08-22 10:50:37.236  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravity,
08-22 10:50:37.236  1015  1027 D SecContentProvider2: mCursor = null
08-22 10:50:37.236  1015  1467 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-22 10:50:37.236  1015  1467 D SecContentProvider2: mCursor = null
,08-22 10:50:37.236  1015  1378 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-22 10:50:37.236  1015  1378 D SecContentProvider2: mCursor = null
,08-22 10:50:37.246  1015  1255 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-22 10:50:37.246  1015  1255 D SecContentProvider2: mCursor = null
,08-22 10:50:37.246  1015  1479 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
08-22 10:50:37.246  1015  1479 D SecContentProvider2: mCursor = null
,08-22 10:50:37.266   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-22 10:50:37.276  1015  3418 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,08-22 10:50:37.286  1175  1175 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-22 10:50:37.296  1015  7777 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-22 10:50:37.326  6869  6869 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-22 10:50:37.336  7828  7828 D AndroidRuntime: 
08-22 10:50:37.336  7828  7828 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-22 10:50:37.336  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 10:50:37.336  6869  6947 I jxcore-log: 
,08-22 10:50:37.336  7828  7828 D AndroidRuntime: CheckJNI is OFF
,08-22 10:50:37.336  7828  7828 D AndroidRuntime: readGMSProperty: start
08-22 10:50:37.336  7828  7828 D AndroidRuntime: readGMSProperty: already setted!!
08-22 10:50:37.336  7828  7828 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 10:50:37.336  7828  7828 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 10:50:37.336  7828  7828 D AndroidRuntime: readGMSProperty: end
08-22 10:50:37.336  7828  7828 D AndroidRuntime: addProductProperty: start
,08-22 10:50:37.346  1015  7777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 08:50:37 GMT], X-Android-Received-Millis=[1471855837351], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471855837327]}
,08-22 10:50:37.346  1015  7777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-22 10:50:37.346  1015  7777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-22 10:50:37.346  1015  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-22 10:50:37.346  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-22 10:50:37.346  1015  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-22 10:50:37.346  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-22 10:50:37.346  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-22 10:50:37.346  1175  1741 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-22 10:50:37.346  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
,08-22 10:50:37.346  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-22 10:50:37.346  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 10:50:37.346  1175  1175 D StatusBar.NetworkController: updateDataNetType()
,08-22 10:50:37.356  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-22 10:50:37.356  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-22 10:50:37.356  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-22 10:50:37.356  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-22 10:50:37.356  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-22 10:50:37.356  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-22 10:50:37.356  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 10:50:37.356  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 10:50:37.356  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.356  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:37.356  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 10:50:37.356  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 10:50:37.446  6869  6869 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-22 10:50:37.446  6869  6947 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 10:50:37.446  6869  6947 I jxcore-log: 
,08-22 10:50:37.456  7828  7828 E AffinityControl: AffinityControl: registerfunction enter,
,08-22 10:50:37.456   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-22 10:50:37.486  7828  7828 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-22 10:50:37.496  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-22 10:50:37.496  1015  1028 D PackageManager: START PACKAGE DELETE: observer{959838461}
08-22 10:50:37.496  1015  1028 D PackageManager: pkg{<packageName>}
08-22 10:50:37.496  1015  1028 D PackageManager: user{0}
,08-22 10:50:37.496  1015  1028 D PackageManager: caller{2000}
08-22 10:50:37.496  1015  1028 D PackageManager: flags{2}
08-22 10:50:37.496  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-22 10:50:37.496  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-22 10:50:37.496  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-22 10:50:37.496  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-22 10:50:37.506  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-22 10:50:37.506  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-22 10:50:37.506  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-22 10:50:37.506  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-22 10:50:37.506  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-22 10:50:37.506  1015  1055 D PackageManager: !@killApplicatoin: 10170, uninstall pkg,
,08-22 10:50:37.506  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-22 10:50:37.506  1015  1041 I ActivityManager: Killing 6869:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-22 10:50:37.516  1015  1041 I ActivityManager:   Force finishing activity ActivityRecord{3fbf91e4 u0 com.test.thalitest/.MainActivity t163}
08-22 10:50:37.516  1015  1041 D InputDispatcher: Focus left window: 6869
08-22 10:50:37.516   257   444 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-22 10:50:37.516   257   440 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-22 10:50:37.556  1015  1041 D InputDispatcher: Focused application released
08-22 10:50:37.556  1015  1046 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-22 10:50:37.556  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 10:50:37.556  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 10:50:37.666  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-22 10:50:37.676  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-22 10:50:37.706  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:37.716  6286  6286 I art     : Explicit concurrent mark sweep GC freed 2081(119KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 790us total 33.176ms
,08-22 10:50:37.716  1015  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 10:50:37.716  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-22 10:50:37.726  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-22 10:50:37.726  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-22 10:50:37.726  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-22 10:50:37.726  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-22 10:50:37.726  1860  1860 E SamsungIME: mOCRHelper is null
,08-22 10:50:37.736  1742  1920 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 10:50:37.746  1015  1122 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-22 10:50:37.746  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.746  1015  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-22 10:50:37.746  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 10:50:37.746  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 10:50:37.746  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-22 10:50:37.756  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-22 10:50:37.756  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 10:50:37.756  1015  1122 V NetworkStats: performPollLocked() took 5ms
,08-22 10:50:37.776  2927  2927 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 22 10:50:37 GMT+02:00 2016
,08-22 10:50:37.796  1015  1438 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-22 10:50:37.796  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-22 10:50:37.796  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:37.796  1015  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:37.796  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-22 10:50:37.806  1450  1450 D PersonaManager: isKioskContainerExistOnDevice,
,08-22 10:50:37.816  1450  1450 D RegisteredServicesCache: empty dynamic service
,08-22 10:50:37.816  2927  2927 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-22 10:50:37.816  1015  1502 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
,08-22 10:50:37.816  1015  1502 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-22 10:50:37.816  1015  1502 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-22 10:50:37.826  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.826  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.826  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.826  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:37.826  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-22 10:50:37.826  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-22 10:50:37.836  1015  1040 W TextServicesManagerService: no available spell checker services found
,08-22 10:50:37.836  7845  7845 E Zygote  : MountEmulatedStorage()
08-22 10:50:37.836  7845  7845 E Zygote  : v2
08-22 10:50:37.836  7845  7845 I libpersona: KNOX_SDCARD checking this for 10090
08-22 10:50:37.836  7845  7845 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:37.836  7845  7845 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:37.836  7845  7845 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:37.846  7845  7845 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-22 10:50:37.846  1015  1502 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7845 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-22 10:50:37.876  1450  1450 D RegisteredComponentCache: Collect Tech packages for Knox
,08-22 10:50:37.876  1450  1450 D PersonaManager: isKioskContainerExistOnDevice
,08-22 10:50:37.876  2927  2927 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-22 10:50:37.876  2927  2927 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 10:50:37.876  7845  7845 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:37.876  7845  7845 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:37.886  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-22 10:50:37.886  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-22 10:50:37.886  2927  2927 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 10:50:37.886  1015  3418 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-22 10:50:37.886  1015  3418 D SecContentProvider2: mCursor = null
,08-22 10:50:37.886  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 10:50:37.906  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-22 10:50:37.906  1015  1015 V EnterpriseBillingPolicy: uID is 10170
08-22 10:50:37.906  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 10:50:37.906  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-22 10:50:37.906  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:37.906  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 10:50:37.906  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 10:50:37.906  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 10:50:37.906  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 10:50:37.906  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-22 10:50:37.906  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 10:50:37.906  2927  7847 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-22 10:50:37.916  1015  1015 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-22 10:50:37.916  2927  7847 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-22 10:50:37.916  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 10:50:37.926  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-22 10:50:37.926  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.926  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.926  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.926  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:37.926  2927  7847 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-22 10:50:37.936  1015  1055 I art     : Explicit concurrent mark sweep GC freed 78192(4MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 8.311ms total 251.016ms
,08-22 10:50:37.936  1015  1025 I art     : WaitForGcToComplete blocked for 150.810ms for cause HeapTrim
,08-22 10:50:37.936  7861  7861 E Zygote  : MountEmulatedStorage()
,08-22 10:50:37.936  7861  7861 I libpersona: KNOX_SDCARD checking this for 10052
08-22 10:50:37.936  7861  7861 E Zygote  : v2
08-22 10:50:37.936  7861  7861 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:37.946  7861  7861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:37.946  7861  7861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:37.946  7861  7861 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-22 10:50:37.946  2927  7847 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-22 10:50:37.946  1015  1041 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7861 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-22 10:50:37.946  7845  7845 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-22 10:50:37.956  7845  7845 D elm:15121: ELMEngine.ELMEngine( context ).
,08-22 10:50:37.956  7845  7845 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-22 10:50:37.956  1015  1502 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-22 10:50:37.966  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.966  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.966  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.966  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:37.976  7861  7861 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-22 10:50:37.976  7861  7861 D ActivityThread: Added TimaKeyStore provider,
,08-22 10:50:37.986  7876  7876 E Zygote  : MountEmulatedStorage()
08-22 10:50:37.986  7876  7876 E Zygote  : v2
08-22 10:50:37.986  7876  7876 I libpersona: KNOX_SDCARD checking this for 10032
08-22 10:50:37.986  7876  7876 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:37.986  7876  7876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:37.986  1015  1502 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7876 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 10:50:37.996  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,08-22 10:50:37.996  7876  7876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:37.996  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.996  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.996  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:37.996  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:37.996  7876  7876 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-22 10:50:38.006  1015  1055 D PackageManager: delete codoeFile: ,
,08-22 10:50:38.006  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 10:50:38.006  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 10:50:38.016  7889  7889 E Zygote  : MountEmulatedStorage()
08-22 10:50:38.016  7889  7889 I libpersona: KNOX_SDCARD checking this for 10098
08-22 10:50:38.016  7889  7889 E Zygote  : v2
08-22 10:50:38.016  7889  7889 I libpersona: KNOX_SDCARD not a persona,
,08-22 10:50:38.016  7889  7889 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:38.026  1015  1041 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7889 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-22 10:50:38.026  7889  7889 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:38.026  1015  3418 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-22 10:50:38.026  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.026  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-22 10:50:38.026  1015  3418 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:38.026  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,08-22 10:50:38.026  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-22 10:50:38.026  7889  7889 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:38.036  1015  1055 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-22 10:50:38.046  1015  1055 D PackageManager: result of delete: 1{959838461}
,08-22 10:50:38.046  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 10:50:38.046  1015  2872 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-22 10:50:38.046  7845  7845 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-22 10:50:38.046  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-22 10:50:38.046  1015  1015 V EnterpriseBillingPolicy: uID is 10170
08-22 10:50:38.046  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 10:50:38.046  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter,
08-22 10:50:38.056  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 10:50:38.056  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 10:50:38.056  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 10:50:38.056  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-22 10:50:38.056  7876  7876 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:50:38.056  7889  7889 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:50:38.056  7876  7876 D ActivityThread: Added TimaKeyStore provider
08-22 10:50:38.056  7889  7889 D ActivityThread: Added TimaKeyStore provider
08-22 10:50:38.056  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 10:50:38.056  7845  7845 D elm:15121: ElmAgentService : onCreate()
08-22 10:50:38.056  7845  7906 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-22 10:50:38.066  7845  7906 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-22 10:50:38.066  7845  7906 D elm:15121: MDMBridge.getInstance()
08-22 10:50:38.066  7845  7906 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 10:50:38.066  7828  7828 D AndroidRuntime: Shutting down VM
,08-22 10:50:38.066  7845  7906 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 10:50:38.066  2927  7847 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-22 10:50:38.076  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-22 10:50:38.086  7845  7845 D elm:15121: ElmAgentService : onDestroy().
,08-22 10:50:38.086  1015  1255 I ActivityManager: Killing 7345:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-22 10:50:38.096  2927  7847 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-22 10:50:38.106  1683  1683 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-22 10:50:38.106  1683  1683 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-22 10:50:38.116  1015  1378 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
08-22 10:50:38.116  2927  7847 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-22 10:50:38.116  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.116  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.116  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.116  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.126  7909  7909 E Zygote  : MountEmulatedStorage()
,08-22 10:50:38.126  7909  7909 E Zygote  : v2
08-22 10:50:38.126  7909  7909 I libpersona: KNOX_SDCARD checking this for 1000
08-22 10:50:38.126  7909  7909 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:38.126  7909  7909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:38.136  7909  7909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:38.136  7909  7909 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:38.146  1015  1378 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7909 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 10:50:38.146  1015  1378 I ActivityManager: Killing 7387:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-22 10:50:38.146  1015  1467 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-22 10:50:38.146  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,08-22 10:50:38.146  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-22 10:50:38.146  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.146  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 10:50:38.146  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-22 10:50:38.176  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 10:50:38.176  7909  7909 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:38.176  7909  7909 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:38.176  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 10:50:38.186  7876  7924 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-22 10:50:38.186  7876  7924 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-22 10:50:38.196  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 10:50:38.196  7360  7925 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-22 10:50:38.206  7876  7924 D SPPClientService: PushLog.txt file is not deleted.
08-22 10:50:38.206  7876  7924 D SPPClientService: PushLog.txt file is not deleted.
08-22 10:50:38.206  7876  7924 D SPPClientService: ============PushLog. stop!
,08-22 10:50:38.206  1015  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-22 10:50:38.206  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 10:50:38.206  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 10:50:38.206  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 10:50:38.206  2927  2927 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-22 10:50:38.206  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 10:50:38.216  1015  1438 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-22 10:50:38.216  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-22 10:50:38.216  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.216  1015  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.216  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-22 10:50:38.216  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 10:50:38.226  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 10:50:38.226  1015  3420 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-22 10:50:38.226  1015  3420 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-22 10:50:38.226  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 10:50:38.226  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 10:50:38.226  1015  3420 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.226  1015  3420 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.226  1015  3420 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-22 10:50:38.236  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 10:50:38.236  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 10:50:38.236  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 10:50:38.236  7360  7925 D AccountUtils: Clearing selected account for com.test.thalitest
,08-22 10:50:38.236  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 10:50:38.236  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 10:50:38.246  1015  3418 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,08-22 10:50:38.246  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-22 10:50:38.246  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 10:50:38.246  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.246  1015  3418 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:38.246  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-22 10:50:38.246  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-22 10:50:38.256  7170  7170 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-22 10:50:38.256  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-22 10:50:38.256  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:38.266  7828  7828 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 10:50:38.276  1015  1378 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-22 10:50:38.276  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.276  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.276  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.276  1015  1378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.286  7933  7933 E Zygote  : MountEmulatedStorage()
,08-22 10:50:38.286  7933  7933 I libpersona: KNOX_SDCARD checking this for 10039
08-22 10:50:38.286  7933  7933 E Zygote  : v2
08-22 10:50:38.286  7933  7933 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:38.296  7933  7933 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:38.296  7933  7933 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:38.296  7933  7933 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 10:50:38.296  1015  1378 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7933 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-22 10:50:38.306  1015  1459 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 10:50:38.306  1015  1459 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.306  1015  1459 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.306  1015  1459 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:38.306  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 10:50:38.316  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.316  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.316  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:38.316  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-22 10:50:38.316  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-22 10:50:38.326  1015  1485 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-22 10:50:38.326  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.326  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.326  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.326  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.336  7951  7951 E Zygote  : MountEmulatedStorage()
08-22 10:50:38.336  7951  7951 I libpersona: KNOX_SDCARD checking this for 1000
08-22 10:50:38.336  7951  7951 E Zygote  : v2
,08-22 10:50:38.336  7951  7951 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:38.336  7951  7951 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:38.336  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest},
08-22 10:50:38.336  1015  1055 D PackageManager: userId{-1}
08-22 10:50:38.336  1015  1055 D PackageManager: andCode{true}
,08-22 10:50:38.346  7951  7951 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:38.346  1015  1485 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7951 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 10:50:38.346  7951  7951 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:38.346  1015  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 10:50:38.346  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,08-22 10:50:38.346  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.346  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.346  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-22 10:50:38.356  7933  7933 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-22 10:50:38.356  7933  7933 D ActivityThread: Added TimaKeyStore provider
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-22 10:50:38.356  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false,
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
08-22 10:50:38.356  7778  7939 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,08-22 10:50:38.356  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
08-22 10:50:38.366  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.366  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.366  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.366  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.366  7951  7951 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:38.366  7951  7951 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:38.376  7360  7925 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-22 10:50:38.376  7965  7965 E Zygote  : MountEmulatedStorage()
08-22 10:50:38.376  7965  7965 E Zygote  : v2
08-22 10:50:38.376  7965  7965 I libpersona: KNOX_SDCARD checking this for 10003
08-22 10:50:38.376  7965  7965 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:38.376  7965  7965 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:38.376  1015  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7965 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-22 10:50:38.386  7965  7965 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-22 10:50:38.386  7965  7965 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:38.396  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-22 10:50:38.396  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
08-22 10:50:38.406  7170  7170 D BluetoothAdapter: cancelDiscovery
,08-22 10:50:38.406  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.406  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.406  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:38.416  1015  1255 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-22 10:50:38.416  7965  7965 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:38.416  2793  2857 D BluetoothAdapterProperties: mDiscovering is false
08-22 10:50:38.416  2793  2857 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
08-22 10:50:38.416  7965  7965 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:38.416  7170  7170 D BluetoothAdapter: cancelDiscovery = true
08-22 10:50:38.416  7170  7170 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-22 10:50:38.416  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.416  1015  1255 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.416  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:38.426  7933  7933 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-22 10:50:38.426  7933  7933 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 10:50:38.426  7933  7933 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 10:50:38.426  7933  7933 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-22 10:50:38.426  1015  1459 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-22 10:50:38.426  7933  7933 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-22 10:50:38.426  7933  7933 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 10:50:38.426  7933  7933 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-22 10:50:38.426  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-22 10:50:38.426  7170  7170 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 10:50:38.436  1015  3418 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 10:50:38.436  1015  3418 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,08-22 10:50:38.436  1015  3418 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.436  1015  3418 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.436  1015  3418 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 10:50:38.436  7360  7360 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-22 10:50:38.436  7360  7360 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
,08-22 10:50:38.476  7951  7951 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,08-22 10:50:38.476  1015  1255 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
,08-22 10:50:38.476  1015  1255 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,08-22 10:50:38.486  1015  1255 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.486  1015  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:38.486  1015  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,08-22 10:50:38.486  1015  1438 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-22 10:50:38.486  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.486  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.486  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.486  1015  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.506  7989  7989 E Zygote  : MountEmulatedStorage(),
08-22 10:50:38.506  7989  7989 I libpersona: KNOX_SDCARD checking this for 1000
08-22 10:50:38.506  7989  7989 E Zygote  : v2
,08-22 10:50:38.506  7989  7989 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:38.506  7989  7989 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:38.506  7989  7989 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:38.506  7989  7989 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:38.506  1015  1438 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7989 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 10:50:38.516  1015  1028 I ActivityManager: Killing 7420:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-22 10:50:38.536  7989  7989 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:38.536  7989  7989 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:38.536   303   303 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 31.816ms
,08-22 10:50:38.546  7360  7983 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,08-22 10:50:38.556  1015  1255 I ActivityManager: Killing 7442:com.android.chrome/u0a77 (adj 15): empty #21
,08-22 10:50:38.556   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 711us total 18.725ms
,08-22 10:50:38.556  1015  1255 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-22 10:50:38.566  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.566  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.566  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.566  1015  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.576  7360  7983 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,08-22 10:50:38.576   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 728us total 18.295ms
,08-22 10:50:38.586  7360  7983 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
08-22 10:50:38.586  7360  7983 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,08-22 10:50:38.596  7989  8006 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED,
08-22 10:50:38.596  1015  1255 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=8007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 10:50:38.596  1015  1255 I ActivityManager: Killing 7461:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,08-22 10:50:38.606  7778  7939 I art     : Explicit concurrent mark sweep GC freed 3811(208KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 4MB/6MB, paused 1.931ms total 177.855ms,
,08-22 10:50:38.606  1015  1438 D LocationManagerService: getProviders()=[passive, gps],
,08-22 10:50:38.606  8007  8007 E Zygote  : MountEmulatedStorage(),
08-22 10:50:38.606  8007  8007 E Zygote  : v2
,08-22 10:50:38.606  8007  8007 I libpersona: KNOX_SDCARD checking this for 1000
08-22 10:50:38.606  8007  8007 I libpersona: KNOX_SDCARD not a persona,
,08-22 10:50:38.616  8007  8007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 10:50:38.616  8007  8007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 10:50:38.616  8007  8007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:38.626  1015  1438 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-22 10:50:38.626  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,08-22 10:50:38.626  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.626  1015  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.626  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-22 10:50:38.626  7360  7983 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
08-22 10:50:38.626  7360  7983 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,08-22 10:50:38.636  2793  2854 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-22 10:50:38.646  7360  7983 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,08-22 10:50:38.646  1015  1485 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,08-22 10:50:38.646  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.646  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 10:50:38.646  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.656  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.656  8007  8007 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 10:50:38.656  7989  8006 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
08-22 10:50:38.656  8007  8007 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:38.666  7360  7983 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
08-22 10:50:38.666  7360  7983 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,08-22 10:50:38.676  7360  7983 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,08-22 10:50:38.676  7360  7983 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,08-22 10:50:38.676  7360  7983 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,08-22 10:50:38.676  7360  7983 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,08-22 10:50:38.686  8028  8028 E Zygote  : MountEmulatedStorage()
08-22 10:50:38.686  8028  8028 I libpersona: KNOX_SDCARD checking this for 10014
08-22 10:50:38.686  8028  8028 E Zygote  : v2
08-22 10:50:38.686  8028  8028 I libpersona: KNOX_SDCARD not a persona
08-22 10:50:38.686  8028  8028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 10:50:38.686  8028  8028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 10:50:38.686  1015  1485 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8028 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,08-22 10:50:38.696  8028  8028 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 10:50:38.706  1015  1438 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-22 10:50:38.706  1015  1438 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,08-22 10:50:38.706  1015  1438 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.706  1015  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 10:50:38.706  1015  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-22 10:50:38.706  7989  7989 D AcmsService: Enter Oncreate
,08-22 10:50:38.706  7989  7989 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 10:50:38.706  7989  7989 D AcmsService: creating AcmsCore
08-22 10:50:38.706  7989  7989 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-22 10:50:38.706  7989  7989 D AcmsCore: AcmsCore
,08-22 10:50:38.716  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-22 10:50:38.716  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,08-22 10:50:38.716  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 10:50:38.716  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 10:50:38.716  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-22 10:50:38.726  7593  7748 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-22 10:50:38.726  7593  7748 D BadgeProvider: sendNotify, [notify] : null
08-22 10:50:38.726  7593  7748 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-22 10:50:38.726  7593  7748 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-22 10:50:38.726  7593  7748 D BadgeProvider: update, [UpdateCount] : 1
,08-22 10:50:38.726  7989  7989 D AcmsCore: init
08-22 10:50:38.726  7989  7989 D AcmsCore: Looper handler is not null
08-22 10:50:38.726  8028  8028 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 10:50:38.726  7989  7989 D AcmsCore: Post to AcmsCoreHandler
08-22 10:50:38.726  7989  7989 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 10:50:38.726  7989  7989 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-22 10:50:38.726  7989  7989 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
08-22 10:50:38.726  7989  7989 D AcmsService: onStartCommand
08-22 10:50:38.726  7989  7989 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
08-22 10:50:38.726  7989  7989 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-22 10:50:38.726  7989  7989 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-22 10:50:38.726  7989  7989 D AcmsService: Incremented Counter Value : onStartCommand
08-22 10:50:38.736  8028  8028 D ActivityThread: Added TimaKeyStore provider
,08-22 10:50:38.746  7989  8045 D AcmsCertificateMngr: AcmsCertificateMngr
,08-22 10:50:38.746  1015  1211 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-22 10:50:38.756  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.756  7989  8045 D AcmsRevocationMngr: AcmsRevocationMngr
08-22 10:50:38.756  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.756  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.756  1015  1211 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 10:50:38.756  1486  1486 D Launcher.Model: reloadBadges entered.,
,08-22 10:50:38.776  1015  1211 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=8049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 10:50:38.776  8049  8049 E Zygote  : MountEmulatedStorage(),
,08-22 10:50:38.776  8049  8049 E Zygote  : v2,
08-22 10:50:38.776  8049  8049 I libpersona: KNOX_SDCARD checking this for 1000
,08-22 10:50:38.776  8049  8049 I libpersona: KNOX_SDCARD not a persona
,08-22 10:50:38.776  1015  1028 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,08-22 10:50:38.776  7989  7989 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,08-22 10:50:38.786  8049  8049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 10:50:38.786  8049  8049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 10:50:38.786  8049  8049 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 10:50:38.796  7989  7989 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,08-22 10:50:38.806  7989  7989 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:473)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:433)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3440)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.app.ActivityThread.access$2200(ActivityThread.java:181)
08-22 10:50:38.806  7989,  7989 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1580)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 10:50:38.806  7989  7989 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 10:50:38.806  7989  7989 D AndroidRuntime: Shutting down VM
,08-22 10:50:38.806  1015  1378 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-22 10:50:38.806  7989  7989 E AndroidRuntime: FATAL EXCEPTION: main
08-22 10:50:38.806  7989  7989 E AndroidRuntime: Process: ACMS.Process, PID: 7989
08-22 10:50:38.806  7989  7989 E AndroidRuntime: java.lang.RuntimeException: Unable to start service com.samsung.android.mirrorlink.acms.api.AcmsService@77a267b with Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService (has extras) }: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3457)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.app.ActivityThread.access$2200(ActivityThread.java:181)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1580)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: Caused by: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:473)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:433)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3440)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	... 9 more
08-22 10:50:38.8,06  7989  7989 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-22 10:50:38.806  7989  7989 E AndroidRuntime: 	... 20 more
08-22 10:50:38.806  7778  8004 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 10:50:38.806  7778  8004 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM usage_log WHERE strftime('%s','now', '-40 days')*1000 - start_time >= 0] disk I/O error
,08-22 10:50:38.806  7778  8004 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 10:50:38.806  7778  8004 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM running_service_log WHERE strftime('%s','now', '-40 days')*1000 - captured_time >= 0] disk I/O error
,08-22 10:50:38.806  7989  8045 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,08-22 10:50:38.806  7989  8045 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,08-22 10:50:38.806  7778  8004 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 10:50:38.806  7778  8004 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM noti_info WHERE strftime('%s','now', '-40 days')*1000 - posted_date >= 0] disk I/O error
,08-22 10:50:38.806  7989  8045 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5338)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2966)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1495)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:473)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:433)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:71)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:56)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:64)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.<init>(AcmsRevocationMngr.java:119)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.getAcmsRevocationMngr(AcmsRevocationMngr.java:129)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.<init>(AcmsCertificateMngr.java:94)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at com.samsung.android.mirror,link.acms.manager.AcmsCertificateMngr.getAcmsCertificateMngr(AcmsCertificateMngr.java:286)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at com.samsung.android.mirrorlink.acms.api.AcmsCore$AcmsHandler.handleMessage(AcmsCore.java:139)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 10:50:38.806  7989  8045 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 10:50:38.816  7989  8045 I Process : Sending signal. PID: 7989 SIG: 9
,08-22 10:50:38.816  1015  1211 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname ACMS.Process
,08-22 10:50:38.816  7933  7933 D NearbySource: Nearby Source Create!
,08-22 10:50:38.816  7933  7933 D NearbyContext: Nearby Context Create!

```
