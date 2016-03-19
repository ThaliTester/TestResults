#### Test 62548124ca582f4_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
03-19 11:44:56.428  1017  2840 D ActivityManager: startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
03-19 11:44:56.428  1017  2840 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.428  1017  2840 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.428  1017  2840 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.428  1017  2840 E ActivityManager: checkUser: useridlist=null, currentuser=0
--------- beginning of main
03-19 11:44:56.438  2940  2940 E Zygote  : MountEmulatedStorage()
03-19 11:44:56.438  2940  2940 E Zygote  : v2
03-19 11:44:56.438  2940  2940 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-19 11:44:56.438  2940  2940 I libpersona: KNOX_SDCARD checking this for 10099
03-19 11:44:56.438  2940  2940 I libpersona: KNOX_SDCARD not a persona
03-19 11:44:56.438  1017  2840 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2940 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 11:44:56.448  2940  2940 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:56.448  2940  2940 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-19 11:44:56.448  1017  1041 W libprocessgroup: failed to open /acct/uid_10138/pid_1779/cgroup.procs: No such file or directory
03-19 11:44:56.468   307   307 I art     : Explicit concurrent mark sweep GC freed 8732(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 23.363ms
03-19 11:44:56.468  2940  2940 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:44:56.468  2940  2940 D ActivityThread: Added TimaKeyStore provider
03-19 11:44:56.478   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 16.786ms
03-19 11:44:56.498  1017  1528 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-19 11:44:56.498   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 17.047ms
03-19 11:44:56.498  1017  1538 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-19 11:44:56.508  1017  1538 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-19 11:44:56.508  1017  1538 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-19 11:44:56.508  1017  1528 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-19 11:44:56.508  1017  1528 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-19 11:44:56.508  1017  1041 W libprocessgroup: failed to open /acct/uid_10136/pid_1507/cgroup.procs: No such file or directory
03-19 11:44:56.518  1017  1538 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-19 11:44:56.518  1017  1528 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-19 11:44:56.518  1017  1538 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-19 11:44:56.518  1017  1528 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,03-19 11:44:56.538  1017  1538 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-19 11:44:56.538  1017  1528 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-19 11:44:56.538  1017  1528 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-19 11:44:56.538  1017  1528 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-19 11:44:56.538  1017  1528 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-19 11:44:56.538  1017  1528 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-19 11:44:56.538  1017  1528 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-19 11:44:56.538  1017  1528 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-19 11:44:56.588  1017  1538 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-19 11:44:56.598  2887  2887 E PhotosPlugin: Loading PhotosPlugin
03-19 11:44:56.598  1017  1528 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-19 11:44:56.598  1017  1538 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-19 11:44:56.598  1017  1538 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-19 11:44:56.598  1017  1528 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-19 11:44:56.708  1017  2840 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 11:44:56.708  1017  2840 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-19 11:44:56.708  1017  2840 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-19 11:44:56.708  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 11:44:56.718  1017  1017 I MotionRecognitionService: Plugged
03-19 11:44:56.718  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-19 11:44:56.718  1184  1184 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 11:44:56.718  1184  1184 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 11:44:56.728  1428  1428 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 11:44:56.728  1428  1428 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-19 11:44:56.728  1184  1184 D PowerUI : Cable  true --> true mBootCompleted : true
03-19 11:44:56.728  1184  1184 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-19 11:44:56.738  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 11:44:56.738  2663  2750 D HeadsetStateMachine: Disconnected process message: 10
03-19 11:44:56.738  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 11:44:56.738  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 11:44:56.738  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 11:44:56.748   297   297 E USB_UICC: Timeout! No signal received. Retry num = 29
03-19 11:44:56.768   316   316 I ServiceManager: Waiting for service AtCmdFwd...
03-19 11:44:56.838  2957  2957 D AndroidRuntime: 
03-19 11:44:56.838  2957  2957 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-19 11:44:56.838  2957  2957 D AndroidRuntime: CheckJNI is OFF
03-19 11:44:56.838  2957  2957 D AndroidRuntime: readGMSProperty: start
03-19 11:44:56.838  2957  2957 D AndroidRuntime: readGMSProperty: already setted!!
03-19 11:44:56.838  2957  2957 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-19 11:44:56.838  2957  2957 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-19 11:44:56.838  2957  2957 D AndroidRuntime: readGMSProperty: end
03-19 11:44:56.838  2957  2957 D AndroidRuntime: addProductProperty: start
03-19 11:44:56.888  2940  2940 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-19 11:44:56.888  2940  2940 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-19 11:44:56.898  1017  1342 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
03-19 11:44:56.898  1017  1342 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
03-19 11:44:56.898  1017  1342 I ActivityManager: Killing 1688:com.google.android.apps.maps/u0a107 (adj 15): empty #31
03-19 11:44:56.908  1017  1017 I DrmEventReceiver: DrmEventReceiver : onReceive
03-19 11:44:56.908  1017  1017 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-19 11:44:56.908  1017  1017 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-19 11:44:56.908  1017  1017 I System.out: start Service
03-19 11:44:56.908  1017  1017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-19 11:44:56.908  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
03-19 11:44:56.918  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.918  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.918  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.918  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.928  1238  1238 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-19 11:44:56.938  1017  1042 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2975 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 11:44:56.938  2975  2975 E Zygote  : MountEmulatedStorage()
03-19 11:44:56.938  2975  2975 E Zygote  : v2
03-19 11:44:56.938  2975  2975 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:44:56.938  2975  2975 I libpersona: KNOX_SDCARD not a persona
03-19 11:44:56.938  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
03-19 11:44:56.938  2975  2975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-19 11:44:56.938  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.938  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.938  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.938  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:56.948  2975  2975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:56.958  2975  2975 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:44:56.968  2983  2983 E Zygote  : MountEmulatedStorage()
03-19 11:44:56.968  2983  2983 E Zygote  : v2
03-19 11:44:56.968  2983  2983 I libpersona: KNOX_SDCARD checking this for 10152
03-19 11:44:56.968  2983  2983 I libpersona: KNOX_SDCARD not a persona
03-19 11:44:56.968  2983  2983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-19 11:44:56.968  1017  1042 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2983 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
03-19 11:44:56.968  1017  1377 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
03-19 11:44:56.968  1017  1377 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
03-19 11:44:56.978  1017  1377 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:56.978  1017  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:56.978  1017  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-19 11:44:56.978  2983  2983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:56.978  2983  2983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:44:56.988  1017  1017 D ActivityManager: startService callerProcessName:android, calleePkgName: android
03-19 11:44:56.988  1017  1017 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
03-19 11:44:56.998  2957  2957 E AffinityControl: AffinityControl: registerfunction enter
03-19 11:44:57.018  2975  2975 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:44:57.018  2975  2975 D ActivityThread: Added TimaKeyStore provider
03-19 11:44:57.028  2957  2957 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-19 11:44:57.028   282   520 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 41
03-19 11:44:57.028   282   520 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 41
03-19 11:44:57.038  1017  3007 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-19 11:44:57.048  1017  1017 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-19 11:44:57.048  1017  1377 E PersonaManagerService: inState():  stateMachine is null !!
03-19 11:44:57.048  1017  1377 I PersonaManagerService: PersonaId don't exist
03-19 11:44:57.048  1017  1377 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-19 11:44:57.058   282   282 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-19 11:44:57.068  1017  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-19 11:44:57.068  2983  2983 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:44:57.068  2983  2983 D ActivityThread: Added TimaKeyStore provider
03-19 11:44:57.078  1017  1226 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-19 11:44:57.078  1017  1226 D SecContentProvider2: mCursor = null
03-19 11:44:57.078  1238  1238 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-19 11:44:57.078  2975  2975 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-19 11:44:57.088  1017  1377 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-19 11:44:57.088  1017  1377 W ActivityManager: mDVFSHelper.acquire()
03-19 11:44:57.088  2975  2975 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
03-19 11:44:57.088  1017  1377 D FocusedStackFrame: Set to : 0
03-19 11:44:57.088  2975  2975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
03-19 11:44:57.098  1489  1489 D Launcher.HomeView: onPause
03-19 11:44:57.098  1489  1489 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-19 11:44:57.108  1017  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-19 11:44:57.108  1017  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-19 11:44:57.108  1017  1377 D InputDispatcher: Focused application set to: xxxx
03-19 11:44:57.108  1017  1377 D InputDispatcher: Focus left window: 1489
03-19 11:44:57.108  1017  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-19 11:44:57.108  1017  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-19 11:44:57.108  1017  1149 D ActivityManager: bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
03-19 11:44:57.108  2957  2957 D AndroidRuntime: Shutting down VM
03-19 11:44:57.108  1017  1149 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-19 11:44:57.108  1017  1149 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:57.108  1017  1149 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:44:57.108  1017  1149 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-19 11:44:57.118  1017  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 11:44:57.118  1017  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-19 11:44:57.118  1017  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-19 11:44:57.118  1017  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-19 11:44:57.118   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-19 11:44:57.118  1017  1041 W libprocessgroup: failed to open /acct/uid_10107/pid_1688/cgroup.procs: No such file or directory
03-19 11:44:57.128  1017  1226 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-19 11:44:57.128  1017  1226 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-19 11:44:57.128  1017  1226 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:57.128  1017  1226 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:57.128  1017  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-19 11:44:57.128  1017  1506 D ActivityManager: startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
03-19 11:44:57.128  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
03-19 11:44:57.138  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:57.138  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:57.138  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
03-19 11:44:57.148  1017  2840 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-19 11:44:57.148  1017  2840 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-19 11:44:57.148  1469  1469 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-19 11:44:57.148  1017  2840 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:57.148  1017  2840 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:57.148  1017  2840 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-19 11:44:57.148  1017  3012 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
03-19 11:44:57.148  1469  1469 D BluetoothBDTestService: onCreate()
03-19 11:44:57.148  1469  1469 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-19 11:44:57.148  1469  1469 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
03-19 11:44:57.148  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.148  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.148  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.158  1469  1469 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
03-19 11:44:57.148  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.168  3014  3014 E Zygote  : MountEmulatedStorage()
03-19 11:44:57.168  3014  3014 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:44:57.168  3014  3014 E Zygote  : v2
03-19 11:44:57.168  3014  3014 I libpersona: KNOX_SDCARD not a persona
03-19 11:44:57.168  3014  3014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-19 11:44:57.178  3014  3014 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:57.178  2983  2983 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
03-19 11:44:57.178  3014  3014 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:44:57.178  1017  3012 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3014 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 11:44:57.198  1469  1469 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-19 11:44:57.198  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.198  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.198  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.198  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.198  3014  3014 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:44:57.198  3014  3014 D ActivityThread: Added TimaKeyStore provider
03-19 11:44:57.218  3029  3029 E Zygote  : MountEmulatedStorage()
03-19 11:44:57.218  3029  3029 E Zygote  : v2
03-19 11:44:57.218  3029  3029 I libpersona: KNOX_SDCARD checking this for 10155
03-19 11:44:57.218  3029  3029 I libpersona: KNOX_SDCARD not a persona
03-19 11:44:57.218  3029  3029 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-19 11:44:57.218  3029  3029 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:57.228  3029  3029 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-19 11:44:57.228  1017  1029 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3029 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-19 11:44:57.238  1017  1030 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
03-19 11:44:57.238  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
03-19 11:44:57.238  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:57.238  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:57.238  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-19 11:44:57.248  1489  1489 V ActivityThread: updateVisibility : ActivityRecord{46e4339 token=android.os.BinderProxy@1dcf55ba {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-19 11:44:57.248  1017  3012 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
03-19 11:44:57.268  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.268  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.268  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.268  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.268  3029  3029 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:44:57.268  3029  3029 D ActivityThread: Added TimaKeyStore provider
03-19 11:44:57.278  1469  1469 D CscUpdateService: onStart
03-19 11:44:57.278  3014  3014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 11:44:57.278  1469  1469 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-19 11:44:57.278  1469  1469 I CscUpdateService: set_CSC_version
03-19 11:44:57.278  1469  1469 E CscParser: update(): xml file exist
03-19 11:44:57.298  1238  3013 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-19 11:44:57.308  3047  3047 E Zygote  : MountEmulatedStorage()
03-19 11:44:57.308  3047  3047 E Zygote  : v2
03-19 11:44:57.308  3047  3047 I libpersona: KNOX_SDCARD checking this for 10003
03-19 11:44:57.308  3047  3047 I libpersona: KNOX_SDCARD not a persona
03-19 11:44:57.308  3047  3047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-19 11:44:57.308  1017  3012 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3047 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-19 11:44:57.308  3047  3047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:57.308  3047  3047 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:44:57.308  2887  2904 W art     : Suspending all threads took: 5.809ms
03-19 11:44:57.308  1017  1226 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
03-19 11:44:57.308  1017  1226 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:57.308  1017  1226 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
03-19 11:44:57.308  1017  1226 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:57.308  1017  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
03-19 11:44:57.318  1017  1377 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-19 11:44:57.318  1017  1377 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-19 11:44:57.318  1017  1377 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-19 11:44:57.328  2957  2957 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-19 11:44:57.338  1489  1489 D Launcher.HomeView: onStop
03-19 11:44:57.338  1469  1469 I CscUtil : isWifiOnly = false
,03-19 11:44:57.338  1489  1489 V ActivityThread: updateVisibility : ActivityRecord{46e4339 token=android.os.BinderProxy@1dcf55ba {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,03-19 11:44:57.338  1469  1469 I System.out: HandDataNode = null
03-19 11:44:57.338  1469  1469 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
,03-19 11:44:57.338  1469  1469 I CscUpdateService: This is normal boot : CSC not updated
,03-19 11:44:57.348  3047  3047 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:44:57.348  1017  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-19 11:44:57.348  3047  3047 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:57.348  1017  1377 D PersonaManager: isKioskContainerExistOnDevice
,03-19 11:44:57.368  1469  3063 E CscParser: update(): xml file exist
,03-19 11:44:57.378  1469  3063 D CscGPS  : CSCGPS.updateParameters
03-19 11:44:57.378  1469  3063 D CscGPS  : supl host : null
03-19 11:44:57.378  1469  3063 D CscGPS  : SUPL Host is null or invalid
03-19 11:44:57.378  1469  3063 D CscGPS  : supl_ver : null
03-19 11:44:57.378  1469  3063 D CscGPS  : SUPL Ver is null or invalid
03-19 11:44:57.378  1469  3063 D CscGPS  : supl port : null
03-19 11:44:57.378  1469  3063 D CscGPS  : SUPL PORT is null or invalid
03-19 11:44:57.378  1469  3063 D CscGPS  : LPP : null
03-19 11:44:57.378  1469  3063 D CscGPS  : LPP is null or invalid
03-19 11:44:57.378  1469  3063 D CscGPS  : CSC don't have any AGPS value.
,03-19 11:44:57.378  1017  1226 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-19 11:44:57.378  1017  1226 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-19 11:44:57.378  1017  1226 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:44:57.378  1017  1226 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-19 11:44:57.388  1017  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-19 11:44:57.388  1469  1469 I CscUpdateService: same CSC Version
,03-19 11:44:57.388  1469  1469 D CscUtil : Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,03-19 11:44:57.398  1017  1377 D PersonaManagerService: getPersonasForUser(): returning null!
,03-19 11:44:57.408  1238  1238 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-19 11:44:57.408  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-19 11:44:57.408  1017  1017 D SensorService: [SO] activate (ident=0xb94f6c38, enabled=0)
,03-19 11:44:57.408  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-19 11:44:57.408  1017  3012 D ActivityManager: startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,03-19 11:44:57.418  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.418  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.418  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.418  1489  1489 D Launcher: onTrimMemory. Level: 20
03-19 11:44:57.418  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:57.428  3014  3014 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
03-19 11:44:57.428  3068  3068 E Zygote  : MountEmulatedStorage()
03-19 11:44:57.428  3068  3068 E Zygote  : v2
,03-19 11:44:57.428  3068  3068 I libpersona: KNOX_SDCARD checking this for 1101
03-19 11:44:57.428  3068  3068 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:57.428  3068  3068 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:57.428  3014  3071 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458384297439
03-19 11:44:57.428  3068  3068 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:44:57.428  1017  1017 D SensorManager: unregisterListener ::   
,03-19 11:44:57.428  1017  1017 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-19 11:44:57.428  1017  3012 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3068 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-19 11:44:57.438  1017  3012 I ActivityManager: Killing 2110:com.android.vending/u0a28 (adj 15): empty #31
03-19 11:44:57.438  3068  3068 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:44:57.438  1017  1017 D SensorService: [SO] changed settle time [1]
03-19 11:44:57.438  1017  1017 D SensorService: [SO] setDelay [66000000]
03-19 11:44:57.438  1017  1017 D SensorService: [SO] activate (ident=0xb94f6c38, enabled=1)
03-19 11:44:57.438  1017  1017 D SensorService: [SO] AR_init
03-19 11:44:57.438  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-19 11:44:57.448  1017  1017 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-19 11:44:57.458  3014  3014 I KnoxUsageLogPro: premStatus:2
,03-19 11:44:57.468  3014  3014 I KnoxUsageLogPro: isEulaShown : false
03-19 11:44:57.468  3014  3014 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-19 11:44:57.478  1017  1226 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,03-19 11:44:57.478  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.478  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.478  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.478  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.478  1469  1480 D TP/MmsProvider: Update uri=content://mms, match=0
,03-19 11:44:57.478  1469  1480 D TP/MmsProvider: update , handleReadChangedBroadcast
,03-19 11:44:57.478  1469  1480 D TP/MmsSmsProvider: need read changed broadcast:false
,03-19 11:44:57.478  3068  3068 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:57.478  3068  3068 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:57.498  3086  3086 E Zygote  : MountEmulatedStorage()
,03-19 11:44:57.498  3086  3086 E Zygote  : v2
03-19 11:44:57.498  3086  3086 I libpersona: KNOX_SDCARD checking this for 10085
03-19 11:44:57.498  3086  3086 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:57.498  3086  3086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:57.498  3086  3086 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:57.498  1017  1226 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3086 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 11:44:57.498  1017  1226 I ActivityManager: Killing 2171:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-19 11:44:57.498  3086  3086 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:44:57.508  1238  3013 E SQLiteLog: (283) recovered 323 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,03-19 11:44:57.508  2365  2365 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-19 11:44:57.508  2365  2365 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 4427.825779
,03-19 11:44:57.508  2365  2365 I Mms/ReservationManager: resetAfterConnected()
,03-19 11:44:57.518  1469  1726 D TP/MmsSmsProvider: query,matched:7, calling pid = 2365
03-19 11:44:57.518  1017  1039 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-19 11:44:57.518  1469  1726 D TP/MmsSmsProvider: match 7:Elapsed time : 5.187 ms
,03-19 11:44:57.518  2751  2880 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:44:57.518  3029  3029 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-19 11:44:57.538  3086  3086 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:57.538  3086  3086 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:57.538  2365  3094 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-19 11:44:57.538  2365  3094 D Mms/TelephonyPermission: isDefault true
,03-19 11:44:57.538  3068  3068 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-19 11:44:57.548  1469  1477 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2365
,03-19 11:44:57.548  2365  2365 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-19 11:44:57.548  3029  3029 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6423-6425)
03-19 11:44:57.548  3029  3029 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 11:44:57.548  1017  1342 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
03-19 11:44:57.548  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
03-19 11:44:57.558  1017  1342 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:57.558  1017  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:57.558  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-19 11:44:57.568  3014  3071 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 36307
,03-19 11:44:57.568  1017  1226 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,03-19 11:44:57.578  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:57.578  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:57.578  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:57.578  3068  3068 V SmartcardService: main Received broadcast
03-19 11:44:57.578  3068  3068 V SmartcardService: Starting smartcard service after boot completed
03-19 11:44:57.578  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:57.588  1017  1039 D SensorService: [SO] currT = 36460104828, prevT = 36130069307, diff = 330035521, [0.134 0.383 10.113]
03-19 11:44:57.588  1017  1039 D SensorService: [SO] 0.134 0.383 10.113
03-19 11:44:57.588  1017  1039 D SensorService: [SO] [100 -> 255]
,03-19 11:44:57.588  3029  3029 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6a443b1}
03-19 11:44:57.588  3086  3086 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-19 11:44:57.588  3029  3029 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 11:44:57.588  3086  3086 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-19 11:44:57.588  3086  3086 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 11:44:57.598  3029  3029 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
03-19 11:44:57.588  3086  3086 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-19 11:44:57.588  3086  3086 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 11:44:57.588  3086  3086 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-19 11:44:57.598  3108  3108 E Zygote  : MountEmulatedStorage()
,03-19 11:44:57.598  3108  3108 I libpersona: KNOX_SDCARD checking this for 10048
03-19 11:44:57.598  3108  3108 E Zygote  : v2
03-19 11:44:57.598  3108  3108 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:57.598  3108  3108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:57.598  3108  3108 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:57.598  1017  1226 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3108 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-19 11:44:57.608  3108  3108 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:44:57.608  1017  1377 D ActivityManager: startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
03-19 11:44:57.608  1017  1377 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,03-19 11:44:57.608  1017  1377 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:44:57.608  1017  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-19 11:44:57.608  1017  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-19 11:44:57.608  1017  1029 I ActivityManager: Killing 2198:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,03-19 11:44:57.628  1017  3012 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
03-19 11:44:57.628  1017  3012 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,03-19 11:44:57.628  1017  3012 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:57.628  1017  3012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:57.628  1017  3012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-19 11:44:57.638  1469  1477 D TP/MmsSmsProvider: query,matched:200, calling pid = 2365
,03-19 11:44:57.638  3108  3108 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:57.648  3108  3108 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:57.648  2887  2887 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-19 11:44:57.648  1469  1477 D TP/MmsSmsProvider: match 200:Elapsed time : 11.566 ms
,03-19 11:44:57.658  3029  3029 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-19 11:44:57.658  3029  3029 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:44:57.658  3029  3029 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-19 11:44:57.668  1017  1377 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,03-19 11:44:57.668  1238  3013 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-19 11:44:57.668  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.668  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.668  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.668  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:57.668  2365  2365 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,03-19 11:44:57.678  2365  3124 D Mms/TelephonyPermission: isDefault true
,03-19 11:44:57.678  2365  3124 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
,03-19 11:44:57.678  2365  3124 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 169.661615
,03-19 11:44:57.678  3108  3108 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-19 11:44:57.678  3108  3108 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 11:44:57.678  1017  1041 E libprocessgroup: failed to kill 1 processes for processgroup 2110
,03-19 11:44:57.678  3108  3108 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-19 11:44:57.698  3029  3029 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-19 11:44:57.698  3029  3029 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
03-19 11:44:57.698  3029  3029 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
03-19 11:44:57.698  3135  3135 E Zygote  : MountEmulatedStorage(),
03-19 11:44:57.698  3135  3135 E Zygote  : v2
03-19 11:44:57.698  1017  1377 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3135 uid=10157 gids={50157, 9997} abi=armeabi-v7a,
03-19 11:44:57.698  3135  3135 I libpersona: KNOX_SDCARD checking this for 10157,
03-19 11:44:57.698  3135  3135 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:57.698  3135  3135 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-19 11:44:57.708  3029  3029 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
03-19 11:44:57.708  3029  3029 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-19 11:44:57.708  3029  3029 I Adreno-EGL: Build Date: 04/06/15 Mon
03-19 11:44:57.708  3029  3029 I Adreno-EGL: Local Branch: 
03-19 11:44:57.708  3029  3029 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-19 11:44:57.708  3029  3029 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-19 11:44:57.708  3029  3029 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-19 11:44:57.708  1017  1226 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context,
03-19 11:44:57.708  1017  1226 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-19 11:44:57.708  3135  3135 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-19 11:44:57.708  2295  2295 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,03-19 11:44:57.708  3135  3135 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-19 11:44:57.708  1017  1226 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:44:57.708  1017  1226 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:57.708  1017  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-19 11:44:57.728  3047  3130 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,03-19 11:44:57.748   297   297 E USB_UICC: Timeout! No signal received. Retry num = 30
,03-19 11:44:57.748  2887  3142 E SQLiteLog: (283) recovered 25 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal,
,03-19 11:44:57.748  3135  3135 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:57.758  3135  3135 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:57.768   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 11:44:57.768  1017  1041 W libprocessgroup: failed to open /acct/uid_10050/pid_2198/cgroup.procs: No such file or directory
,03-19 11:44:57.778  3047  3130 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,03-19 11:44:57.778   368   368 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 10003, gid 10003, pid 3047
03-19 11:44:57.778   368   368 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
03-19 11:44:57.778  3047  3130 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,03-19 11:44:57.778  3047  3130 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,03-19 11:44:57.778   368   368 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 10003, gid 10003, pid 3047
03-19 11:44:57.778   368   368 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,03-19 11:44:57.808   258  1796 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-19 11:44:57.808   258  1099 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-19 11:44:57.828  1017  1041 W libprocessgroup: failed to open /acct/uid_10031/pid_2171/cgroup.procs: No such file or directory
,03-19 11:44:57.858   297   297 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-19 11:44:57.858   297   297 E USB_UICC: usb_uicc_init_qmi failed ! 
03-19 11:44:57.858   297   297 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-19 11:44:57.858   297   297 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-19 11:44:57.868  1469  1726 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-19 11:44:57.868  1469  1726 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
,03-19 11:44:57.868  1469  1726 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-19 11:44:57.868  1469  1726 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
,03-19 11:44:57.868  1469  1726 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81,
03-19 11:44:57.878  2887  2904 W art     : Suspending all threads took: 16.995ms
03-19 11:44:57.878  1469  1726 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-19 11:44:57.878  1469  1726 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-19 11:44:57.878  1469  1726 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-19 11:44:57.878  1469  1726 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-19 11:44:57.878  1469  1726 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id),
03-19 11:44:57.878  1469  1726 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-19 11:44:57.878  1469  1726 D TP/MmsSmsProvider: delete threadId: 9223372036854775806,
03-19 11:44:57.878  1469  1726 D TP/MmsSmsProvider: need read changed broadcast:false
03-19 11:44:57.878  2365  3124 D Mms/Conversation: deleteTempConversation(),deleted=0,
,03-19 11:44:57.898  1017  1095 V AlarmManager: waitForAlarm result :8,
03-19 11:44:57.898  1017  1095 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 11:44:57.938  1017  1506 I art     : Explicit concurrent mark sweep GC freed 144305(8MB) AllocSpace objects, 5(1821KB) LOS objects, 33% free, 26MB/39MB, paused 2.727ms total 252.144ms
,03-19 11:44:57.938  1017  1027 I art     : WaitForGcToComplete blocked for 226.614ms for cause HeapTrim
,03-19 11:44:57.958  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-19 11:44:57.958  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-19 11:44:57.968  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:44:57.968  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-19 11:44:57.968  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-19 11:44:57.978  1017  1342 D ActivityManager: startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
,03-19 11:44:57.978  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.978  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.978  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:57.978  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:57.998  3179  3179 E Zygote  : MountEmulatedStorage()
03-19 11:44:57.998  3179  3179 E Zygote  : v2
03-19 11:44:57.998  3179  3179 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:44:57.998  3179  3179 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:57.998  3179  3179 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:57.998  1017  1342 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3179 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 11:44:58.008  3179  3179 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:58.008  1017  1377 D ActivityManager: startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
03-19 11:44:58.008  1017  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,03-19 11:44:58.008  3179  3179 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:44:58.018   275  1010 D EnterpriseController: uids 10120
03-19 11:44:58.018   275  1010 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-19 11:44:58.018   275  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10120
,03-19 11:44:58.018  1017  1377 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:44:58.018  1017  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:44:58.018  1017  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
03-19 11:44:58.018  3135  3135 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 11:44:58.018  1469  1480 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-19 11:44:58.028  1017  1149 D SettingsProvider: name = block_emergency_message
03-19 11:44:58.028  1017  1149 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 11:44:58.028  1017  1149 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 11:44:58.028  1017  1149 D SettingsProvider: selectionArgs: false
03-19 11:44:58.028  1017  1149 D SettingsProvider: selectionArgs: 10048
03-19 11:44:58.028  1017  1149 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 11:44:58.028  1017  1149 D SettingsProvider: ret = -1
,03-19 11:44:58.028  1017  3163 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,03-19 11:44:58.028  1469  1480 D TP/MmsSmsProvider: need read changed broadcast:false
,03-19 11:44:58.038  1238  3013 V MediaScanner: processDirectory :  /system/media
,03-19 11:44:58.048  2887  2887 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-19 11:44:58.068  1469  1480 D TP/SmsProvider: query,matched:0, calling pid = 2365
,03-19 11:44:58.068  1017  3012 D SettingsProvider: name = next_alarm_formatted
,03-19 11:44:58.068  1017  3012 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-19 11:44:58.068  1017  3012 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 11:44:58.068  1017  3012 D SettingsProvider: selectionArgs: false
,03-19 11:44:58.068  1017  3012 D SettingsProvider: selectionArgs: 10085
,03-19 11:44:58.068  1017  3012 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-19 11:44:58.068  1017  3012 D SettingsProvider: ret = -1
,03-19 11:44:58.068  1469  1480 D TP/SmsProvider: match 0:Elapsed time : 6.630 ms
,03-19 11:44:58.078  1017  3012 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,03-19 11:44:58.088  1238  3013 V MediaScanner:  prescan time: 621ms (DB items: 141)
03-19 11:44:58.088  1238  3013 V MediaScanner:     scan time: 64ms (Caching mode: true), (makeEntry time: 29ms ~45%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-19 11:44:58.088  1238  3013 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-19 11:44:58.088  1238  3013 V MediaScanner:    total time: 685ms
03-19 11:44:58.088  1238  3013 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
,03-19 11:44:58.088  1184  1184 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 11:44:58.088  1238  3013 D MediaScanner: checkDefaultSounds
03-19 11:44:58.088  1238  3013 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
,03-19 11:44:58.088  2365  3124 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-19 11:44:58.088  2365  3124 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-19 11:44:58.088  2365  3124 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
,03-19 11:44:58.098  3179  3179 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:44:58.098  1238  3013 D MediaScanner: OK. alarm_alert is already exist in setting DB.
,03-19 11:44:58.098  3179  3179 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:58.108  1238  3013 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
,03-19 11:44:58.108  1017  3163 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-19 11:44:58.108  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.108  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.108  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.108  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:58.118  1238  3013 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-19 11:44:58.118  1469  1684 D TP/SmsProvider: query,matched:51, calling pid = 2365
,03-19 11:44:58.118  1469  1684 D TP/SmsProvider: match 51:Elapsed time : 2.668 ms
,03-19 11:44:58.118  1238  3013 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-19 11:44:58.128  3029  3158 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-19 11:44:58.128  1469  1726 D TP/SmsProvider: query,matched:26, calling pid = 2365
,03-19 11:44:58.128  1469  1726 D TP/SmsProvider: match 26:Elapsed time : 4.357 ms
,03-19 11:44:58.138  3211  3211 E Zygote  : MountEmulatedStorage()
03-19 11:44:58.138  3211  3211 I libpersona: KNOX_SDCARD checking this for 10159
03-19 11:44:58.138  3211  3211 E Zygote  : v2
03-19 11:44:58.138  3211  3211 I libpersona: KNOX_SDCARD not a persona
03-19 11:44:58.138  3211  3211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:58.138  3211  3211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:44:58.138  1017  3163 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3211 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 11:44:58.148  1238  3013 D MediaScanner: OK. ringtone is already exist in setting DB.
03-19 11:44:58.148  3211  3211 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
03-19 11:44:58.148  1238  3013 D MediaScannerService: !@done scanning volume internal
,03-19 11:44:58.168   307   307 I art     : Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 24.773ms
,03-19 11:44:58.188   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 601us total 16.656ms
,03-19 11:44:58.188  1017  1226 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-19 11:44:58.188  1017  1226 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-19 11:44:58.188  1833  1833 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 11:44:58.198  1238  3013 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private],
,03-19 11:44:58.208   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 20.213ms
,03-19 11:44:58.208  2641  2641 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2641) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-19 11:44:58.208  2641  2641 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2641) ACTION_MEDIA_SCANNER_FINISHED = /system/media
,03-19 11:44:58.208  2641  2641 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2641) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-19 11:44:58.208  2365  3094 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-19 11:44:58.208  3211  3211 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:44:58.208  3211  3211 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:58.218  2365  3124 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-19 11:44:58.218  2365  3124 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-19 11:44:58.218  2365  3124 D Mms/TelephonyPermission: isDefault true
,03-19 11:44:58.228  1017  1395 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,03-19 11:44:58.228  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,03-19 11:44:58.228  2887  3217 W AccountFeatureHelper: Write apps_features disabled false
,03-19 11:44:58.228  1469  1480 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2365
,03-19 11:44:58.238  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:58.238  1017  1395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:58.238  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,03-19 11:44:58.248  1334  1334 I WifiCredService: onCreate
,03-19 11:44:58.268  2907  2920 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-19 11:44:58.268  3029  3029 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:44:58.298  1238  3013 D MediaProvider: savePlaylistTableInBulkDeleter started
03-19 11:44:58.298  1238  3013 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-19 11:44:58.298  2907  2920 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
,03-19 11:44:58.298  2907  2920 D BadgeProvider: sendNotify, [notify] : null
03-19 11:44:58.298  2907  2920 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-19 11:44:58.298  2907  2920 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-19 11:44:58.298  2907  2920 D BadgeProvider: update, [UpdateCount] : 1
,03-19 11:44:58.298  1489  1489 D Launcher.Model: reloadBadges entered.
,03-19 11:44:58.298  2365  3094 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-19 11:44:58.308  3211  3211 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
,03-19 11:44:58.308  1238  3013 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-19 11:44:58.308  1334  1334 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-19 11:44:58.308  1334  1334 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-19 11:44:58.308  1334  1334 D MY_TAG  : Action boot completed received
,03-19 11:44:58.308  1469  1477 D TP/MmsSmsProvider: query,matched:200, calling pid = 2365
,03-19 11:44:58.318  1334  1334 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,03-19 11:44:58.318  1469  1477 D TP/MmsSmsProvider: match 200:Elapsed time : 4.211 ms
,03-19 11:44:58.318  3029  3029 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-19 11:44:58.318  1238  3013 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-19 11:44:58.318  1238  3013 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-19 11:44:58.318  1238  3013 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,03-19 11:44:58.318  1238  3013 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,03-19 11:44:58.318  1238  3013 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-19 11:44:58.318  1017  1134 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,03-19 11:44:58.328  1017  1134 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-19 11:44:58.328  1017  1134 E WifiNative-wlan0: invaild command id : 215
,03-19 11:44:58.328  3179  3179 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,03-19 11:44:58.328  1238  3013 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-19 11:44:58.328  1184  1184 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 11:44:58.328  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 11:44:58.328  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 11:44:58.338  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 11:44:58.338  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 11:44:58.338  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 11:44:58.338  2365  3094 D Mms/MessagingNotification: remove alarm
03-19 11:44:58.348  3086  3086 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 178.668ms
,03-19 11:44:58.348  3029  3029 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-19 11:44:58.348  3029  3029 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-19 11:44:58.358  2365  3231 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-19 11:44:58.358  3029  3029 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-19 11:44:58.378  1334  1334 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
03-19 11:44:58.378  1334  1334 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
,03-19 11:44:58.378  1334  1334 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,03-19 11:44:58.378  3029  3029 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 11:44:58.378  3029  3029 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:44:58.378  1334  1334 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-19 11:44:58.378  1334  3234 V NearbySettings: MountReceiver.mPrefHandler - 7002
,03-19 11:44:58.388  1017  3162 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,03-19 11:44:58.398  1017  1506 D ActivityManager: startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
03-19 11:44:58.398  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.398  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.398  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.398  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:58.408  1238  3013 V MediaScanner: processDirectory :  /storage/emulated/0
,03-19 11:44:58.408  1238  3013 D MediaScanner: Skipping:
,03-19 11:44:58.408  1238  3013 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-19 11:44:58.428  3237  3237 E Zygote  : MountEmulatedStorage()
03-19 11:44:58.428  3237  3237 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:44:58.428  3237  3237 E Zygote  : v2
03-19 11:44:58.428  3237  3237 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:58.428  3237  3237 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:58.428  3237  3237 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:44:58.438  3237  3237 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:44:58.438  1017  1506 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3237 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 11:44:58.438  1017  1506 I ActivityManager: Killing 2254:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,03-19 11:44:58.448  1469  1684 I art     : Explicit concurrent mark sweep GC freed 40248(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/13MB, paused 1.060ms total 73.163ms
03-19 11:44:58.448  1238  3013 D MediaScanner: Skipping:
03-19 11:44:58.448  1238  3013 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,03-19 11:44:58.458  1469  1684 D TP/SmsProvider: query,matched:0, calling pid = 2365
,03-19 11:44:58.458  1469  1684 D TP/SmsProvider: match 0:Elapsed time : 2.116 ms
,03-19 11:44:58.468  2365  3094 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 790.46125
,03-19 11:44:58.478  1184  1184 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 11:44:58.478  1334  1334 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-19 11:44:58.478  1334  1334 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-19 11:44:58.488  3237  3237 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:58.488  3237  3237 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:58.488  3179  3179 D DSM     : [Lines:107] Normal booted,
03-19 11:44:58.488  3179  3179 D DSM     : [Lines:114] Boot completed
,03-19 11:44:58.488  1017  2840 D SettingsProvider: name = personal_mode_enabled
,03-19 11:44:58.488  1469  1726 D TP/SmsProvider: query,matched:0, calling pid = 2365
,03-19 11:44:58.488   368   368 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,03-19 11:44:58.508  1469  1726 D TP/SmsProvider: match 0:Elapsed time : 15.776 ms
,03-19 11:44:58.518  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,03-19 11:44:58.518  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.518  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.518  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.518  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:58.528  3029  3255 D OpenGLRenderer: Render dirty regions requested: true
,03-19 11:44:58.528  3256  3256 E Zygote  : MountEmulatedStorage()
,03-19 11:44:58.528  3256  3256 E Zygote  : v2
03-19 11:44:58.528  3256  3256 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:44:58.528  3256  3256 I libpersona: KNOX_SDCARD not a persona
03-19 11:44:58.538  3256  3256 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:58.538  3256  3256 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:44:58.538  3256  3256 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:44:58.538  1238  3013 V MediaScanner: processDirectory :  /storage/extSdCard
03-19 11:44:58.538  1017  1030 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3256 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 11:44:58.538  1238  3013 W MediaScanner: Error opening directory, reason : Permission denied.
,03-19 11:44:58.538  1017  1030 I ActivityManager: Killing 1626:com.google.android.partnersetup/u0a15 (adj 15): empty #31
03-19 11:44:58.538  1238  3013 W MediaScanner: 7klwibgf7fxlKdCbid7,
,03-19 11:44:58.548  1017  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-19 11:44:58.548  1017  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
,03-19 11:44:58.548  1017  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false,
,03-19 11:44:58.548  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-19 11:44:58.548  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,03-19 11:44:58.558  1017  1149 I ActivityManager: Killing 2349:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-19 11:44:58.558  3029  3029 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-19 11:44:58.558  3029  3029 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-19 11:44:58.568   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-19 11:44:58.578  1017  3162 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,03-19 11:44:58.578  3047  3130 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
,03-19 11:44:58.578  2887  3207 W Flag    : Duration spec must be at least 2 characters long
03-19 11:44:58.578  3047  3130 I SecureStorage: [INFO]: SPID(0x00000005)Skip using SecureStorageExceptionJNI
,03-19 11:44:58.578  3256  3256 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:44:58.578  3256  3256 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:58.588  1017  1226 D InputDispatcher: Focus entered window: 3029,
,03-19 11:44:58.588  1017  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.588  1017  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.588  1017  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.588  1017  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:58.588  1469  1477 D TP/SmsProvider: query,matched:51, calling pid = 2365
,03-19 11:44:58.588  1238  3013 V MediaScanner:  prescan time: 84ms (DB items: 27)
03-19 11:44:58.588  1238  3013 V MediaScanner:     scan time: 136ms (Caching mode: true), (makeEntry time: 123ms ~90%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-19 11:44:58.588  1238  3013 V MediaScanner: postscan time: 46ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-19 11:44:58.588  1238  3013 V MediaScanner:    total time: 266ms
03-19 11:44:58.588  1238  3013 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-19 11:44:58.588  3029  3029 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-19 11:44:58.588  3029  3255 I OpenGLRenderer: Initialized EGL, version 1.4
,03-19 11:44:58.598  1017  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 11:44:58.598  1017  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-19 11:44:58.598  1469  1469 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-19 11:44:58.598  1469  1469 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-19 11:44:58.598  3272  3272 E Zygote  : MountEmulatedStorage()
03-19 11:44:58.598  1469  1469 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-19 11:44:58.598  3272  3272 E Zygote  : v2
03-19 11:44:58.598  3272  3272 I libpersona: KNOX_SDCARD checking this for 10160
03-19 11:44:58.598  3272  3272 I libpersona: KNOX_SDCARD not a persona
03-19 11:44:58.598  1469  1469 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 11:44:58.598  1469  1469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 11:44:58.598  1469  1469 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-19 11:44:58.598  3272  3272 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:58.608  3029  3255 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-19 11:44:58.608  3029  3255 D OpenGLRenderer: Enabling debug mode 0
03-19 11:44:58.608  1469  1477 D TP/SmsProvider: match 51:Elapsed time : 17.936 ms
,03-19 11:44:58.608  3272  3272 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:44:58.608  3272  3272 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:44:58.608  1017  3162 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3272 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,03-19 11:44:58.608  1017  3162 I ActivityManager: Killing 2405:com.sec.android.omc/1000 (adj 15): empty #31
,03-19 11:44:58.618  1238  3013 D MediaScannerService: !@done scanning volume external
,03-19 11:44:58.618  2641  2641 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2641) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-19 11:44:58.628  2641  2641 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2641) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-19 11:44:58.628  2641  2641 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2641) ...
03-19 11:44:58.628  2641  2641 D FactoryTestApp: [Support$Values.getString](2641) id=MODEL_COMMUNICATION_MODE, value=gsm
03-19 11:44:58.628  2641  2641 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2641) mConnectionMode = gsm
,03-19 11:44:58.628  2641  2641 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2641) Create IPCWriterToSecPhoneService
03-19 11:44:58.628  2641  2641 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2641)  
03-19 11:44:58.628  2641  2641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-19 11:44:58.628  1017  1395 D ActivityManager: bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
03-19 11:44:58.628  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-19 11:44:58.638  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:44:58.638  1017  1395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-19 11:44:58.638  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-19 11:44:58.648  3272  3272 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:44:58.648  3272  3272 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:58.658  1017  3012 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-19 11:44:58.668  1017  3288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 11:44:58.678  1184  1184 D PanelView: There is/are notification(s) 
,03-19 11:44:58.678  3029  3029 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@131635d2 time:37559
,03-19 11:44:58.688  3256  3256 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-19 11:44:58.688  1799  1799 I SamsungIME: getCurrentCandidateView
,03-19 11:44:58.708  1334  1334 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
,03-19 11:44:58.708   289   289 E SMD     : DCD OFF
03-19 11:44:58.708  1334  1334 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-19 11:44:58.718  1017  1049 I ActivityManager: Displayed Component not be shown by security: +1s523ms
03-19 11:44:58.718  2641  2641 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2641) connected done
,03-19 11:44:58.718  2641  2641 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2641) Send Response Message to SecPhone
,03-19 11:44:58.718  2641  2641 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2641) Response ��
,03-19 11:44:58.718  1017  1049 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,03-19 11:44:58.718  1017  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{27834147 u0 com.test.thalitest/.MainActivity t12} time:37598
03-19 11:44:58.718  1017  1049 W ActivityManager: mDVFSHelper.release()
,03-19 11:44:58.728  1017  1042 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-19 11:44:58.728   312  1074 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-19 11:44:58.738  2641  2641 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2641) Send BOOTING COMPLETED done
,03-19 11:44:58.748  3272  3272 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-19 11:44:58.748  1017  1041 W libprocessgroup: failed to open /acct/uid_10015/pid_1626/cgroup.procs: No such file or directory
03-19 11:44:58.748  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2349/cgroup.procs: No such file or directory
03-19 11:44:58.748  1017  1041 W libprocessgroup: failed to open /acct/uid_10113/pid_2254/cgroup.procs: No such file or directory
03-19 11:44:58.748  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2405/cgroup.procs: No such file or directory
03-19 11:44:58.748  2365  3124 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-19 11:44:58.758  2907  2920 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-19 11:44:58.768  1334  1334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-19 11:44:58.768  1334  1334 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-19 11:44:58.778   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 11:44:58.778  2663  2767 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-19 11:44:58.778  3256  3256 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-19 11:44:58.788  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-19 11:44:58.788  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,03-19 11:44:58.788  3256  3256 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,03-19 11:44:58.798  2663  2767 D BluetoothMediaBrowser: no now playing list
03-19 11:44:58.798  2663  2767 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-19 11:44:58.808  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-19 11:44:58.818  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-19 11:44:58.818  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-19 11:44:58.818  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-19 11:44:58.818  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-19 11:44:58.818  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-19 11:44:58.818  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-19 11:44:58.828  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-19 11:44:58.828   312  1074 D AT_Distributor: SetAtdStatus(), 1_1_0
03-19 11:44:58.828   312  1074 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-19 11:44:58.838  3256  3256 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,03-19 11:44:58.838  3256  3256 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,03-19 11:44:58.838  1017  3163 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,03-19 11:44:58.838  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:58.838  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:58.838  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.838  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:58.858  3298  3298 E Zygote  : MountEmulatedStorage()
,03-19 11:44:58.858  3298  3298 E Zygote  : v2
,03-19 11:44:58.858  3298  3298 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:44:58.858  3298  3298 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:58.858  3298  3298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:58.858  1017  3163 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3298 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 11:44:58.858  3298  3298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:44:58.858  3298  3298 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-19 11:44:58.868  1334  1334 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-19 11:44:58.878  2907  2920 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-19 11:44:58.878  2907  2920 D BadgeProvider: sendNotify, [notify] : null
03-19 11:44:58.878  2907  2920 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-19 11:44:58.878  2907  2920 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-19 11:44:58.878  2907  2920 D BadgeProvider: update, [UpdateCount] : 1
03-19 11:44:58.878  1489  1489 D Launcher.Model: reloadBadges entered.
,03-19 11:44:58.878  2365  3124 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-19 11:44:58.888  2365  3124 D Mms/MessagingNotification: remove alarm
,03-19 11:44:58.888  3272  3272 D [0]UMC:UMCContentProvider: @onCreate
,03-19 11:44:58.898  3298  3298 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:58.898  3298  3298 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:58.898  3272  3272 D [0]UMC:Core: onCreate(): 
03-19 11:44:58.898  3272  3272 D [0]UMC:Core: @isManagedProfileUser
03-19 11:44:58.898  3272  3272 D [0]UMC:Core: userId: 0
,03-19 11:44:58.908  2365  3312 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-19 11:44:58.908  1334  1334 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
,03-19 11:44:58.908  1334  1334 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-19 11:44:58.908  3272  3272 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-19 11:44:58.908  3272  3272 D [0]UMC:Core: userInfo.isManagedProfile() : false
,03-19 11:44:58.908  1334  1334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-19 11:44:58.908  1469  1684 D TP/SmsProvider: query,matched:0, calling pid = 2365
,03-19 11:44:58.918  1334  3315 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-19 11:44:58.918  1469  1684 D TP/SmsProvider: match 0:Elapsed time : 5.978 ms
,03-19 11:44:58.928  2365  3124 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 456.896093
,03-19 11:44:58.928  1017  1377 I ActivityManager: Killing 2420:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,03-19 11:44:58.938   258   448 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-19 11:44:58.938   258  1099 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-19 11:44:58.948  1017  1501 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,03-19 11:44:58.948  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.948  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.948  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:58.948  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:58.948  3272  3272 D [0]UMC:DeviceInfo: USA==US==
,03-19 11:44:58.968  3316  3316 E Zygote  : MountEmulatedStorage()
03-19 11:44:58.968  3316  3316 E Zygote  : v2
03-19 11:44:58.968  3316  3316 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:44:58.968  3316  3316 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-19 11:44:58.968  3316  3316 I libpersona: KNOX_SDCARD not a persona
03-19 11:44:58.968  3316  3316 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:58.968  1017  1501 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3316 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 11:44:58.968  3316  3316 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:44:58.998  3316  3316 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:58.998  3316  3316 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:58.998  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2420/cgroup.procs: No such file or directory
,03-19 11:44:59.008  3316  3316 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 11:44:59.018  1017  3012 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,03-19 11:44:59.018  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.018  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.018  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.018  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:59.028  1017  1017 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,03-19 11:44:59.028  3332  3332 E Zygote  : MountEmulatedStorage()
,03-19 11:44:59.028  3332  3332 E Zygote  : v2
03-19 11:44:59.028  3332  3332 I libpersona: KNOX_SDCARD checking this for 10150
03-19 11:44:59.028  3332  3332 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:59.038  1017  3012 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3332 uid=10150 gids={50150, 9997} abi=armeabi-v7a,
,03-19 11:44:59.058  3298  3298 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-19 11:44:59.078  3316  3316 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-19 11:44:59.118  3332  3332 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:59.118  3332  3332 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:44:59.118  3332  3332 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-19 11:44:59.148  3332  3332 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:59.148  3332  3332 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:59.158  1799  1799 D SamsungIME: Dismiss ExpandCandiate
,03-19 11:44:59.178  3029  3029 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3029
,03-19 11:44:59.188  3272  3272 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-19 11:44:59.198  3272  3272 D [0]UMC:AdminManager: init - start
,03-19 11:44:59.218  3272  3272 D [0]UMC:AdminManager: loadAdmins
,03-19 11:44:59.228  3272  3272 D [0]UMC:AdminManager: init - end
,03-19 11:44:59.228  3272  3272 D GSLBManager: migrateStoredUrlFromOldPref
,03-19 11:44:59.238  3272  3272 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-19 11:44:59.238  3272  3272 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-19 11:44:59.248  3272  3272 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-19 11:44:59.248  3272  3272 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-19 11:44:59.248  3272  3272 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-19 11:44:59.248  3272  3272 D [0]UMC:UMCAdmin: isContainer : 0
,03-19 11:44:59.278  1017  1395 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-19 11:44:59.278  3272  3272 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
,03-19 11:44:59.278  3272  3272 D [0]UMC:UMCAdmin: isContainer : 0
,03-19 11:44:59.288  3272  3272 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-19 11:44:59.298  1017  3162 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,03-19 11:44:59.298  1017  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:59.298  1017  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.298  1017  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.298  1017  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:59.318  3354  3354 E Zygote  : MountEmulatedStorage()
03-19 11:44:59.318  3354  3354 E Zygote  : v2
03-19 11:44:59.318  3354  3354 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:44:59.318  3354  3354 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:59.318  3354  3354 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:59.328  1017  3162 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3354 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 11:44:59.328  1017  3162 I ActivityManager: Killing 2439:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
03-19 11:44:59.328  3354  3354 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:44:59.328  3354  3354 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:44:59.328  1017  3164 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
03-19 11:44:59.328  1017  3164 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
03-19 11:44:59.328  1017  3164 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:59.328  1017  3164 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:59.328  1017  3164 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-19 11:44:59.338  3272  3272 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-19 11:44:59.348  3272  3272 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-19 11:44:59.348  3272  3272 D [0]UMC:CoreReceiver:  check PreETag 
,03-19 11:44:59.358  3354  3354 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:59.358  3354  3354 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:59.368  3298  3298 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-19 11:44:59.368  3272  3272 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-19 11:44:59.368  3272  3272 V [0]UMC:ProfileStorage: Enter loadList
,03-19 11:44:59.368  3272  3272 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-19 11:44:59.368  3272  3272 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-19 11:44:59.378  3316  3316 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-19 11:44:59.378  3272  3272 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-19 11:44:59.378  3272  3272 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-19 11:44:59.378  3272  3272 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-19 11:44:59.378  3272  3272 D [0]UMC:UMCAdmin: isContainer : 0
,03-19 11:44:59.378  3316  3316 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-19 11:44:59.378  1017  2840 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-19 11:44:59.388  3272  3272 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-19 11:44:59.388  3272  3272 D [0]UMC:UMCAdmin: isContainer : 0
,03-19 11:44:59.388  1017  1342 I ActivityManager: Killing 2338:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-19 11:44:59.388  3272  3272 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-19 11:44:59.398  3272  3272 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-19 11:44:59.398  3272  3272 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
,03-19 11:44:59.398  3272  3272 I [0]UMC:Core: shutdown
,03-19 11:44:59.398  1017  1149 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-19 11:44:59.398  1017  1149 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:44:59.408  3354  3354 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-19 11:44:59.408  3316  3316 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-19 11:44:59.408  1017  1149 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-19 11:44:59.408  1017  1149 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-19 11:44:59.418  3272  3272 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-19 11:44:59.428  3029  3029 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-19 11:44:59.428  3272  3272 I art     : System.exit called, status: 0
,03-19 11:44:59.438  3272  3272 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-19 11:44:59.438  3298  3298 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,03-19 11:44:59.448  3298  3298 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-19 11:44:59.448  3298  3298 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-19 11:44:59.448  3298  3298 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-19 11:44:59.448  3298  3298 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-19 11:44:59.468  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2338/cgroup.procs: No such file or directory
,03-19 11:44:59.468  1017  1041 W libprocessgroup: failed to open /acct/uid_10131/pid_2439/cgroup.procs: No such file or directory
,03-19 11:44:59.468  1017  3164 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,03-19 11:44:59.468  1017  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.468  1017  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.468  1017  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.468  1017  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:59.488  3374  3374 E Zygote  : MountEmulatedStorage(),
03-19 11:44:59.488  3374  3374 E Zygote  : v2
03-19 11:44:59.488  3374  3374 I libpersona: KNOX_SDCARD checking this for 10086
03-19 11:44:59.488  3374  3374 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:59.498  1017  3012 E Tethering: No numeric data,
,03-19 11:44:59.488  3374  3374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-19 11:44:59.498  1017  1342 E Tethering: No numeric data
,03-19 11:44:59.498  3374  3374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-19 11:44:59.508  3374  3374 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
03-19 11:44:59.508  1017  3164 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3374 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,03-19 11:44:59.508  1017  3164 I ActivityManager: Killing 2470:com.wsomacp/u0a25 (adj 15): empty #31
,03-19 11:44:59.508  1017  1030 E Tethering: No numeric data
,03-19 11:44:59.518  1017  3163 E Tethering: No numeric data
,03-19 11:44:59.538  3374  3374 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:59.538  3374  3374 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:59.538  1017  1395 E Tethering: No numeric data
,03-19 11:44:59.558  1017  3012 E Tethering: No numeric data
,03-19 11:44:59.578  1017  1377 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3272)(adj 0) has died(179,1079)
,03-19 11:44:59.608  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-19 11:44:59.608  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-19 11:44:59.608  1316  1316 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-19 11:44:59.618  3316  3316 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-19 11:44:59.618  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-19 11:44:59.618  3316  3316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-19 11:44:59.618  1017  1226 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
03-19 11:44:59.618  1017  1226 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-19 11:44:59.628  1017  1226 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:59.628  1017  1226 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:59.628  1017  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-19 11:44:59.628  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-19 11:44:59.628  1316  1316 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-19 11:44:59.628  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-19 11:44:59.638  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-19 11:44:59.638  1184  1184 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-19 11:44:59.638  1184  1184 D OverheatReceiver: into the SAFE_MODE_ACTION
03-19 11:44:59.638  1184  1184 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-19 11:44:59.648  1184  1184 D OverheatReceiver: isSafeMode = false
,03-19 11:44:59.688  1017  1041 W libprocessgroup: failed to open /acct/uid_10025/pid_2470/cgroup.procs: No such file or directory
,03-19 11:44:59.688  1469  1469 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-19 11:44:59.688  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-19 11:44:59.698  3316  3316 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-19 11:44:59.698  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-19 11:44:59.698  3316  3316 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-19 11:44:59.698  1017  1029 D SettingsProvider: name = internet_call_settings_visibility
03-19 11:44:59.698  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 11:44:59.698  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-19 11:44:59.698  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 11:44:59.698  1017  1029 D SettingsProvider: selectionArgs: false
03-19 11:44:59.698  1017  1029 D SettingsProvider: selectionArgs: 1001
03-19 11:44:59.698  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 11:44:59.698  1017  1029 D SettingsProvider: ret = -1
,03-19 11:44:59.698  3316  3316 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-19 11:44:59.698  1469  1469 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-19 11:44:59.708  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-19 11:44:59.708  1316  1316 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-19 11:44:59.708  1334  3315 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-19 11:44:59.708  3316  3316 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-19 11:44:59.708  1334  3315 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-19 11:44:59.718  3316  3316 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-19 11:44:59.718  3316  3351 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-19 11:44:59.728  3316  3351 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-19 11:44:59.728  3316  3351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-19 11:44:59.728  1017  1395 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,03-19 11:44:59.738  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.738  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.738  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:44:59.738  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:44:59.748  3316  3316 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-19 11:44:59.748  3394  3394 E Zygote  : MountEmulatedStorage()
03-19 11:44:59.748  3394  3394 E Zygote  : v2
03-19 11:44:59.748  3394  3394 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:44:59.748  3394  3394 I libpersona: KNOX_SDCARD not a persona
,03-19 11:44:59.748  3394  3394 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:44:59.748  3394  3394 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:44:59.758  3394  3394 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:44:59.758  1017  1395 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3394 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 11:44:59.768  3029  3295 D jxcore_app_log: JniHelper::setJavaVM(0xb8d88450), pthread_self() = -1188042744
,03-19 11:44:59.778   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-19 11:44:59.778  3029  3295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-19 11:44:59.778  3029  3295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-19 11:44:59.778  3029  3295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-19 11:44:59.778  3029  3295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-19 11:44:59.778  3029  3295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-19 11:44:59.778  3029  3295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed25ec9 added. We now have 1 listener(s)
,03-19 11:44:59.788  3374  3374 E UpdateRequestReceiver: ignoring update request
,03-19 11:44:59.788  3029  3295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-19 11:44:59.788  3394  3394 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:44:59.788  3394  3394 D ActivityThread: Added TimaKeyStore provider
,03-19 11:44:59.788  3029  3295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,03-19 11:44:59.798  3029  3295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-19 11:44:59.798  3029  3295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-19 11:44:59.798  3029  3295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@781c7fc added. We now have 1 listener(s)
,03-19 11:44:59.798  3029  3295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-19 11:44:59.808  1017  2766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-19 11:44:59.808  3316  3316 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-19 11:44:59.808  3316  3316 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-19 11:44:59.818  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-19 11:44:59.818  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-19 11:44:59.818  3029  3295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-19 11:44:59.828  1799  1799 I SamsungIME: getDebugLevel  : 0x4f4c
,03-19 11:44:59.828  3029  3295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-19 11:44:59.828  3029  3295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-19 11:44:59.828  3029  3295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-19 11:44:59.828  3029  3295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-19 11:44:59.898  1799  1799 I SamsungIME: getDebugLevel  : 0x4f4c
,03-19 11:44:59.908  1017  1377 I art     : Explicit concurrent mark sweep GC freed 19333(994KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/39MB, paused 2.846ms total 190.635ms
,03-19 11:44:59.908  1017  1501 E Tethering: No numeric data
,03-19 11:44:59.918  1017  3012 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
,03-19 11:44:59.918  1017  3012 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-19 11:44:59.918  1799  1799 I SamsungIME: KeybaordView init() : load resources
,03-19 11:44:59.928  1316  1316 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-19 11:44:59.928  3316  3316 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-19 11:44:59.928  1017  3012 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:59.928  1017  3012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:59.928  1017  3012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-19 11:44:59.928  1017  1226 E Tethering: No numeric data
,03-19 11:44:59.938  1316  1316 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-19 11:44:59.938  1316  1316 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-19 11:44:59.938  1316  1316 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-19 11:44:59.938  1316  1316 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-19 11:44:59.938  1444  1444 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-19 11:44:59.938  1316  1316 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-19 11:44:59.938  1316  1316 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-19 11:44:59.948  1017  2840 E Tethering: No numeric data
,03-19 11:44:59.948  3029  3295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-19 11:44:59.958  1017  1377 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-19 11:44:59.958  1017  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-19 11:44:59.968  1017  3163 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
03-19 11:44:59.968  1017  3163 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-19 11:44:59.968  1017  3163 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:44:59.968  1017  3163 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:44:59.968  1017  3163 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-19 11:44:59.978  3374  3374 E UpdateRequestReceiver: ignoring update request
,03-19 11:44:59.978  1017  2840 D SettingsProvider: name = aw_daemon_service_key_version_check
03-19 11:44:59.978  1017  2840 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 11:44:59.978  1017  2840 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 11:44:59.978  1017  2840 D SettingsProvider: selectionArgs: false
03-19 11:44:59.978  1017  2840 D SettingsProvider: selectionArgs: 10162
03-19 11:44:59.978  1017  2840 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 11:44:59.978  1017  2840 D SettingsProvider: ret = -1
,03-19 11:44:59.978  1833  1833 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 11:44:59.988  1017  1095 V AlarmManager: waitForAlarm result :8
,03-19 11:44:59.988  1017  2840 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-19 11:44:59.998  3029  3295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-19 11:44:59.998  1017  1506 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
,03-19 11:44:59.998  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-19 11:45:00.008  1017  3164 E Tethering: No numeric data
,03-19 11:45:00.008  1316  1316 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-19 11:45:00.008  1799  1799 I SamsungIME: getCurrentKeyboard
03-19 11:45:00.008  1799  1799 I SamsungIME: getTextKeyboard
,03-19 11:45:00.008  1184  1184 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 11:45:00.008  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:00.008  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:45:00.008  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-19 11:45:00.018  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-19 11:45:00.018  1444  1444 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-19 11:45:00.018  1017  1149 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-19 11:45:00.028  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.028  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.028  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.028  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:00.028  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
03-19 11:45:00.028  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-19 11:45:00.028  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-19 11:45:00.038  1316  1316 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-19 11:45:00.038  3418  3418 E Zygote  : MountEmulatedStorage(),
03-19 11:45:00.038  3029  3295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-19 11:45:00.038  3029  3295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-19 11:45:00.038  3029  3295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-19 11:45:00.038  3029  3295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-19 11:45:00.038  3029  3295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-19 11:45:00.038  3029  3295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-19 11:45:00.038  3029  3295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-19 11:45:00.038  3029  3295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-19 11:45:00.048  3418  3418 I libpersona: KNOX_SDCARD checking this for 10057
03-19 11:45:00.038  3029  3295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-19 11:45:00.048  3418  3418 I libpersona: KNOX_SDCARD not a persona
03-19 11:45:00.038  3029  3295 D io.jxcore.node.ConnectivityMonitor: start: OK
03-19 11:45:00.038  3029  3295 I io.jxcore.node.LifeCycleMonitor: start: OK
03-19 11:45:00.048  3418  3418 E Zygote  : v2
,03-19 11:45:00.048  3418  3418 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-19 11:45:00.048  1017  1149 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3418 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-19 11:45:00.048  3029  3029 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-19 11:45:00.048  3418  3418 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:45:00.048  3418  3418 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-19 11:45:00.048  1799  1799 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-19 11:45:00.058  3374  3374 E UpdateRequestReceiver: ignoring update request
,03-19 11:45:00.058  1184  1184 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-19 11:45:00.058  1184  1184 D KeyguardUpdateMonitor: handleTimeUpdate
03-19 11:45:00.058  1316  1316 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-19 11:45:00.058  1316  1316 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-19 11:45:00.068  1017  1226 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
03-19 11:45:00.068  1017  1226 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-19 11:45:00.068  1017  1226 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:00.068  1017  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:45:00.068  1017  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-19 11:45:00.068  1184  1184 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-19 11:45:00.078  1184  1184 D SecKeyguardClockView: HomeTimezone(): 1
,03-19 11:45:00.098  1017  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 11:45:00.108  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458384300068
,03-19 11:45:00.108  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458405840000
03-19 11:45:00.108  1017  1501 V VibratorService: hasVibrator - useVibetonz: true
,03-19 11:45:00.108  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-19 11:45:00.108  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
03-19 11:45:00.108  3316  3316 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-19 11:45:00.108  3029  3029 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
03-19 11:45:00.108  1184  1184 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-19 11:45:00.108  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:00.108  1017  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-19 11:45:00.108  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-19 11:45:00.108  1184  1184 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-19 11:45:00.108  1184  1184 I KeyguardEffectViewController: *** don't update sliding image ***
,03-19 11:45:00.108  3418  3418 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:45:00.108  3029  3029 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-19 11:45:00.118  3047  3047 E BluetoothHeadset: BTStateChangeCB is registed,
,03-19 11:45:00.118  3418  3418 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:00.118  3047  3047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-19 11:45:00.118  1017  3163 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
03-19 11:45:00.118  1017  3163 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-19 11:45:00.118  1017  3163 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:00.118  1017  3163 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:45:00.118  1017  3163 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-19 11:45:00.118  3047  3047 E BluetoothHeadset: BluetoothHeadset service is binded
,03-19 11:45:00.128  3316  3316 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-19 11:45:00.138  3047  3047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-19 11:45:00.138  1017  1506 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
03-19 11:45:00.138  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-19 11:45:00.138  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:00.138  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:45:00.138  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-19 11:45:00.138  1316  1316 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458405840000
,03-19 11:45:00.168  1334  3315 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-19 11:45:00.168  1017  1226 V VibratorService: hasVibrator - useVibetonz: true
,03-19 11:45:00.178  1017  2840 V VibratorService: hasVibrator - useVibetonz: true
,03-19 11:45:00.178  3316  3351 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-19 11:45:00.198  3374  3374 E UpdateRequestReceiver: ignoring update request
,03-19 11:45:00.208   283   696 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-19 11:45:00.208   283   696 D audio_hw_extn: audio_extn_get_parameters: returns 
03-19 11:45:00.208   283   696 V msm8974_platform: platform_get_parameters: exit: returns - 
03-19 11:45:00.208   283   696 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-19 11:45:00.208   283   696 I str_params: key: 'call_forwarding' value: ''
,03-19 11:45:00.218  1316  1316 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 72
,03-19 11:45:00.218  1316  1316 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458405840000
,03-19 11:45:00.228  1942  1942 V InCall  : ProximitySensor -  - screenonImmediately: false
03-19 11:45:00.228  1942  1942 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-19 11:45:00.228  1942  1942 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-19 11:45:00.238  1942  1942 D ScoverManager: serviceVersion : 16908288
,03-19 11:45:00.238  1017  1226 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 11:45:00.238  1942  1942 D InCall  : InCallUtils - isCoverClosed false
,03-19 11:45:00.238  1444  1444 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-19 11:45:00.238  1017  1506 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 11:45:00.238  1942  1942 D InCall  : InCallUtils - isCoverClosed false
,03-19 11:45:00.248  1942  1942 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-19 11:45:00.248  1738  1738 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,03-19 11:45:00.248  1738  1738 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-19 11:45:00.258  1738  1738 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-19 11:45:00.258  1738  1738 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-19 11:45:00.258  1942  1942 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-19 11:45:00.258  1942  1942 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-19 11:45:00.258  1738  1738 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-19 11:45:00.268  1738  1738 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
03-19 11:45:00.268  1738  1738 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,03-19 11:45:00.268  1738  1738 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,03-19 11:45:00.268  1738  1738 D accuweather: [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
03-19 11:45:00.268  1334  3315 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 11:45:00.278  1942  1942 I InCall  : CallSContextMotion - stopPutDownListening
,03-19 11:45:00.278  1942  1942 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-19 11:45:00.278  1738  1738 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 11 45
,03-19 11:45:00.288  1184  1184 D PhoneStatusBarView: setCallBackground:0
,03-19 11:45:00.318  1017  1377 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 11:45:00.318  1942  1942 D InCall  : InCallUtils - isCoverClosed false
,03-19 11:45:00.328  1316  1316 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-19 11:45:00.328  1316  1316 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-19 11:45:00.328  3374  3374 E UpdateRequestReceiver: ignoring update request
,03-19 11:45:00.338  1017  1149 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 11:45:00.408  1017  1149 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:00.408  1017  1149 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:45:00.408  1017  1149 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 11:45:00.438  1017  2840 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-19 11:45:00.438  1017  2840 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.438  1017  2840 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.438  1017  2840 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.438  1017  2840 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:00.458  3444  3444 E Zygote  : MountEmulatedStorage()
,03-19 11:45:00.458  3444  3444 E Zygote  : v2
03-19 11:45:00.458  3444  3444 I libpersona: KNOX_SDCARD checking this for 10166
03-19 11:45:00.458  3444  3444 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:00.458  3444  3444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-19 11:45:00.458  1017  2840 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3444 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 11:45:00.468  3444  3444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-19 11:45:00.468  3444  3444 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-19 11:45:00.468  1942  1942 D VideoCallManager: Instantiating VideoCallManager
,03-19 11:45:00.478  1184  1184 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 11:45:00.478  1942  1942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-19 11:45:00.478  1942  1942 I GFX construct_block_size_descriptor_2d second part: took 2.333803ms for 0*0 texture 0
,03-19 11:45:00.478  1017  2840 I ActivityManager: Killing 2519:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,03-19 11:45:00.488   307   307 I art     : Explicit concurrent mark sweep GC freed 8773(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 767us total 28.330ms
,03-19 11:45:00.488  1942  1942 I GFX generate_partition_tables: took 5.404531ms for 0*0 texture 0
,03-19 11:45:00.488  3316  3351 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-19 11:45:00.488  1942  1942 I GFX raster: took 11.670779ms for 176*144 texture 0
03-19 11:45:00.488  1942  1942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb9162120 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb917a330 counterpartCT=4 counterpartW=176 counterparth=144
,03-19 11:45:00.508   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 771us total 21.159ms
,03-19 11:45:00.508  1184  1184 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 11:45:00.518  1942  1942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-19 11:45:00.518  1942  1942 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-19 11:45:00.518  1942  1942 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-19 11:45:00.518  1942  1942 I Adreno-EGL: Build Date: 04/06/15 Mon
03-19 11:45:00.518  1942  1942 I Adreno-EGL: Local Branch: 
03-19 11:45:00.518  1942  1942 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-19 11:45:00.518  1942  1942 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-19 11:45:00.518  1942  1942 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-19 11:45:00.528  1184  1184 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 11:45:00.538  3444  3444 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:45:00.538  3444  3444 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:00.538  3316  3351 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-19 11:45:00.548   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 28.127ms
,03-19 11:45:00.548  3316  3351 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-19 11:45:00.548  3316  3351 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-19 11:45:00.568  1184  1184 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 11:45:00.578  1017  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-19 11:45:00.578  1942  1942 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-19 11:45:00.588  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:00.588  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:00.588  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:00.588  3394  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-19 11:45:00.588  1942  1942 I glCompressedTexImage2D: took 0.329166ms for 320*61440 texture 37809
,03-19 11:45:00.588  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:00.598  3394  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-19 11:45:00.608  1942  1942 I draw setup: took 10.676771ms for 320*240 texture 37809,
03-19 11:45:00.608  1942  1942 E GFX GPU raster: drawn
,03-19 11:45:00.618  3468  3468 E Zygote  : MountEmulatedStorage(),
03-19 11:45:00.618  3468  3468 E Zygote  : v2
03-19 11:45:00.618  3468  3468 I libpersona: KNOX_SDCARD checking this for 10009
,03-19 11:45:00.618  3394  3463 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-19 11:45:00.618  3468  3468 I libpersona: KNOX_SDCARD not a persona
03-19 11:45:00.618  3468  3468 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-19 11:45:00.618  3468  3468 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-19 11:45:00.618  3468  3468 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-19 11:45:00.618  1017  1030 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3468 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-19 11:45:00.618  1942  1942 I GFX GPU raster ASTC: took 41.959845ms for 320*240 texture 12,
03-19 11:45:00.618  1942  1942 I GFX raster: took 42.013335ms for 320*240 texture 0
03-19 11:45:00.618  1942  1942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb917a330 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb917c670 counterpartCT=4 counterpartW=320 counterparth=240
,03-19 11:45:00.638  3394  3394 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-19 11:45:00.638  3394  3463 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-19 11:45:00.638  1017  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-19 11:45:00.638  1017  1041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,03-19 11:45:00.648  1942  1942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-19 11:45:00.648  1942  1942 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-19 11:45:00.648  1942  1942 I glCompressedTexImage2D: took 0.369531ms for 480*122880 texture 37813
03-19 11:45:00.648  1942  1942 I draw setup: took 0.740625ms for 480*640 texture 37813
03-19 11:45:00.648  1942  1942 E GFX GPU raster: drawn
03-19 11:45:00.658  1942  1942 I GFX GPU raster ASTC: took 7.032969ms for 480*640 texture 12
03-19 11:45:00.658  1942  1942 I GFX raster: took 7.110521ms for 480*640 texture 0
03-19 11:45:00.658  1942  1942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb917c670 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb93aab00 counterpartCT=4 counterpartW=480 counterparth=640
,03-19 11:45:00.678  3374  3374 E UpdateRequestReceiver: ignoring update request
,03-19 11:45:00.688  3394  3394 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-19 11:45:00.698  1942  1942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-19 11:45:00.698  1942  1942 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-19 11:45:00.698  1942  1942 I glCompressedTexImage2D: took 0.343386ms for 440*116864 texture 37809
03-19 11:45:00.698  1942  1942 I draw setup: took 0.729323ms for 440*330 texture 37809
03-19 11:45:00.698  1942  1942 E GFX GPU raster: drawn
,03-19 11:45:00.698  1942  1942 I GFX GPU raster ASTC: took 4.423802ms for 440*330 texture 12
03-19 11:45:00.698  1942  1942 I GFX raster: took 4.528228ms for 440*330 texture 0
03-19 11:45:00.698  1942  1942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb93aab00 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb93beef0 counterpartCT=4 counterpartW=440 counterparth=330
,03-19 11:45:00.708  3468  3468 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:00.708  3468  3468 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:00.708  1017  3012 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,03-19 11:45:00.708  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.708  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.708  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.708  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:00.728  3394  3463 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-19 11:45:00.738  1942  1942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640,
03-19 11:45:00.738  1942  1942 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-19 11:45:00.738  1942  1942 I glCompressedTexImage2D: took 0.402968ms for 480*163840 texture 37811
03-19 11:45:00.738  1942  1942 I draw setup: took 0.767240ms for 480*640 texture 37811
03-19 11:45:00.738  1942  1942 E GFX GPU raster: drawn
,03-19 11:45:00.738  1017  3012 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3486 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 11:45:00.748  1942  1942 I GFX GPU raster ASTC: took 5.544115ms for 480*640 texture 12,
03-19 11:45:00.748  1942  1942 I GFX raster: took 5.615625ms for 480*640 texture 0
03-19 11:45:00.748  1942  1942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb93aed00 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb93bea28 counterpartCT=4 counterpartW=480 counterparth=640
,03-19 11:45:00.748  3486  3486 E Zygote  : MountEmulatedStorage()
,03-19 11:45:00.748  3486  3486 E Zygote  : v2
03-19 11:45:00.748  3486  3486 I libpersona: KNOX_SDCARD checking this for 10092
03-19 11:45:00.748  3486  3486 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:00.748  3486  3486 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-19 11:45:00.758  3486  3486 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:45:00.758  3486  3486 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-19 11:45:00.768  3486  3486 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:00.768  3486  3486 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:00.798  3047  3047 D BluetoothA2dp: Proxy object connected
,03-19 11:45:00.808  1942  1942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-19 11:45:00.808  1942  1942 I GFX construct_block_size_descriptor_2d second part: took 1.969375ms for 0*0 texture 0
,03-19 11:45:00.818  1942  1942 I GFX generate_partition_tables: took 7.391719ms for 0*0 texture 0
,03-19 11:45:00.818  1942  1942 I GFX raster: took 11.306458ms for 176*144 texture 0
03-19 11:45:00.818  1942  1942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb93a83c0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb93a84e0 counterpartCT=4 counterpartW=176 counterparth=144
,03-19 11:45:00.838  3394  3394 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-19 11:45:00.838  3394  3394 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-19 11:45:00.838  3394  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-19 11:45:00.838  3394  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-19 11:45:00.848  3394  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-19 11:45:00.848  1334  3315 D ScoverManager: serviceVersion : 16908288
,03-19 11:45:00.878  1017  1041 W libprocessgroup: failed to open /acct/uid_10088/pid_2519/cgroup.procs: No such file or directory
,03-19 11:45:00.898  1942  1942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-19 11:45:00.898  1942  1942 I GFX construct_block_size_descriptor_2d second part: took 2.141875ms for 0*0 texture 0
,03-19 11:45:00.908  1942  1942 I GFX generate_partition_tables: took 5.999011ms for 0*0 texture 0
,03-19 11:45:00.908  1942  1942 I GFX raster: took 10.318489ms for 176*144 texture 0
03-19 11:45:00.908  1942  1942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb93a8700 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb93a86a0 counterpartCT=4 counterpartW=176 counterparth=144
,03-19 11:45:00.918  1942  1942 D ScoverManager: registerListener
,03-19 11:45:00.918  1017  2840 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 11:45:00.918  1017  1501 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 11:45:00.918  1017  1501 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@2b78c9a2, pid : 1942, uid : 1001, type : 1
,03-19 11:45:00.928  1942  1942 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-19 11:45:00.978  3029  3426 W jxcore-log: Initializing JXcore engine
03-19 11:45:00.978  3029  3426 W jxcore-log: JXcore engine is ready
,03-19 11:45:00.978  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-19 11:45:00.988  2887  3207 I System.out: Thread-348(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-19 11:45:00.988  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.988  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.988  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:00.988  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:01.008  3506  3506 E Zygote  : MountEmulatedStorage(),
03-19 11:45:01.008  3506  3506 E Zygote  : v2
03-19 11:45:01.008  3506  3506 I libpersona: KNOX_SDCARD checking this for 10015
,03-19 11:45:01.008  3506  3506 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:01.008  3506  3506 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-19 11:45:01.008  1017  1029 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3506 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-19 11:45:01.008  3506  3506 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:45:01.018  3506  3506 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-19 11:45:01.018  1017  2872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 11:45:01.028  3506  3506 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:01.028  3506  3506 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:01.048  1886  1886 E audit   : type=1400 msg=audit(1458384301.048:205): avc:  denied  { ioctl } for  pid=3426 comm="Thread-380" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-19 11:45:01.048  1886  1886 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:45:01.048  1886  1886 E audit   : type=1300 msg=audit(1458384301.048:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9ef5a8f8 items=0 ppid=307 ppcomm=main pid=3426 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-380" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-19 11:45:01.048  1886  1886 E audit   : type=1320 msg=audit(1458384301.048:205): 
,03-19 11:45:01.048  1017  2840 D LocationManagerService: getProviders()=[passive]
,03-19 11:45:01.058  3029  3426 W jxcore-log: Starting JXcore engine,
,03-19 11:45:01.118  3029  3046 I art     : Background sticky concurrent mark sweep GC freed 42204(3MB) AllocSpace objects, 4(1550KB) LOS objects, 25% free, 12MB/17MB, paused 8.151ms total 53.501ms
,03-19 11:45:01.128  3444  3504 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-19 11:45:01.128  3444  3504 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-19 11:45:01.188  2887  3207 I System.out: Thread-348(ApacheHTTPLog):isSBSettingEnabled false
03-19 11:45:01.188  2887  3207 I System.out: Thread-348(ApacheHTTPLog):isShipBuild true
03-19 11:45:01.188  2887  3207 I System.out: Thread-348(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-19 11:45:01.188  2887  3207 I System.out: Thread-348(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-19 11:45:01.218  3029  3426 W jxcore-log: Platform android
03-19 11:45:01.218  3029  3426 W jxcore-log: 
03-19 11:45:01.218  3029  3426 W jxcore-log: Process ARCH arm
03-19 11:45:01.218  3029  3426 W jxcore-log: 
,03-19 11:45:01.258  3444  3504 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-19 11:45:01.318  1334  3315 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-19 11:45:01.338  1184  1184 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 11:45:01.338  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 11:45:01.338  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 11:45:01.338  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 11:45:01.338  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 11:45:01.338  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 11:45:01.348  1334  3315 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-19 11:45:01.398  3394  3463 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-19 11:45:01.418  3394  3463 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-19 11:45:01.428  3444  3504 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-19 11:45:01.468  3444  3504 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26b38c39: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-19 11:45:01.468  3444  3504 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-19 11:45:01.468  3029  3426 I jxcore-log: JXcore Cordova bridge is ready!
03-19 11:45:01.468  3029  3426 I jxcore-log: 
,03-19 11:45:01.468  3029  3426 W jxcore-log: JXcore engine is started
,03-19 11:45:01.468  1017  1149 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-19 11:45:01.468  1017  1149 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-19 11:45:01.478  1017  1149 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:45:01.478  1017  1149 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-19 11:45:01.478  1017  1149 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-19 11:45:01.478  3029  3295 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-19 11:45:01.488  3029  3029 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-19 11:45:01.498  3394  3463 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-19 11:45:01.498  3394  3463 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-19 11:45:01.508  1017  1030 I ActivityManager: Killing 2531:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-19 11:45:01.508  3029  3426 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-19 11:45:01.508  3029  3426 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-19 11:45:01.518  1017  3012 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,03-19 11:45:01.528  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:01.528  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:01.528  3029  3029 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
03-19 11:45:01.528  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:01.528  3394  3463 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-19 11:45:01.528  1017  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:01.538  1017  3012 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3539 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 11:45:01.538  3029  3029 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-19 11:45:01.538  1017  3012 I ActivityManager: Killing 2608:com.android.calendar/u0a135 (adj 15): empty #31
03-19 11:45:01.548  1017  3012 I ActivityManager: Killing 2593:com.samsung.android.securitylogagent/1000 (adj 15): empty #32
03-19 11:45:01.548  1017  3012 I ActivityManager: Killing 2564:com.sec.android.app.camera/u0a139 (adj 15): empty #33
03-19 11:45:01.548  3539  3539 E Zygote  : MountEmulatedStorage()
03-19 11:45:01.548  3539  3539 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:45:01.548  3539  3539 E Zygote  : v2
03-19 11:45:01.548  3539  3539 I libpersona: KNOX_SDCARD not a persona
03-19 11:45:01.548  1017  1149 D FocusedStackFrame: Set to : 0
03-19 11:45:01.548  1017  1149 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-19 11:45:01.548  1017  1149 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-19 11:45:01.558  1017  1149 D InputDispatcher: Focused application set to: xxxx
03-19 11:45:01.558  3539  3539 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-19 11:45:01.558  3539  3539 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:45:01.558  1017  1149 D InputDispatcher: Focus left window: 3029
,03-19 11:45:01.568  3539  3539 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-19 11:45:01.568  1017  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 11:45:01.568  1017  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-19 11:45:01.568   258  1099 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (179 us)
,03-19 11:45:01.598  3029  3029 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,03-19 11:45:01.598  3029  3029 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-19 11:45:01.608  3316  3351 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-19 11:45:01.608  3029  3295 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 63ms. Plugin should use CordovaInterface.getThreadPool().
03-19 11:45:01.608  3394  3463 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-19 11:45:01.628  2624  2638 W art     : Suspending all threads took: 20.642ms
,03-19 11:45:01.628  3539  3539 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:01.638  3539  3539 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:01.638  1017  1342 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
03-19 11:45:01.638  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-19 11:45:01.638  1017  1342 W ActivityManager: userId = 0, bbcId = -10000,
03-19 11:45:01.638  1017  1342 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-19 11:45:01.638  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-19 11:45:01.638  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-19 11:45:01.638  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:01.638  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:01.638  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:01.658  3394  3463 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-19 11:45:01.658  1017  1342 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3557 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-19 11:45:01.658  1017  3012 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-19 11:45:01.658  1017  3012 W ActivityManager: mDVFSHelper.acquire(),
,03-19 11:45:01.658  1017  3012 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1,
03-19 11:45:01.658  1017  3012 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-19 11:45:01.658  1017  3012 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false,
,03-19 11:45:01.668  3557  3557 E Zygote  : MountEmulatedStorage(),
03-19 11:45:01.668  3557  3557 E Zygote  : v2
03-19 11:45:01.668  3557  3557 I libpersona: KNOX_SDCARD checking this for 10092
03-19 11:45:01.668  3557  3557 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:01.668  3557  3557 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-19 11:45:01.668  3557  3557 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:45:01.668  3557  3557 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-19 11:45:01.678  1489  1489 D Launcher: onRestart, Launcher: 688417261
,03-19 11:45:01.688  1489  1489 D Launcher: onStart, Launcher: 688417261
,03-19 11:45:01.688  1489  1489 D Launcher.HomeView: onStart
,03-19 11:45:01.688  1489  1489 D Launcher: onResume, Launcher: 688417261
,03-19 11:45:01.688  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-19 11:45:01.698  1017  1377 D SettingsProvider: name = kids_home_mode,
03-19 11:45:01.698  1017  1377 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 11:45:01.698  1017  1377 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 11:45:01.698  1017  1377 D SettingsProvider: selectionArgs: false,
03-19 11:45:01.698  1017  1377 D SettingsProvider: selectionArgs: 10007
03-19 11:45:01.698  1017  1377 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 11:45:01.698  1017  1377 D SettingsProvider: ret = -1
03-19 11:45:01.698  1489  1489 D Launcher.HomeView: onResume,
03-19 11:45:01.698  1017  1017 D SensorService: [SO] activate (ident=0xb94f6c38, enabled=0)
03-19 11:45:01.698  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0,
,03-19 11:45:01.698  3557  3557 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:01.698  3557  3557 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:01.708  1489  1489 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-19 11:45:01.708  1017  1017 D SensorManager: unregisterListener ::   
,03-19 11:45:01.708  1017  1017 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-19 11:45:01.708  1017  1017 D SensorService: [SO] changed settle time [0]
03-19 11:45:01.708  1017  1017 D SensorService: [SO] setDelay [200000000]
03-19 11:45:01.708  1017  1017 D SensorService: [SO] activate (ident=0xb94f6c38, enabled=1)
03-19 11:45:01.708  1017  1017 D SensorService: [SO] AR_init
03-19 11:45:01.708  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-19 11:45:01.718   289   289 E SMD     : DCD OFF,
,03-19 11:45:01.718  2295  2295 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
03-19 11:45:01.718  2295  2295 I dhcpcd  : wlan0: no IPv6 Routers available
,03-19 11:45:01.718  1017  1017 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-19 11:45:01.728  2641  3294 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3294)  
,03-19 11:45:01.748  1489  1489 D MenuAppsGridFragment: onResume
,03-19 11:45:01.748  1017  1506 D ActivityManager: handle home activity for 0
,03-19 11:45:01.748  1017  1506 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-19 11:45:01.748  1017  1506 D KnoxTimeoutHandler: post home show event for user 0
03-19 11:45:01.748  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,03-19 11:45:01.748  1017  1506 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-19 11:45:01.748  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,03-19 11:45:01.748  1017  1506 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-19 11:45:01.748  1017  1506 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false,
03-19 11:45:01.758  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-19 11:45:01.758  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,03-19 11:45:01.758  1017  1226 I ActivityManager: Killing 2684:com.android.keychain/1000 (adj 15): empty #31
,03-19 11:45:01.758   258   258 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-19 11:45:01.758  1017  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-19 11:45:01.768  3394  3463 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-19 11:45:01.768  3394  3463 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-19 11:45:01.768  3394  3463 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
03-19 11:45:01.768  1017  1501 D InputDispatcher: Focus entered window: 1489
,03-19 11:45:01.778  3394  3464 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true,
03-19 11:45:01.778  1017  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-19 11:45:01.778  3394  3464 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-19 11:45:01.778  1017  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
,03-19 11:45:01.778  1017  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-19 11:45:01.778  3394  3464 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-19 11:45:01.788  1489  1489 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-19 11:45:01.808  3394  3464 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-19 11:45:01.808  3394  3464 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-19 11:45:01.808  3394  3464 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-19 11:45:01.808  3394  3464 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-19 11:45:01.818  1489  1489 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-19 11:45:01.818  1017  1149 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-19 11:45:01.828  1017  3577 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 11:45:01.828  1184  1184 D PanelView: There is/are notification(s) 
,03-19 11:45:01.828  3539  3539 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-19 11:45:01.838  3394  3463 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/25/14:07:31
,03-19 11:45:01.838  3554  3554 D AndroidRuntime: 
03-19 11:45:01.838  3554  3554 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-19 11:45:01.838  3554  3554 D AndroidRuntime: CheckJNI is OFF
,03-19 11:45:01.838  3554  3554 D AndroidRuntime: readGMSProperty: start
03-19 11:45:01.838  3554  3554 D AndroidRuntime: readGMSProperty: already setted!!
03-19 11:45:01.838  3554  3554 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-19 11:45:01.838  3554  3554 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-19 11:45:01.838  3554  3554 D AndroidRuntime: readGMSProperty: end
03-19 11:45:01.838  3554  3554 D AndroidRuntime: addProductProperty: start
,03-19 11:45:01.848  3029  3029 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-19 11:45:01.848  1799  1799 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-19 11:45:01.858  3394  3464 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-19 11:45:01.858  3394  3464 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-19 11:45:01.858  3394  3464 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-19 11:45:01.868  3394  3463 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/19/11:45:01
,03-19 11:45:01.868  3539  3539 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-19 11:45:01.878  3394  3463 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-19 11:45:01.878  3394  3463 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-19 11:45:01.878  1017  2840 I ActivityManager: Killing 2504:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-19 11:45:01.888  1489  1774 W OpenGLRenderer: SFEffectCache::get: create texture(0x9ffab724): name, size, mSize = 35, 143440, 311440
,03-19 11:45:01.898  3539  3539 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-19 11:45:01.898  3539  3539 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-19 11:45:01.898  1489  1489 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1dcf55ba time:40777
,03-19 11:45:01.918  1017  1039 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-19 11:45:01.928  3394  3464 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0,
,03-19 11:45:01.928  1017  1149 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,03-19 11:45:01.938  1017  1041 W libprocessgroup: failed to open /acct/uid_10142/pid_2531/cgroup.procs: No such file or directory
,03-19 11:45:01.938  1017  1041 W libprocessgroup: failed to open /acct/uid_10135/pid_2608/cgroup.procs: No such file or directory
,03-19 11:45:01.938  1017  1041 W libprocessgroup: failed to open /acct/uid_10139/pid_2564/cgroup.procs: No such file or directory
03-19 11:45:01.938  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2593/cgroup.procs: No such file or directory
,03-19 11:45:01.938  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:01.938  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:01.938  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:01.938  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:01.958  1017  1049 D PersonaManager: isKioskContainerExistOnDevice,
03-19 11:45:01.958  1017  1149 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3587 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 11:45:01.958  3587  3587 E Zygote  : MountEmulatedStorage(),
03-19 11:45:01.958  3587  3587 E Zygote  : v2
03-19 11:45:01.958  3587  3587 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:45:01.958  3587  3587 I libpersona: KNOX_SDCARD not a persona
03-19 11:45:01.958   275  1010 D EnterpriseController: uids 10091
03-19 11:45:01.958   275  1010 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-19 11:45:01.958   275  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10091
03-19 11:45:01.958  3587  3587 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:01.968  3587  3587 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-19 11:45:01.968  3587  3587 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:45:01.988  1017  1049 I ActivityManager: Displayed Component not be shown by security: +329ms
,03-19 11:45:01.988  3554  3554 E AffinityControl: AffinityControl: registerfunction enter
,03-19 11:45:02.008  3394  3464 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-19 11:45:02.018  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-19 11:45:02.018  3554  3554 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-19 11:45:02.018  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:02.018  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:02.018  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:02.018  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:02.028  3394  3463 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-19 11:45:02.038  3486  3486 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-19 11:45:02.038  3606  3606 E Zygote  : MountEmulatedStorage()
03-19 11:45:02.038  3606  3606 I libpersona: KNOX_SDCARD checking this for 10003
03-19 11:45:02.038  3606  3606 E Zygote  : v2
03-19 11:45:02.038  3606  3606 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:02.038  1799  3424 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-19 11:45:02.048  3606  3606 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:02.048  3606  3606 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:45:02.048  3606  3606 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:45:02.048  1017  3162 D PackageManager: START PACKAGE DELETE: observer{958422500}
03-19 11:45:02.048  1017  3162 D PackageManager: pkg{<packageName>}
03-19 11:45:02.048  1017  3162 D PackageManager: user{0}
03-19 11:45:02.048  1017  3162 D PackageManager: caller{2000}
03-19 11:45:02.048  1017  3162 D PackageManager: flags{2}
03-19 11:45:02.048  1017  3162 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-19 11:45:02.048  1017  3162 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-19 11:45:02.048  1017  3162 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-19 11:45:02.048  1017  3162 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-19 11:45:02.048  1017  3162 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-19 11:45:02.048  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-19 11:45:02.048  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-19 11:45:02.048  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-19 11:45:02.048  1017  1017 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3606 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-19 11:45:02.048  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
03-19 11:45:02.048  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-19 11:45:02.068  3587  3587 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:02.068  3587  3587 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:02.078  1017  1057 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,03-19 11:45:02.078  1017  3164 I ActivityManager: Killing 2796:com.android.email/u0a145 (adj 15): empty #31
,03-19 11:45:02.078  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
03-19 11:45:02.078  1017  1042 I ActivityManager: Killing 3029:com.test.thalitest/u0a155 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-19 11:45:02.098  3606  3606 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:02.098  3606  3606 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:02.118  1017  1039 D SensorService: [SO] currT = 40990098836, prevT = 40520077482, diff = 470021354, [0.134 0.402 10.132]
,03-19 11:45:02.118  1017  1039 D SensorService: [SO] 0.134 0.402 10.132
03-19 11:45:02.118  1017  1039 D SensorService: [SO] [100 -> 255]
,03-19 11:45:02.128  3394  3463 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-19 11:45:02.148  3418  3531 I SearchServiceFactory: refreshing internal icing corpora
,03-19 11:45:02.158  1017  1042 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,03-19 11:45:02.158  1017  1042 W ActivityManager: mDVFSHelper.release()
03-19 11:45:02.158  1017  1042 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-19 11:45:02.208  2663  2739 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-19 11:45:02.218  1017  1395 I WindowState: WIN DEATH: Window{1a1f45f7 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-19 11:45:02.228  3394  3464 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-19 11:45:02.248  3394  3464 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-19 11:45:02.268  3486  3486 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-19 11:45:02.278  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2684/cgroup.procs: No such file or directory
03-19 11:45:02.278  1017  1041 W libprocessgroup: failed to open /acct/uid_10044/pid_2504/cgroup.procs: No such file or directory
,03-19 11:45:02.278  1017  1041 W libprocessgroup: failed to open /acct/uid_10145/pid_2796/cgroup.procs: No such file or directory
,03-19 11:45:02.278  3394  3463 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-19 11:45:02.298  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,03-19 11:45:02.308  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-19 11:45:02.308  3587  3587 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-19 11:45:02.308  3587  3587 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-19 11:45:02.308  3587  3587 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-19 11:45:02.338  1017  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-19 11:45:02.338  3606  3606 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-19 11:45:02.348  1833  2085 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-19 11:45:02.348  1799  1799 E SamsungIME: mOCRHelper is null
,03-19 11:45:02.358  1469  1469 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-19 11:45:02.358  1017  3162 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-19 11:45:02.358  1017  3162 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-19 11:45:02.358  1017  3162 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:02.358  1017  3162 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:45:02.358  1017  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-19 11:45:02.368  3418  3624 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-19 11:45:02.368  3418  3624 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_icing_corpora]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
03-19 11:45:02.368  3418  3624 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-19 11:45:02.368  3418  3624 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
03-19 11:45:02.368  3418  3624 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_doodle]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-19 11:45:02.378  3418  3628 I SearchServiceFactory: refreshing search history.
,03-19 11:45:02.388   258  1099 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-19 11:45:02.388   258   451 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-19 11:45:02.398  3486  3486 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-19 11:45:02.418  1017  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{199c1112 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:41292
,03-19 11:45:02.418  3486  3486 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-19 11:45:02.428  3486  3486 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-19 11:45:02.448  3606  3606 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-19 11:45:02.448  3606  3606 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-19 11:45:02.448  3606  3606 D UserAnalysis: Create SecureDbHelper
,03-19 11:45:02.448  1017  1501 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-19 11:45:02.448  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,03-19 11:45:02.458  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:45:02.458  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:45:02.458  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-19 11:45:02.468  3587  3603 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-19 11:45:02.488  3418  3632 I UpdateIcingCorporaServi: Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,03-19 11:45:02.488  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
03-19 11:45:02.488  1017  1129 V NetworkStats: removeUidsLocked() for UIDs [10155]
03-19 11:45:02.488  1017  1129 V NetworkStats: performPollLocked(flags=0x3)
,03-19 11:45:02.488  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
03-19 11:45:02.488  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-19 11:45:02.498  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
03-19 11:45:02.498  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-19 11:45:02.498  1017  1041 W TextServicesManagerService: no available spell checker services found
,03-19 11:45:02.498  1017  1129 V NetworkStats: performPollLocked() took 6ms
03-19 11:45:02.498  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-19 11:45:02.508  3606  3606 D IntelligenceServiceApplication: onCreate()
,03-19 11:45:02.508  3606  3606 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-19 11:45:02.508  1453  1453 D RegisteredComponentCache: Collect Tech packages for Knox
,03-19 11:45:02.528  3486  3486 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-19 11:45:02.538  3606  3606 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-19 11:45:02.538  3486  3486 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-19 11:45:02.558  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-19 11:45:02.558  3539  3539 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-19 11:45:02.558  1453  1453 D PersonaManager: isKioskContainerExistOnDevice
,03-19 11:45:02.568  3539  3539 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-19 11:45:02.568  3539  3539 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-19 11:45:02.598  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,03-19 11:45:02.608  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-19 11:45:02.608  3606  3606 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-19 11:45:02.608  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 11:45:02.608  3316  3351 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-19 11:45:02.618  1017  3163 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,03-19 11:45:02.618  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-19 11:45:02.618  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,03-19 11:45:02.618  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:02.618  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:02.618  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:02.618  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:02.618  1017  1017 D OTPFW   : OtpDbHelper::getInstance New instance created
,03-19 11:45:02.618  1017  1017 D OTPFW   : DBIntegrity::getInstance - New instance created
,03-19 11:45:02.638  3637  3637 E Zygote  : MountEmulatedStorage(),
03-19 11:45:02.638  3637  3637 E Zygote  : v2
,03-19 11:45:02.638  3637  3637 I libpersona: KNOX_SDCARD checking this for 10060
03-19 11:45:02.638  3637  3637 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:02.638  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0,
,03-19 11:45:02.638  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter,
,03-19 11:45:02.648  1017  3163 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3637 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-19 11:45:02.648  3637  3637 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-19 11:45:02.648  3637  3637 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:45:02.648  3637  3637 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:45:02.648  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-19 11:45:02.678  3606  3606 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-19 11:45:02.678  3606  3606 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-19 11:45:02.688  1017  1395 D ActivityManager: bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,03-19 11:45:02.688  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-19 11:45:02.688  3637  3637 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:02.688  3637  3637 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:02.698  3486  3486 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-19 11:45:02.708  1017  1342 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-19 11:45:02.708  1017  1342 D SecContentProvider2: mCursor = null
,03-19 11:45:02.728  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-19 11:45:02.728  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-19 11:45:02.728  3486  3486 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-19 11:45:02.728  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:45:02.728  1017  1395 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-19 11:45:02.728  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
03-19 11:45:02.728  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 11:45:02.738  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-19 11:45:02.738  1017  1017 V EnterpriseBillingPolicy: uID is 10155
03-19 11:45:02.738  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
03-19 11:45:02.738  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-19 11:45:02.738  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-19 11:45:02.738  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-19 11:45:02.738  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-19 11:45:02.738  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-19 11:45:02.738  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-19 11:45:02.738  1184  1184 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 11:45:02.738  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 11:45:02.738  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 11:45:02.748  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 11:45:02.748  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 11:45:02.748  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 11:45:02.748  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-19 11:45:02.748  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-19 11:45:02.758  3418  3632 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 265 ms] updated apps [took 263 ms] 
,03-19 11:45:02.768  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-19 11:45:02.778  1017  1017 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
03-19 11:45:02.778  1017  2766 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-19 11:45:02.778  1017  1017 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,03-19 11:45:02.778  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-19 11:45:02.778  1017  1017 V EnterpriseBillingPolicy: uID is 10155
03-19 11:45:02.778  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
03-19 11:45:02.778  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-19 11:45:02.778  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-19 11:45:02.778  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-19 11:45:02.778  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-19 11:45:02.778  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-19 11:45:02.778  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-19 11:45:02.778  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 11:45:02.788  1017  3163 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,03-19 11:45:02.788  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:02.788  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:02.788  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:02.788  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:02.808  1017  3163 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3655 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 11:45:02.808  3655  3655 E Zygote  : MountEmulatedStorage(),
03-19 11:45:02.808  3655  3655 E Zygote  : v2,
,03-19 11:45:02.808  1017  3163 I ActivityManager: Killing 1904:com.android.defcontainer/u0a4 (adj 15): empty #31
03-19 11:45:02.818  3655  3655 I libpersona: KNOX_SDCARD checking this for 1000
,03-19 11:45:02.818  3655  3655 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:02.818  3655  3655 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:02.818  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 11:45:02.818  3655  3655 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-19 11:45:02.828  3655  3655 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:45:02.828  1453  1453 D PersonaManager: isKioskContainerExistOnDevice
03-19 11:45:02.828  1453  1453 D RegisteredServicesCache: empty dynamic service
03-19 11:45:02.828  3418  3628 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-19 11:45:02.848  3418  3628 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1726-1728)
03-19 11:45:02.848  3418  3628 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-19 11:45:02.868  3655  3655 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:02.878  3655  3655 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:02.878  3418  3628 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:45:02.878  3418  3628 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-19 11:45:02.898  2887  3207 I System.out: BaseSyncManager calls detatch()
,03-19 11:45:02.928  3655  3655 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-19 11:45:02.928  3655  3655 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-19 11:45:02.948  1334  3315 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-19 11:45:02.958  3587  3603 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-19 11:45:02.988  3655  3655 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-19 11:45:03.028  3655  3655 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-19 11:45:03.028  1017  1173 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
,03-19 11:45:03.028  1017  1173 D TaskPersister: removeObsoleteFile: deleting file=12_task_thumbnail.png
,03-19 11:45:03.108  1489  1489 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-19 11:45:03.108  1489  1489 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-19 11:45:03.118  1489  1489 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-19 11:45:03.118  1017  1057 I art     : Explicit concurrent mark sweep GC freed 53723(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 30MB/45MB, paused 4.260ms total 702.331ms
,03-19 11:45:03.168  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-19 11:45:03.168  1017  1149 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-19 11:45:03.168  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.168  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.168  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.168  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.178  3682  3682 E Zygote  : MountEmulatedStorage(),
03-19 11:45:03.178  3682  3682 E Zygote  : v2
03-19 11:45:03.178  3682  3682 I libpersona: KNOX_SDCARD checking this for 10094
03-19 11:45:03.178  3682  3682 I libpersona: KNOX_SDCARD not a persona,
03-19 11:45:03.178  3682  3682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:03.188  3682  3682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-19 11:45:03.188  3682  3682 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 11:45:03.188  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-19 11:45:03.188  1017  1149 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3682 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
,03-19 11:45:03.208  1017  1057 D PackageManager: delete codoeFile: 
,03-19 11:45:03.218  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
03-19 11:45:03.218  1017  1057 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,03-19 11:45:03.218  1017  1057 D PackageManager: result of delete: 1{958422500}
,03-19 11:45:03.218  3682  3682 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:03.218  3554  3554 D AndroidRuntime: Shutting down VM
,03-19 11:45:03.218  3682  3682 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:03.228  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-19 11:45:03.228  1017  1057 D PackageManager: userId{-1}
03-19 11:45:03.228  1017  1057 D PackageManager: andCode{true}
,03-19 11:45:03.228  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,03-19 11:45:03.248  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.248  3444  3579 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-19 11:45:03.248  3444  3579 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-19 11:45:03.258  3655  3655 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-19 11:45:03.258  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 11:45:03.268  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.268  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.268  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.288  3705  3705 E Zygote  : MountEmulatedStorage()
03-19 11:45:03.288  3705  3705 E Zygote  : v2
03-19 11:45:03.288  3705  3705 I libpersona: KNOX_SDCARD checking this for 10004
03-19 11:45:03.288  3705  3705 I libpersona: KNOX_SDCARD not a persona
03-19 11:45:03.288  3705  3705 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:03.288  3705  3705 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:45:03.288  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=3705 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-19 11:45:03.298  3655  3655 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-19 11:45:03.298  3655  3655 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-19 11:45:03.298  3682  3682 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-19 11:45:03.298  3682  3682 D elm:15183: ELMEngine.ELMEngine( context ).
,03-19 11:45:03.298  3682  3682 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-19 11:45:03.298  3705  3705 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:45:03.308  1017  1342 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
03-19 11:45:03.308  1017  1342 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:03.308  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
03-19 11:45:03.308  1017  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 11:45:03.308  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-19 11:45:03.318  3486  3681 I System.out: Thread-464(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-19 11:45:03.318  3486  3681 I System.out: Thread-464(ApacheHTTPLog):isSBSettingEnabled false
03-19 11:45:03.318  3486  3681 I System.out: Thread-464(ApacheHTTPLog):isShipBuild true
03-19 11:45:03.318  3486  3681 I System.out: Thread-464(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-19 11:45:03.318  3486  3681 I System.out: Thread-464(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-19 11:45:03.318   307   307 I art     : Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 27.752ms
,03-19 11:45:03.318   275  1010 D EnterpriseController: uids 10092
03-19 11:45:03.318   275  1010 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-19 11:45:03.318   275  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-19 11:45:03.328  3655  3655 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-19 11:45:03.328  3655  3655 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-19 11:45:03.328  3655  3655 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-19 11:45:03.328  3655  3655 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-19 11:45:03.328  3682  3682 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
03-19 11:45:03.328  3637  3637 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-19 11:45:03.338  3705  3705 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:03.338  3705  3705 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:03.338   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 21.481ms
,03-19 11:45:03.348  1428  1428 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-19 11:45:03.358   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 18.793ms
,03-19 11:45:03.368  1428  1428 V EmergencyMode: [EmergencyBase] setBootTime
03-19 11:45:03.368  1428  1428 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-19 11:45:03.368  3682  3682 D elm:15183: ElmAgentService : onCreate()
,03-19 11:45:03.368  3418  3628 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:45:03.368  3682  3721 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-19 11:45:03.368  1017  3163 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
03-19 11:45:03.368  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 11:45:03.368  3682  3682 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,03-19 11:45:03.368  3682  3682 D elm:15183: BootCompletedState : startBootCompleted() call
,03-19 11:45:03.378  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.378  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.378  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.378  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.378  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-19 11:45:03.378  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-19 11:45:03.378  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 11:45:03.378  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-19 11:45:03.388  3682  3682 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-19 11:45:03.398  3727  3727 E Zygote  : MountEmulatedStorage()
03-19 11:45:03.398  3727  3727 I libpersona: KNOX_SDCARD checking this for 10062
03-19 11:45:03.398  3727  3727 E Zygote  : v2
03-19 11:45:03.398  3727  3727 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:03.398  3727  3727 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:03.398  3727  3727 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:45:03.398  3727  3727 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:45:03.398  1017  3163 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3727 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 11:45:03.408  3682  3682 I elm:15183: Get License : 0
03-19 11:45:03.408  1334  3315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
03-19 11:45:03.408  3682  3682 D elm:15183: ElmAgentService : onDestroy().
,03-19 11:45:03.408  1017  3162 I ActivityManager: Killing 2777:com.samsung.android.sm/1000 (adj 15): empty #31
,03-19 11:45:03.418  1017  1506 I ActivityManager: Killing 2907:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-19 11:45:03.428  1334  3315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-19 11:45:03.428  1334  3315 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-19 11:45:03.428  3554  3554 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,03-19 11:45:03.448  3727  3727 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:03.448  3727  3727 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:03.448  1017  3163 D ActivityManager: startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,03-19 11:45:03.448  3468  3468 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-19 11:45:03.448  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.448  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.458  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.458  1017  3163 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.468  3748  3748 E Zygote  : MountEmulatedStorage(),
,03-19 11:45:03.468  3748  3748 E Zygote  : v2,
03-19 11:45:03.468  3748  3748 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:45:03.468  3748  3748 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:03.468  3748  3748 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:03.478  3748  3748 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:45:03.478  3748  3748 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:45:03.478  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 11:45:03.478  1017  3163 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3748 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 11:45:03.488  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-19 11:45:03.488  3701  3701 I dex2oat : ----------------------------------------------------
03-19 11:45:03.488  3701  3701 I dex2oat : <SS>: S T A R T I N G . . .
03-19 11:45:03.488  3701  3701 I dex2oat : <SS>: Zip is absent. Canceled.
,03-19 11:45:03.488  3701  3701 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-791471381.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-791471381.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-19 11:45:03.488  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-19 11:45:03.488  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-19 11:45:03.498  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 11:45:03.498  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-19 11:45:03.498  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-19 11:45:03.498  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
03-19 11:45:03.498  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-19 11:45:03.508  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 11:45:03.508  1017  3163 I ActivityManager: Killing 2940:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-19 11:45:03.508  1017  3163 I ActivityManager: Killing 2213:flipboard.app/u0a98 (adj 15): empty #31
03-19 11:45:03.508  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-19 11:45:03.508  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-19 11:45:03.508  1017  1041 W libprocessgroup: failed to open /acct/uid_10004/pid_1904/cgroup.procs: No such file or directory
,03-19 11:45:03.518  3748  3748 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:03.518  3748  3748 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:03.518  3468  3468 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-19 11:45:03.528  3468  3468 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-19 11:45:03.538  2887  3207 W GAV2    : BaseSyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,03-19 11:45:03.548  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2777/cgroup.procs: No such file or directory
03-19 11:45:03.548  1017  1041 W libprocessgroup: failed to open /acct/uid_10072/pid_2907/cgroup.procs: No such file or directory
,03-19 11:45:03.558  3468  3468 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-19 11:45:03.558  1017  1149 D ActivityManager: startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,03-19 11:45:03.558  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.558  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.558  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.558  1017  1149 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.578  3772  3772 E Zygote  : MountEmulatedStorage()
,03-19 11:45:03.578  3772  3772 E Zygote  : v2
03-19 11:45:03.578  3772  3772 I libpersona: KNOX_SDCARD checking this for 10014
03-19 11:45:03.578  3772  3772 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:03.578  3772  3772 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:03.578  1017  1149 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3772 uid=10014 gids={50014, 9997} abi=armeabi-v7a
03-19 11:45:03.578  3772  3772 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:45:03.578  1017  1149 I ActivityManager: Killing 2975:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-19 11:45:03.588  3772  3772 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-19 11:45:03.598  3772  3772 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:03.598  3772  3772 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:03.618  3316  3351 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-19 11:45:03.618  3748  3748 I CameraApp: CameraApp.onCreate()... mFeature : null
03-19 11:45:03.618  3748  3748 I testFeature: Feature.Feature(context)
03-19 11:45:03.618  3748  3748 I testFeature: Feature.readInternalDefaultXml()
03-19 11:45:03.618  3748  3748 I testFeature: ResetFeatureValue
,03-19 11:45:03.618  3748  3748 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-19 11:45:03.618  3748  3748 I CameraApp: CameraApp.getAppFeature()...
,03-19 11:45:03.628  1017  1226 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,03-19 11:45:03.628  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.628  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.628  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.628  1017  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.638  3772  3772 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-19 11:45:03.648  3789  3789 E Zygote  : MountEmulatedStorage()
03-19 11:45:03.648  3789  3789 I libpersona: KNOX_SDCARD checking this for 10100
03-19 11:45:03.648  3789  3789 E Zygote  : v2
03-19 11:45:03.648  3789  3789 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:03.648  3789  3789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:03.648  3789  3789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-19 11:45:03.648  1017  1226 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3789 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-19 11:45:03.648  3789  3789 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-19 11:45:03.648  1017  1226 I ActivityManager: Killing 2983:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
03-19 11:45:03.648  1017  1149 D ActivityManager: startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
03-19 11:45:03.648  1017  1149 W ActivityManager: userId = 0, bbcId = -10000,
03-19 11:45:03.648  1017  1149 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-19 11:45:03.648  1017  1149 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:45:03.648  1017  1149 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-19 11:45:03.668  2641  2641 D FactoryTestApp: [DummyFtClient$onDestroy](2641) Destroy DummyFtClient service
,03-19 11:45:03.668  3772  3797 V OneTimeService: OneTimeService.onHandleIntent
,03-19 11:45:03.668  2641  2641 D FactoryTestApp: [Support$Values.getString](2641) id=MODEL_COMMUNICATION_MODE, value=gsm
03-19 11:45:03.668  2641  2641 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2641) mConnectionMode = gsm
03-19 11:45:03.668  2641  2641 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2641) RUNNING_FTCLIENT : false
03-19 11:45:03.668  2641  2641 D FactoryTestApp: [DummyFtClient$onDestroy](2641) kill process
,03-19 11:45:03.668  2641  2641 I Process : Sending signal. PID: 2641 SIG: 9
,03-19 11:45:03.678  1017  1506 I ActivityManager: Killing 2388:com.sec.modem.settings/1000 (adj 15): empty #31
,03-19 11:45:03.678  3789  3789 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 11:45:03.678  3789  3789 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:03.688  1017  3163 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-19 11:45:03.688  1017  3163 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-19 11:45:03.688  1017  3163 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:03.688  1017  3163 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:45:03.688  1017  3163 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-19 11:45:03.688   275  1010 D EnterpriseController: uids 10057
03-19 11:45:03.688   275  1010 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-19 11:45:03.688   275  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10057
,03-19 11:45:03.698  3444  3444 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
03-19 11:45:03.698  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-19 11:45:03.698  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-19 11:45:03.708  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:03.708  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:45:03.708  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-19 11:45:03.708  1017  1149 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:03.708  1017  1149 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-19 11:45:03.708  1017  1149 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:45:03.708  1017  1149 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
03-19 11:45:03.708  1017  1149 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-19 11:45:03.708  1017  1506 I ActivityManager: Killing 3014:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-19 11:45:03.708  3789  3789 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-19 11:45:03.708  1017  3162 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-19 11:45:03.718  1017  3162 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-19 11:45:03.718  1017  3162 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:45:03.718  1017  3162 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-19 11:45:03.718  1017  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-19 11:45:03.718  3727  3727 I ExternalOEMControlProvider: onCreate
,03-19 11:45:03.728  3701  3701 I dex2oat : dex2oat took 238.704ms (threads: 4)
,03-19 11:45:03.728  1017  1377 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,03-19 11:45:03.728  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.728  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.728  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.728  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.738  3789  3789 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-19 11:45:03.758  3819  3819 E Zygote  : MountEmulatedStorage()
03-19 11:45:03.758  3819  3819 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:45:03.758  3819  3819 E Zygote  : v2
03-19 11:45:03.758  3819  3819 I libpersona: KNOX_SDCARD not a persona
,03-19 11:45:03.758  3819  3819 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:03.758  1017  1377 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3819 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 11:45:03.758  1017  1377 I ActivityManager: Killing 3068:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-19 11:45:03.758  3819  3819 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:45:03.758  1017  1501 I ActivityManager: Process com.sec.factory (pid 2641)(adj 0) has died(114,1121)
03-19 11:45:03.758  3819  3819 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-19 11:45:03.768  1017  1377 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,03-19 11:45:03.768  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.768  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.768  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.768  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.778  1017  3163 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-19 11:45:03.778  1017  3163 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 11:45:03.778  1017  3163 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 11:45:03.778  1017  3163 D SettingsProvider: selectionArgs: false
03-19 11:45:03.778  1017  3163 D SettingsProvider: selectionArgs: 10062
,03-19 11:45:03.778  1017  3163 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-19 11:45:03.778  1017  3163 D SettingsProvider: ret = -1
,03-19 11:45:03.788  3836  3836 E Zygote  : MountEmulatedStorage()
03-19 11:45:03.788  3836  3836 I libpersona: KNOX_SDCARD checking this for 10101
03-19 11:45:03.788  3836  3836 E Zygote  : v2
03-19 11:45:03.788  3836  3836 I libpersona: KNOX_SDCARD not a persona
03-19 11:45:03.788  3836  3836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:03.798  3836  3836 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-19 11:45:03.798  1017  1377 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3836 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 11:45:03.798  3836  3836 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-19 11:45:03.798  3819  3819 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:03.798  1017  1377 I ActivityManager: Killing 2365:com.android.mms/u0a46 (adj 15): empty #31
,03-19 11:45:03.798  3819  3819 D ActivityThread: Added TimaKeyStore provider
,03-19 11:45:03.798  1017  1226 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-19 11:45:03.808  1017  1226 W ActivityManager: userId = 0, bbcId = -10000
03-19 11:45:03.808  1017  1226 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
03-19 11:45:03.808  1017  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 11:45:03.808  1017  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-19 11:45:03.818  1017  1377 D ActivityManager: startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
03-19 11:45:03.818  2624  3197 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-19 11:45:03.818  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.818  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.818  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 11:45:03.818  1017  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 11:45:03.828  2624  3197 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-19 11:45:03.828  2624  3197 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-19 11:45:03.838  3836  3836 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:03.838  3836  3836 D ActivityThread: Added TimaKeyStore provider
03-19 11:45:03.838  3819  3819 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-19 11:45:03.838  2624  3197 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-19 11:45:03.848  3853  3853 I libpersona: KNOX_SDCARD checking this for 1000
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-19 11:45:03.838  2624  3197 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-19 11:45:03.848  3853  3853 I libpersona: KNOX_SDCARD not a persona
03-19 11:45:03.838  3853  3853 E Zygote  : MountEmulatedStorage()
03-19 11:45:03.838  3853  3853 E Zygote  : v2
,03-19 11:45:03.848  1017  1377 I ActivityManager: Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3853 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 11:45:03.848  3853  3853 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-19 11:45:03.848  3853  3853 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-19 11:45:03.848  3853  3853 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 11:45:03.858  2624  3197 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-19 11:45:03.868  2624  3197 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-19 11:45:03.868  2624  3197 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-19 11:45:03.868  3506  3843 E SQLiteLog: (28) failed to open "/data/user/0/com.google.android.partnersetup/databases/rlz_data.db" with flag (131138) and mode_t (0) due to error (30)
,03-19 11:45:03.878  3853  3853 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 11:45:03.878  3444  3444 I System.out: YouTube MDX: MDX video stage moved to NEW
03-19 11:45:03.878  3853  3853 D ActivityThread: Added TimaKeyStore provider
03-19 11:45:03.878  3444  3444 I System.out: YouTube MDX: MDX video player state moved to UNSTARTED
,03-19 11:45:03.888  3444  3444 I System.out: YouTube MDX: MDX ad player state moved to UNSTARTED
,03-19 11:45:03.888  2624  3197 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-19 11:45:03.888  2624  3197 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-19 11:45:03.888  2624  3197 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-19 11:45:03.888  3506  3843 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.partnersetup/databases/rlz_data.db'.
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at com.google.android.partnersetup.RlzProvider.update(RlzProvider.java:411)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntentWithContext(RlzPingIntentService.java:137)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntent(RlzPingIntentService.java:111)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-19 11:45:03.888  3506  3843 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-19 11:45:03.888  2624  3197 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-19 11:45:03.898  2624  3197 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-19 11:45:03.898  2624  3197 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-19 11:45:03.898  2624  3197 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-19 11:45:03.898  2624  3197 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-19 11:45:03.908  3506  3843 E AndroidRuntime: FATAL EXCEPTION: IntentService[GooglePartnerSetup]
03-19 11:45:03.908  3506  3843 E AndroidRuntime: Process: com.google.android.partnersetup, PID: 3506
03-19 11:45:03.908  3506  3843 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at com.google.android.partnersetup.RlzProvider.update(RlzProvider.java:411)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntentWithContext(RlzPingIntentService.java:137)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntent(RlzPingIntentService.java:111)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-19 11:45:03.908  3506  3843 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-19 11:45:03.908  1017  1149 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 11:45:03.908  1017  1149 W ActivityManager: userId = 0, bbcId = -10000
,03-19 11:45:03.908  1017  1149 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-19 11:45:03.908  1017  1149 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-19 11:45:03.908  2624  3197 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-19 11:45:03.918  2624  3197 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-19 11:45:03.918  2624  3197 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:03.918  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:03.918  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,03-19 11:45:03.918  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-19 11:45:03.918  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-19 11:45:03.918  2624  3197 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-19 11:45:03.918  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-19 11:45:03.918  2624  3197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
,03-19 11:45:03.918  2624  3197 E SQLiteDatabase: ,	
```
