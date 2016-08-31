#### Test 83084099807e426_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-31 16:50:39.280  5710  5890 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-31 16:50:39.290  1437  1465 D TP/SmsProvider: query,matched:26, calling pid = 5710
08-31 16:50:39.290  1437  1465 D TP/SmsProvider: match 26:Elapsed time : 0.796 ms
08-31 16:50:39.300  1437  1626 D TP/MmsSmsProvider: query,matched:6, calling pid = 5710
08-31 16:50:39.300  1437  1626 D TP/MmsSmsProvider: match 6:Elapsed time : 0.875 ms
08-31 16:50:39.310   287   287 E SMD     : DCD OFF
--------- beginning of system
08-31 16:50:39.320  1017  1540 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-31 16:50:39.320  1017  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.320  1017  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.320  1017  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.320  1017  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.330  1017  1540 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5945 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-31 16:50:39.340  5945  5945 E Zygote  : MountEmulatedStorage()
08-31 16:50:39.340  5945  5945 E Zygote  : v2
08-31 16:50:39.340  5945  5945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:50:39.340  5945  5945 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:50:39.340  5945  5945 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:50:39.340  5945  5945 I libpersona: KNOX_SDCARD checking this for 10023
08-31 16:50:39.340  5945  5945 I libpersona: KNOX_SDCARD not a persona
,08-31 16:50:39.360  5945  5945 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:39.360  5945  5945 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:39.370  1017  4263 I ActivityManager: Killing 5584:com.android.defcontainer/u0a3 (adj 15): empty #21
08-31 16:50:39.380  5725  5762 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-31 16:50:39.420  5945  5945 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-31 16:50:39.420  5922  5922 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-31 16:50:39.430  1017  1313 I ActivityManager: Killing 5365:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-31 16:50:39.430  1017  1056 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-31 16:50:39.430  1017  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-31 16:50:39.440  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.440  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.440  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.440  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.440  5710  5890 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-31 16:50:39.450  5962  5962 E Zygote  : MountEmulatedStorage()
08-31 16:50:39.450  5962  5962 I libpersona: KNOX_SDCARD checking this for 10003
08-31 16:50:39.450  5962  5962 E Zygote  : v2
08-31 16:50:39.450  5962  5962 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:39.450  5962  5962 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:50:39.450  5962  5962 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:50:39.460  5962  5962 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:50:39.470  1017  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5962 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-31 16:50:39.480  5962  5962 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:39.480  5962  5962 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:39.490  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-31 16:50:39.500  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-31 16:50:39.500  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-31 16:50:39.500  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-31 16:50:39.500  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-31 16:50:39.510  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-31 16:50:39.510  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-31 16:50:39.510  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-31 16:50:39.510  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-31 16:50:39.510  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-31 16:50:39.520  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-31 16:50:39.520  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-31 16:50:39.520  5945  5945 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-31 16:50:39.520   283   283 E installd: system dir 0 : /system/app/
08-31 16:50:39.520   283   283 E installd: system dir 1 : /system/priv-app/
08-31 16:50:39.520   283   283 E installd: system dir 2 : /vendor/app/
08-31 16:50:39.520   283   283 E installd: system dir 3 : /oem/app/
08-31 16:50:39.540  1017  1056 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-31 16:50:39.630  1017  1030 I ActivityManager: Killing 5624:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-31 16:50:39.630  5960  5960 D AndroidRuntime: 
08-31 16:50:39.630  5960  5960 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 16:50:39.640  5960  5960 D AndroidRuntime: CheckJNI is OFF
08-31 16:50:39.640  5960  5960 D AndroidRuntime: readGMSProperty: start
08-31 16:50:39.640  5960  5960 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:50:39.640  5960  5960 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:50:39.640  5960  5960 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:50:39.640  5960  5960 D AndroidRuntime: readGMSProperty: end
08-31 16:50:39.640  5960  5960 D AndroidRuntime: addProductProperty: start
08-31 16:50:39.660  5725  5762 I AcmsKeyStoreHelper: Key Store exist
08-31 16:50:39.660  5725  5762 I AcmsKeyStoreHelper: Hence loading the keystore file
08-31 16:50:39.660  1017  1466 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-31 16:50:39.670  1017  4263 I art     : Explicit concurrent mark sweep GC freed 146373(8MB) AllocSpace objects, 4(1912KB) LOS objects, 33% free, 22MB/34MB, paused 2.799ms total 166.860ms
08-31 16:50:39.770  5960  5960 E AffinityControl: AffinityControl: registerfunction enter
08-31 16:50:39.770  5725  5762 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-31 16:50:39.770  5725  5762 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-31 16:50:39.770  5725  5762 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-31 16:50:39.770  5725  5762 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-31 16:50:39.770  5725  5762 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-31 16:50:39.770  5725  5762 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-31 16:50:39.770  5725  5762 D AcmsCore: This is NOT a valid MirrorLink app
08-31 16:50:39.770  5725  5762 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-31 16:50:39.770  5725  5762 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-31 16:50:39.770  5725  5762 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-31 16:50:39.770  5725  5762 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-31 16:50:39.770  5725  5725 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-31 16:50:39.770  5725  5725 D AcmsService: Enter onDestroy
08-31 16:50:39.780  5725  5725 I AcmsService: cleanUp(): inside service clean up
08-31 16:50:39.780  5725  5725 D AcmsCore: AcmsCore: inside DeInit
08-31 16:50:39.780  5725  5725 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-31 16:50:39.780  5725  5725 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-31 16:50:39.780  5725  5725 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-31 16:50:39.780  5725  5725 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-31 16:50:39.780  5725  5725 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-31 16:50:39.780  1017  2716 D SSRM:n  : SIOP:: AP = 390
08-31 16:50:39.780  5725  5725 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-31 16:50:39.780  5725  5725 D AcmsService: killing acms process
08-31 16:50:39.780  5725  5725 I Process : Sending signal. PID: 5725 SIG: 9
08-31 16:50:39.800  5960  5960 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 16:50:39.810  1017  1313 E PersonaManagerService: inState():  stateMachine is null !!
08-31 16:50:39.810  1017  1313 I PersonaManagerService: PersonaId don't exist
08-31 16:50:39.810  1017  1313 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 16:50:39.820  1017  1313 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 16:50:39.840  1017  1313 W ActivityManager: mDVFSHelper.acquire()
08-31 16:50:39.840  1017  1313 D FocusedStackFrame: Set to : 0
08-31 16:50:39.850  5744  5814 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-31 16:50:39.850  5744  5814 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 16:50:39.850  5744  5814 I GAv4    :   adb logcat -s GAv4
08-31 16:50:39.860  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.860  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.860  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.860  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.860  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 16:50:39.860  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-31 16:50:39.870  5994  5994 E Zygote  : MountEmulatedStorage()
08-31 16:50:39.870  5994  5994 E Zygote  : v2
08-31 16:50:39.870  5994  5994 I libpersona: KNOX_SDCARD checking this for 10170
08-31 16:50:39.870  5994  5994 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:39.870  5994  5994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:50:39.880  1017  1313 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-31 16:50:39.880  1017  1313 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5994 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 16:50:39.880  1017  1313 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 16:50:39.880  1017  1313 D InputDispatcher: Focused application set to: xxxx
08-31 16:50:39.880  5994  5994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:50:39.880  1017  1313 D InputDispatcher: Focus left window: 1471
08-31 16:50:39.880  5960  5960 D AndroidRuntime: Shutting down VM
08-31 16:50:39.880  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 16:50:39.880  1017  1135 I ActivityManager: Process ACMS.Process (pid 5725)(adj 0) has died(55,777)
08-31 16:50:39.880  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 16:50:39.880   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
08-31 16:50:39.890  5994  5994 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 16:50:39.910  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 16:50:39.910  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:50:39.910  5744  5814 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-31 16:50:39.910  1017  1451 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-31 16:50:39.910  5994  5994 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:39.910  5994  5994 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:39.920  1017  1135 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-31 16:50:39.920  1017  1017 V ActivityManager: Display changed displayId=0
08-31 16:50:39.920  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 16:50:39.940  1017  1135 D PersonaManager: isKioskContainerExistOnDevice
08-31 16:50:39.950  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-31 16:50:39.960  5744  5814 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-31 16:50:39.990   257   447 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-31 16:50:40.000   257  5519 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-31 16:50:40.000  1787  3858 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-31 16:50:40.000  5744  5814 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-31 16:50:40.000  1471  1471 V ActivityThread: updateVisibility : ActivityRecord{bb1df29 token=android.os.BinderProxy@d1b8acb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-31 16:50:40.000  1471  1471 D Launcher: onTrimMemory. Level: 20
08-31 16:50:40.010  5744  6011 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-31 16:50:40.090  5960  5960 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 16:50:40.110  5994  5994 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-31 16:50:40.150  1787  3858 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-31 16:50:40.200  1787  3858 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-31 16:50:40.200  5994  5994 I cr.library_loader: Time to load native libraries: 14 ms (timestamps 2875-2889)
08-31 16:50:40.210  5994  5994 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 16:50:40.210  1017  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-31 16:50:40.210  1017  1540 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:50:40.210  1017  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:50:40.210  1017  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 16:50:40.250  5994  5994 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ee774e4}
08-31 16:50:40.260  5994  5994 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 16:50:40.260  5994  5994 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 16:50:40.310  5994  5994 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-31 16:50:40.320  5994  5994 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:40.320  5994  5994 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 16:50:40.380  5994  6020 W chromium: [WARNING:dns_config_service_posix.cc(298)] Failed to read DnsConfig.
08-31 16:50:40.380  5994  5994 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 16:50:40.380  5994  5994 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:50:40.380  5994  5994 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:50:40.380  5994  5994 I Adreno-EGL: Local Branch: 
08-31 16:50:40.380  5994  5994 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:50:40.380  5994  5994 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:50:40.380  5994  5994 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-31 16:50:40.400  1017  1312 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-31 16:50:40.400  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:40.400  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:40.400  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:40.400  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:40.410  6024  6024 E Zygote  : MountEmulatedStorage()
08-31 16:50:40.410  6024  6024 E Zygote  : v2
08-31 16:50:40.410  6024  6024 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:50:40.410  6024  6024 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:40.410  6024  6024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:50:40.420  1017  1312 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6024 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 16:50:40.420  1017  1312 I ActivityManager: Killing 4534:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-31 16:50:40.420  6024  6024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:50:40.420  6024  6024 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:50:40.440  6024  6024 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:40.440  6024  6024 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:40.440  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{bb5d61a u0 com.test.thalitest/.MainActivity t163}
08-31 16:50:40.460  5744  6019 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 16:50:40.460  5744  6019 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-31 16:50:40.460  6024  6024 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-31 16:50:40.470  6024  6024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-31 16:50:40.470  1017  1539 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-31 16:50:40.470  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-31 16:50:40.470  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:50:40.470  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:50:40.470  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-31 16:50:40.480  1017  1305 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-31 16:50:40.480  6024  6024 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-31 16:50:40.490  5744  6019 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-31 16:50:40.500  6024  6039 E FilterInstaller: installFilters
08-31 16:50:40.510  6024  6039 E FilterInstaller: There is no requred permission
08-31 16:50:40.520  1017  1029 I ActivityManager: Killing 5654:com.sec.spp.push/u0a32 (adj 15): empty #21
08-31 16:50:40.520  5994  5994 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 16:50:40.530  5994  5994 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-31 16:50:40.530  5994  5994 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-31 16:50:40.540  5994  5994 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-31 16:50:40.540  5994  5994 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-31 16:50:40.550  5744  6019 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-31 16:50:40.550  5744  6019 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33818d0f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-31 16:50:40.550  5744  6019 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-31 16:50:40.650  5994  5994 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:40.660  5994  5994 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 16:50:40.670  5994  5994 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 16:50:40.670  5994  5994 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-31 16:50:40.680  5994  5994 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-31 16:50:40.690  5994  5994 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:40.690  5994  5994 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:50:40.810  5994  6059 D OpenGLRenderer: Render dirty regions requested: true
,08-31 16:50:40.810  1017  4262 I ActivityManager: Killing 5637:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-31 16:50:40.820  1017  1539 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 16:50:40.820  1017  1539 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 16:50:40.820  1017  1539 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 16:50:40.820  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 16:50:40.820  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 16:50:40.820  5994  5994 V ActivityThread: updateVisibility : ActivityRecord{3b91657 token=android.os.BinderProxy@1eca2bf1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 16:50:40.820  5994  6045 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-31 16:50:40.830  5994  5994 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-31 16:50:40.830  5994  5994 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-31 16:50:40.840   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,08-31 16:50:40.860  1017  1470 D InputDispatcher: Focus entered window: 5994
,08-31 16:50:40.870  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 16:50:40.870  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:50:40.870  5994  5994 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-31 16:50:40.870  5994  6059 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 16:50:40.880  5994  6059 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-31 16:50:40.880  5994  6059 D OpenGLRenderer: Enabling debug mode 0
,08-31 16:50:40.910  1017  1305 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 16:50:40.910  1176  1176 D PanelView: There is/are notification(s) 
,08-31 16:50:40.920  1017  6065 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:50:40.930  1017  1047 I ActivityManager: Displayed Component not be shown by security: +988ms (total +1s73ms)
,08-31 16:50:40.930  1017  1047 W ActivityManager: mDVFSHelper.release()
,08-31 16:50:40.930  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bb5d61a u0 com.test.thalitest/.MainActivity t163} time:93616
,08-31 16:50:40.940  5994  5994 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-31 16:50:40.940  5994  5994 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1eca2bf1 time:93622
,08-31 16:50:40.940  1810  1810 I SamsungIME: getCurrentCandidateView
,08-31 16:50:40.950   257  5519 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
,08-31 16:50:40.960  5994  5994 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5994
,08-31 16:50:41.080  1810  1810 D SamsungIME: Dismiss ExpandCandiate
,08-31 16:50:41.110  5710  5710 I Mms/MmsApp:  start initViewCache mms
,08-31 16:50:41.110  5710  5710 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1887.451978
,08-31 16:50:41.110  5710  5710 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-31 16:50:41.150  5994  5994 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 16:50:41.210  5710  5724 W art     : Suspending all threads took: 8.229ms
,08-31 16:50:41.210  5710  5710 D AbsListView: Get MotionRecognitionManager
,08-31 16:50:41.210  1017  1451 D MotionRecognitionService:  ssp status : false
,08-31 16:50:41.220  5710  5710 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 106.872344
,08-31 16:50:41.250  1810  1810 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 16:50:41.250  5994  6063 D jxcore_app_log: JniHelper::setJavaVM(0xb84ec2b0), pthread_self() = -1196953952
,08-31 16:50:41.260  5994  6063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 16:50:41.260  5994  6063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 16:50:41.260  5994  6063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 16:50:41.260  5994  6063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 16:50:41.260  5994  6063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 16:50:41.260  5994  6063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2994f0ba added. We now have 1 listener(s)
,08-31 16:50:41.260  5994  6063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-31 16:50:41.260  5994  6063 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 16:50:41.270  5994  6063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 16:50:41.270  5994  6063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 16:50:41.270  5994  6063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38ecf361 added. We now have 1 listener(s)
,08-31 16:50:41.270  5994  6063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 16:50:41.280  5994  6063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 16:50:41.280  5994  6063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 16:50:41.280  5994  6063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-31 16:50:41.280  5994  6063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 16:50:41.280  5994  6063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 16:50:41.280  5994  6063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 16:50:41.280  5994  6063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-31 16:50:41.290  5994  6063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:50:41.290  5994  6063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:50:41.290  5994  6063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:41.290  5994  6063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:41.290  5994  6063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:41.290  5994  6063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:41.290  5994  6063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:41.290  5994  6063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:41.290  5994  6063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:50:41.290  5994  6063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 16:50:41.290  5994  6063 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 16:50:41.290  5994  6063 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 16:50:41.310  1810  1810 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 16:50:41.320  1810  1810 I SamsungIME: KeybaordView init() : load resources
,08-31 16:50:41.320  5710  5710 D Mms/BubbleViewCache: fillCache bubble = 1
,08-31 16:50:41.330  5994  5994 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,08-31 16:50:41.350  1810  1810 I SamsungIME: getCurrentKeyboard,
,08-31 16:50:41.350  1810  1810 I SamsungIME: getTextKeyboard
,08-31 16:50:41.370  1810  1810 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 16:50:41.940  5994  6072 W jxcore-log: Initializing JXcore engine
08-31 16:50:41.940  5994  6072 W jxcore-log: JXcore engine is ready
,08-31 16:50:41.940  1017  2733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:50:41.990  1912  1912 E audit   : type=1400 msg=audit(1472655041.990:203): avc:  denied  { ioctl } for  pid=6072 comm="Thread-1105" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 16:50:41.990  1912  1912 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:50:41.990  1912  1912 E audit   : type=1300 msg=audit(1472655041.990:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9eb4b8f8 items=0 ppid=302 ppcomm=main pid=6072 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1105" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-31 16:50:41.990  1912  1912 E audit   : type=1320 msg=audit(1472655041.990:203): 
,08-31 16:50:42.000  5994  6072 W jxcore-log: Starting JXcore engine
,08-31 16:50:42.110  5994  6072 W jxcore-log: Platform android
08-31 16:50:42.110  5994  6072 W jxcore-log: 
08-31 16:50:42.110  5994  6072 W jxcore-log: Process ARCH arm
08-31 16:50:42.110  5994  6072 W jxcore-log: 
,08-31 16:50:42.310   287   287 E SMD     : DCD OFF
,08-31 16:50:42.320  5994  6072 I jxcore-log: JXcore Cordova bridge is ready!
08-31 16:50:42.320  5994  6072 I jxcore-log: 
,08-31 16:50:42.320  5994  6072 W jxcore-log: JXcore engine is started
,08-31 16:50:42.320  5994  6063 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 16:50:42.320  5994  5994 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 16:50:43.210  1017  1539 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 16:50:43.210  1017  1539 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 16:50:43.210  1017  1539 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-31 16:50:43.210  1017  1539 D BatteryService: stay LED for charging
08-31 16:50:43.210  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:50:43.210  1017  1017 I MotionRecognitionService: Plugged
,08-31 16:50:43.210  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
08-31 16:50:43.210  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 16:50:43.210  1397  1397 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-31 16:50:43.210  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 16:50:43.210  1397  1397 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 16:50:43.240  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 16:50:43.240  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 16:50:43.240  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 16:50:44.210  1640  1640 I ConfigService: onDestroy
,08-31 16:50:44.520   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6f687c8
08-31 16:50:44.520   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-31 16:50:44.530   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-31 16:50:44.530   271   348 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1225358024)
,08-31 16:50:44.580   271   348 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
08-31 16:50:44.580   271   348 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-31 16:50:44.580   271   348 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1225358024) wakelock released: 1, error no: 0,
08-31 16:50:44.580   271   348 I rmt_storage: 
,08-31 16:50:44.590   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb6f687c8
,08-31 16:50:45.310   287   287 E SMD     : DCD OFF,
,08-31 16:50:48.310   287   287 E SMD     : DCD OFF
,08-31 16:50:49.590  1017  1056 D PackageManager: [MSG] MCS_UNBIND
,08-31 16:50:49.590  1017  1466 I ActivityManager: Killing 5670:com.samsung.helphub/1000 (adj 15): empty #21
,08-31 16:50:49.800  1017  2716 D SSRM:n  : SIOP:: AP = 370
,08-31 16:50:49.820  1017  1049 I PowerManagerService: [PWL] Off : 50s ago,
,08-31 16:50:49.860  1017  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 16:50:51.320   287   287 E SMD     : DCD OFF
,08-31 16:50:53.250  1017  1539 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 16:50:53.250  1017  1539 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4263, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-31 16:50:53.250  1017  1539 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 16:50:53.250  1017  1539 D BatteryService: stay LED for charging
,08-31 16:50:53.250  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:50:53.260  1017  1017 I MotionRecognitionService: Plugged
,08-31 16:50:53.260  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 16:50:53.260  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 16:50:53.260  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 16:50:53.260  1397  1397 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 16:50:53.260  1397  1397 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 16:50:53.290  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 16:50:53.290  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 16:50:53.290  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 16:50:53.290  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{19371962 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,08-31 16:50:54.120  1017  1095 V AlarmManager: waitForAlarm result :4
,08-31 16:50:54.120  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-31 16:50:54.320   287   287 E SMD     : DCD OFF
,08-31 16:50:54.350  5249  5361 D Finsky  : [934] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-31 16:50:54.350  5249  5249 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-31 16:50:55.210  1017  1297 E Watchdog: !@Sync 3
,08-31 16:50:55.470  5139  5139 D FactoryTest: Not factory mode
,08-31 16:50:55.470  5139  5139 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-31 16:50:55.470  5139  5139 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-31 16:50:55.470  5139  5139 D MTPRx   : still no open session command from host, so toast
,08-31 16:50:55.470  5139  5139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-31 16:50:55.470  5139  5139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-31 16:50:55.470  5139  5139 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:108156
,08-31 16:50:55.470  1017  1030 E PersonaManagerService: inState():  stateMachine is null !!
,08-31 16:50:55.470  1017  1030 I PersonaManagerService: PersonaId don't exist
08-31 16:50:55.470  1017  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-31 16:50:55.480  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-31 16:50:55.480  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:50:55.480  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:50:55.480  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-31 16:50:55.480  1017  1030 W ActivityManager: mDVFSHelper.acquire()
,08-31 16:50:55.500  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
,08-31 16:50:55.500  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 16:50:55.500  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-31 16:50:55.500  1017  1030 D InputDispatcher: Focused application set to: xxxx
,08-31 16:50:55.510  1017  1030 D InputDispatcher: Focus left window: 5994
,08-31 16:50:55.510  5139  5139 E MTPRx   : started activity for popup
,08-31 16:50:55.510  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 16:50:55.510  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 16:50:55.530  5139  5139 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-31 16:50:55.530  5139  5139 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-31 16:50:55.530  5139  5139 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-31 16:50:55.530  5139  5139 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 16:50:55.530  5139  5139 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 16:50:55.530  5139  5139 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 16:50:55.550  5139  5139 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-31 16:50:55.550  1017  1312 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-31 16:50:55.550  1017  1312 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 16:50:55.560  1017  1312 D InputDispatcher: Focused application set to: xxxx
,08-31 16:50:55.560  1017  1312 D InputDispatcher: Focus entered window: 5994
,08-31 16:50:55.560  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 16:50:55.560  1017  1466 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 16:50:55.560  1017  1466 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@a7c2f82 attribute=null, token = android.os.BinderProxy@19120907
,08-31 16:50:55.560  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 16:50:55.600  5139  5139 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-31 16:50:55.610  5139  5139 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-31 16:50:55.610  5139  5139 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-31 16:50:55.630  5994  5994 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 16:50:55.630  5994  5994 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-31 16:50:55.630  5994  5994 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 16:50:55.630  5994  5994 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-31 16:50:55.630  1017  1540 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 16:50:55.630  1017  1540 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 16:50:55.630  1017  1540 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 16:50:55.630  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 16:50:55.630  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 16:50:55.650  5994  5994 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 16:50:55.650  5994  5994 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-31 16:50:55.650  5994  5994 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@159643bd Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@28f4748, 16908290=android.view.AbsSavedState$1@28f4748}, android:focusedViewId=100}]}]
08-31 16:50:55.650  5994  5994 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-31 16:50:55.650  5994  5994 V ActivityThread: updateVisibility : ActivityRecord{3b91657 token=android.os.BinderProxy@1eca2bf1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-31 16:50:55.650  5994  5994 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 16:50:55.650  5994  5994 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-31 16:50:55.650  5994  5994 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1eca2bf1 time:108337
,08-31 16:50:55.650  1017  1451 D PersonaManager: isKioskContainerExistOnDevice
,08-31 16:50:56.320   312   312 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-31 16:50:56.320   312   312 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-31 16:50:57.320   287   287 E SMD     : DCD OFF
,08-31 16:50:58.490  1017  1042 W ActivityManager: mDVFSHelper.release(),
,08-31 16:50:59.820  1017  2716 D SSRM:n  : SIOP:: AP = 360
,08-31 16:50:59.990  1017  1095 V AlarmManager: waitForAlarm result :8,
,08-31 16:51:00.130  5994  6072 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-31 16:51:00.130  5994  6072 I jxcore-log: 
,08-31 16:51:00.140  5994  6072 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-31 16:51:00.140  5994  6072 I jxcore-log: 
,08-31 16:51:00.140  5994  6072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-31 16:51:00.140  5994  6072 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:51:00.140  5994  6072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:00.140  5994  6072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:51:00.140  5994  6072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:51:00.140  5994  6072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:51:00.140  5994  6072 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:00.140  5994  6072 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:00.140  5994  6072 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:51:00.140  5994  6072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:00.140  5994  6072 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:51:00.140  5994  6072 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 16:51:00.140  5994  6072 I jxcore-log: 
,08-31 16:51:00.140  5994  6072 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 16:51:00.140  5994  6072 I jxcore-log: 
,08-31 16:51:00.320   287   287 E SMD     : DCD OFF,
,08-31 16:51:00.610  5994  6072 I jxcore-log: Running unit tests,
08-31 16:51:00.610  5994  6072 I jxcore-log: 
08-31 16:51:00.610  5994  6072 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-31 16:51:00.610  5994  6072 I jxcore-log: Failed to execute UT.
08-31 16:51:00.610  5994  6072 I jxcore-log: 
,08-31 16:51:00.610  5994  6072 I jxcore-log: Unit Test app is loaded,
08-31 16:51:00.610  5994  6072 I jxcore-log: 
,08-31 16:51:00.620  5994  6072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 16:51:00.620  5994  6072 I jxcore-log: 
,08-31 16:51:00.620  5994  5994 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 16:51:00.630  1017  1539 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 16:51:00.630  1017  1539 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 16:51:00.630  1017  1539 D SecContentProvider2: mCursor = null
,08-31 16:51:00.640  1017  1539 D WifiService: setWifiEnabled: true pid=5994, uid=10170
,08-31 16:51:00.640  1017  1539 W ActivityManager: Permission Denial: getCurrentUser() from pid=5994, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:51:00.640  1017  1539 W WifiService: Failed getting userId using ActivityManagerNative
08-31 16:51:00.640  1017  1539 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5994, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:51:00.640  1017  1539 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 16:51:00.640  1017  1539 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 16:51:00.640  1017  1539 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 16:51:00.640  1017  1539 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 16:51:00.640  1017  1539 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 16:51:00.640  1017  1539 D SettingsProvider: name = wifi_on
,08-31 16:51:00.650  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 16:51:00.650  1017  1305 I WifiService: disconnect: pid=5994, uid=10170
,08-31 16:51:00.710  5994  6072 D BluetoothAdapter: enable()
,08-31 16:51:00.730  1017  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=5994, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:51:00.730  1017  1029 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 16:51:00.730  1017  1029 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5994, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:51:00.730  1017  1029 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 16:51:00.730  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 16:51:00.730  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 16:51:00.730  1017  1029 W BluetoothManagerService: ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 16:51:00.730  1017  1029 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 16:51:00.730  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:51:00.730  1017  1029 D SettingsProvider: name = bluetooth_on
08-31 16:51:00.730  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:51:00.740  5994  6072 I jxcore-log: My device name is: samsung-SM-A300FU,
08-31 16:51:00.740  5994  6072 I jxcore-log: 
08-31 16:51:00.740  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:51:00.740  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:51:00.750  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 16:51:00.770  2633  2692 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-31 16:51:00.770  2633  2692 D BluetoothAdapterProperties: Setting state to 11
,08-31 16:51:00.770  2633  2692 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 16:51:00.770  2633  2692 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:51:00.770  2633  2692 D BluetoothAdapterService: updateAdapterState state is 11
08-31 16:51:00.770  2633  2692 D BluetoothAdapterService: Autoconnection is available 
08-31 16:51:00.770  2633  2692 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-31 16:51:00.770  2633  2692 D BtConfig.SecureMode: isSecureModeOn:false
08-31 16:51:00.770  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 16:51:00.770  2633  2692 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-31 16:51:00.770  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 16:51:00.770  2633  2692 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 16:51:00.770  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 16:51:00.780  2633  2692 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 16:51:00.780  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 16:51:00.780  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:00.780  2633  2692 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,08-31 16:51:00.780  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
08-31 16:51:00.780  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 16:51:00.780  2633  2692 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 16:51:00.780  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 16:51:00.780  2633  2692 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 16:51:00.780  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 16:51:00.790  2633  2692 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 16:51:00.790  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 16:51:00.790  2633  2692 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-31 16:51:00.790  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 16:51:00.790  2633  2692 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:00.790  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 16:51:00.790  2633  2692 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:00.790  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 16:51:00.800  2633  2692 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 16:51:00.800  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 16:51:00.800  2633  2692 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-31 16:51:00.800  2633  2692 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-31 16:51:00.800  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 16:51:00.800  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 16:51:00.800  2633  2692 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 16:51:00.800  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 16:51:00.800  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:00.800  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-31 16:51:00.800  1810  1810 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 16:51:00.810  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:51:00.810  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 16:51:00.820  1017  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:00.820  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 16:51:00.820  5994  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:51:00.820  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:00.820  1017  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:00.820  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:00.820  1017  1466 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 16:51:00.820  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-31 16:51:00.820  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 16:51:00.820  2633  2692 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 16:51:00.840  1017  1466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:00.840  1017  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 16:51:00.840  1017  1135 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 16:51:00.840  1017  1466 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:00.840  1017  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:00.840  1017  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:00.840  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-31 16:51:00.840  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 16:51:00.840  2633  2692 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 16:51:00.840  1017  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 16:51:00.840  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 16:51:00.840  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 16:51:00.850  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:00.850  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:00.850  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:00.850  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-31 16:51:00.850  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 16:51:00.850  2633  2692 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 16:51:00.850  1640  1640 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 16:51:00.860  1017  4262 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:00.860  1017  4262 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 16:51:00.860  1017  4262 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:00.860  2633  2633 D HeadsetService: Received start request. Starting profile...
08-31 16:51:00.860  1017  4262 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:00.860  1017  4262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:00.860  2633  2633 D HeadsetService: start()
,08-31 16:51:00.860  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-31 16:51:00.860  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 16:51:00.860  2633  2692 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 16:51:00.860  1017  4262 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:00.860  1017  4262 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-31 16:51:00.860  2633  2633 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 16:51:00.870  1017  4262 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:00.870  1017  4262 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:00.870  1017  4262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:00.870  2633  2633 D HeadsetStateMachine: make
,08-31 16:51:00.870  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 16:51:00.870  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 16:51:00.870  2633  2692 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 16:51:00.870  1017  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 16:51:00.870  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 16:51:00.870  2633  2633 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 16:51:00.880  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:00.880  1017  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:00.880  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:00.880  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-31 16:51:00.880  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 16:51:00.880  2633  2692 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 16:51:00.890  1017  1451 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:00.890  1017  1451 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 16:51:00.890  1017  1451 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:00.890  1017  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:00.890  1017  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:00.890  4267  4267 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 16:51:00.890  1017  1135 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-31 16:51:00.890  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 16:51:00.890  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:00.890  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:00.890  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:00.890  2633  2692 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:00.890  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:00.890  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:00.890  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-31 16:51:00.890  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:00.890  2633  2692 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:00.890  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 16:51:00.890  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 16:51:00.890  2633  2692 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 16:51:00.890  2633  2692 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 16:51:00.890  2633  2692 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 16:51:00.890  2633  2692 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 16:51:00.890  2633  2692 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 16:51:00.900  1017  1540 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 16:51:00.900  1017  1540 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:00.900  1017  1540 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-31 16:51:00.900  1017  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:00.900  1017  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-31 16:51:00.900  2633  2633 I bluedroid: get_profile_interface handsfree
08-31 16:51:00.910  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:00.910  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-31 16:51:00.910  1017  1470 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-31 16:51:00.910  1017  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:00.910  1017  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:00.910  1017  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:00.910  1017  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:00.930  6098  6098 E Zygote  : MountEmulatedStorage()
,08-31 16:51:00.930  6098  6098 I libpersona: KNOX_SDCARD checking this for 10055
08-31 16:51:00.930  6098  6098 E Zygote  : v2
08-31 16:51:00.930  6098  6098 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:00.930  1017  1470 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6098 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-31 16:51:00.930  6098  6098 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 16:51:00.930  6098  6098 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 16:51:00.930  6098  6098 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:00.970  2633  2633 I DualScoManager: Instantiating Dual Sco Manager
,08-31 16:51:00.970  2633  2633 I DualScoManager: Set HeadsetServiceHelper
,08-31 16:51:00.970  2633  2633 D BluetoothAtMessage: createCMTIContentObservers
08-31 16:51:00.970  1017  1029 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-31 16:51:00.970  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.970  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.970  1017  1029 D SettingsProvider: selectionArgs: false
08-31 16:51:00.970  1017  1029 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.970  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.970  1017  1029 D SettingsProvider: ret = -1
,08-31 16:51:00.970  6098  6098 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:00.970  6098  6098 D ActivityThread: Added TimaKeyStore provider,
,08-31 16:51:00.970  1017  1029 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
08-31 16:51:00.980  2633  6097 D HeadsetStateMachine: Enter Disconnected: -2
08-31 16:51:00.980  2633  2633 D HeadsetService: mStartError = false
08-31 16:51:00.980  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16da1077
,08-31 16:51:00.990  2633  6097 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-31 16:51:00.990  1017  1017 D BluetoothA2dp: Proxy object connected
,08-31 16:51:00.990  2633  2633 D A2dpService: Received start request. Starting profile...
08-31 16:51:00.990  2633  2633 D A2dpService: start()
,08-31 16:51:00.990  2633  2633 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 16:51:00.990  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 16:51:01.000  2633  6097 D HeadsetStateMachine: map size, before remove : 0
08-31 16:51:01.000  2633  6097 D HeadsetStateMachine: map size, after remove: 0
,08-31 16:51:01.000  2633  2633 I bluedroid: get_profile_interface avrcp
,08-31 16:51:01.020  6098  6098 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 16:51:01.030  2633  2633 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 16:51:01.030  2633  2633 D Avrcp   : Initialize Media Controller
08-31 16:51:01.030  2633  2633 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-31 16:51:01.030  2633  2633 E Avrcp   : getActiveSessions
08-31 16:51:01.030  2633  2633 D Avrcp   : pick active media Controller
08-31 16:51:01.030  2633  2633 D Avrcp   : Get the active Media Controller 
,08-31 16:51:01.050  2633  2633 I Avrcp   :  Updating now playing list upon AVRCP Start,
,08-31 16:51:01.050  2633  6113 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-31 16:51:01.050  2633  2633 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 16:51:01.050  2633  2633 D A2dpStateMachine: make
,08-31 16:51:01.060  2633  6113 D BluetoothMediaBrowser: no now playing list
08-31 16:51:01.070  2633  6113 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-31 16:51:01.070  2633  2633 I bluedroid: get_profile_interface a2dp
,08-31 16:51:01.070  2633  6121 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 16:51:01.070  2633  2633 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 16:51:01.070  2633  2633 D A2dpService: mStartError = false
08-31 16:51:01.070  2633  6120 D A2dpStateMachine: Enter Disconnected: -2
,08-31 16:51:01.070  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16da1077
,08-31 16:51:01.070  2633  2633 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 16:51:01.070  6098  6098 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 16:51:01.070  6098  6098 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 16:51:01.070  6098  6098 D UserAnalysis: Create SecureDbHelper
,08-31 16:51:01.080  2633  2633 D HidService: Received start request. Starting profile...
,08-31 16:51:01.080  2633  2633 D HidService: start()
08-31 16:51:01.080  2633  2633 I bluedroid: get_profile_interface hidhost
08-31 16:51:01.080  2633  2633 D HidService: setHidService(): set to: null
08-31 16:51:01.080  2633  2633 D HidService: mStartError = false
,08-31 16:51:01.080  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16da1077
,08-31 16:51:01.080  2633  2633 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 16:51:01.080  6098  6098 D IntelligenceServiceApplication: onCreate()
,08-31 16:51:01.080  2633  2633 D HealthService: Received start request. Starting profile...
08-31 16:51:01.080  2633  2633 D HealthService: start()
,08-31 16:51:01.090  1017  1468 I ActivityManager: Killing 5213:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-31 16:51:01.090  2633  2633 I bluedroid: get_profile_interface health
,08-31 16:51:01.090  2633  2633 D HealthService: mStartError = false
08-31 16:51:01.090  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16da1077
,08-31 16:51:01.090  6098  6098 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 16:51:01.100  2633  2633 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 16:51:01.100  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-31 16:51:01.100  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 16:51:01.100  2633  2633 D PanService: Received start request. Starting profile...
08-31 16:51:01.100  2633  2633 D PanService: start()
,08-31 16:51:01.100  2633  2633 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 16:51:01.100  2633  2633 I bluedroid: get_profile_interface pan
08-31 16:51:01.100  6098  6098 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 16:51:01.100  2633  2633 D PanService: mStartError = false
08-31 16:51:01.100  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16da1077
,08-31 16:51:01.110  2633  2633 D BluetoothMapService: Received start request. Starting profile...
08-31 16:51:01.110  2633  2633 D BluetoothMapService: start()
,08-31 16:51:01.110  2633  2633 D BluetoothMapService: mStartError = false
08-31 16:51:01.110  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16da1077
,08-31 16:51:01.110  2633  2633 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-31 16:51:01.110  6098  6098 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 16:51:01.120  2633  2633 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 16:51:01.120  1413  1432 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 16:51:01.120  1413  1413 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-31 16:51:01.120  1413  1413 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState,
,08-31 16:51:01.120  1413  1413 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-31 16:51:01.130  1413  1413 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 16:51:01.140  1413  1413 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 16:51:01.140  1413  1413 W BluetoothHeadset: Proxy not attached to service
,08-31 16:51:01.140  1413  1432 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 16:51:01.140  2633  2633 D SapService: Received start request. Starting profile...
,08-31 16:51:01.140  2633  2633 D SapService: start()
08-31 16:51:01.140  2633  2633 D BluetoothSAPServiceJni: initializeNative(L209): sap
,08-31 16:51:01.140  2633  2633 I bluedroid: get_profile_interface sap
08-31 16:51:01.140  2633  2633 D SapService: mStartError = false
,08-31 16:51:01.140  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16da1077
,08-31 16:51:01.140  2633  2633 D HeadsetStateMachine: Proxy object connected
,08-31 16:51:01.150  2633  2633 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 16:51:01.150  2633  2633 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-31 16:51:01.150  2633  6097 D HeadsetStateMachine: Disconnected process message: 11
08-31 16:51:01.150  2633  6097 D HeadsetStateMachine: Disconnected process message: 18
08-31 16:51:01.150  2633  2633 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-31 16:51:01.150  2633  2633 E BluetoothAdapterService(383389815): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true,
08-31 16:51:01.150  2633  2633 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 16:51:01.150  2633  2633 D BluetoothA2dp: Proxy object connected
08-31 16:51:01.150  2633  6097 D HeadsetStateMachine: Disconnected process message: 10
08-31 16:51:01.150  2633  2633 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-31 16:51:01.150  2633  6097 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 16:51:01.150  2633  6097 D HeadsetStateMachine: Disconnected process message: 11
,08-31 16:51:01.150  2633  2633 E BluetoothAdapterService(383389815): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 16:51:01.150  2633  2633 E BluetoothAdapterService(383389815): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 16:51:01.150  2633  2633 E BluetoothAdapterService(383389815): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-31 16:51:01.150  2633  2633 E BluetoothAdapterService(383389815): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-31 16:51:01.160  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 16:51:01.160  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:01.160  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.160  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.160  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:01.170  6126  6126 E Zygote  : MountEmulatedStorage(),
08-31 16:51:01.170  6126  6126 E Zygote  : v2
08-31 16:51:01.170  6126  6126 I libpersona: KNOX_SDCARD checking this for 10105
08-31 16:51:01.170  6126  6126 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:01.180  6126  6126 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:01.180  1017  1030 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6126 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-31 16:51:01.180  6126  6126 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:01.180  1017  1135 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,08-31 16:51:01.180  6126  6126 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:01.180  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.180  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.180  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.180  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:01.200  1017  1044 D Tethering: interfaceAdded wlan0
,08-31 16:51:01.210  6126  6126 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-31 16:51:01.210  6126  6126 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:01.210  1017  1130 E Tethering: No numeric data
08-31 16:51:01.220  1017  1135 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6137 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-31 16:51:01.220   277  1016 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 16:51:01.220  6137  6137 I libpersona: KNOX_SDCARD checking this for 10141
08-31 16:51:01.220   277  1016 D SoftapController: Softap fwReload - Ok
08-31 16:51:01.220  6137  6137 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:01.220  6137  6137 E Zygote  : MountEmulatedStorage()
08-31 16:51:01.220  6137  6137 E Zygote  : v2
08-31 16:51:01.220  6137  6137 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:01.220  6137  6137 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 16:51:01.220  6137  6137 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:01.230  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 16:51:01.230  1017  1130 D Tethering: clearTetheredNotification()
08-31 16:51:01.230  1017  1123 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:01.240   277  1016 D CommandListener: Setting iface cfg
08-31 16:51:01.240   277  1016 D CommandListener: Trying to bring down wlan0
,08-31 16:51:01.240   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-31 16:51:01.240  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 16:51:01.240   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:01.240   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:01.240   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,08-31 16:51:01.240   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-31 16:51:01.250  1017  1123 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:01.250  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 16:51:01.250  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:01.250  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:01.250  6137  6137 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:01.250  6137  6137 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:01.250  1017  1123 V NetworkStats: performPollLocked() took 3ms
,08-31 16:51:01.250  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:01.250  1017  1124 D NtpTrustedTime: forceRefresh Fail.
08-31 16:51:01.250  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:01.250  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 16:51:01.250  1017  1130 D Tethering: InitialState.processMessage what=4
,08-31 16:51:01.260  1017  1044 D Tethering: interfaceAdded p2p0
,08-31 16:51:01.260  1017  1130 E Tethering: No numeric data
08-31 16:51:01.260  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 16:51:01.260  1017  1130 D Tethering: clearTetheredNotification()
08-31 16:51:01.260  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
08-31 16:51:01.260  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 16:51:01.260  1176  1176 D HotspotTile: updateTetherState():false, false
08-31 16:51:01.260  1017  1123 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:01.260  1017  1123 D NtpTrustedTime: forceRefresh Fail.
08-31 16:51:01.260  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 16:51:01.260  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:01.260  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 16:51:01.260  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.260  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.260  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-31 16:51:01.260  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 16:51:01.260  1176  1176 D HotspotTile: updateTetherState():false, false
08-31 16:51:01.270  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
08-31 16:51:01.270  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:01.270  1017  1123 V NetworkStats: performPollLocked() took 3ms
08-31 16:51:01.270  1017  1124 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:01.290  6137  6137 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-31 16:51:01.290  6137  6137 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:01.290  6137  6137 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 16:51:01.290  6137  6137 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 16:51:01.290  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 16:51:01.310  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 16:51:01.310  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:01.310  4267  4267 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:01.310  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:01.310  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 16:51:01.310  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.310  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.310  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.310  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.310  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:01.310  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-31 16:51:01.310  1176  1176 D HotspotTile: onReceive : 2, 0
,08-31 16:51:01.330  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,08-31 16:51:01.330   312   312 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:51:01.330  5994  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:51:01.350  1017  1539 D RCPManagerService: exchangeData() failure , invalid userId,
08-31 16:51:01.350  6159  6159 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 16:51:01.350  6159  6159 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 16:51:01.350  6159  6159 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,08-31 16:51:01.370  1017  1540 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:01.370  6159  6159 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-31 16:51:01.380   404   404 I SecureStorage: [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 6159
08-31 16:51:01.380   404   404 I SecureStorage: [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
08-31 16:51:01.380  6159  6159 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 16:51:01.380  6159  6159 I wpa_supplicant: ssSupport state is = 1
08-31 16:51:01.380  6159  6159 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 16:51:01.380  6159  6159 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-31 16:51:01.380   404   404 I SecureStorage: [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 6159
08-31 16:51:01.380   404   404 I SecureStorage: [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,08-31 16:51:01.430  1017  1313 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:01.440  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:01.490  2633  2633 E BluetoothAdapterService(383389815): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true,
08-31 16:51:01.490  2633  2633 E BluetoothAdapterService(383389815): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 16:51:01.490  1017  4263 I ActivityManager: Killing 5533:com.samsung.android.sm/1000 (adj 15): empty #21,
,08-31 16:51:01.500  5910  5919 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,08-31 16:51:01.510  2633  2692 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false,
08-31 16:51:01.510  2633  2692 I bluedroid: enable
,08-31 16:51:01.510  1017  4263 D RCPManagerService: exchangeData() failure , invalid userId,
08-31 16:51:01.510  5910  5919 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-31 16:51:01.510  5910  5919 D BadgeProvider: sendNotify, [notify] : null
08-31 16:51:01.510  5910  5919 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-31 16:51:01.510  5910  5919 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 16:51:01.510   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 16:51:01.510  5910  5919 D BadgeProvider: update, [UpdateCount] : 1
08-31 16:51:01.510   256   515 W Vold    : Returning OperationFailed - no handler for errno 0,
,08-31 16:51:01.520  6126  6167 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 16:51:01.530  2633  2695 E bt-btif : Adding UUID=0x110C i,
,08-31 16:51:01.530  2633  2695 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 16:51:01.530  2633  2695 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type,
08-31 16:51:01.530  2633  2695 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-31 16:51:01.530  2633  2695 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-31 16:51:01.530  2633  2695 E BluetoothServiceJni: populateRssiValuesNative
08-31 16:51:01.530  2633  2695 I bluedroid: getModelRssiValues
08-31 16:51:01.530  2633  2695 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127,
08-31 16:51:01.530  2633  2695 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 16:51:01.530  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 16:51:01.530  2633  2695 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-31 16:51:01.530  5994  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 16:51:01.540  2633  2695 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:51:01.540  2633  2695 D BluetoothAdapterProperties: Scan Mode:20
08-31 16:51:01.540  2633  2695 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:51:01.540  2633  2695 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-31 16:51:01.540  2633  2695 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2,
08-31 16:51:01.540  2633  2695 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-31 16:51:01.540  2633  2695 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 16:51:01.540  2633  2695 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 16:51:01.540  2633  2695 D IOP_DB_BT: db_open: db_open : handle 3028373520l, read 13894 bytes onto local cache,
08-31 16:51:01.540  2633  2695 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-31 16:51:01.540  2633  2695 D IOP_DB_BT: db_query: result 1
08-31 16:51:01.540  2633  2695 I         : iop_db_open: iop_db_open status 0
,08-31 16:51:01.540  2633  2695 D bte_conf: Device ID record 1 : primary
08-31 16:51:01.540  2633  2695 D bte_conf:   vendorId            = 0075
08-31 16:51:01.540  2633  2695 D bte_conf:   vendorIdSource      = 0001
08-31 16:51:01.540  2633  2695 D bte_conf:   product             = 0100,
08-31 16:51:01.540  2633  2695 D bte_conf:   version             = 0200
08-31 16:51:01.540  2633  2695 D bte_conf:   clientExecutableURL = 
08-31 16:51:01.540  2633  2695 D bte_conf:   serviceDescription  = 
08-31 16:51:01.540  2633  2695 D bte_conf:   documentationURL    = 
08-31 16:51:01.540  2633  2695 D bte_conf: bte_load_did_conf no section named DID2.
08-31 16:51:01.540  2633  2695 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 16:51:01.540  2633  2695 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 16:51:01.540  2633  2692 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 16:51:01.540  2633  2692 D BluetoothAdapterProperties: ScanMode =  20
08-31 16:51:01.540  2633  2692 D BluetoothAdapterProperties: State =  11
,08-31 16:51:01.550  1017  4262 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
08-31 16:51:01.550  1471  1471 D Launcher.Model: reloadBadges entered.
08-31 16:51:01.550  2633  2692 D BluetoothAdapterProperties: Setting state to 12
08-31 16:51:01.550  2633  2692 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 16:51:01.560  1017  1539 D RCPManagerService: exchangeData() failure , invalid userId,
08-31 16:51:01.560  2633  2695 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:51:01.560  2633  2695 D BluetoothAdapterProperties: Scan Mode:21
08-31 16:51:01.560  2633  2695 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 16:51:01.560  1017  1313 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-31 16:51:01.560  1017  1313 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-31 16:51:01.560  1017  1313 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.560  1017  1313 D SettingsProvider: selectionArgs: false
08-31 16:51:01.560  1017  1313 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.560  1017  1313 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.560  1017  1313 D SettingsProvider: ret = -1
,08-31 16:51:01.560  5994  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage,
,08-31 16:51:01.560  1017  1313 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.570  2633  2692 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
08-31 16:51:01.570  2633  2692 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 16:51:01.570  1017  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.570  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.570  5994  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage,
08-31 16:51:01.570  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.570  1017  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.570  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:01.580  6137  6170 W art     : Verification of void com.android.email.activity.MessageListItemOuterContainer.<init>(android.content.Context) took 105.588ms
,08-31 16:51:01.590  5994  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 16:51:01.590  2633  2692 D BluetoothAdapterService: Autoconnection is available 
08-31 16:51:01.590  2633  2692 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 16:51:01.590  2633  2692 D BluetoothAdapterService: starting service from this receiver
,08-31 16:51:01.610   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 16:51:01.610   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:01.610  6126  6167 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 16:51:01.610  5994  6003 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:51:01.610  5994  6003 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:01.610  1601  1612 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:01.610  1601  1612 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:01.610  1437  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:51:01.610  1437  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:01.620  5994  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:01.620  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:01.620  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:51:01.620  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:51:01.620  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:01.620  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:01.620  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:01.620  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:51:01.620  1017  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 16:51:01.620  1017  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.620  1017  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:01.620  1017  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.620  1017  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:01.620  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:01.630  2633  2692 I BluetoothAdapterState: Entering On State from state = 11
,08-31 16:51:01.630  1640  1650 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:01.630  1640  1650 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:01.630  5994  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:51:01.630  2633  2633 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-31 16:51:01.640  1176  2945 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:51:01.640  1176  2945 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:01.640  2633  6095 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 16:51:01.650  1413  1447 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:51:01.650  1413  1447 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:01.650  1422  1609 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:01.650  1422  1609 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:01.650  2633  2633 I BluetoothPbapService: Handler(): got msg=1
,08-31 16:51:01.650  1017  1451 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 16:51:01.650  2633  2643 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:01.650  2633  2643 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:01.660  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 16:51:01.660  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:01.660  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:01.660  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 16:51:01.660  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 16:51:01.660  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:51:01.660  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-31 16:51:01.660  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 16:51:01.670  2633  6177 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 16:51:01.670  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-31 16:51:01.670   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
08-31 16:51:01.670  1413  1413 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3f9f5de5, true
,08-31 16:51:01.670  1810  1810 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 16:51:01.670  6159  6159 I SecureStorage: [INFO]: SPID(0x00000001)Processing data has been completed
08-31 16:51:01.670  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 16:51:01.670  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:01.670  1176  1176 D BluetoothTile:  getBluetoothState : 12
,08-31 16:51:01.680  1413  1413 D BluetoothHeadset: registerMessageListener
,08-31 16:51:01.680  2633  2644 D HeadsetService: registerMessageListener
,08-31 16:51:01.690  2633  2644 D HeadsetService: registerMessageListener
,08-31 16:51:01.690  2633  6097 D HeadsetStateMachine: Disconnected process message: 70
08-31 16:51:01.690  1413  1413 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 16:51:01.690  2633  6177 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:51:01.690  1413  1413 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 16:51:01.690  2633  6177 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:51:01.690  2633  6097 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1567ad99
,08-31 16:51:01.690  5994  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:51:01.690  2633  6177 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-31 16:51:01.690  2633  6177 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 16:51:01.690  2633  6177 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 16:51:01.690  2633  6177 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@115fb85e
,08-31 16:51:01.690  2633  6178 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 16:51:01.690  2633  6177 D BluetoothSocket: channel: 19
08-31 16:51:01.690  2633  6177 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 16:51:01.690  1017  1312 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 16:51:01.690  1413  1413 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 16:51:01.690  1413  1413 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-31 16:51:01.690  1413  1413 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 16:51:01.690  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:51:01.690  1017  1305 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-31 16:51:01.690  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 16:51:01.690  2633  6097 D HeadsetStateMachine: Disconnected process message: 9
,08-31 16:51:01.700  2633  6097 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 16:51:01.700  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:51:01.700  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:51:01.700  2633  6178 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 16:51:01.700  2633  6178 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:51:01.710  2633  6178 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,08-31 16:51:01.710  2633  6178 D BluetoothSocket: bindListen(), new LocalSocket 
,08-31 16:51:01.710  2633  6178 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 16:51:01.710  2633  6178 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6a2543f
,08-31 16:51:01.710  2633  6178 D BluetoothSocket: channel: 5
,08-31 16:51:01.710   282   672 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-31 16:51:01.710   282   672 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 16:51:01.710   282   672 V voice   : voice_set_parameters: exit with code(-2)
08-31 16:51:01.710   282   672 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-31 16:51:01.710   282   672 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 16:51:01.710   282   672 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 16:51:01.710   282   672 V audio_hw_primary: adev_set_parameters: exit
,08-31 16:51:01.720  2633  6097 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 16:51:01.720  6159  6159 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 16:51:01.730  6159  6159 I SecureStorage: [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,08-31 16:51:01.750  6159  6159 I SecureStorage: [INFO]: SPID(0x00000001)This device supports Secure Storage,
08-31 16:51:01.750   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 6159
08-31 16:51:01.750   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-31 16:51:01.750  6159  6159 I SecureStorage: [INFO]: SPID(0x00000001)SS Daemon is running
,08-31 16:51:01.750  6159  6159 I wpa_supplicant: ssSupport state is = 1
,08-31 16:51:01.760  6159  6159 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 16:51:01.760  6159  6159 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:01.760  6159  6159 E wpa_supplicant: SIM READ ERROR
08-31 16:51:01.760  6159  6159 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.760  6159  6159 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:01.760  6159  6159 E wpa_supplicant: SIM READ ERROR
08-31 16:51:01.760  6159  6159 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 16:51:01.760  6159  6159 I wpa_supplicant: wpa_default_ap_write_once
08-31 16:51:01.760  6159  6159 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 16:51:01.760  6159  6159 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.760  6159  6159 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 16:51:01.760  6159  6159 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.760  6159  6159 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 16:51:01.760  6159  6159 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 16:51:01.770  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 16:51:01.770  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:01.770  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 16:51:01.820  6159  6159 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 16:51:01.880  6126  6126 D StrictMode: StrictMode policy violation; ~duration=430 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 16:51:01.880  6126  6126 D StrictMode: StrictMode policy violation; ~duration=430 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.880  6126  6126 D StrictMode: StrictMode policy violation; ~duration=428 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.880  6126  6126 D StrictMode: StrictMode policy violation; ~duration=427 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.880  6126  6126 D StrictMode: StrictMode policy violation; ~duration=424 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.880  6126  6126 D StrictMode: StrictMode policy violation; ~duration=357 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.880  6126  6126 D StrictMode: StrictMode policy violation; ~duration=357 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.880  6126  6126 D StrictMode: StrictMode policy violation; ~duration=356 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.880  6126  6126 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.880  1017  1468 I ActivityManager: Killing 4942:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-31 16:51:01.890  1017  1451 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 16:51:01.890  1017  1451 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 16:51:01.890  1017  1451 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.890  1017  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.890  1017  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 16:51:01.890  4016  4016 I Hs20UtilService: Starting #2
08-31 16:51:01.900  4016  4031 I Hs20UtilService: Message received 5011
08-31 16:51:01.900  1017  1305 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-31 16:51:01.900  1017  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.900  1017  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.900  1017  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.900  1017  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.910  6189  6189 E Zygote  : MountEmulatedStorage()
08-31 16:51:01.910  1017  1305 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6189 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 16:51:01.910  6189  6189 E Zygote  : v2
08-31 16:51:01.910  6189  6189 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:01.910  6189  6189 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:01.920  6189  6189 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:01.920  6189  6189 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:01.920  6189  6189 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:51:01.940  1017  2733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-31 16:51:01.950   302   302 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 880us total 39.552ms
,08-31 16:51:01.960  6189  6189 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:01.960  6189  6189 D ActivityThread: Added TimaKeyStore provider,
,08-31 16:51:01.960  6159  6159 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-31 16:51:01.970  6159  6159 I SecureStorage: [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,08-31 16:51:01.980   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 2.098ms total 19.579ms
,08-31 16:51:01.980  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-31 16:51:01.980  1017  1029 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-31 16:51:01.990  6159  6159 I SecureStorage: [INFO]: SPID(0x00000001)This device supports Secure Storage
,08-31 16:51:01.990   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 6159
08-31 16:51:01.990   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-31 16:51:01.990  6159  6159 I SecureStorage: [INFO]: SPID(0x00000001)SS Daemon is running
08-31 16:51:01.990  6159  6159 I wpa_supplicant: ssSupport state is = 1
,08-31 16:51:01.990  1017  4263 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.990  1017  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.990   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.825ms,
,08-31 16:51:02.000  6159  6159 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 16:51:02.000  6159  6159 I SecureStorage: [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,08-31 16:51:02.010  6159  6159 I SecureStorage: [INFO]: SPID(0x00000001)This device supports Secure Storage
08-31 16:51:02.010   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 6159
08-31 16:51:02.010   404   404 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-31 16:51:02.010  6159  6159 I SecureStorage: [INFO]: SPID(0x00000001)SS Daemon is running
08-31 16:51:02.010  6159  6159 I wpa_supplicant: ssSupport state is = 1
08-31 16:51:02.010  6159  6159 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:02.010  6159  6159 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:02.010  6159  6159 E wpa_supplicant: SIM READ ERROR
08-31 16:51:02.010  6159  6159 I wpa_supplicant: wpa_default_ap_write_once
08-31 16:51:02.010  6159  6159 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 16:51:02.010  6159  6159 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 16:51:02.020  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:02.020  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:02.020  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-31 16:51:02.020  6189  6189 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 16:51:02.020  6189  6189 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:51:02.020  6189  6189 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 16:51:02.020  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:02.020  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:02.020  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 16:51:02.020  6189  6189 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 16:51:02.020  1017  1470 I ActivityManager: Killing 5693:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-31 16:51:02.030  6126  6186 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 16:51:02.040  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 16:51:02.040  1017  1313 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 16:51:02.040  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.040  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.040  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.040  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 16:51:02.050  1640  1640 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 16:51:02.060  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:02.060  6159  6159 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-31 16:51:02.060  6159  6159 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 16:51:02.060  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.060  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:02.060  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 16:51:02.070  4267  4267 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 16:51:02.080  4267  4267 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:51:02.080  1017  1029 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 16:51:02.080  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.080  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.080  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.080  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.080  4267  4267 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 16:51:02.080  4267  4267 E BluetoothHeadset: BTStateChangeCB is registed
,08-31 16:51:02.080  4267  4267 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:51:02.080  1017  1466 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 16:51:02.080  1017  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 16:51:02.090  1017  1466 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.090  1017  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.090  1017  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.090  4267  4267 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 16:51:02.090  4267  4267 D BluetoothMap: Create BluetoothMap proxy object
,08-31 16:51:02.090  1017  1539 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-31 16:51:02.090  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.090  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.090  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.090  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.100  1017  1466 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-31 16:51:02.100  1017  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.100  1017  1466 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.100  1017  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.100  1017  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.110  4267  4267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,08-31 16:51:02.110  1017  4263 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-31 16:51:02.110  1017  4263 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.110  1017  4263 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.110  1017  4263 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.110  1017  4263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.110  4267  4267 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 16:51:02.120  1017  1029 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-31 16:51:02.120  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.120  6159  6159 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-31 16:51:02.120  6159  6159 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 16:51:02.120  6159  6159 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 16:51:02.120  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.120  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.120  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.120  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-31 16:51:02.130  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 16:51:02.130  6159  6159 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 16:51:02.130  6159  6159 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:02.130  6159  6159 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:02.130  6159  6159 E wpa_supplicant: SIM READ ERROR
08-31 16:51:02.130  6159  6159 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 16:51:02.130  1017  4262 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-31 16:51:02.130  1017  4262 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.130  1017  4262 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.130  1017  4262 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.130  1017  4262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.140  6159  6159 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-31 16:51:02.140  4267  4267 D LocalBluetoothProfileManager: PANU : true
08-31 16:51:02.140  4267  4267 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
08-31 16:51:02.140  4267  4267 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 16:51:02.140  4267  4267 D DockEventReceiver: finishStartingService: stopping service
,08-31 16:51:02.140  4267  4267 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 16:51:02.150  4267  4267 D BluetoothA2dp: Proxy object connected
,08-31 16:51:02.150  4267  4267 D A2dpProfile: Bluetooth service connected
08-31 16:51:02.150  6159  6159 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 16:51:02.150  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:02.150  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 16:51:02.160  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-31 16:51:02.160  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 16:51:02.160  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:02.160  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 16:51:02.170  4267  4267 D HeadsetProfile: Bluetooth service connected
,08-31 16:51:02.170  5994  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:02.170  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:02.170  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:51:02.170  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:02.170  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:02.170  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:02.170  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:02.170  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:51:02.180  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:02.180  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:02.180  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16da1077
08-31 16:51:02.180  2633  2633 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 16:51:02.180  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:02.180  1017  1466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:02.180  1017  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.180  1017  1466 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.180  1017  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.180  1017  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.180  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:02.190  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:51:02.190  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-31 16:51:02.190  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 16:51:02.190  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:51:02.190  1176  1176 D HotspotTile: onReceive : 3, 0
,08-31 16:51:02.190  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:02.190  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:02.190  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 16:51:02.190  5994  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:51:02.190  4267  4267 D BluetoothMap: Proxy object connected
,08-31 16:51:02.190  4267  4267 D MapProfile: Bluetooth service connected
08-31 16:51:02.190  4267  4267 D BluetoothMap: getConnectedDevices()
,08-31 16:51:02.200  1017  1126 E WifiConfigStore: Not a HS20
,08-31 16:51:02.200  1017  1540 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 16:51:02.200  1017  1540 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:02.200  1017  1540 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.200  1017  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.200  1017  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:02.200  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 16:51:02.210  4016  4016 I Hs20UtilService: Starting #3
,08-31 16:51:02.210  4016  4031 I Hs20UtilService: Message received 5011
,08-31 16:51:02.210  4267  4267 D BluetoothPbap: Proxy object connected
,08-31 16:51:02.210  4267  4267 D PbapServerProfile: Bluetooth service connected
,08-31 16:51:02.210  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 16:51:02.210  6159  6159 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 16:51:02.210  6159  6159 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 16:51:02.210  6159  6159 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 16:51:02.210  6159  6159 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 16:51:02.210  6159  6159 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 16:51:02.210  6159  6159 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 16:51:02.210  6159  6159 I wpa_supplicant: First Scan Start
,08-31 16:51:02.210  6159  6159 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 16:51:02.210  4267  4267 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 16:51:02.210  4267  4267 D SapProfile: Bluetooth service connected
08-31 16:51:02.210  4267  4267 D Bluetoothsap: getConnectedDevices()
,08-31 16:51:02.220  6189  6189 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 16:51:02.220  6189  6189 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:51:02.220  6189  6189 D SecurityLogAgent: StateMachine : Current State = 1
08-31 16:51:02.220  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
08-31 16:51:02.220  6189  6189 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 16:51:02.220  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 16:51:02.220  1017  1126 I WifiNative-HAL: startHal
,08-31 16:51:02.220  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9f0b488c
08-31 16:51:02.220  1017  1126 I WifiNative-HAL: Could not start hal
08-31 16:51:02.220  4267  4267 D BluetoothInputDevice: Proxy object connected
08-31 16:51:02.220  4267  4267 D HidProfile: Bluetooth service connected
,08-31 16:51:02.220  4267  4267 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 16:51:02.220  4267  4267 D PanProfile: Bluetooth service connected
,08-31 16:51:02.230  1017  1313 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 16:51:02.240  2633  6218 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:51:02.240  2633  6218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:51:02.240  2633  6218 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-31 16:51:02.240  2633  6218 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 16:51:02.240  2633  6218 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 16:51:02.240  2633  6218 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33c876d1
08-31 16:51:02.240  1017  1126 E WifiNative-wlan0: do suspend true
,08-31 16:51:02.240  2633  6218 D BluetoothSocket: channel: 12
08-31 16:51:02.240  2633  6218 I BtOppRfcommListener: Accept thread started.
,08-31 16:51:02.240  4267  4267 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:51:02.240  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 16:51:02.240  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 16:51:02.240   277  1016 D CommandListener: Setting iface cfg
08-31 16:51:02.250   277  1016 D CommandListener: Trying to bring up p2p0
,08-31 16:51:02.250  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-31 16:51:02.250  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-31 16:51:02.250  1017  1151 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:02.250  1017  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:02.250  1017  1150 I WifiNative-HAL: startHal
08-31 16:51:02.250  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9e0749bc
08-31 16:51:02.250  1017  1150 I WifiNative-HAL: Could not start hal
08-31 16:51:02.250  1017  1150 E WifiScanningService: could not start HAL
,08-31 16:51:02.250  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 16:51:02.250  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 16:51:02.250  1017  1126 E WifiNative-wlan0: invaild command id : 215
08-31 16:51:02.250  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 16:51:02.250  1017  1125 D WifiP2pService: P2pEnablingState
,08-31 16:51:02.250  6159  6159 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 16:51:02.250  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-31 16:51:02.250  6159  6159 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 16:51:02.250  1017  1125 D WifiP2pService: P2p socket connection successful
08-31 16:51:02.250  6159  6159 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-31 16:51:02.250  1017  1126 E WifiStateMachine: Failed to set frequency band 0
,08-31 16:51:02.260  1017  1125 D WifiP2pService: P2pEnabledState
,08-31 16:51:02.260  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: IDLE
08-31 16:51:02.260  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:02.260  1017  1126 D SecContentProvider2: mCursor = null
,08-31 16:51:02.260  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 16:51:02.260  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-31 16:51:02.260  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 16:51:02.260  1017  1047 D WifiDisplayController: disconnect
,08-31 16:51:02.260  1017  1047 D WifiDisplayController: updateConnection
08-31 16:51:02.260  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 16:51:02.260  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 16:51:02.260  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 16:51:02.260  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 16:51:02.260  1017  1126 E WifiNative-wlan0: invaild command id : 215
08-31 16:51:02.260  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:02.260  1017  1126 D SecContentProvider2: mCursor = null
,08-31 16:51:02.260  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 16:51:02.270  1017  4262 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:02.270  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 16:51:02.280  1017  1125 D WifiP2pService: create mNetworkAgent
,08-31 16:51:02.290  1017  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-31 16:51:02.290  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-31 16:51:02.290  1017  1128 E ConnectivityService: updateNetworkInfo(),
08-31 16:51:02.290  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:02.290  1017  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
08-31 16:51:02.290  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 16:51:02.290  4267  4267 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 16:51:02.300  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,08-31 16:51:02.300  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-31 16:51:02.300  1017  1125 D WifiP2pService: DeviceAddress: 0a:75:42
,08-31 16:51:02.300  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  secondary type: null
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  wps: 0
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  grpcapab: 0
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  devcapab: 0
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  status: 3
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  wfdInfo: null
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-31 16:51:02.300  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-31 16:51:02.310  4267  4267 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 16:51:02.310  4267  4267 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 16:51:02.310  4267  4267 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,08-31 16:51:02.310  4267  4267 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 16:51:02.310  4267  4267 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 16:51:02.310  4267  4324 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 16:51:02.310  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-31 16:51:02.310  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.310  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.310  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.310  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.330  6222  6222 E Zygote  : MountEmulatedStorage(),
,08-31 16:51:02.330  6222  6222 E Zygote  : v2,
08-31 16:51:02.330  6222  6222 I libpersona: KNOX_SDCARD checking this for 10064
08-31 16:51:02.330  6222  6222 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:02.330  6222  6222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 16:51:02.330   312   312 I ServiceManager: Waiting for service AtCmdFwd...
08-31 16:51:02.330  1017  1029 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6222 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:02.330  6222  6222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:02.330  6222  6222 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:02.340  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
08-31 16:51:02.340  1017  1125 D WifiP2pService: InactiveState
08-31 16:51:02.340  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-31 16:51:02.340  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 16:51:02.340  6159  6159 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 16:51:02.340  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 16:51:02.340  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-31 16:51:02.340  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 16:51:02.350  6222  6222 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:02.350  6222  6222 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:02.370  6222  6222 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 16:51:02.380  6222  6222 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:51:02.390  6222  6222 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 16:51:02.420  6222  6222 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 16:51:02.420  1017  1312 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-31 16:51:02.420  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.420  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.420  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.420  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.430  6237  6237 E Zygote  : MountEmulatedStorage(),
,08-31 16:51:02.440  6237  6237 E Zygote  : v2
08-31 16:51:02.440  6237  6237 I libpersona: KNOX_SDCARD checking this for 10065
08-31 16:51:02.440  6237  6237 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:02.440  6237  6237 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 16:51:02.440  1017  1312 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6237 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-31 16:51:02.440  1017  1312 I ActivityManager: Killing 5744:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-31 16:51:02.440  6237  6237 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:02.450  6237  6237 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:02.460  6237  6237 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:02.470  6237  6237 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:02.490  6237  6237 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:51:02.490  1017  1313 I ActivityManager: Killing 5308:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-31 16:51:03.300  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 16:51:03.300  1017  1029 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4251, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-31 16:51:03.300  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 16:51:03.300  1017  1029 D BatteryService: stay LED for charging
08-31 16:51:03.300  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:51:03.300  1017  1017 I MotionRecognitionService: Plugged
,08-31 16:51:03.300  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 16:51:03.310  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 16:51:03.310  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 16:51:03.310  1397  1397 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 16:51:03.310  1397  1397 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 16:51:03.320  2633  2633 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 16:51:03.320  2633  6097 D HeadsetStateMachine: Disconnected process message: 10
,08-31 16:51:03.320   287   287 E SMD     : DCD OFF,
,08-31 16:51:03.330  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 16:51:03.330   312   312 I ServiceManager: Waiting for service AtCmdFwd...
08-31 16:51:03.330  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 16:51:03.330  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 16:51:03.430  6159  6159 I wpa_supplicant: nl80211: Received scan results (28 BSSes),
08-31 16:51:03.430  6159  6159 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 16:51:03.430  6159  6159 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-31 16:51:03.430  6159  6159 I wpa_supplicant: Trying to associate with  'G700'
08-31 16:51:03.430  6159  6159 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-31 16:51:03.430  6159  6159 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 16:51:03.430  1017  6209 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-31 16:51:03.430  1017  1126 I WifiNative-HAL: startHal
08-31 16:51:03.430  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9f0b48ac
08-31 16:51:03.430  1017  1126 I WifiNative-HAL: Could not start hal,
,08-31 16:51:03.450  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:03.450  1017  1126 D SecContentProvider2: mCursor = null
,08-31 16:51:03.710  6159  6159 E wpa_supplicant: Cmd 35605 not handled
,08-31 16:51:03.710  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:03.710  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 16:51:03.710  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 16:51:03.710  6159  6159 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 16:51:03.710  6159  6159 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 16:51:03.710  6159  6159 I wpa_supplicant: Associated with F4.99.3E
08-31 16:51:03.710  6159  6159 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 16:51:03.710  6159  6159 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 16:51:03.710  6159  6159 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-31 16:51:03.710  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 16:51:03.710  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 16:51:03.710  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 16:51:03.710  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:03.710  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 16:51:03.710  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 16:51:03.710  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 16:51:03.710  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:51:03.710  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:51:03.720  1017  1130 E Tethering: No numeric data
,08-31 16:51:03.720  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 16:51:03.720  1017  1130 D Tethering: clearTetheredNotification()
08-31 16:51:03.720  1017  1123 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:03.720   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:03.720   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-31 16:51:03.720  6159  6159 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-31 16:51:03.720  6159  6159 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 16:51:03.720  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:03.720  1017  1126 D SecContentProvider2: mCursor = null
,08-31 16:51:03.720  6159  6159 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-31 16:51:03.720  6159  6159 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-31 16:51:03.720  6159  6159 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 16:51:03.720  6159  6159 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 16:51:03.720  6159  6159 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-31 16:51:03.720  6159  6159 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 16:51:03.720  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 16:51:03.720  6159  6159 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-31 16:51:03.720  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:51:03.720  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:51:03.730  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 16:51:03.730  1176  1176 D HotspotTile: updateTetherState():false, false
08-31 16:51:03.730   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:03.730   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:03.730  1017  1123 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:03.730  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:51:03.730  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:03.730  1017  1126 D SecContentProvider2: mCursor = null
,08-31 16:51:03.730  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:03.730  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:03.730  1017  1123 V NetworkStats: performPollLocked() took 3ms
,08-31 16:51:03.730  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:03.730  1017  1124 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:03.740  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 16:51:03.740  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 16:51:03.750  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-31 16:51:03.750  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 16:51:03.750  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 16:51:03.750  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:03.750  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 16:51:03.750  1017  1451 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 16:51:03.750  1017  1451 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:03.750  1017  1451 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:03.750  1017  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:03.750  1017  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:03.760  4016  4016 I Hs20UtilService: Starting #4
,08-31 16:51:03.760  4016  4031 I Hs20UtilService: Message received 5007
,08-31 16:51:03.760  4267  4267 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:51:03.760  4267  4267 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 16:51:03.760  4267  4267 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 16:51:03.760  4267  4267 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-31 16:51:03.760  4267  4267 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 16:51:03.760  4267  4267 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 16:51:03.760  4267  4324 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 16:51:03.760  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 16:51:03.760  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 16:51:03.760  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 16:51:03.770  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.770  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.770  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.770  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:03.770  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 16:51:03.780   277  1016 D CommandListener: Setting iface cfg,
,08-31 16:51:03.780  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 1
,08-31 16:51:03.790  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:03.790  1017  1126 D SecContentProvider2: mCursor = null
,08-31 16:51:03.790  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 16:51:03.790  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 16:51:03.800  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 16:51:03.800  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:03.800  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:03.800  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:03.800  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:03.800  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:03.800  1017  1126 D SecContentProvider2: mCursor = null
,08-31 16:51:03.810  1017  1126 E WifiNative-wlan0: do suspend false
,08-31 16:51:03.810  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-31 16:51:03.810  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 16:51:04.020  6258  6258 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 16:51:04.030  6258  6258 I dhcpcd  : version 5.5.6 starting,
,08-31 16:51:04.030  6258  6258 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 16:51:04.080  6258  6258 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-31 16:51:04.080  6258  6258 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 16:51:04.080  6258  6258 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-31 16:51:04.080  6258  6258 I dhcpcd  : bssid match
,08-31 16:51:04.080  6258  6258 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-31 16:51:04.140  6258  6258 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-31 16:51:04.220  6258  6258 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-31 16:51:04.330   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:51:04.420  1017  1126 E WifiNative-wlan0: do suspend true,
,08-31 16:51:04.460  1017  1125 D WifiP2pService: InactiveState{ what=143375 },
08-31 16:51:04.460  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 16:51:04.470  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 16:51:04.470  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 16:51:04.470  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 16:51:04.470  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.470  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.470  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.470  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.470  1017  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-31 16:51:04.470  1017  1126 E WifiStateMachine: VerifyingLinkState enter
,08-31 16:51:04.480  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 16:51:04.480  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-31 16:51:04.480  1017  1128 D ConnectivityService: Adding iface wlan0 to network 502
,08-31 16:51:04.500  1017  1144 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
08-31 16:51:04.500  1017  1144 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 16:51:04.500  1017  1144 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-31 16:51:04.500  1017  1144 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 16:51:04.500  1017  1144 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
,08-31 16:51:04.520  1017  1312 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 16:51:04.520  1017  1312 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:04.520  1017  1312 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:04.520  1017  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 16:51:04.520  1017  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:04.520  1017  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-31 16:51:04.520  4267  4267 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:51:04.520  4016  4016 I Hs20UtilService: Starting #5
,08-31 16:51:04.520  1017  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,08-31 16:51:04.530  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 16:51:04.530  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.530  1017  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
08-31 16:51:04.530  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-31 16:51:04.530  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.530  1017  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
08-31 16:51:04.530  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.530  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.530  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.530  4016  4031 I Hs20UtilService: Message received 5007
08-31 16:51:04.530  1017  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 16:51:04.530  1017  1128 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
08-31 16:51:04.530  1017  1128 D ConnectivityService: LTETest block dns file not exists
,08-31 16:51:04.530  4267  4267 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 16:51:04.540  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 16:51:04.540  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:51:04.540  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:04.540  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:04.550  1017  1128 V NetworkStats: performPollLocked() took 5ms
,08-31 16:51:04.550  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 16:51:04.550  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 16:51:04.550  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.550  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 16:51:04.550  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 16:51:04.550  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 16:51:04.550  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 16:51:04.550  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:51:04.550  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:04.550  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 16:51:04.550  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:04.550  1017  1128 V NetworkStats: performPollLocked() took 2ms
,08-31 16:51:04.560  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:04.560   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:04.560   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:04.560  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 16:51:04.560  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-31 16:51:04.560  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 16:51:04.560   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:04.560   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:04.560  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
08-31 16:51:04.560  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.560  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 16:51:04.560  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.560  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.560  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.560  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.570  1017  1124 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:04.570  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 16:51:04.570  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-31 16:51:04.570  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.580  1017  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.580  1017  6256 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:04.580  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-31 16:51:04.580  1017  6256 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-31 16:51:04.580  1017  6256 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:51:04.580  1017  6256 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-31 16:51:04.580  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:04.580  1017  1124 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:04.580  1017  1466 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 16:51:04.580  1017  1466 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:04.580  1017  1466 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:04.580  1017  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:04.580  1017  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:04.590  4016  4016 I Hs20UtilService: Starting #6
,08-31 16:51:04.590  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.590  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.590  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.590  4016  4031 I Hs20UtilService: Message received 5007
,08-31 16:51:04.590  4267  4267 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:51:04.590  4267  4267 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 16:51:04.590  1017  6256 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-31 16:51:04.590  1017  6256 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:04.590  1017  6256 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 16:51:04.590  1017  6256 I System.out: (HTTPLog)-Thread-171-416549224: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 16:51:04.590  1017  6256 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:51:04.590  4267  4267 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 16:51:04.590  4267  4267 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-31 16:51:04.590  4267  4267 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 16:51:04.590  4267  4267 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 16:51:04.590  4267  4324 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 16:51:04.600  1017  1128 D ConnectivityService:    accepting network in place of null
,08-31 16:51:04.600  1017  1128 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,08-31 16:51:04.600  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 16:51:04.600  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:51:04.600   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:04.600   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 1000
08-31 16:51:04.600  1437  1437 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:51:04.600  1437  1437 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:51:04.610  1017  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-31 16:51:04.610  1017  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
08-31 16:51:04.610  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 16:51:04.610  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-31 16:51:04.610  1017  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-31 16:51:04.610  1017  1130 D Tethering: MasterInitialState.processMessage what=3
,08-31 16:51:04.620  1017  1123 V NetworkStats: updateIfacesLocked()
,08-31 16:51:04.620  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:04.620  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 16:51:04.620  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:04.620  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:04.620  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
08-31 16:51:04.620  1017  1124 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:04.620  1017  1313 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 16:51:04.620  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
,08-31 16:51:04.620  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 16:51:04.620  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 16:51:04.620  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 16:51:04.620  1017  1123 V NetworkStats: performPollLocked() took 4ms
08-31 16:51:04.620  1176  1176 D StatusBar.NetworkController: updateDataNetType()
,08-31 16:51:04.620  1017  1313 W ActivityManager: userId = 0, bbcId = -10000,
08-31 16:51:04.620  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 16:51:04.620  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 16:51:04.620  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-31 16:51:04.620  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 16:51:04.620  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-31 16:51:04.630  1176  1702 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 16:51:04.630  4016  4016 I Hs20UtilService: Starting #7
08-31 16:51:04.630  4267  4267 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 16:51:04.630  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-31 16:51:04.630  4016  4031 I Hs20UtilService: Message received 5007
08-31 16:51:04.630  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-31 16:51:04.630  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-31 16:51:04.630  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-31 16:51:04.630  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.630  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 16:51:04.630  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:04.630  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.630  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.630  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.630  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.630  1017  1124 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:04.630  4267  4267 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 16:51:04.650  1017  1470 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-31 16:51:04.660  1017  1468 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-31 16:51:04.660  1017  1468 D SecContentProvider2: mCursor = null
,08-31 16:51:04.660  1017  1135 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-31 16:51:04.660  1017  1135 D SecContentProvider2: mCursor = null
,08-31 16:51:04.660  1017  1305 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-31 16:51:04.660  1017  1305 D SecContentProvider2: mCursor = null
,08-31 16:51:04.660  1017  1313 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-31 16:51:04.660  1017  1313 D SecContentProvider2: mCursor = null
,08-31 16:51:04.670  1017  1466 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-31 16:51:04.670  1017  1466 D SecContentProvider2: mCursor = null
,08-31 16:51:04.670  1017  1451 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-31 16:51:04.670  1017  1451 D SecContentProvider2: mCursor = null
,08-31 16:51:04.700   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,08-31 16:51:04.700  1017  6256 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 16:51:04.720  1017  1470 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017,
,08-31 16:51:04.720  1176  1176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 16:51:04.760  5994  6072 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 16:51:04.760  5994  6072 I jxcore-log: 
,08-31 16:51:04.900  1017  6256 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 14:51:04 GMT], X-Android-Received-Millis=[1472655064910], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472655064745]}
,08-31 16:51:04.900  1017  6256 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-31 16:51:04.910  1017  6256 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-31 16:51:04.910  1017  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.910  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.910  1017  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,08-31 16:51:04.910  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.910  1176  1702 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 16:51:04.910  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 16:51:04.920  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
,08-31 16:51:04.920  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-31 16:51:04.920  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 16:51:04.920  1176  1176 D StatusBar.NetworkController: updateDataNetType()
,08-31 16:51:04.920  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 16:51:04.920  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 16:51:04.920  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-31 16:51:04.920  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-31 16:51:04.920  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-31 16:51:04.920  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-31 16:51:04.920  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 16:51:04.920  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-31 16:51:04.930  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.930  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.930  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.930  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:05.110  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:05.120  1017  1372 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:05.120  1017  1372 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:05.130  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:05.150  5994  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:05.150  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:05.150  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:51:05.150  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:05.150  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:05.150  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 16:51:05.150  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 16:51:05.150  5994  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 16:51:05.150  5875  5875 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-31 16:51:05.150  5875  5875 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-31 16:51:05.150  5875  5875 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 16:51:05.150  5875  5875 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:05.150  5994  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 16:51:05.160  1017  1468 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-31 16:51:05.160  1017  1468 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,08-31 16:51:05.160  1017  1468 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-31 16:51:05.160  1017  1468 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-31 16:51:05.170  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 16:51:05.170  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.170  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.170  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.170  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.180  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6298 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:05.190  6298  6298 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.190  6298  6298 E Zygote  : v2
08-31 16:51:05.190  6298  6298 I libpersona: KNOX_SDCARD checking this for 10001
08-31 16:51:05.190  6298  6298 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:05.190  1017  1041 E GpsLocationProvider: No APN found to select.
,08-31 16:51:05.190  6298  6298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 16:51:05.190  6298  6298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 16:51:05.190  6298  6298 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.210  6298  6298 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:05.210  6298  6298 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.290  1017  1451 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 16:51:05.290  1017  1451 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.290  1017  1451 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.290  1017  1451 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.290  1017  1451 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.310  6315  6315 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.310  6315  6315 E Zygote  : v2
,08-31 16:51:05.310  1017  1451 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6315 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 16:51:05.310  6315  6315 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:05.310  1017  1451 I ActivityManager: Killing 5771:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-31 16:51:05.310  6315  6315 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:05.310  6315  6315 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.310  6315  6315 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:05.310  6315  6315 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.330   312   312 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:51:05.330  6315  6315 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.340  6315  6315 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.370  6315  6315 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 16:51:05.400  5994  6072 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 16:51:05.400  5994  6072 I jxcore-log: 
,08-31 16:51:05.430  5994  6072 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 16:51:05.430  5994  6072 I jxcore-log: 
,08-31 16:51:05.500  6315  6315 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 16:51:05.510  6315  6315 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-31 16:51:05.520  6315  6315 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:05.520  6315  6315 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
08-31 16:51:05.520  6315  6315 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-31 16:51:05.520  6315  6315 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-31 16:51:05.600  1017  1470 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-31 16:51:05.610  1017  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 16:51:05.610  1017  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.610  1017  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.610  1017  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 16:51:05.620  1017  1470 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6331 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:05.620  6331  6331 E Zygote  : MountEmulatedStorage(),
08-31 16:51:05.620  6331  6331 E Zygote  : v2
08-31 16:51:05.620  6331  6331 I libpersona: KNOX_SDCARD checking this for 10008
08-31 16:51:05.620  6331  6331 I libpersona: KNOX_SDCARD not a persona,
,08-31 16:51:05.620  6331  6331 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.630  6331  6331 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 16:51:05.630  6331  6331 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.640  6331  6331 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.640  6331  6331 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.720  1017  1540 I ActivityManager: Killing 5796:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-31 16:51:05.720  6331  6331 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-31 16:51:05.730  6331  6331 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-31 16:51:05.730  6331  6331 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-31 16:51:05.730  6331  6331 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-31 16:51:05.760  1017  1312 I ActivityManager: Killing 5839:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-31 16:51:05.770  1017  1305 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-31 16:51:05.770  1017  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.770  1017  1305 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:05.770  1017  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:05.770  1017  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 16:51:05.780   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:05.780   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 16:51:05.800  1787  1787 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,08-31 16:51:05.850  1787  6353 I iu.SyncManager: SYNC; picasa accounts
,08-31 16:51:05.860  1787  1787 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-31 16:51:05.860  1787  1787 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 16:51:05.860  1787  6353 I iu.UploadsManager: num queued entries: 0
,08-31 16:51:05.870  1787  6353 I iu.UploadsManager: num updated entries: 0
,08-31 16:51:05.870  1787  6353 I iu.SyncManager: NEXT; no task
,08-31 16:51:05.880  1017  1466 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 16:51:05.880  1017  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.880  1017  1466 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:05.880  1017  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:05.880  1017  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:05.890  1787  1787 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 16:51:05.890  1787  1787 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-31 16:51:05.910  2767  2767 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 16:51:05 GMT+02:00 2016
,08-31 16:51:05.910  1017  1468 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 16:51:05.910  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.910  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:05.910  1017  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:05.910  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 16:51:05.920  2767  2767 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 16:51:05.920  2767  2767 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 16:51:05.920  1017  1540 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-31 16:51:05.920  1017  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.920  1017  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.920  1017  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.920  2767  2767 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-31 16:51:05.920  1017  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.930  2767  2767 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 16:51:05.930  2767  6355 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 16:51:05.930  2767  6355 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-31 16:51:05.940  6356  6356 E Zygote  : MountEmulatedStorage()
,08-31 16:51:05.940  6356  6356 E Zygote  : v2
08-31 16:51:05.940  6356  6356 I libpersona: KNOX_SDCARD checking this for 10031
08-31 16:51:05.940  6356  6356 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.940  6356  6356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.940  1017  1540 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6356 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-31 16:51:05.950  1017  1312 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-31 16:51:05.950  1017  1312 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.950  1017  1312 W ActivityManager: userId = 0, bbcId = -10000,
08-31 16:51:05.950  1017  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:05.950  1017  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-31 16:51:05.950  6356  6356 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 16:51:05.950  2767  6355 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-31 16:51:05.960  6356  6356 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.960  2767  6355 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-31 16:51:05.980  6356  6356 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.980  6356  6356 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:06.000  2767  6355 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-31 16:51:06.010  2767  6355 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-31 16:51:06.010  2767  6355 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-31 16:51:06.020  2767  2767 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 16:51:06.070  1017  1466 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-31 16:51:06.070  1017  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.070  1017  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.070  1017  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.070  1017  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.070  3303  6378 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:06.080  1017  1305 I art     : Explicit concurrent mark sweep GC freed 77020(4MB) AllocSpace objects, 19(304KB) LOS objects, 33% free, 23MB/34MB, paused 3.906ms total 186.190ms
,08-31 16:51:06.080  6379  6379 E Zygote  : MountEmulatedStorage()
08-31 16:51:06.090  3303  6378 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
08-31 16:51:06.090  1017  1466 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6379 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:06.090  3303  6378 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-31 16:51:06.090  6379  6379 I libpersona: KNOX_SDCARD checking this for 10032
08-31 16:51:06.090  6379  6379 E Zygote  : v2
08-31 16:51:06.090  6379  6379 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:06.090  6379  6379 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:06.090  6379  6379 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:06.090  6379  6379 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-31 16:51:06.090  3303  6378 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(259/xdmNotInitSetResume)] DM Not Init
,08-31 16:51:06.100  3303  6378 I DBG_POLICYDM: [com.policydm.XDMService(300/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,08-31 16:51:06.100  3303  3409 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,08-31 16:51:06.100  3303  3409 I DBG_POLICYDM: [com.policydm.agent.XDMTask(200/xdmAgentTaskHandler)] XEVENT_DM_INIT
,08-31 16:51:06.110  3303  3409 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:06.110  1017  1470 I ActivityManager: Killing 5818:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-31 16:51:06.120  3303  3409 I DBG_POLICYDM: [com.policydm.XDMService(661/xdmGetNotibarState)] get NotibarState : 7
08-31 16:51:06.120  3303  3409 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,08-31 16:51:06.120  3303  3409 I DBG_POLICYDM: [com.policydm.XDMService(653/xdmSetNotibarState)] set NotibarState : 7
,08-31 16:51:06.130  6379  6379 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-31 16:51:06.130  6379  6379 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:06.150  3303  3409 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(234/xdbGetCryptionkey)] try read dbString
,08-31 16:51:06.160  3303  3409 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(442/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,08-31 16:51:06.170  3303  3409 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(574/xdbGetFUMOInitiatedType)] Initiated Type: 0
,08-31 16:51:06.170  3303  3410 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(216/xdmUIEvent)] XUI_DM_IDLE_STATE :true
08-31 16:51:06.170  3303  3409 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(78/xpollingCheckVersionInfo)] 
,08-31 16:51:06.170  3303  3409 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(277/xpollingCheckTimer)] 
,08-31 16:51:06.180  3303  3410 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:06.190  3303  3409 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(291/xpollingCheckTimer)] savedpollingtime : 2016/09/02/02:15:00
,08-31 16:51:06.190  3303  3410 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,08-31 16:51:06.190  3303  3409 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(292/xpollingCheckTimer)] currentTime : 2016/08/31/16:51:06
,08-31 16:51:06.190  3303  3410 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,08-31 16:51:06.190  3303  3409 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(296/xpollingCheckTimer)] Restart Timer..
,08-31 16:51:06.200  3303  3409 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 0
,08-31 16:51:06.200  6379  6396 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-31 16:51:06.200  3303  3410 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,08-31 16:51:06.200  6379  6396 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-31 16:51:06.200  3303  3410 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,08-31 16:51:06.200  3303  3410 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,08-31 16:51:06.200  3303  3410 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/xnotiPushAdpClearSessionStatus)] 
,08-31 16:51:06.210  3303  3410 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,08-31 16:51:06.210  6379  6379 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-31 16:51:06.210  3303  3410 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(453/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,08-31 16:51:06.210  1017  1305 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-31 16:51:06.220  1017  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.220  1017  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.220  1017  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.220  1017  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.220  6379  6396 D SPPClientService: PushLog.txt file is not deleted.
08-31 16:51:06.220  6379  6396 D SPPClientService: PushLog.txt file is not deleted.
,08-31 16:51:06.220  6379  6396 D SPPClientService: ============PushLog. stop!
,08-31 16:51:06.230  3303  3409 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(318/xPollingReportReStartAlarm)] ,
,08-31 16:51:06.230  6398  6398 E Zygote  : MountEmulatedStorage()
,08-31 16:51:06.240  6398  6398 E Zygote  : v2
08-31 16:51:06.240  6398  6398 I libpersona: KNOX_SDCARD checking this for 10036
08-31 16:51:06.240  6398  6398 I libpersona: KNOX_SDCARD not a persona,
,08-31 16:51:06.240  6398  6398 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:06.240  1017  1305 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=6398 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:06.240  1017  1305 I ActivityManager: Killing 5891:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-31 16:51:06.240  6398  6398 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:06.240  6398  6398 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-31 16:51:06.240  3303  3410 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(552/xdbSetFUMOInitiatedType)] Initiated Type: 0
,08-31 16:51:06.270  6398  6398 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:06.270  6398  6398 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:06.280  3303  3410 I DBG_POLICYDM: [com.policydm.db.XDB(1781/xdbSetBackUpServerUrl)] 
,08-31 16:51:06.300  3303  3409 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 1
,08-31 16:51:06.300  3303  3409 I DBG_POLICYDM: [com.policydm.agent.XDMTask(225/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,08-31 16:51:06.320  6398  6398 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@2e86684c
,08-31 16:51:06.320   287   287 E SMD     : DCD OFF
,08-31 16:51:06.330  6398  6398 I SA      : [SSP] onCreated
,08-31 16:51:06.330   312   312 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-31 16:51:06.340  6398  6398 I SA      : [TPM] There is no property file
,08-31 16:51:06.350  6398  6398 I SA      : [SCU] isHaveSA() - false
,08-31 16:51:06.350  6398  6398 I SA      : [TPM] getModelProperty : null
,08-31 16:51:06.350  6398  6398 I SA      : [TPM] getCSCProperty : null
,08-31 16:51:06.350  6398  6398 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-31 16:51:06.350  6398  6398 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,08-31 16:51:06.350  6398  6398 I SA      : [DM] TFT FEATURE: false
,08-31 16:51:06.360  6398  6398 I SA      : [DM] init START
,08-31 16:51:06.360  6398  6398 I SA      : [DM] This device is not a Vodafone
,08-31 16:51:06.370  6398  6398 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-31 16:51:06.370  6398  6398 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-31 16:51:06.370  6398  6398 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-31 16:51:06.370  6398  6398 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-31 16:51:06.370  6398  6398 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-31 16:51:06.370  6398  6398 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-31 16:51:06.370  6398  6398 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-31 16:51:06.370  6398  6398 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 16:51:06.370  6398  6398 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-31 16:51:06.380  6398  6398 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-31 16:51:06.390  6398  6398 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-31 16:51:06.390  6398  6398 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-31 16:51:06.390  6398  6398 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-31 16:51:06.390  6398  6398 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-31 16:51:06.390  6398  6398 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-31 16:51:06.390  6398  6398 I SA      : [SCU] isHaveSA() - false
08-31 16:51:06.390  6398  6398 I SA      : support phone number id : false
08-31 16:51:06.390  6398  6398 I SA      : [DM] Supports Ref Jpn : true
,08-31 16:51:06.390  6398  6398 I SA      : [DM] init END
08-31 16:51:06.390  6398  6398 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-31 16:51:06.390  6398  6398 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-31 16:51:06.390  6398  6398 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 16:51:06.400  6398  6398 I SA      : [SLFUCHKMGR] constructor called,
,08-31 16:51:06.400  3303  3410 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,08-31 16:51:06.400  6398  6398 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-31 16:51:06.400  6398  6398 I SA      : [OR] == isSIMCardReady false ==
,08-31 16:51:06.410  6398  6398 I SA      : [SCU] == networkStateCheck == true
,08-31 16:51:06.410  6398  6398 I SA      : [DM] getCountryCodeFromCSC : PL
08-31 16:51:06.410  6398  6398 I SA      : isChinaCountryCode : false
08-31 16:51:06.410  6398  6398 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-31 16:51:06.410  6398  6398 I SA      : [OR] == networkStateCheck true ==
,08-31 16:51:06.410  6398  6398 I SA      : [OR] GetMyCountryZoneTask,
08-31 16:51:06.420  6398  6398 I SA      : [OR] onReceive END
,08-31 16:51:06.420  1017  4263 I ActivityManager: Killing 5710:com.android.mms/u0a41 (adj 15): empty #21
,08-31 16:51:06.420  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:06.430  3303  3410 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,08-31 16:51:06.430  6398  6418 I SA      : [SRS] prepareGetMyCountryZone
,08-31 16:51:06.440  1017  1313 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-31 16:51:06.440  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.440  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:06.440  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:06.440  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-31 16:51:06.440  6398  6418 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 16:51:06.440  6398  6418 I SA      : [SSP] query invoked
,08-31 16:51:06.450  1709  1709 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 16:51:06.450  6398  6418 I SA      : [TPMU] GetMccFromDB : null
,08-31 16:51:06.450  6398  6418 I SA      : [SCU] getMccFromPreferece mcc = 260
08-31 16:51:06.450  6398  6418 I SA      : [LBE] isSupportCheckDomainRegion : false
08-31 16:51:06.450  6398  6418 I SA      : [TPM] isNoProxy(default) : true
,08-31 16:51:06.450  1743  1752 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-31 16:51:06.460  1709  1709 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-31 16:51:06.460  1709  1709 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-31 16:51:06.460  1709  1709 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-31 16:51:06.460  1709  1709 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-31 16:51:06.460  1017  1466 D CountryDetector: No listener is left
,08-31 16:51:06.460  6398  6418 E File    : fail readDirectory() errno=2
,08-31 16:51:06.460  1017  1312 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-31 16:51:06.460  1017  1312 D SecContentProvider2: mCursor = null
,08-31 16:51:06.470  1709  1709 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 16:51:06.470  1709  1709 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-31 16:51:06.470  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-31 16:51:06.470  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.470  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.470  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.470  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.490  6421  6421 E Zygote  : MountEmulatedStorage()
08-31 16:51:06.490  6421  6421 E Zygote  : v2
08-31 16:51:06.490  6421  6421 I libpersona: KNOX_SDCARD checking this for 10077
08-31 16:51:06.490  6421  6421 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:06.490  6421  6421 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:06.490  6421  6421 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:06.490  1017  1029 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6421 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:06.490  6421  6421 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-31 16:51:06.510  6421  6421 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:06.520  6421  6421 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:06.770  1017  1468 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,08-31 16:51:06.770  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.770  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.770  1017  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.770  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-31 16:51:06.770  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-31 16:51:06.780  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.780  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.780  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.780  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.790  1017  1029 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6440 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 16:51:06.790  6440  6440 E Zygote  : MountEmulatedStorage()
08-31 16:51:06.790  6440  6440 E Zygote  : v2
08-31 16:51:06.790  6440  6440 I libpersona: KNOX_SDCARD checking this for 10102
,08-31 16:51:06.790  6440  6440 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:06.790  1017  1313 I ActivityManager: Killing 5922:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-31 16:51:06.790  6440  6440 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:06.800  6440  6440 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 16:51:06.800  6440  6440 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:06.820  6440  6440 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:06.820  6440  6440 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:06.840  6440  6440 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 16:51:06.940  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 16:51:06.940  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 16:51:06.940  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:51:06.940  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 16:51:06.940  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:06.950  1017  1128 V NetworkStats: performPollLocked() took 5ms,
,08-31 16:51:06.950  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502],
08-31 16:51:06.950  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:06.950  1176  1702 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 16:51:06.950  1017  1124 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:06.950  1176  1702 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 16:51:06.950   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:06.950   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,08-31 16:51:07.030  1017  1124 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1472655066290 mCachedNtpElapsedRealtime : 119710 mCachedNtpCertainty : 11
,08-31 16:51:07.030  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:51:07.030  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:07.070  6440  6461 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-31 16:51:07.070  6440  6461 I Babel_SMS: MmsConfig.loadMmsSettings
,08-31 16:51:07.070  6440  6461 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-31 16:51:07.070  6440  6461 I Babel_SMS: MmsConfig.loadFromDatabase
,08-31 16:51:07.080  6440  6461 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-31 16:51:07.080  6440  6461 I Babel_SMS: MmsConfig.loadFromResources
,08-31 16:51:07.090  6440  6461 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 16:51:07.090  6440  6461 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-31 16:51:07.130  1017  1466 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-31 16:51:07.130  1017  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.130  1017  1466 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:07.130  1017  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:07.130  1017  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 16:51:07.150  6440  6440 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 16:51:07.160  6440  6440 I Babel_Crash: startup - clean
,08-31 16:51:07.200  1017  1312 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-31 16:51:07.200  1017  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.200  1017  1312 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:07.200  1017  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:07.200  1017  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 16:51:07.210  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-31 16:51:07.210  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.210  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.210  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.210  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.230  6464  6464 E Zygote  : MountEmulatedStorage(),
,08-31 16:51:07.230  1017  1029 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6464 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:07.250  6464  6464 E Zygote  : v2
08-31 16:51:07.250  6464  6464 I libpersona: KNOX_SDCARD checking this for 10110
08-31 16:51:07.250  6464  6464 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:07.250  6464  6464 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:07.250  6464  6464 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:07.250  6464  6464 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:07.260   302   302 I art     : Explicit concurrent mark sweep GC freed 8675(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 643us total 20.932ms
,08-31 16:51:07.280   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 16.772ms
,08-31 16:51:07.300   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 17.157ms
,08-31 16:51:07.300  6464  6464 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:07.300  6464  6464 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:07.300  6440  6440 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.310  6440  6440 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 16:51:07.310  6440  6440 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 16:51:07.320  6440  6440 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-31 16:51:07.320  6440  6440 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-31 16:51:07.340  6398  6418 I SA      : [RC New] Execute method=[GET] start
,08-31 16:51:07.340  6440  6440 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-31 16:51:07.340  6440  6440 W AudioCapabilities: Unsupported mime audio/x-ima
,08-31 16:51:07.340  6440  6440 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 16:51:07.340  6440  6440 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 16:51:07.360  6440  6440 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 16:51:07.360  6440  6440 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 16:51:07.370  6440  6440 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-31 16:51:07.370  6440  6440 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 16:51:07.380  6440  6440 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 16:51:07.380  6440  6440 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-31 16:51:07.380  6440  6440 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-31 16:51:07.380  6440  6440 W VideoCapabilities: Unsupported mime video/mp43
,08-31 16:51:07.390  6440  6440 W VideoCapabilities: Unsupported mime video/sorenson,
,08-31 16:51:07.400  6440  6440 W VideoCapabilities: Unsupported mime video/mp4v-esdp,
,08-31 16:51:07.410  6398  6418 I SA      : [RC New] Security=[true],
,08-31 16:51:07.410  6398  6418 I System.out: Thread-1151(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,08-31 16:51:07.410  6398  6418 I System.out: Thread-1151(ApacheHTTPLog):isSBSettingEnabled false
08-31 16:51:07.410  6398  6418 I System.out: Thread-1151(ApacheHTTPLog):isShipBuild true
08-31 16:51:07.410  6398  6418 I System.out: Thread-1151(ApacheHTTPLog):SMARTBONDING_ENABLED is false
08-31 16:51:07.410  6398  6418 I System.out: Thread-1151(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-31 16:51:07.420   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:07.420   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10036
,08-31 16:51:07.420  6440  6440 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 16:51:07.450  6440  6440 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.450  6440  6440 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.480  6440  6440 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.480  6440  6440 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.490  6440  6440 I vclib   : onServiceConnected
,08-31 16:51:07.490  1017  1451 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-31 16:51:07.490  1017  1451 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.490  1017  1451 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:07.490  1017  1451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.490  1017  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 16:51:07.530  6440  6480 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-31 16:51:07.530  6440  6480 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:51:07.530  6440  6480 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 16:51:07.530  6440  6480 I System.out: (HTTPLog)-Thread-1164-74888904: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 16:51:07.530  6440  6480 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:07.530   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:07.530   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10102
,08-31 16:51:07.540  1017  1468 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 16:51:07.550  2633  2693 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 16:51:07.570  6440  6480 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 16:51:07.580  1017  1149 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-31 16:51:07.640  6440  6480 I Babel   : connection state changed from UNKNOWN to CONNECTED
,08-31 16:51:07.660  1017  1305 I ActivityManager: Killing 5945:com.wsomacp/u0a23 (adj 15): empty #21
,08-31 16:51:07.690   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 16:51:07.690   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:07.690  6464  6486 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 16:51:07.700   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 16:51:07.700   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:07.700  6464  6486 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
,08-31 16:51:07.710   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 16:51:07.710   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:07.710  6464  6487 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 16:51:07.720   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 16:51:07.720   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:07.720  6464  6487 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 16:51:07.720  5994  6072 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 16:51:07.720  5994  6072 I jxcore-log: 
,08-31 16:51:07.740  6464  6464 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 16:51:07.740  6464  6464 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 16:51:07.740  6464  6464 I GAv4    :   adb logcat -s GAv4
,08-31 16:51:07.760  6464  6464 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:51:07.760  1017  1135 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 16:51:07.780  6464  6464 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:51:07.780  6464  6489 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:51:08.030  6398  6418 I SA      : [RC New] [v2liruge] api execute + 623
08-31 16:51:08.030  6398  6418 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,08-31 16:51:08.030  6398  6418 I System.out: AsyncTask #1 calls detatch()
,08-31 16:51:08.050  1017  1540 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:08.060  6398  6418 I SA      : [ODM] saveOpenData( GEO_IP, PL )
08-31 16:51:08.060  6464  6464 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-31 16:51:08.060  1017  1540 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:08.060  1017  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:08.060  1017  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.070  6398  6418 I SA      : [OCP] update openData : PL
,08-31 16:51:08.070  6398  6418 I SA      : [TPMU] getNetworkMcc : 260
,08-31 16:51:08.070  6398  6418 I SA      : [SCU] saveMccToPreferece Start
,08-31 16:51:08.070  6398  6418 I SA      : [SCU] RegionMCC : 260
08-31 16:51:08.070  6398  6418 I SA      : [SSP] query invoked
,08-31 16:51:08.080  6398  6418 I SA      : [TPMU] GetMccFromDB : null
,08-31 16:51:08.080  6398  6418 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-31 16:51:08.080  5994  6072 I jxcore-log: ERROR runTests: 
08-31 16:51:08.080  5994  6072 I jxcore-log: 
08-31 16:51:08.080  6398  6418 I SA      : [SCU] saveMccToPreferece End
,08-31 16:51:08.080  6398  6418 I SA      : [RC New] executeRequest [v2liruge] end. 744
08-31 16:51:08.080  6398  6418 I SA      : [RC New] Execute end
,08-31 16:51:08.080  6398  6398 I SA      : [OR] GetMyCountryZoneTask mcc = 260
08-31 16:51:08.080  6398  6398 I SA      : [OR] GetMyCountryZoneTask Success
,08-31 16:51:08.080  5994  6072 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:51:08.080  5994  6072 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-31 16:51:08.090  6464  6464 I cr.library_loader: Time to load native libraries: 10 ms (timestamps 763-773)
,08-31 16:51:08.090  6464  6464 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 16:51:08.100  5994  6072 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _functionName: 'loadFile',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _lineNumber: '26',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _columnNumber: '11',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 16:51:08.100  5994  6072 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _functionName: '',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _lineNumber: '38',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _columnNumber: '7',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 16:51:08.100  5994  6072 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _functionName: '',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _lineNumber: '35',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _columnNumber: '3',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 16:51:08.100  5994  6072 I jxcore-log:   { _fileName: 'module.js',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _lineNumber: '621',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _columnNumber: '8',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 16:51:08.100  5994  6072 I jxcore-log:   { _fileName: 'module.js',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _lineNumber: '651',
08-31 16:51:08.100  5994  6072 I jxcore-log:     _columnNumber: '1',
08-31 16:51:08.100  5994  6072 I jxcore-log:    
08-31 16:51:08.100  5994  6072 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 16:51:08.100  5994  6072 I jxcore-log: 
,08-31 16:51:08.100  5994  6072 E jxcore-log: Error: 
08-31 16:51:08.100  5994  6072 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:51:08.100  5994  6072 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 16:51:08.100  5994  6072 E jxcore-log: 
08-31 16:51:08.100  5994  6072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 16:51:08.100  5994  6072 I jxcore-log: 
08-31 16:51:08.100  5994  6072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 16:51:08.100  5994  6072 I jxcore-log: 
08-31 16:51:08.100  5994  6072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 16:51:08.100  5994  6072 I jxcore-log: 
08-31 16:51:08.110  6464  6464 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {108caf0d}
08-31 16:51:08.110  6464  6464 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 16:51:08.110  6464  6464 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 16:51:08.130  6464  6464 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 16:51:08.130  6464  6464 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:51:08.140  6464  6464 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 16:51:08.150  6464  6464 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 16:51:08.150  6464  6464 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:51:08.150  6464  6464 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:51:08.150  6464  6464 I Adreno-EGL: Local Branch: 
08-31 16:51:08.150  6464  6464 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:51:08.150  6464  6464 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:51:08.150  6464  6464 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:51:08.190   257  5519 I SurfaceFlinger: id=13 Removed Uoast (8/9)
,08-31 16:51:08.190   257   447 I SurfaceFlinger: id=13 Removed Uoast (-2/9)
,08-31 16:51:08.190  1017  1312 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 120876
,08-31 16:51:08.190  1017  1312 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0),
08-31 16:51:08.190  1017  1312 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10049}) (elapsedTime=3475)
,08-31 16:51:08.220  6464  6464 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 16:51:08.230  6464  6519 W cr.media: Requires BLUETOOTH permission
,08-31 16:51:08.230  6464  6464 I NSApplication: Starting up...
,08-31 16:51:08.230  1017  1451 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 16:51:08.230  1017  1466 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 16:51:08.240  1017  1313 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-31 16:51:08.240  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:08.240  6258  6258 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-31 16:51:08.250  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:08.250  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:08.250  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:08.260  6524  6524 E Zygote  : MountEmulatedStorage()
,08-31 16:51:08.260  6524  6524 E Zygote  : v2
08-31 16:51:08.260  6524  6524 I libpersona: KNOX_SDCARD checking this for 10117
08-31 16:51:08.260  6524  6524 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:08.260  6524  6524 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:08.260  1017  1313 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6524 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:08.260  1017  1313 I ActivityManager: Killing 6024:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21,
08-31 16:51:08.260  6524  6524 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:08.260  6524  6524 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:08.290  6524  6524 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:08.290  6524  6524 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:08.310  6524  6524 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 16:51:08.400  6510  6510 D AndroidRuntime: ,
08-31 16:51:08.400  6510  6510 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 16:51:08.410  6510  6510 D AndroidRuntime: CheckJNI is OFF,
08-31 16:51:08.410  6510  6510 D AndroidRuntime: readGMSProperty: start,
08-31 16:51:08.410  6510  6510 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:51:08.410  6510  6510 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:51:08.410  6510  6510 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:51:08.410  6510  6510 D AndroidRuntime: readGMSProperty: end,
08-31 16:51:08.410  6510  6510 D AndroidRuntime: addProductProperty: start
,08-31 16:51:08.530  6510  6510 E AffinityControl: AffinityControl: registerfunction enter,
,08-31 16:51:08.560  6510  6510 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 16:51:08.570  1017  1313 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-31 16:51:08.570  1017  1313 D PackageManager: START PACKAGE DELETE: observer{900817861}
08-31 16:51:08.570  1017  1313 D PackageManager: pkg{<packageName>}
08-31 16:51:08.570  1017  1313 D PackageManager: user{0}
08-31 16:51:08.570  1017  1313 D PackageManager: caller{2000}
08-31 16:51:08.570  1017  1313 D PackageManager: flags{2}
08-31 16:51:08.570  1017  1313 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 16:51:08.580  1017  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-31 16:51:08.570  1017  1313 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-31 16:51:08.570  1017  1313 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 16:51:08.570  1017  1313 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 16:51:08.580  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-31 16:51:08.580  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 16:51:08.580  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-31 16:51:08.580  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 16:51:08.580  1017  1056 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-31 16:51:08.580  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-31 16:51:08.580  1017  1042 I ActivityManager: Killing 5994:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-31 16:51:08.590  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{bb5d61a u0 com.test.thalitest/.MainActivity t163}
,08-31 16:51:08.590  1017  1042 D InputDispatcher: Focus left window: 5994
,08-31 16:51:08.590   257  1097 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,08-31 16:51:08.600   257  5519 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-31 16:51:08.620  1017  1042 D InputDispatcher: Focused application released
08-31 16:51:08.620  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 16:51:08.620  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 16:51:08.720  1017  1056 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-31 16:51:08.740  1017  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-31 16:51:08.760  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 16:51:08.760  5419  5419 I art     : Explicit concurrent mark sweep GC freed 2547(151KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 728us total 29.475ms
,08-31 16:51:08.770  1810  1810 E SamsungIME: mOCRHelper is null
,08-31 16:51:08.770  1601  1874 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 16:51:08.790  1017  1017 D RCPManagerService: PackageReceiver onReceive(),
,08-31 16:51:08.790  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 16:51:08.790  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 16:51:08.790  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-31 16:51:08.790  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-31 16:51:08.800  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 16:51:08.800  1422  1422 D PersonaManager: isKioskContainerExistOnDevice
,08-31 16:51:08.810  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 16:51:08.810  1017  1305 I ActivityManager: Killing 5962:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-31 16:51:08.830  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-31 16:51:08.830  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:51:08.830  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-31 16:51:08.830  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:08.830  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:08.830  1017  1123 V NetworkStats: performPollLocked() took 5ms
08-31 16:51:08.830  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:08.840  1422  1422 D RegisteredServicesCache: empty dynamic service
,08-31 16:51:08.850  1422  1422 D RegisteredComponentCache: Collect Tech packages for Knox
,08-31 16:51:08.860  1422  1422 D PersonaManager: isKioskContainerExistOnDevice
,08-31 16:51:08.890  1017  1466 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-31 16:51:08.890  1017  1466 D SecContentProvider2: mCursor = null
,08-31 16:51:08.900  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:51:08.900  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:08.910  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 16:51:08.910  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-31 16:51:08.910  1017  1041 W TextServicesManagerService: no available spell checker services found
,08-31 16:51:08.910  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-31 16:51:08.920  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:08.920  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:08.920  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:08.920  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:08.930  6555  6555 E Zygote  : MountEmulatedStorage()
08-31 16:51:08.930  6555  6555 I libpersona: KNOX_SDCARD checking this for 10121
08-31 16:51:08.930  6555  6555 E Zygote  : v2
08-31 16:51:08.930  6555  6555 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:08.930  6555  6555 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:08.940  6555  6555 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:08.940  6555  6555 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:08.940  1017  1135 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6555 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-31 16:51:08.950  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:08.950  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 16:51:08.950  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 16:51:08.950  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-31 16:51:08.950  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-31 16:51:08.950  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 16:51:08.950  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 16:51:08.950  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 16:51:08.950  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 16:51:08.950  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 16:51:08.950  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 16:51:08.960  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:08.960  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 16:51:08.960  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:08.960  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:08.970  6555  6555 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:08.970  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 16:51:08.970  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
08-31 16:51:08.970  1017  2716 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-31 16:51:08.970  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-31 16:51:08.970  6555  6555 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:08.970  6524  6538 W art     : Suspending all threads took: 7.532ms
,08-31 16:51:09.000  6555  6555 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:09.000  6555  6555 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 16:51:09.000  6555  6555 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 16:51:09.030  6555  6555 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:09.030  6555  6555 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 16:51:09.040  1017  1056 I art     : Explicit concurrent mark sweep GC freed 39582(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/34MB, paused 4.995ms total 238.617ms
,08-31 16:51:09.040  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-31 16:51:09.040  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-31 16:51:09.040  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
,08-31 16:51:09.040  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 16:51:09.040  6555  6555 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-31 16:51:09.040  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 16:51:09.040  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 16:51:09.040  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 16:51:09.040  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 16:51:09.040  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 16:51:09.060  1017  1470 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:09.060  1017  1312 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-31 16:51:09.060  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.070  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.070  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.070  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.080  6572  6572 E Zygote  : MountEmulatedStorage()
,08-31 16:51:09.080  6572  6572 E Zygote  : v2
08-31 16:51:09.080  6572  6572 I libpersona: KNOX_SDCARD checking this for 10009
08-31 16:51:09.080  6572  6572 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:09.080  6572  6572 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:09.080  1017  1312 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=6572 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-31 16:51:09.080  6572  6572 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:09.080  6572  6572 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-31 16:51:09.080  1017  1312 I ActivityManager: Killing 5249:com.android.vending/u0a26 (adj 15): empty #21
,08-31 16:51:09.100  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-31 16:51:09.100  6572  6572 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:09.110  6572  6572 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:09.120  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.130  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.140  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.150  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 16:51:09.150  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:09.150  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 16:51:09.150  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.150  1017  1056 D PackageManager: delete codoeFile: 
,08-31 16:51:09.160  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.160  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 16:51:09.160  1017  1056 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-31 16:51:09.160  1017  1056 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-31 16:51:09.160  1017  1056 D PackageManager: result of delete: 1{900817861}
,08-31 16:51:09.170  6510  6510 D AndroidRuntime: Shutting down VM
08-31 16:51:09.170  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 16:51:09.170  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 16:51:09.170  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.170  1017  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 16:51:09.170  1017  1056 D PackageManager: userId{-1}
08-31 16:51:09.170  1017  1056 D PackageManager: andCode{true}
,08-31 16:51:09.170  1017  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-31 16:51:09.170  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 16:51:09.170  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 16:51:09.180  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 16:51:09.180  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-31 16:51:09.180  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.180  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.180  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.180  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.180  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.190  6572  6572 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-31 16:51:09.190  6588  6588 E Zygote  : MountEmulatedStorage()
08-31 16:51:09.190  6588  6588 E Zygote  : v2
08-31 16:51:09.190  6588  6588 I libpersona: KNOX_SDCARD checking this for 10003
08-31 16:51:09.190  6588  6588 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:09.190  6588  6588 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:09.200  6588  6588 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 16:51:09.200  6588  6588 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:51:09.200  1017  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6588 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 16:51:09.200  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-31 16:51:09.200  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-31 16:51:09.210  1017  1135 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-31 16:51:09.210  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-31 16:51:09.210  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:09.210  1017  1135 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 16:51:09.210  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-31 16:51:09.220  6588  6588 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:09.220  6588  6588 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:09.270  1017  1030 I ActivityManager: Killing 5910:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-31 16:51:09.320   287   287 E SMD     : DCD OFF
,08-31 16:51:09.340  3303  3409 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-31 16:51:09.350  3303  3409 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-31 16:51:09.350  3303  3409 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-31 16:51:09.350  3303  3409 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-31 16:51:09.360  3303  3409 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-31 16:51:09.360  3303  3409 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-31 16:51:09.360  3303  3409 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-31 16:51:09.360  3303  3409 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-31 16:51:09.370  3303  3409 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered,
,08-31 16:51:09.380  6510  6510 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 16:51:09.390  3303  3409 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:09.440  1017  1466 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-31 16:51:09.440  1017  1466 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-31 16:51:09.440  1017  1466 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:09.440  1017  1466 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 16:51:09.440  1017  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-31 16:51:09.450  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:09.450  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:09.450  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 16:51:09.460  6572  6572 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-31 16:51:09.460  6572  6572 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
08-31 16:51:09.460  6572  6572 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
08-31 16:51:09.460  6572  6572 D InitializeManagerStateMachine: exit::IDLE
08-31 16:51:09.460  6572  6572 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-31 16:51:09.470  6572  6572 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
,08-31 16:51:09.470  6572  6572 D InitializeManagerStateMachine: exit::NETWORK_CHECK
,08-31 16:51:09.470  6572  6572 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
,08-31 16:51:09.470  6572  6572 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-31 16:51:09.470  6572  6572 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-31 16:51:09.470  6572  6572 D InitializeManagerStateMachine: entry::SUCCESS
08-31 16:51:09.470  6572  6572 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
08-31 16:51:09.470  6572  6572 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,08-31 16:51:09.480  6572  6572 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-31 16:51:09.480  6572  6572 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-31 16:51:09.480  6572  6572 D InitializeManagerStateMachine: exit::SUCCESS
08-31 16:51:09.480  6572  6572 D InitializeManagerStateMachine: entry::IDLE
,08-31 16:51:09.520  1017  1305 I ActivityManager: Killing 6098:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-31 16:51:09.530  2767  2767 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 16:51:09 GMT+02:00 2016
,08-31 16:51:09.530  1017  4263 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-31 16:51:09.530  1017  4263 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 16:51:09.530  1017  4263 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:09.530  1017  4263 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:09.530  1017  4263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 16:51:09.530  2767  2767 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 16:51:09.530  1017  1312 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
,08-31 16:51:09.530  1017  1312 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-31 16:51:09.540  2767  2767 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 16:51:09.540  1017  1312 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-31 16:51:09.540  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.540  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.540  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.540  1017  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 16:51:09.540  2767  2767 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 16:51:09.550  2767  2767 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 16:51:09.550  2767  6610 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 16:51:09.550  2767  6610 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-31 16:51:09.550  6611  6611 E Zygote  : MountEmulatedStorage()
,08-31 16:51:09.550  6611  6611 E Zygote  : v2
08-31 16:51:09.550  6611  6611 I libpersona: KNOX_SDCARD checking this for 10090
08-31 16:51:09.550  6611  6611 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:09.560  6611  6611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:09.560  2767  6610 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-31 16:51:09.560  6611  6611 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:09.560  2767  6610 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-31 16:51:09.560  1017  1312 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6611 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-31 16:51:09.560  6611  6611 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-31 16:51:09.560  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-31 16:51:09.570  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.570  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.570  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.570  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.570  6379  6379 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
,08-31 16:51:09.570  6379  6379 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at com.sec.spp.push.i.a.a(Unknown Source)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at com.sec.spp.push.i.c.d(Unknown Source)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:09.570  6379  6379 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 16:51:09.570  6379  6379 E SPPClientService: [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
,08-31 16:51:09.580  6611  6611 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:09.580  6611  6611 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:09.580  6626  6626 E Zygote  : MountEmulatedStorage()
08-31 16:51:09.580  6626  6626 E Zygote  : v2
08-31 16:51:09.580  6626  6626 I libpersona: KNOX_SDCARD checking this for 10052
08-31 16:51:09.580  6626  6626 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:09.580  6626  6626 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:09.590  1017  1042 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6626 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-31 16:51:09.590  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,08-31 16:51:09.590  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 16:51:09.590  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.590  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.590  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 16:51:09.590  6626  6626 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:09.590  6626  6626 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:09.600  6638  6638 E Zygote  : MountEmulatedStorage()
08-31 16:51:09.600  6638  6638 E Zygote  : v2
08-31 16:51:09.600  6638  6638 I libpersona: KNOX_SDCARD checking this for 10098
08-31 16:51:09.600  6638  6638 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:09.600  6638  6638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:09.610  6638  6638 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:09.610  1017  1042 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6638 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-31 16:51:09.610  6638  6638 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:09.620  1017  1313 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-31 16:51:09.620  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.620  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.620  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.620  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.620  2767  6610 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-31 16:51:09.630  2767  6610 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-31 16:51:09.630  2767  6610 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.klmsagent/databases/klms.db'.
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:09.630  2767  6610 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:09.630  2767  6610 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 16:51:09.630  2767  6610 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-31 16:51:09.630  6654  6654 E Zygote  : MountEmulatedStorage(),
08-31 16:51:09.630  6654  6654 I libpersona: KNOX_SDCARD checking this for 10032
08-31 16:51:09.630  6654  6654 E Zygote  : v2
08-31 16:51:09.630  6654  6654 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:09.640  6654  6654 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:09.640  6626  6626 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:09.640  6626  6626 D ActivityThread: Added TimaKeyStore provider,
08-31 16:51:09.640  1017  1313 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6654 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:09.640  2767  6610 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest,
08-31 16:51:09.640  6654  6654 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:09.640  6654  6654 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-31 16:51:09.640  2767  6610 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-31 16:51:09.640  6638  6638 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:09.640  6638  6638 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:09.650  2767  2767 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 16:51:09.660  6654  6654 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:09.660  6654  6654 D ActivityThread: Added TimaKeyStore provider

```
