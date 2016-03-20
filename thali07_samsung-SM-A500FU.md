#### Test 625481245382a4d_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
03-20 12:39:38.537  1019  1555 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-20 12:39:38.537  1019  1552 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-20 12:39:38.537  1019  1555 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-20 12:39:38.537  1019  1555 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-20 12:39:38.537  1019  1552 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
--------- beginning of system
03-20 12:39:38.557  1019  1060 D PackageManager: [MSG] MCS_UNBIND
03-20 12:39:38.567  1019  1032 I ActivityManager: Killing 1194:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-20 12:39:38.587  1019  1329 D RCPManagerService: exchangeData() failure , invalid userId
03-20 12:39:38.587  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
03-20 12:39:38.637  2892  2892 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-20 12:39:38.637  2892  2892 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-20 12:39:38.647  1019  1446 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=88, mSplitNum[1]=125, mSplitNum[2]=162, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 51 receivers.size=198
03-20 12:39:38.647  1019  1446 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
03-20 12:39:38.657  1019  1446 I ActivityManager: Killing 1403:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
03-20 12:39:38.657  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceive
03-20 12:39:38.667  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-20 12:39:38.657  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-20 12:39:38.657  1019  1019 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-20 12:39:38.657  1019  1019 I System.out: start Service
03-20 12:39:38.667  2719  2719 E BluetoothAdapterService(452957877): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
03-20 12:39:38.667  1019  1019 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
03-20 12:39:38.667  2719  2719 E BluetoothAdapterService(452957877): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
03-20 12:39:38.677  1019  1131 I ActivityManager: Killing 1528:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
03-20 12:39:38.677  2719  2807 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
03-20 12:39:38.677  2719  2807 I bluedroid: enable
03-20 12:39:38.677  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.677  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.677  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.677  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.687  1229  1229 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-20 12:39:38.697   283   518 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 2622
03-20 12:39:38.697   283   518 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 2622
03-20 12:39:38.697  2928  2928 E Zygote  : MountEmulatedStorage()
03-20 12:39:38.697  2928  2928 E Zygote  : v2
03-20 12:39:38.697  2928  2928 I libpersona: KNOX_SDCARD checking this for 10085
03-20 12:39:38.697  2928  2928 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:38.697  2928  2928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:38.697  1019  1044 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2928 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-20 12:39:38.697  2928  2928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:38.697  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.697  2928  2928 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:38.697  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.697  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.697  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.717  2719  2807 I bt_hci_bdroid: init
03-20 12:39:38.717  2719  2941 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
03-20 12:39:38.717  2719  2807 I bt_vendor: bt-vendor : init
03-20 12:39:38.717  2719  2807 I bt_vendor: bt-vendor : get_bt_soc_type
03-20 12:39:38.717  2719  2807 E bt_vendor: get_bt_soc_type: Failed to get soc type
03-20 12:39:38.717  2719  2807 I bt_vendor: init: Local BD Address : 22:18:51:0e:f9:7c
03-20 12:39:38.717  2719  2807 D bt_userial_mct: userial_init
03-20 12:39:38.717  2719  2807 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
03-20 12:39:38.717  2719  2807 I bt_vendor: Starting hciattach daemon
03-20 12:39:38.717  2719  2807 I bt_vendor: try to set false
03-20 12:39:38.717  2943  2943 E Zygote  : MountEmulatedStorage()
03-20 12:39:38.717  2943  2943 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:38.717  2943  2943 E Zygote  : v2
03-20 12:39:38.717  2943  2943 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:38.717  2943  2943 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:38.717  2719  2807 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
03-20 12:39:38.717  2719  2807 I bt_vendor: Starting hciattach daemon
03-20 12:39:38.717  2719  2807 I bt_vendor: try to set true
03-20 12:39:38.727  2943  2943 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:38.727  1019  1044 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2943 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-20 12:39:38.727  2943  2943 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:38.747   306   306 I art     : Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.043ms total 26.323ms
03-20 12:39:38.747  2928  2928 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:38.747  2957  2957 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
03-20 12:39:38.747  2928  2928 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:38.757  2943  2943 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:38.757  2943  2943 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:38.767  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_1194/cgroup.procs: No such file or directory
03-20 12:39:38.767  1019  1131 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
03-20 12:39:38.767  1019  1131 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:38.767  1019  1131 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:38.767  1019  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-20 12:39:38.777   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 27.824ms
03-20 12:39:38.777  1728  1839 I NotificationStore: System rebooted after Notification storage file was last written
03-20 12:39:38.777  1728  1839 I NotificationStore: Deleting the file
03-20 12:39:38.787  1019  2937 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-20 12:39:38.787  1019  1043 W libprocessgroup: failed to open /acct/uid_10096/pid_1403/cgroup.procs: No such file or directory
03-20 12:39:38.787  1019  1019 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-20 12:39:38.797  1019  2820 D SSRM:a  : DeviceInfo:: 000000000000
03-20 12:39:38.797  1019  2820 D SSRM:a  : SettingsAirViewInfo:: 000000000
03-20 12:39:38.797   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 18.417ms
03-20 12:39:38.807  1019  1482 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
03-20 12:39:38.807  1019  1482 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
03-20 12:39:38.817  2971  2971 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
03-20 12:39:38.817  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-20 12:39:38.817   283   283 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-20 12:39:38.817  1019  1019 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
03-20 12:39:38.817  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:38.817  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:38.817  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-20 12:39:38.827  1019  1446 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-20 12:39:38.827  1019  1446 D SecContentProvider2: mCursor = null
03-20 12:39:38.827  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_1528/cgroup.procs: No such file or directory
03-20 12:39:38.827  2972  2972 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
03-20 12:39:38.827  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
03-20 12:39:38.837  2928  2928 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-20 12:39:38.837  2928  2928 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-20 12:39:38.837  2928  2928 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-20 12:39:38.837  2928  2928 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-20 12:39:38.837  2928  2928 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-20 12:39:38.837  2928  2928 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-20 12:39:38.847  2974  2974 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
03-20 12:39:38.847  1182  2349 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-20 12:39:38.847  1182  2349 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-20 12:39:38.857  2975  2975 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
03-20 12:39:38.857  1468  1468 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-20 12:39:38.857  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-20 12:39:38.867  2976  2976 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
03-20 12:39:38.877  2977  2977 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
03-20 12:39:38.877  1182  1182 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
03-20 12:39:38.887  1229  1229 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-20 12:39:38.887  1019  1446 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:38.887  1019  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:38.887  1019  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
03-20 12:39:38.887  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
03-20 12:39:38.897  1606  1626 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
03-20 12:39:38.897  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:38.897  1019  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:38.897  1019  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-20 12:39:38.897  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-20 12:39:38.897  1019  1329 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:38.897  1019  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:38.897  1019  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-20 12:39:38.907  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.907  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.907  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.907  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.917  1468  1468 D CscUpdateService: onStart
03-20 12:39:38.917  1468  1468 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-20 12:39:38.917  1468  1468 I CscUpdateService: set_CSC_version
03-20 12:39:38.917  1468  1468 E CscParser: update(): xml file exist
03-20 12:39:38.917  2920  2920 D AndroidRuntime: 
03-20 12:39:38.917  2920  2920 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-20 12:39:38.917  1182  1182 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
03-20 12:39:38.917   297   297 E USB_UICC: Timeout! No signal received. Retry num = 29
03-20 12:39:38.917  2980  2980 E Zygote  : MountEmulatedStorage()
03-20 12:39:38.917  2920  2920 D AndroidRuntime: CheckJNI is OFF
03-20 12:39:38.917  2980  2980 E Zygote  : v2
03-20 12:39:38.917  2920  2920 D AndroidRuntime: readGMSProperty: start
03-20 12:39:38.917  2920  2920 D AndroidRuntime: readGMSProperty: already setted!!
03-20 12:39:38.917  2920  2920 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-20 12:39:38.917  2920  2920 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-20 12:39:38.927  1019  1559 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2980 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-20 12:39:38.917  2920  2920 D AndroidRuntime: readGMSProperty: end
03-20 12:39:38.917  2920  2920 D AndroidRuntime: addProductProperty: start
03-20 12:39:38.927  2980  2980 I libpersona: KNOX_SDCARD checking this for 10003
03-20 12:39:38.927  2980  2980 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:38.927  2980  2980 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:38.927  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:38.927  1019  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-20 12:39:38.927  1019  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:38.927  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-20 12:39:38.937  2980  2980 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:38.937  2980  2980 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:38.937  1182  1182 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
03-20 12:39:38.937  1019  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-20 12:39:38.937  1019  1482 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:38.937  1019  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:38.937  1019  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-20 12:39:38.937  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-20 12:39:38.937  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:38.937  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:38.937  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-20 12:39:38.947  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.947  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.947  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.947  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:38.947  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
03-20 12:39:38.947  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
03-20 12:39:38.957   316   316 I ServiceManager: Waiting for service AtCmdFwd...
03-20 12:39:38.967  1182  1182 D PanelView: There is/are notification(s) 
03-20 12:39:38.967  2995  2995 I libpersona: KNOX_SDCARD checking this for 10160
03-20 12:39:38.967  1182  1182 D PanelView: kidsfalse mQsExpansionEnabled:true
03-20 12:39:38.967  2995  2995 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:38.967  2980  2980 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:38.967  2980  2980 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:38.967  2995  2995 E Zygote  : MountEmulatedStorage()
03-20 12:39:38.967  2995  2995 E Zygote  : v2
03-20 12:39:38.967  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
03-20 12:39:38.967  1182  1182 D PanelView: There is/are notification(s) 
03-20 12:39:38.967  1182  1182 D PanelView: kidsfalse mQsExpansionEnabled:true
03-20 12:39:38.967  2995  2995 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:38.967  2995  2995 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:38.967  1019  1559 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2995 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-20 12:39:38.967  1019  1559 I ActivityManager: Killing 1606:com.sec.android.provider.badge/u0a72 (adj 13): empty #31
03-20 12:39:38.977  2995  2995 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:38.977  1019  1266 D RCPManagerService: exchangeData() failure , invalid userId
03-20 12:39:38.987  1468  1468 I CscUtil : isWifiOnly = false
03-20 12:39:38.987  1468  1468 I System.out: HandDataNode = null
03-20 12:39:38.987  1468  1468 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-20 12:39:38.987  1468  1468 I CscUpdateService: This is normal boot : CSC not updated
03-20 12:39:38.997  1019  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-20 12:39:38.997  1019  1482 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:38.997  1019  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:38.997  1019  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-20 12:39:38.997  1468  3011 E CscParser: update(): xml file exist
03-20 12:39:39.007  1468  3011 D CscGPS  : CSCGPS.updateParameters
03-20 12:39:39.007  1468  3011 D CscGPS  : supl host : null
03-20 12:39:39.007  1468  3011 D CscGPS  : SUPL Host is null or invalid
03-20 12:39:39.007  1468  3011 D CscGPS  : supl_ver : null
03-20 12:39:39.007  1468  3011 D CscGPS  : SUPL Ver is null or invalid
03-20 12:39:39.007  1468  3011 D CscGPS  : supl port : null
03-20 12:39:39.007  1468  3011 D CscGPS  : SUPL PORT is null or invalid
03-20 12:39:39.007  1468  3011 D CscGPS  : LPP : null
03-20 12:39:39.007  1468  3011 D CscGPS  : LPP is null or invalid
03-20 12:39:39.007  1468  3011 D CscGPS  : CSC don't have any AGPS value.
03-20 12:39:39.017  1019  1266 D RCPManagerService: exchangeData() failure , invalid userId
03-20 12:39:39.027  1728  2821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-20 12:39:39.027  1728  2821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-20 12:39:39.027  1728  2821 I GLSUser : [GLSUser] Extracting token using key: Auth
03-20 12:39:39.027  1728  2821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-20 12:39:39.027  1728  2821 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-20 12:39:39.037  1468  1468 I CscUpdateService: same CSC Version
03-20 12:39:39.037  1468  1468 D CscUtil : Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
03-20 12:39:39.037  1182  1182 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
03-20 12:39:39.047  2995  2995 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:39.047  2995  2995 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:39.067  1728  2821 I art     : WaitForGcToComplete blocked for 36.514ms for cause Explicit
03-20 12:39:39.067  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-20 12:39:39.077  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-20 12:39:39.077  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:39.077  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:39.077  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:39.077  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:39.077  1019  1131 I ActivityManager: Killing 2855:com.android.email/u0a145 (adj 13): depends on provider com.sec.android.provider.badge/.BadgeProvider in dying proc com.sec.android.provider.badge
03-20 12:39:39.077  1728  1742 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-20 12:39:39.097  2920  2920 E AffinityControl: AffinityControl: registerfunction enter
03-20 12:39:39.107  1728  2821 I art     : Explicit concurrent mark sweep GC freed 1961(89KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 997us total 41.002ms
03-20 12:39:39.117  1229  3014 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-20 12:39:39.117  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
03-20 12:39:39.117  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:39.117  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:39.117  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-20 12:39:39.127  1019  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
03-20 12:39:39.127  1019  1482 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:39.127  1019  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:39.127  1019  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-20 12:39:39.127  1019  1559 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-20 12:39:39.127  2920  2920 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-20 12:39:39.127  1019  1559 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-20 12:39:39.127  1019  1559 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-20 12:39:39.127  3025  3025 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:51:18:22 
03-20 12:39:39.127  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-20 12:39:39.137  1019  1043 W libprocessgroup: failed to open /acct/uid_10072/pid_1606/cgroup.procs: No such file or directory
03-20 12:39:39.137  1019  1019 I MotionRecognitionService: Plugged
03-20 12:39:39.137  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
03-20 12:39:39.137  2995  2995 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-20 12:39:39.147  1019  1385 E PersonaManagerService: inState():  stateMachine is null !!
03-20 12:39:39.147  1019  1385 I PersonaManagerService: PersonaId don't exist
03-20 12:39:39.147  1019  1385 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-20 12:39:39.147  3027  3027 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
03-20 12:39:39.157  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-20 12:39:39.157  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-20 12:39:39.157  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-20 12:39:39.167  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
03-20 12:39:39.167  1182  1182 D PowerUI : Cable  true --> true mBootCompleted : true
03-20 12:39:39.167  1182  1182 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-20 12:39:39.177  2719  2719 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-20 12:39:39.177  2719  2843 D HeadsetStateMachine: Disconnected process message: 10
03-20 12:39:39.187  2719  2807 I bt_vendor: bluetooth satus is on
03-20 12:39:39.187  2719  2945 D bt_userial_mct: userial_open(port:0)
03-20 12:39:39.187  2719  2945 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
03-20 12:39:39.187  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 12:39:39.187  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 12:39:39.187  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-20 12:39:39.187  1019  1385 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-20 12:39:39.197  2719  2945 I bt_vendor: Done intiailizing UART
03-20 12:39:39.197  2719  2945 I bt_vendor: Done intiailizing UART
03-20 12:39:39.197  2719  2945 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
03-20 12:39:39.197  2719  2945 I bt_vendor: Bluetooth Firmware and transport layer are initialized
03-20 12:39:39.197  2719  3032 D bt_userial_mct: Entering userial_read_thread()
03-20 12:39:39.197  1229  1229 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-20 12:39:39.207  1019  1385 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-20 12:39:39.207  1019  1385 W ActivityManager: mDVFSHelper.acquire()
03-20 12:39:39.207  1019  1385 D FocusedStackFrame: Set to : 0
03-20 12:39:39.217  1019  1385 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-20 12:39:39.217  1019  1385 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-20 12:39:39.217  1019  1385 D InputDispatcher: Focused application set to: xxxx
03-20 12:39:39.217  1019  1385 D InputDispatcher: Focus left window: 1493
03-20 12:39:39.217  1493  1493 D Launcher.HomeView: onPause
03-20 12:39:39.217  2920  2920 D AndroidRuntime: Shutting down VM
03-20 12:39:39.217  1493  1493 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-20 12:39:39.217  2980  3031 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
03-20 12:39:39.217  1229  3014 E SQLiteLog: (283) recovered 101 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-20 12:39:39.217  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-20 12:39:39.227  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:39.227  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:39.227  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-20 12:39:39.227  1019  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-20 12:39:39.227  1019  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-20 12:39:39.227  1019  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-20 12:39:39.227  1019  1488 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:39.227  1019  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:39.227  1019  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-20 12:39:39.237  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-20 12:39:39.237  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-20 12:39:39.237  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-20 12:39:39.237  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-20 12:39:39.237  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.237   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-20 12:39:39.237  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.237  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.237  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.257  3034  3034 E Zygote  : MountEmulatedStorage()
03-20 12:39:39.257  3034  3034 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:39.257  3034  3034 E Zygote  : v2
03-20 12:39:39.257  3034  3034 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:39.257  1019  1043 W libprocessgroup: failed to open /acct/uid_10145/pid_2855/cgroup.procs: No such file or directory
03-20 12:39:39.257  3034  3034 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:39.257  3034  3034 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:39.257  1019  1496 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3034 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-20 12:39:39.257  3034  3034 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:39.267  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.267  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.267  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.267  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.277  2980  3031 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
03-20 12:39:39.287  3045  3045 E Zygote  : MountEmulatedStorage()
03-20 12:39:39.287  3045  3045 E Zygote  : v2
03-20 12:39:39.287  3045  3045 I libpersona: KNOX_SDCARD checking this for 10174
03-20 12:39:39.287  3045  3045 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:39.287  3045  3045 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:39.287  3045  3045 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:39.287  1019  1385 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3045 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-20 12:39:39.287  3045  3045 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-20 12:39:39.297  2735  2861 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-20 12:39:39.297   337   337 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2980
03-20 12:39:39.297   337   337 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
03-20 12:39:39.297  2980  3031 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
03-20 12:39:39.297  2980  3031 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
03-20 12:39:39.307   337   337 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2980
03-20 12:39:39.307   337   337 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
03-20 12:39:39.307  1468  2556 D TP/MmsProvider: Update uri=content://mms, match=0
03-20 12:39:39.307  1468  2556 D TP/MmsProvider: update , handleReadChangedBroadcast
03-20 12:39:39.307  1468  2556 D TP/MmsSmsProvider: need read changed broadcast:false
03-20 12:39:39.317  1493  1493 V ActivityThread: updateVisibility : ActivityRecord{1a232f67 token=android.os.BinderProxy@350e842e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-20 12:39:39.317  2435  2435 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-20 12:39:39.317  2435  2435 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 3584.209582
03-20 12:39:39.317  2435  2435 I Mms/ReservationManager: resetAfterConnected()
03-20 12:39:39.317  3034  3034 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:39.317  1468  1486 D TP/MmsSmsProvider: query,matched:7, calling pid = 2435
03-20 12:39:39.327  3034  3034 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:39.327  1468  1486 D TP/MmsSmsProvider: match 7:Elapsed time : 9.320 ms
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_HCI
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_L2CAP
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_RFCOMM
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_AVDT
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_AVRC
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_A2D
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_BNEP
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_BTM
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_GAP
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_PAN
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_SAP
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_SDP
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_GATT
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_SMP
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_BTAPP
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_BTIF
03-20 12:39:39.337  2719  2941 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
03-20 12:39:39.337  2435  3060 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-20 12:39:39.337  2435  3060 D Mms/TelephonyPermission: isDefault true
03-20 12:39:39.337  3045  3045 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:39.337  3045  3045 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:39.347  1019  1482 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-20 12:39:39.347  1019  1482 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-20 12:39:39.347  1019  1482 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-20 12:39:39.347  1493  1493 D Launcher.HomeView: onStop
03-20 12:39:39.347  1493  1493 V ActivityThread: updateVisibility : ActivityRecord{1a232f67 token=android.os.BinderProxy@350e842e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-20 12:39:39.347  2995  2995 D [0]UMC:UMCContentProvider: @onCreate
03-20 12:39:39.357  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-20 12:39:39.357  2735  2815 E BooksSync: Soft error
03-20 12:39:39.357  2735  2815 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-20 12:39:39.357  2735  2815 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-20 12:39:39.357  2735  2815 E BooksSync: Sync error
03-20 12:39:39.357  2735  2815 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-20 12:39:39.357  2735  2815 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-20 12:39:39.357  2735  2815 I BooksSync: Finished books sync
03-20 12:39:39.367  1019  1482 D PersonaManager: isKioskContainerExistOnDevice
03-20 12:39:39.397  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-20 12:39:39.397  1019  1019 D SensorService: [SO] activate (ident=0xb7a9c258, enabled=0)
03-20 12:39:39.397  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-20 12:39:39.397  2995  2995 D [0]UMC:Core: onCreate(): 
03-20 12:39:39.397  2995  2995 D [0]UMC:Core: @isManagedProfileUser
03-20 12:39:39.397  2995  2995 D [0]UMC:Core: userId: 0
03-20 12:39:39.407  1019  1019 D SensorManager: unregisterListener ::   
03-20 12:39:39.407  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-20 12:39:39.407  1019  1019 D SensorService: [SO] changed settle time [1]
03-20 12:39:39.407  1019  1019 D SensorService: [SO] setDelay [66000000]
03-20 12:39:39.407  1019  1019 D SensorService: [SO] activate (ident=0xb7a9c258, enabled=1)
03-20 12:39:39.407  1019  1019 D SensorService: [SO] AR_init
03-20 12:39:39.407  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-20 12:39:39.407  2995  2995 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-20 12:39:39.407  2995  2995 D [0]UMC:Core: userInfo.isManagedProfile() : false
03-20 12:39:39.417  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-20 12:39:39.417  1019  1043 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 24795, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-20 12:39:39.427  2920  2920 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-20 12:39:39.447  1468  1490 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2435
,03-20 12:39:39.447  2719  2941 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,03-20 12:39:39.457  2719  2941 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa44106e9 
,03-20 12:39:39.457  2719  2941 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa44106e9 
,03-20 12:39:39.477  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-20 12:39:39.477  2995  2995 D [0]UMC:DeviceInfo: USA==US==
,03-20 12:39:39.487  2719  2810 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,03-20 12:39:39.487  2719  2810 E bt-btif :                : sec
,03-20 12:39:39.487  2719  2810 E bt-btif : BTM_SEC_REG[8]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
03-20 12:39:39.487  2719  2810 D BluetoothAdapterProperties: Address is:7C:F9:0E:51:18:22
03-20 12:39:39.487  2719  2810 E BluetoothServiceJni: populateRssiValuesNative
03-20 12:39:39.487  2719  2810 I bluedroid: getModelRssiValues
03-20 12:39:39.487  2719  2810 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-20 12:39:39.487  2719  2810 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,03-20 12:39:39.537  2995  2995 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-20 12:39:39.537  2995  2995 D [0]UMC:AdminManager: init - start
,03-20 12:39:39.547  1019  1041 D SensorService: [SO] 0.172 0.421 10.228
03-20 12:39:39.547  1019  1041 D SensorService: [SO] [100 -> 255]
,03-20 12:39:39.547  2995  2995 D [0]UMC:AdminManager: loadAdmins
,03-20 12:39:39.557  2995  2995 D [0]UMC:AdminManager: init - end
,03-20 12:39:39.557  2995  2995 D GSLBManager: migrateStoredUrlFromOldPref
,03-20 12:39:39.577  2995  2995 D GSLBManager:  key : segd-api
,03-20 12:39:39.577  2995  2995 D GSLBManager:  value : https://eu-segd-api.secb2b.com:443/v2
,03-20 12:39:39.587  2995  2995 D GSLBManager:  key : umc-cdn
,03-20 12:39:39.587  2995  2995 D GSLBManager:  value : 
,03-20 12:39:39.597  2995  2995 D GSLBManager:  key : segp-api
,03-20 12:39:39.597  2995  2995 D GSLBManager:  value : 
,03-20 12:39:39.607  2995  2995 D GSLBManager:  key : myknoxapi
03-20 12:39:39.607  2995  2995 D GSLBManager:  value : 
,03-20 12:39:39.607  1019  1488 I art     : Explicit concurrent mark sweep GC freed 167253(9MB) AllocSpace objects, 56(4MB) LOS objects, 33% free, 26MB/40MB, paused 5.298ms total 241.328ms
,03-20 12:39:39.617  1019  1482 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-20 12:39:39.617  1019  1482 D SecContentProvider2: mCursor = null
03-20 12:39:39.617  1019  3069 D SettingsProvider: name = next_alarm_formatted
03-20 12:39:39.617  1019  3069 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-20 12:39:39.617  1019  3069 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-20 12:39:39.617  1019  3069 D SettingsProvider: selectionArgs: false
03-20 12:39:39.617  1019  3069 D SettingsProvider: selectionArgs: 10085
03-20 12:39:39.617  1019  3069 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-20 12:39:39.617  1019  3069 D SettingsProvider: ret = -1
,03-20 12:39:39.617  1019  1019 D SettingsProvider: name = bluetooth_name
,03-20 12:39:39.617  2719  2810 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A5)
03-20 12:39:39.617  2995  2995 D GSLBManager: migrateStoredUrlFromOldPref : Finished Migrating
,03-20 12:39:39.617  2995  2995 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-20 12:39:39.617  2719  2810 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-20 12:39:39.617  2719  2810 D BluetoothAdapterProperties: Scan Mode:20
03-20 12:39:39.617  2719  2810 D BluetoothAdapterProperties: Discoverable Timeout:120
,03-20 12:39:39.617  2719  2810 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:A2:30:44
03-20 12:39:39.617  2719  2810 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-20 12:39:39.617  2719  2810 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
03-20 12:39:39.617  2719  2810 E bt-btif : btif_sock_init: !radio_req && !rfc_init
03-20 12:39:39.617  2719  2810 E bt-btif : btif_sock_init: !vhci_init
,03-20 12:39:39.617  2719  2810 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,03-20 12:39:39.627  1019  3069 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
03-20 12:39:39.627  2719  2810 D IOP_DB_BT: db_open: db_open : handle 3028168720l, read 13894 bytes onto local cache
03-20 12:39:39.627  2719  2810 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
03-20 12:39:39.627  2719  2810 D IOP_DB_BT: db_query: result 1
03-20 12:39:39.627  2719  2810 I         : iop_db_open: iop_db_open status 0
,03-20 12:39:39.627  2995  2995 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-20 12:39:39.627  2719  3032 E bt_mct  : hci lib postload completed
,03-20 12:39:39.637  1229  3014 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-20 12:39:39.647  2719  2810 D bte_conf: Device ID record 1 : primary
,03-20 12:39:39.647  2719  2810 D bte_conf:   vendorId            = 0075
03-20 12:39:39.647  2719  2810 D bte_conf:   vendorIdSource      = 0001
03-20 12:39:39.647  2719  2810 D bte_conf:   product             = 0100
03-20 12:39:39.647  2719  2810 D bte_conf:   version             = 0200
03-20 12:39:39.647  2719  2810 D bte_conf:   clientExecutableURL = ,
03-20 12:39:39.647  2719  2810 D bte_conf:   serviceDescription  = 
,03-20 12:39:39.647  2719  2810 D bte_conf:   documentationURL    = 
03-20 12:39:39.647  2719  2810 D bte_conf: bte_load_did_conf no section named DID2.
03-20 12:39:39.647  2719  2810 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
03-20 12:39:39.647  2435  2435 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-20 12:39:39.647  2995  2995 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,03-20 12:39:39.647  2995  2995 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-20 12:39:39.647  2995  2995 D [0]UMC:UMCAdmin: isContainer : 0
,03-20 12:39:39.647  2719  2807 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-20 12:39:39.647  2719  2807 D BluetoothAdapterProperties: ScanMode =  20
03-20 12:39:39.647  2719  2807 D BluetoothAdapterProperties: State =  11
,03-20 12:39:39.647  1019  1488 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,03-20 12:39:39.657  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:39.657  1019  3069 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,03-20 12:39:39.657  2719  2807 D BluetoothAdapterProperties: Setting state to 12
03-20 12:39:39.657  2719  2807 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,03-20 12:39:39.657  1493  1493 D Launcher: onTrimMemory. Level: 20
,03-20 12:39:39.657  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:39.657  1019  3069 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:39.657  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-20 12:39:39.667  2719  2810 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-20 12:39:39.667  2719  2810 D BluetoothAdapterProperties: Scan Mode:21
03-20 12:39:39.667  2719  2810 D BluetoothAdapterProperties: Discoverable Timeout:120
,03-20 12:39:39.667  1019  1482 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-20 12:39:39.667  1019  1482 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-20 12:39:39.667  1019  1482 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-20 12:39:39.667  1019  1482 D SettingsProvider: selectionArgs: false
03-20 12:39:39.667  1019  1482 D SettingsProvider: selectionArgs: 1002
03-20 12:39:39.667  1019  1482 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-20 12:39:39.667  1019  1482 D SettingsProvider: ret = -1
,03-20 12:39:39.677  1019  1482 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-20 12:39:39.677  2719  2807 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,03-20 12:39:39.677  2719  2807 D BluetoothAdapterService: updateAdapterState state is 12
,03-20 12:39:39.677  1019  3069 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,03-20 12:39:39.677  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:39.677  1019  3069 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:39.677  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-20 12:39:39.687  1443  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-20 12:39:39.687  1443  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-20 12:39:39.697  1454  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
03-20 12:39:39.697  1454  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-20 12:39:39.697  1182  1538 D BluetoothAdapter: onBluetoothStateChange: up=true
03-20 12:39:39.697  1182  1538 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-20 12:39:39.697  2719  2724 D BluetoothAdapter: onBluetoothStateChange: up=true
03-20 12:39:39.697  2719  2724 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-20 12:39:39.697  2719  2807 D BluetoothAdapterService: Autoconnection is available 
03-20 12:39:39.697  2719  2807 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-20 12:39:39.697  2719  2807 D BluetoothAdapterService: starting service from this receiver
03-20 12:39:39.697  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
03-20 12:39:39.697  1019  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-20 12:39:39.707  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.707  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.707  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
03-20 12:39:39.707  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.707  2719  2719 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
03-20 12:39:39.707  2719  2719 I BluetoothPbapService: Handler(): got msg=1
03-20 12:39:39.717  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.717  1019  1496 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-20 12:39:39.717  1019  1559 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-20 12:39:39.717  1468  1490 D BluetoothAdapter: onBluetoothStateChange: up=true
03-20 12:39:39.717  1468  1490 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-20 12:39:39.717  2995  2995 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-20 12:39:39.717  2995  2995 D [0]UMC:UMCAdmin: isContainer : 0
03-20 12:39:39.717  2150  2164 D BluetoothAdapter: onBluetoothStateChange: up=true
03-20 12:39:39.717  1468  1713 D TP/MmsSmsProvider: query,matched:200, calling pid = 2435
03-20 12:39:39.717  2150  2164 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-20 12:39:39.727  1468  1713 D TP/MmsSmsProvider: match 200:Elapsed time : 3.635 ms
03-20 12:39:39.727  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-20 12:39:39.727  3034  3034 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,03-20 12:39:39.727  1791  2037 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-20 12:39:39.727  1791  2037 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-20 12:39:39.727  2719  2839 D BluetoothA2dp: onBluetoothStateChange: up=true
,03-20 12:39:39.727  2995  2995 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-20 12:39:39.737  3079  3079 E Zygote  : MountEmulatedStorage(),
03-20 12:39:39.737  2719  3078 V BluetoothPbapService: PBAP Service initSocket try: 0
03-20 12:39:39.737  3079  3079 I libpersona: KNOX_SDCARD checking this for 10048
03-20 12:39:39.737  3079  3079 E Zygote  : v2
03-20 12:39:39.737  3079  3079 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:39.737  3079  3079 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:39.737  1019  1031 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3079 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-20 12:39:39.737  1019  3069 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,03-20 12:39:39.737  3079  3079 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:39.737  3079  3079 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:39.757  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:39.757  1019  3069 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:39.757  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-20 12:39:39.757  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,03-20 12:39:39.757  2719  2807 I BluetoothAdapterState: Entering On State from state = 11
,03-20 12:39:39.757  1019  1131 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
03-20 12:39:39.767  1019  1131 W ActivityManager: userId = 0, bbcId = -10000,
03-20 12:39:39.767  1019  1131 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:39.767  1019  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-20 12:39:39.767  2719  3078 D BluetoothSocket: bindListen(): myUserId = 0
03-20 12:39:39.767  2719  3078 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-20 12:39:39.767  2995  2995 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-20 12:39:39.777  2435  2435 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,03-20 12:39:39.777  2435  3077 D Mms/TelephonyPermission: isDefault true
03-20 12:39:39.777  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-20 12:39:39.777  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
03-20 12:39:39.777  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,03-20 12:39:39.777  2995  2995 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-20 12:39:39.777  2995  2995 D [0]UMC:CoreReceiver:  check PreETag 
,03-20 12:39:39.777  2435  3077 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
,03-20 12:39:39.777  2435  3077 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 462.13177
,03-20 12:39:39.787  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,03-20 12:39:39.787  3079  3079 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:39.787  3079  3079 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:39.797  1772  1772 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,03-20 12:39:39.797  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-20 12:39:39.807  1443  1443 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@34ac93e4, true
,03-20 12:39:39.807  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,03-20 12:39:39.807  1182  1182 D BluetoothTile:  getBluetoothState : 12
,03-20 12:39:39.807  2928  2928 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 161.323ms
,03-20 12:39:39.817  1229  3014 V MediaScanner: processDirectory :  /system/media
,03-20 12:39:39.817  1443  1443 D BluetoothHeadset: registerMessageListener
,03-20 12:39:39.817  2719  3078 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
03-20 12:39:39.817  1182  1719 D BluetoothTile:  handleUpdatestate:false name:null
03-20 12:39:39.817  2719  3078 D BluetoothSocket: bindListen(), new LocalSocket 
03-20 12:39:39.817  2719  3078 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-20 12:39:39.817  2719  3078 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3272e381
03-20 12:39:39.817  2719  3078 D BluetoothSocket: channel: 19
03-20 12:39:39.817  2719  3078 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,03-20 12:39:39.817   258   430 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
03-20 12:39:39.817   258   428 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-20 12:39:39.827  2995  2995 D [0]UMC:CoreReceiver: bulk enrolled package: null
03-20 12:39:39.827  2995  2995 V [0]UMC:ProfileStorage: Enter loadList
,03-20 12:39:39.827  2995  2995 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-20 12:39:39.827  2995  2995 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-20 12:39:39.827  3034  3034 D DSM     : [Lines:107] Normal booted
,03-20 12:39:39.837  2719  2724 D HeadsetService: registerMessageListener
,03-20 12:39:39.837  2719  2724 D HeadsetService: registerMessageListener
,03-20 12:39:39.837  2719  2843 D HeadsetStateMachine: Disconnected process message: 70
,03-20 12:39:39.837  2719  2843 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1b790067
,03-20 12:39:39.837  1443  1443 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-20 12:39:39.837  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,03-20 12:39:39.837  3034  3034 D DSM     : [Lines:114] Boot completed
,03-20 12:39:39.837  1019  1131 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-20 12:39:39.847  1182  1719 D BluetoothTile:  handleUpdatestate:false name:null
,03-20 12:39:39.847  1182  1719 D BluetoothTile:  handleUpdatestate:false name:null
,03-20 12:39:39.847  1468  1713 D TP/SmsProvider: query,matched:0, calling pid = 2435
,03-20 12:39:39.857  2719  3098 D BluetoothMapMasInstance: set MAP SDP message type : 1
,03-20 12:39:39.857  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,03-20 12:39:39.857  1468  1713 D TP/SmsProvider: match 0:Elapsed time : 4.632 ms
03-20 12:39:39.857  1019  1482 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,03-20 12:39:39.857  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,03-20 12:39:39.857  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,03-20 12:39:39.857  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-20 12:39:39.867  2995  2995 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-20 12:39:39.867  2719  2843 D HeadsetStateMachine: Disconnected process message: 9
,03-20 12:39:39.867  2719  2843 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,03-20 12:39:39.867  3045  3045 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-20 12:39:39.877  2995  2995 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-20 12:39:39.877  2995  2995 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-20 12:39:39.877  2995  2995 D [0]UMC:UMCAdmin: isContainer : 0
,03-20 12:39:39.887   284   695 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,03-20 12:39:39.887  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.887  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.887  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:39.887  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:39.887   284   695 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-20 12:39:39.887  1229  3014 V MediaScanner:  prescan time: 615ms (DB items: 141)
03-20 12:39:39.887   284   695 V voice   : voice_set_parameters: exit with code(-2)
03-20 12:39:39.887  1229  3014 V MediaScanner:     scan time: 86ms (Caching mode: true), (makeEntry time: 61ms ~70%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-20 12:39:39.887   284   695 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-20 12:39:39.887  1229  3014 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-20 12:39:39.887   284   695 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-20 12:39:39.887  1229  3014 V MediaScanner:    total time: 701ms
03-20 12:39:39.887   284   695 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-20 12:39:39.887  1229  3014 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
03-20 12:39:39.887   284   695 V audio_hw_primary: adev_set_parameters: exit
03-20 12:39:39.887  2719  2843 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,03-20 12:39:39.887  1229  3014 D MediaScanner: checkDefaultSounds
03-20 12:39:39.887  1229  3014 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
,03-20 12:39:39.897  1019  1131 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-20 12:39:39.897  3045  3045 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6351-6353)
03-20 12:39:39.897  3045  3045 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-20 12:39:39.897  2995  2995 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-20 12:39:39.897  2995  2995 D [0]UMC:UMCAdmin: isContainer : 0
,03-20 12:39:39.897  2995  2995 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-20 12:39:39.897  1468  2556 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-20 12:39:39.907  3102  3102 E Zygote  : MountEmulatedStorage()
03-20 12:39:39.907  3102  3102 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:39.907  3102  3102 E Zygote  : v2
03-20 12:39:39.907  3102  3102 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:39.907  3102  3102 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:39.907  3102  3102 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:39.907  3102  3102 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:39.907  1468  2556 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
03-20 12:39:39.907  2995  2995 D [0]UMC:ByodSetupStarter: Container ID : 0,
03-20 12:39:39.917  1019  1385 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3102 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-20 12:39:39.917  1468  2556 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-20 12:39:39.917  1468  2556 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
,03-20 12:39:39.917  1468  2556 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-20 12:39:39.917   297   297 E USB_UICC: Timeout! No signal received. Retry num = 30
03-20 12:39:39.917  1468  2556 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-20 12:39:39.927  1468  2556 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-20 12:39:39.927  2995  2995 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
03-20 12:39:39.927  2995  2995 I [0]UMC:Core: shutdown
03-20 12:39:39.927  3045  3045 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23bc814a}
03-20 12:39:39.927  3045  3045 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-20 12:39:39.927  3045  3045 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-20 12:39:39.927  3079  3079 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-20 12:39:39.927  3079  3079 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-20 12:39:39.927  3079  3079 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-20 12:39:39.927  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-20 12:39:39.927  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:39.927  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:39.927  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-20 12:39:39.937  2719  3098 D BluetoothSocket: bindListen(): myUserId = 0
03-20 12:39:39.937  2719  3098 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-20 12:39:39.937  2995  2995 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-20 12:39:39.937  2719  3098 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,03-20 12:39:39.937  1468  2556 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-20 12:39:39.937  1468  2556 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-20 12:39:39.937  1468  2556 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-20 12:39:39.937  1468  2556 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-20 12:39:39.937  3102  3102 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:39.937  2719  3098 D BluetoothSocket: bindListen(), new LocalSocket 
,03-20 12:39:39.937  2719  3098 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-20 12:39:39.937  2719  3098 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@74ebe14
03-20 12:39:39.937  3102  3102 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:39.937  2719  3098 D BluetoothSocket: channel: 5
,03-20 12:39:39.947  1468  2557 D TP/SmsProvider: query,matched:51, calling pid = 2435
03-20 12:39:39.947  1229  3014 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-20 12:39:39.947  1229  3014 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
,03-20 12:39:39.947  1229  3014 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-20 12:39:39.957  1229  3014 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-20 12:39:39.957  1229  3014 D MediaScanner: OK. ringtone is already exist in setting DB.
03-20 12:39:39.957   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 12:39:39.957  1019  1488 I ActivityManager: Killing 1691:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,03-20 12:39:39.957  3102  3102 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-20 12:39:39.967  2694  2694 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2694) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-20 12:39:39.967  2694  2694 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2694) ACTION_MEDIA_SCANNER_FINISHED = /system/media
,03-20 12:39:39.967  2694  2694 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2694) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-20 12:39:39.967  3045  3045 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-20 12:39:39.967  3045  3045 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-20 12:39:39.967  2995  2995 I art     : System.exit called, status: 0
03-20 12:39:39.967  2995  2995 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-20 12:39:39.967  3045  3045 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-20 12:39:39.977  1229  3014 D MediaScannerService: !@done scanning volume internal
03-20 12:39:39.977  1229  3014 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-20 12:39:39.977  1468  2557 D TP/SmsProvider: match 51:Elapsed time : 36.081 ms
,03-20 12:39:39.997  3045  3045 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-20 12:39:39.997  1019  1031 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2995)(adj 0) has died(80,1077)
,03-20 12:39:40.007  3045  3045 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-20 12:39:40.007  3045  3045 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-20 12:39:40.007  1468  2556 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-20 12:39:40.007  1468  2556 D TP/MmsSmsProvider: need read changed broadcast:false
,03-20 12:39:40.017  1229  3014 D MediaProvider: savePlaylistTableInBulkDeleter started
03-20 12:39:40.017   297   297 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-20 12:39:40.017   297   297 E USB_UICC: usb_uicc_init_qmi failed ! 
03-20 12:39:40.017   297   297 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-20 12:39:40.017   297   297 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-20 12:39:40.017  1229  3014 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-20 12:39:40.017  2435  3077 D Mms/Conversation: deleteTempConversation(),deleted=0
,03-20 12:39:40.017  1468  1490 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-20 12:39:40.027  1229  3014 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty,
,03-20 12:39:40.027  1229  3014 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-20 12:39:40.027  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-20 12:39:40.027  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-20 12:39:40.027  1291  1291 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-20 12:39:40.027  1229  3014 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-20 12:39:40.027  1229  3014 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,03-20 12:39:40.027  1229  3014 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,03-20 12:39:40.037  1229  3014 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-20 12:39:40.037  1468  1490 D TP/MmsSmsProvider: need read changed broadcast:false,
,03-20 12:39:40.047  3102  3102 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-20 12:39:40.057  1468  2557 I art     : Explicit concurrent mark sweep GC freed 39051(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/12MB, paused 950us total 71.789ms,
,03-20 12:39:40.057  1291  1291 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-20 12:39:40.057  1291  1291 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-20 12:39:40.067  1229  3014 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-20 12:39:40.067  1291  1291 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-20 12:39:40.067  1291  1291 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-20 12:39:40.067  1019  3069 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
03-20 12:39:40.067  1291  1291 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-20 12:39:40.067  1291  1291 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-20 12:39:40.067  1291  1291 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-20 12:39:40.067  1291  1291 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-20 12:39:40.067  1291  1291 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-20 12:39:40.067  1019  1385 D SettingsProvider: name = block_emergency_message
03-20 12:39:40.067  1019  1385 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-20 12:39:40.067  1019  1385 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-20 12:39:40.067  1019  1385 D SettingsProvider: selectionArgs: false
03-20 12:39:40.067  1019  1385 D SettingsProvider: selectionArgs: 10048
03-20 12:39:40.067  1019  1385 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-20 12:39:40.067  1019  1385 D SettingsProvider: ret = -1
03-20 12:39:40.067  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:40.067  1019  3069 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:40.067  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:40.077  1019  1488 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing,
03-20 12:39:40.077  1019  1446 D SettingsProvider: name = aw_daemon_service_key_version_check
,03-20 12:39:40.077  1019  1446 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-20 12:39:40.077  1019  1446 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-20 12:39:40.077  1019  1446 D SettingsProvider: selectionArgs: false
03-20 12:39:40.077  1019  1446 D SettingsProvider: selectionArgs: 10162
03-20 12:39:40.077  1019  1446 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-20 12:39:40.077  1019  1446 D SettingsProvider: ret = -1
,03-20 12:39:40.087  2435  3077 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-20 12:39:40.087  2435  3077 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-20 12:39:40.087  2435  3077 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
,03-20 12:39:40.087  1229  3014 V MediaScanner: processDirectory :  /storage/emulated/0
,03-20 12:39:40.087  1019  1446 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-20 12:39:40.087  1291  1291 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-20 12:39:40.097  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-20 12:39:40.097  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-20 12:39:40.097  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
03-20 12:39:40.097  2435  3060 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-20 12:39:40.097  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
03-20 12:39:40.097  3102  3102 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
03-20 12:39:40.097  1229  3014 D MediaScanner: Skipping:
03-20 12:39:40.097  1229  3014 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-20 12:39:40.097  1019  1043 W libprocessgroup: failed to open /acct/uid_10138/pid_1691/cgroup.procs: No such file or directory
,03-20 12:39:40.107  1229  3014 D MediaScanner: Skipping:
03-20 12:39:40.107  1229  3014 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-20 12:39:40.107  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.107  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.107  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.107  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.107  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-20 12:39:40.107  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-20 12:39:40.107  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-20 12:39:40.107  1468  1713 D TP/SmsProvider: query,matched:26, calling pid = 2435
,03-20 12:39:40.107  1291  1291 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-20 12:39:40.107  1468  1713 D TP/SmsProvider: match 26:Elapsed time : 3.860 ms
,03-20 12:39:40.117  1291  1291 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-20 12:39:40.117  1291  1291 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-20 12:39:40.117  1229  3014 V MediaScanner: processDirectory :  /storage/extSdCard
03-20 12:39:40.117  1229  3014 W MediaScanner: Error opening directory, reason : Permission denied.
03-20 12:39:40.117  1229  3014 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-20 12:39:40.117  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458473980127
03-20 12:39:40.117  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458495540000
03-20 12:39:40.117  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-20 12:39:40.117  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-20 12:39:40.117  1229  3014 V MediaScanner:  prescan time: 51ms (DB items: 27)
03-20 12:39:40.117  1229  3014 V MediaScanner:     scan time: 30ms (Caching mode: true), (makeEntry time: 16ms ~53%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-20 12:39:40.117  1229  3014 V MediaScanner: postscan time: 4ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
,03-20 12:39:40.117  1229  3014 V MediaScanner:    total time: 85ms
03-20 12:39:40.117  1229  3014 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-20 12:39:40.127  3132  3132 E Zygote  : MountEmulatedStorage()
,03-20 12:39:40.127  3132  3132 E Zygote  : v2
03-20 12:39:40.127  3132  3132 I libpersona: KNOX_SDCARD checking this for 10072
03-20 12:39:40.127  3132  3132 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:40.127  3132  3132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:40.127  1019  1329 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3132 uid=10072 gids={50072, 9997} abi=armeabi-v7a
03-20 12:39:40.127  3132  3132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:40.137  3132  3132 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-20 12:39:40.137  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-20 12:39:40.137  1229  3014 D MediaScannerService: !@done scanning volume external
,03-20 12:39:40.137  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.147  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.147  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.147  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.147  1291  1291 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458495540000,
,03-20 12:39:40.147  2694  2694 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2694) action= = android.intent.action.MEDIA_SCANNER_FINISHED,
03-20 12:39:40.147  2694  2694 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2694) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-20 12:39:40.147  2694  2694 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2694) ...
03-20 12:39:40.147  2694  2694 D FactoryTestApp: [Support$Values.getString](2694) id=MODEL_COMMUNICATION_MODE, value=gsm,
03-20 12:39:40.147  2694  2694 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2694) mConnectionMode = gsm
03-20 12:39:40.147  2694  2694 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2694) Create IPCWriterToSecPhoneService
03-20 12:39:40.147  2694  2694 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2694)  ,
,03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-20 12:39:40.157  2694  2694 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
,03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-20 12:39:40.157  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-20 12:39:40.167  3045  3045 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-20 12:39:40.167  3045  3045 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-20 12:39:40.167  3045  3045 I Adreno-EGL: Build Date: 04/06/15 Mon
03-20 12:39:40.167  3045  3045 I Adreno-EGL: Local Branch: 
03-20 12:39:40.167  3045  3045 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-20 12:39:40.167  3045  3045 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-20 12:39:40.167  3045  3045 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-20 12:39:40.167  1291  1291 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 19
03-20 12:39:40.167  1291  1291 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458495540000
03-20 12:39:40.167  3142  3142 E Zygote  : MountEmulatedStorage()
03-20 12:39:40.167  3142  3142 E Zygote  : v2
03-20 12:39:40.167  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-20 12:39:40.167  3142  3142 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:40.167  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-20 12:39:40.167  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-20 12:39:40.167  3132  3132 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:40.167  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-20 12:39:40.167  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-20 12:39:40.167  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-20 12:39:40.167  3142  3142 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:40.167  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-20 12:39:40.167  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-20 12:39:40.167  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-20 12:39:40.167  3132  3132 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:40.167  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-20 12:39:40.167  3142  3142 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:40.177  1019  1446 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3142 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-20 12:39:40.177  3102  3102 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-20 12:39:40.177  3142  3142 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:40.177  1019  1446 I ActivityManager: Killing 1561:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
03-20 12:39:40.177  3142  3142 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:40.177  3102  3102 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-20 12:39:40.177   337   337 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
03-20 12:39:40.187  1019  3068 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,03-20 12:39:40.187  1019  3068 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:40.187  1019  3068 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:40.187  1019  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-20 12:39:40.197  1019  3069 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
03-20 12:39:40.197  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:40.197  1291  1291 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-20 12:39:40.197  1291  1291 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
03-20 12:39:40.197  1019  3069 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:40.197  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-20 12:39:40.207  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.207  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.207  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.207  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.217  1330  1330 I WifiCredService: onCreate
03-20 12:39:40.217  3142  3142 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:40.217  3142  3142 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:40.227  2980  3031 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
03-20 12:39:40.227  2980  3031 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,03-20 12:39:40.237  3175  3175 E Zygote  : MountEmulatedStorage()
03-20 12:39:40.237  3175  3175 E Zygote  : v2
03-20 12:39:40.237  3175  3175 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:40.237  3175  3175 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:40.237  3175  3175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-20 12:39:40.247  3175  3175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:40.247  1019  1446 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3175 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-20 12:39:40.247  3175  3175 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:40.247  2435  3077 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-20 12:39:40.247  2435  3077 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-20 12:39:40.247  2435  3077 D Mms/TelephonyPermission: isDefault true
,03-20 12:39:40.257  2694  2694 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2694) connected done
03-20 12:39:40.257  2694  2694 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2694) Send Response Message to SecPhone
03-20 12:39:40.257  2694  2694 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2694) Response ��
,03-20 12:39:40.267  1929  1929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-20 12:39:40.277  1330  1330 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,03-20 12:39:40.277  1019  1136 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-20 12:39:40.277  1019  1136 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-20 12:39:40.277  1019  1136 E WifiNative-wlan0: invaild command id : 215
,03-20 12:39:40.277  1468  1490 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2435
,03-20 12:39:40.277  1330  1330 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-20 12:39:40.277  1330  1330 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-20 12:39:40.277  1330  1330 D MY_TAG  : Action boot completed received
,03-20 12:39:40.277  1019  1488 D ActivityManager: retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,03-20 12:39:40.277  3132  3132 D BadgeProvider: onCreate
03-20 12:39:40.277  3132  3132 D BadgeProvider: DatabaseHelper
,03-20 12:39:40.287  1019  1488 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:40.287  1019  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:40.287  1019  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-20 12:39:40.287  1929  1929 D SecUISvc: Service started flags 0 startId 1
,03-20 12:39:40.287  1929  3194 D SecUISvc: Thread created.
03-20 12:39:40.287   312  1077 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-20 12:39:40.297  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.297  3175  3175 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:40.297  3175  3175 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:40.297  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.297  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.297  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.307  2694  2694 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2694) Send BOOTING COMPLETED done,
,03-20 12:39:40.307  3142  3142 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-20 12:39:40.317  3197  3197 E Zygote  : MountEmulatedStorage()
03-20 12:39:40.317  3197  3197 E Zygote  : v2
03-20 12:39:40.317  3197  3197 I libpersona: KNOX_SDCARD checking this for 10028
03-20 12:39:40.317  3197  3197 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:40.317  3197  3197 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:40.317  3197  3197 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-20 12:39:40.317  3197  3197 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-20 12:39:40.317  1019  1031 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3197 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-20 12:39:40.347  3197  3197 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:40.347  3197  3197 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:40.357  3132  3141 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-20 12:39:40.367  1330  1330 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-20 12:39:40.367  1330  2645 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-20 12:39:40.367  1019  3068 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,03-20 12:39:40.367  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.367  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.367  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.367  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.387  3214  3214 E Zygote  : MountEmulatedStorage()
03-20 12:39:40.387  3214  3214 E Zygote  : v2
03-20 12:39:40.387  3214  3214 I libpersona: KNOX_SDCARD checking this for 10086
03-20 12:39:40.387  3214  3214 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:40.387  3214  3214 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:40.387  3214  3214 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:40.387  3214  3214 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-20 12:39:40.387  1019  1385 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3214 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,03-20 12:39:40.397   312  1077 D AT_Distributor: SetAtdStatus(), 1_1_0
03-20 12:39:40.397   312  1077 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
,03-20 12:39:40.397  1019  1385 I ActivityManager: Killing 2150:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-20 12:39:40.407  1468  1486 D TP/MmsSmsProvider: query,matched:200, calling pid = 2435
,03-20 12:39:40.407  1468  1486 D TP/MmsSmsProvider: match 200:Elapsed time : 1.482 ms
,03-20 12:39:40.407  1019  1043 W libprocessgroup: failed to open /acct/uid_10057/pid_1561/cgroup.procs: No such file or directory
,03-20 12:39:40.407   306   306 I art     : Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 19.849ms
,03-20 12:39:40.417  3214  3214 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:40.417  3214  3214 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:40.427  3132  3141 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-20 12:39:40.427  3132  3141 D BadgeProvider: sendNotify, [notify] : null
03-20 12:39:40.427  3132  3141 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-20 12:39:40.427  3132  3141 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-20 12:39:40.427  3132  3141 D BadgeProvider: update, [UpdateCount] : 1
,03-20 12:39:40.427   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 17.069ms
03-20 12:39:40.427  1493  1493 D Launcher.Model: reloadBadges entered.
,03-20 12:39:40.437  2435  3060 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-20 12:39:40.437  2435  3060 D Mms/MessagingNotification: remove alarm
,03-20 12:39:40.447  1468  1486 D TP/SmsProvider: query,matched:0, calling pid = 2435
,03-20 12:39:40.447  1468  1486 D TP/SmsProvider: match 0:Elapsed time : 1.206 ms
,03-20 12:39:40.447  1468  2557 D TP/SmsProvider: query,matched:0, calling pid = 2435
,03-20 12:39:40.447  1019  1131 I ActivityManager: Killing 2172:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
03-20 12:39:40.447   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.373ms
,03-20 12:39:40.447  2435  3060 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 673.343698
,03-20 12:39:40.447  2435  3231 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-20 12:39:40.447  1468  2557 D TP/SmsProvider: match 0:Elapsed time : 5.296 ms
,03-20 12:39:40.467  1468  1490 D TP/SmsProvider: query,matched:51, calling pid = 2435
,03-20 12:39:40.467  1468  1490 D TP/SmsProvider: match 51:Elapsed time : 2.950 ms
,03-20 12:39:40.477  2435  3077 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-20 12:39:40.487  3132  3232 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-20 12:39:40.487  1330  1330 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,03-20 12:39:40.487  1330  1330 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-20 12:39:40.487  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:40.497  1019  1496 D SettingsProvider: name = personal_mode_enabled
,03-20 12:39:40.507  2719  2844 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-20 12:39:40.507  3045  3045 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-20 12:39:40.517  3175  3175 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-20 12:39:40.517  2719  2844 D BluetoothMediaBrowser: no now playing list
,03-20 12:39:40.527  2719  2844 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-20 12:39:40.527  3132  3141 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
,03-20 12:39:40.527  1493  1493 D Launcher.Model: reloadBadges entered.
,03-20 12:39:40.527  3132  3141 D BadgeProvider: sendNotify, [notify] : null
03-20 12:39:40.527  3132  3141 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-20 12:39:40.527  3132  3141 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-20 12:39:40.527  3132  3141 D BadgeProvider: update, [UpdateCount] : 1
,03-20 12:39:40.527  2435  3077 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-20 12:39:40.537  2435  3077 D Mms/MessagingNotification: remove alarm
,03-20 12:39:40.547  1019  1043 W libprocessgroup: failed to open /acct/uid_10031/pid_2150/cgroup.procs: No such file or directory
,03-20 12:39:40.547  1019  1043 W libprocessgroup: failed to open /acct/uid_10050/pid_2172/cgroup.procs: No such file or directory
,03-20 12:39:40.547  2435  3233 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-20 12:39:40.557  1468  2556 D TP/SmsProvider: query,matched:0, calling pid = 2435
,03-20 12:39:40.557  1468  2556 D TP/SmsProvider: match 0:Elapsed time : 2.597 ms
,03-20 12:39:40.557  2435  3077 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 107.977812
,03-20 12:39:40.567  1019  1482 I ActivityManager: Killing 2194:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,03-20 12:39:40.617  3045  3045 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-20 12:39:40.627  3045  3045 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-20 12:39:40.627  3045  3045 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-20 12:39:40.627  3045  3045 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-20 12:39:40.637  3045  3045 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-20 12:39:40.637  3045  3045 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-20 12:39:40.677  1019  1043 W libprocessgroup: failed to open /acct/uid_10113/pid_2194/cgroup.procs: No such file or directory
03-20 12:39:40.677  1468  1468 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-20 12:39:40.677  1468  1468 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-20 12:39:40.677  1468  1468 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-20 12:39:40.677  1468  1468 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-20 12:39:40.677  1468  1468 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-20 12:39:40.677  1468  1468 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-20 12:39:40.687  3045  3241 D OpenGLRenderer: Render dirty regions requested: true
,03-20 12:39:40.687  1019  1329 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-20 12:39:40.687  1019  1329 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-20 12:39:40.687  1019  1329 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-20 12:39:40.687  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-20 12:39:40.697  3045  3171 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-20 12:39:40.697  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-20 12:39:40.697  1989  3130 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,03-20 12:39:40.697  3045  3045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-20 12:39:40.697  3045  3045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-20 12:39:40.717   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-20 12:39:40.717  1019  1031 D InputDispatcher: Focus entered window: 3045,
,03-20 12:39:40.727  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-20 12:39:40.727  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-20 12:39:40.727  3045  3045 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-20 12:39:40.727  3045  3241 I OpenGLRenderer: Initialized EGL, version 1.4
,03-20 12:39:40.737  3045  3241 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-20 12:39:40.737  3045  3241 D OpenGLRenderer: Enabling debug mode 0
,03-20 12:39:40.757  3214  3214 E UpdateRequestReceiver: ignoring update request
,03-20 12:39:40.767  3214  3214 E UpdateRequestReceiver: ignoring update request
,03-20 12:39:40.797  3214  3214 E UpdateRequestReceiver: ignoring update request
,03-20 12:39:40.837  3175  3175 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-20 12:39:40.847  3175  3175 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-20 12:39:40.847  1019  1482 I art     : Explicit concurrent mark sweep GC freed 12823(614KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/40MB, paused 2.597ms total 153.410ms
,03-20 12:39:40.857  3175  3175 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-20 12:39:40.857  3175  3175 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-20 12:39:40.857  3175  3175 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-20 12:39:40.857  3175  3175 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-20 12:39:40.877  3214  3214 E UpdateRequestReceiver: ignoring update request
,03-20 12:39:40.877  3214  3214 E UpdateRequestReceiver: ignoring update request
,03-20 12:39:40.897  3214  3214 E UpdateRequestReceiver: ignoring update request
,03-20 12:39:40.897  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.897  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.907  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.907  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.907  1019  1032 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-20 12:39:40.917  1019  3255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 12:39:40.917  3256  3256 E Zygote  : MountEmulatedStorage()
03-20 12:39:40.917  3256  3256 E Zygote  : v2
03-20 12:39:40.917  3256  3256 I libpersona: KNOX_SDCARD checking this for 10094
03-20 12:39:40.917  3256  3256 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:40.917  3256  3256 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-20 12:39:40.927  1182  1182 D PanelView: There is/are notification(s) 
03-20 12:39:40.927  3256  3256 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:40.927  3256  3256 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:40.927  1019  1131 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3256 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-20 12:39:40.927  1019  1131 I ActivityManager: Killing 1510:com.android.printspooler/u0a136 (adj 15): empty #31
,03-20 12:39:40.937   289   289 E SMD     : DCD OFF
,03-20 12:39:40.937  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.937  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.937  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:40.937  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:40.947  3045  3045 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2aee55b4 time:37402
,03-20 12:39:40.947  1772  1772 I SamsungIME: getCurrentCandidateView
,03-20 12:39:40.957  3256  3256 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:40.957  3256  3256 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:40.957   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-20 12:39:40.967  3274  3274 E Zygote  : MountEmulatedStorage(),
03-20 12:39:40.967  3274  3274 E Zygote  : v2
03-20 12:39:40.967  3274  3274 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:40.967  3274  3274 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:40.967  3274  3274 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:40.967  1019  1031 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3274 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-20 12:39:40.967  3274  3274 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:40.967  3274  3274 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:40.967  1019  1050 I ActivityManager: Displayed Component not be shown by security: +1s707ms
,03-20 12:39:40.977  1019  1050 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-20 12:39:40.977  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{32c000b3 u0 com.test.thalitest/.MainActivity t236} time:37433
03-20 12:39:40.977  1019  1050 W ActivityManager: mDVFSHelper.release()
03-20 12:39:40.977  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-20 12:39:40.987  1330  1330 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-20 12:39:40.987  1330  1330 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-20 12:39:40.997  1989  3130 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 299 ms
,03-20 12:39:41.017  1330  1330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-20 12:39:41.017  1330  1330 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-20 12:39:41.017  3274  3274 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:41.027  3274  3274 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:41.027  1772  1772 D SamsungIME: Dismiss ExpandCandiate
,03-20 12:39:41.047  1019  1043 W libprocessgroup: failed to open /acct/uid_10136/pid_1510/cgroup.procs: No such file or directory
,03-20 12:39:41.067  3256  3256 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-20 12:39:41.067  3256  3256 D elm:15183: ELMEngine.ELMEngine( context ).
,03-20 12:39:41.067  3256  3256 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-20 12:39:41.067  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-20 12:39:41.067  1019  1446 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:41.067  1019  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:41.067  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-20 12:39:41.077  3256  3256 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-20 12:39:41.077  1421  1421 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-20 12:39:41.077  3256  3256 D elm:15183: ElmAgentService : onCreate()
,03-20 12:39:41.077  3256  3290 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-20 12:39:41.077  3256  3256 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-20 12:39:41.077  3256  3256 D elm:15183: BootCompletedState : startBootCompleted() call
,03-20 12:39:41.087  3256  3256 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-20 12:39:41.087  3256  3256 I elm:15183: Get License : 0
,03-20 12:39:41.087  3256  3256 D elm:15183: ElmAgentService : onDestroy().
,03-20 12:39:41.087  1019  1266 I ActivityManager: Killing 2396:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-20 12:39:41.117  3197  3197 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-20 12:39:41.127  1330  1330 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-20 12:39:41.127  1330  1330 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
,03-20 12:39:41.127  1330  1330 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-20 12:39:41.147  1330  1330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-20 12:39:41.147  1330  3298 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-20 12:39:41.157  1421  1421 V EmergencyMode: [EmergencyBase] setBootTime
,03-20 12:39:41.157  1421  1421 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-20 12:39:41.157  1019  3069 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.157  1019  3069 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.157  1019  3069 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.157  1019  3069 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:41.167  1772  1772 I SamsungIME: getDebugLevel  : 0x4f4c
,03-20 12:39:41.177   258   430 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
03-20 12:39:41.177   258  1105 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
03-20 12:39:41.177  3299  3299 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:41.177  3299  3299 E Zygote  : MountEmulatedStorage()
03-20 12:39:41.177  3299  3299 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:41.177  3299  3299 E Zygote  : v2
03-20 12:39:41.177  3299  3299 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:41.177  3299  3299 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:41.177  3299  3299 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:41.177  1019  3069 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3299 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-20 12:39:41.187  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.187  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.187  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.187  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.197  1019  1043 W libprocessgroup: failed to open /acct/uid_10142/pid_2396/cgroup.procs: No such file or directory,
,03-20 12:39:41.207  3312  3312 E Zygote  : MountEmulatedStorage()
03-20 12:39:41.207  3312  3312 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:41.207  3312  3312 E Zygote  : v2
03-20 12:39:41.207  3312  3312 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:41.207  3312  3312 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:41.207  3312  3312 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:41.207  3312  3312 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:41.207  1019  1559 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3312 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-20 12:39:41.217  3299  3299 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:41.217  3299  3299 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:41.217  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.217  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.217  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.217  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:41.227  3312  3312 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:41.227  3312  3312 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:41.227  3328  3328 E Zygote  : MountEmulatedStorage(),
03-20 12:39:41.227  3328  3328 E Zygote  : v2
03-20 12:39:41.227  3328  3328 I libpersona: KNOX_SDCARD checking this for 10009
03-20 12:39:41.227  3328  3328 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:41.227  3328  3328 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:41.227  3274  3274 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-20 12:39:41.237  3328  3328 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:41.237  1019  1446 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3328 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-20 12:39:41.237  3274  3274 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-20 12:39:41.237  3328  3328 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-20 12:39:41.247  3274  3326 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-20 12:39:41.247  3274  3274 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
03-20 12:39:41.247  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.247  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.247  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.247  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:41.247  3274  3326 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-20 12:39:41.257  3299  3299 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-20 12:39:41.267  3350  3350 E Zygote  : MountEmulatedStorage()
03-20 12:39:41.267  3350  3350 E Zygote  : v2
03-20 12:39:41.267  3350  3350 I libpersona: KNOX_SDCARD checking this for 10150
03-20 12:39:41.267  3350  3350 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:41.267  3350  3350 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:41.267  3350  3350 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:41.267  3274  3326 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-20 12:39:41.267  3350  3350 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-20 12:39:41.267  3274  3274 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
03-20 12:39:41.267  3328  3328 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:41.267  1019  1131 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3350 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,03-20 12:39:41.277  3328  3328 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:41.277  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-20 12:39:41.277  3274  3274 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-20 12:39:41.277  3274  3274 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
03-20 12:39:41.277  2980  2980 E BluetoothHeadset: BTStateChangeCB is registed
,03-20 12:39:41.277  3274  3274 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
03-20 12:39:41.277  3274  3274 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,03-20 12:39:41.287  2980  2980 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-20 12:39:41.287  3274  3274 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-20 12:39:41.287  3274  3274 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-20 12:39:41.287  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-20 12:39:41.297  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:41.297  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:41.297  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-20 12:39:41.297  2980  2980 E BluetoothHeadset: BluetoothHeadset service is binded
,03-20 12:39:41.297  3274  3274 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-20 12:39:41.297  3274  3274 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-20 12:39:41.297  2980  2980 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-20 12:39:41.307  1019  1385 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-20 12:39:41.307  3274  3274 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-20 12:39:41.307  3350  3350 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:41.307  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:41.307  1019  1385 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:41.307  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
03-20 12:39:41.307  3350  3350 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:41.357  2980  2980 D BluetoothA2dp: Proxy object connected
,03-20 12:39:41.377  3312  3312 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-20 12:39:41.377  3312  3312 I testFeature: Feature.Feature(context)
,03-20 12:39:41.377  3312  3312 I testFeature: Feature.readInternalDefaultXml()
03-20 12:39:41.377  3312  3312 I testFeature: ResetFeatureValue
,03-20 12:39:41.377  3312  3312 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
,03-20 12:39:41.377  3312  3312 I CameraApp: CameraApp.getAppFeature()...
,03-20 12:39:41.387  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:41.387  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.387  2187  2187 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,03-20 12:39:41.387  2187  2187 I dhcpcd  : wlan0: no IPv6 Routers available
03-20 12:39:41.387  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.387  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:41.397  3369  3369 E Zygote  : MountEmulatedStorage()
,03-20 12:39:41.397  3369  3369 E Zygote  : v2
03-20 12:39:41.397  3369  3369 I libpersona: KNOX_SDCARD checking this for 10100
03-20 12:39:41.397  3369  3369 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:41.397  3369  3369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-20 12:39:41.397  3369  3369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:41.407  3369  3369 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:41.407  1019  1496 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3369 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-20 12:39:41.407  1019  1496 I ActivityManager: Killing 2416:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-20 12:39:41.417  3369  3369 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:41.417  3369  3369 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:41.447  3369  3369 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-20 12:39:41.457  3369  3369 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-20 12:39:41.457  1019  1482 I ActivityManager: Killing 1751:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-20 12:39:41.457  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,03-20 12:39:41.457  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:41.467  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-20 12:39:41.467  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-20 12:39:41.467  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:41.467  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.467  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.467  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:41.477  1728  3392 I GoogleHttpClient: GMS http client unavailable, use old client
,03-20 12:39:41.487  3395  3395 E Zygote  : MountEmulatedStorage()
03-20 12:39:41.487  3395  3395 E Zygote  : v2
03-20 12:39:41.487  3395  3395 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:41.487  3395  3395 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:41.497  3395  3395 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:41.497  3395  3395 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:41.497  3395  3395 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:41.497  1019  1329 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3395 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-20 12:39:41.507  3045  3045 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3045
,03-20 12:39:41.527  3299  3299 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-20 12:39:41.537  1772  1772 I SamsungIME: getDebugLevel  : 0x4f4c
,03-20 12:39:41.537  1019  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_2416/cgroup.procs: No such file or directory
03-20 12:39:41.537  1019  1043 W libprocessgroup: failed to open /acct/uid_10015/pid_1751/cgroup.procs: No such file or directory
,03-20 12:39:41.547  3395  3395 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:41.547  3395  3395 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:41.557  1772  1772 I SamsungIME: KeybaordView init() : load resources
,03-20 12:39:41.557  3197  3197 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-20 12:39:41.577  3299  3299 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-20 12:39:41.587  3299  3299 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-20 12:39:41.587  3299  3299 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-20 12:39:41.637  1772  1772 I SamsungIME: getCurrentKeyboard
03-20 12:39:41.637  1772  1772 I SamsungIME: getTextKeyboard
,03-20 12:39:41.687  3274  3286 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-20 12:39:41.687  3274  3326 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-20 12:39:41.687  3274  3286 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-20 12:39:41.687  3274  3326 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-20 12:39:41.697  3274  3286 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-20 12:39:41.697  1772  1772 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-20 12:39:41.697  3274  3283 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-20 12:39:41.707  3274  3326 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-20 12:39:41.717  3274  3283 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-20 12:39:41.717  3274  3283 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-20 12:39:41.717  1019  1131 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:41.727  1019  1131 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:41.727  1019  1131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:41.727  3274  3326 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-20 12:39:41.727  1019  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-20 12:39:41.727  3274  3326 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-20 12:39:41.727  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.727  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.727  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.727  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:41.737  3299  3299 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220,
03-20 12:39:41.737  3422  3422 E Zygote  : MountEmulatedStorage(),
03-20 12:39:41.737  3422  3422 E Zygote  : v2
03-20 12:39:41.737  3422  3422 I libpersona: KNOX_SDCARD checking this for 10012,
03-20 12:39:41.737  3422  3422 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:41.747  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State,
03-20 12:39:41.747  3422  3422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:41.747  3299  3299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 ,
,03-20 12:39:41.747  3422  3422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:41.747  3422  3422 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-20 12:39:41.747  3274  3326 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-20 12:39:41.757  1019  1131 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3422 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-20 12:39:41.757  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-20 12:39:41.757  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:41.757  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:41.757  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-20 12:39:41.767  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-20 12:39:41.767  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-20 12:39:41.767  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-20 12:39:41.767  3045  3045 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-20 12:39:41.777  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.777  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.777  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.777  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:41.777  3274  3326 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0,
,03-20 12:39:41.787  3274  3326 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-20 12:39:41.797  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
03-20 12:39:41.797  3439  3439 E Zygote  : MountEmulatedStorage()
,03-20 12:39:41.797  3439  3439 E Zygote  : v2
03-20 12:39:41.797  3299  3299 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-20 12:39:41.797  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-20 12:39:41.797  1019  1559 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3439 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-20 12:39:41.797  3299  3299 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-20 12:39:41.797  1019  1559 I ActivityManager: Killing 2475:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-20 12:39:41.797  3439  3439 I libpersona: KNOX_SDCARD checking this for 1000
,03-20 12:39:41.797  3439  3439 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:41.797  3422  3422 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:41.807  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-20 12:39:41.807  3422  3422 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:41.807  3299  3299 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On,
,03-20 12:39:41.807  3274  3326 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] ,
,03-20 12:39:41.807  3274  3326 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] ,
,03-20 12:39:41.807  3439  3439 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-20 12:39:41.817  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0,
03-20 12:39:41.817  3299  3299 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-20 12:39:41.817  3299  3299 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-20 12:39:41.817  1182  1182 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-20 12:39:41.817  1182  1182 D OverheatReceiver: into the SAFE_MODE_ACTION,
03-20 12:39:41.817  1182  1182 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
03-20 12:39:41.817  3439  3439 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:41.817  1182  1182 D OverheatReceiver: isSafeMode = false,
,03-20 12:39:41.817  3439  3439 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:41.817  3274  3326 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/25/13:36:09
,03-20 12:39:41.827  3274  3326 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/20/12:39:41
,03-20 12:39:41.827  3274  3327 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-20 12:39:41.827  3274  3326 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-20 12:39:41.827  3299  3416 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-20 12:39:41.827  3274  3327 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-20 12:39:41.827  3299  3299 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-20 12:39:41.827  1468  1468 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
03-20 12:39:41.837  1019  1385 D SettingsProvider: name = internet_call_settings_visibility
03-20 12:39:41.837  1019  1385 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-20 12:39:41.837  1019  1385 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-20 12:39:41.837  1019  1385 D SettingsProvider: selectionArgs: false
03-20 12:39:41.837  1019  1385 D SettingsProvider: selectionArgs: 1001
03-20 12:39:41.837  1019  1385 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-20 12:39:41.837  1019  1385 D SettingsProvider: ret = -1
,03-20 12:39:41.837  1468  1468 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-20 12:39:41.837  3274  3326 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-20 12:39:41.847  3299  3416 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-20 12:39:41.847  1443  1443 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-20 12:39:41.847  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-20 12:39:41.857  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:41.857  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:41.857  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-20 12:39:41.857  3439  3439 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:41.857  3299  3416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-20 12:39:41.857  3439  3439 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:41.857  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-20 12:39:41.867  3274  3327 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-20 12:39:41.867  3422  3422 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-20 12:39:41.867  3422  3422 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-20 12:39:41.867  3299  3299 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-20 12:39:41.867  3274  3327 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-20 12:39:41.867  1443  1443 I Telecom : InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,03-20 12:39:41.877  3274  3327 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-20 12:39:41.877  3299  3299 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
03-20 12:39:41.877  3274  3327 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-20 12:39:41.877  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-20 12:39:41.877  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:41.877  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:41.877  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-20 12:39:41.877  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-20 12:39:41.877  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-20 12:39:41.877  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:41.877  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-20 12:39:41.877  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
,03-20 12:39:41.887  3299  3299 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-20 12:39:41.897  3274  3327 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-20 12:39:41.897  3274  3327 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-20 12:39:41.897  3274  3327 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
03-20 12:39:41.907  3274  3327 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-20 12:39:41.927  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:41.927  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-20 12:39:41.927  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:41.927  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-20 12:39:41.927  3197  3197 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,03-20 12:39:41.927  3197  3197 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-20 12:39:41.937  3274  3326 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-20 12:39:41.937  3454  3454 E Zygote  : MountEmulatedStorage(),
03-20 12:39:41.937  3454  3454 E Zygote  : v2
03-20 12:39:41.947  3454  3454 I libpersona: KNOX_SDCARD checking this for 1000,
03-20 12:39:41.947  3454  3454 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:41.947  3454  3454 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:41.947  3454  3454 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:41.947  3454  3454 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:41.947  3422  3422 I MultiDex: VM with version 2.1.0 has multidex support
03-20 12:39:41.947  3422  3422 I MultiDex: install
03-20 12:39:41.947  3422  3422 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-20 12:39:41.957  1019  1385 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3454 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-20 12:39:41.957  1019  1385 I ActivityManager: Killing 2526:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-20 12:39:41.957  1019  1385 I ActivityManager: Killing 2507:com.sec.modem.settings/1000 (adj 15): empty #32
,03-20 12:39:41.957  1019  1385 I ActivityManager: Killing 2496:com.sec.android.omc/1000 (adj 15): empty #33
03-20 12:39:41.957   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
03-20 12:39:41.957  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-20 12:39:41.957  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:41.957  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:41.957  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-20 12:39:41.967  1443  1443 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-20 12:39:41.977  1443  1443 I Telecom : InCallController: Unbinding from InCallService unbind
,03-20 12:39:41.977   306   306 I art     : Explicit concurrent mark sweep GC freed 8793(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 664us total 23.854ms
,03-20 12:39:41.997   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 703us total 18.324ms
,03-20 12:39:42.017  1019  1032 I ActivityManager: Killing 2537:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-20 12:39:42.027   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 24.100ms
03-20 12:39:42.027  3045  3239 I chromium: [INFO:SkError.cpp(84)] Skia Error: Unknown error: ---- failed to create texture for cache [720 818]
03-20 12:39:42.027  3045  3239 I chromium: 
03-20 12:39:42.027  3045  3239 I chromium: 
03-20 12:39:42.027  3045  3239 I chromium: [INFO:SkError.cpp(84)] Skia Error: Unknown error: Couldn't convert bitmap to texture.
03-20 12:39:42.027  3045  3239 I chromium: 
,03-20 12:39:42.027  3299  3416 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-20 12:39:42.037  1019  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-20 12:39:42.037  3454  3454 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:42.037  3454  3454 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:42.037  1019  1488 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:42.037  1019  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.037  1019  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-20 12:39:42.067  3299  3299 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-20 12:39:42.077  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2475/cgroup.procs: No such file or directory
,03-20 12:39:42.077  2735  2800 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-20 12:39:42.077  3422  3422 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-20 12:39:42.117  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:42.117  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:42.117  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:42.117  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.117  3299  3299 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-20 12:39:42.127   284   284 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-20 12:39:42.127   284   284 D audio_hw_extn: audio_extn_get_parameters: returns 
03-20 12:39:42.127   284   284 V msm8974_platform: platform_get_parameters: exit: returns - 
,03-20 12:39:42.127   284   284 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-20 12:39:42.127   284   284 I str_params: key: 'call_forwarding' value: ''
,03-20 12:39:42.127  1943  1943 V InCall  : ProximitySensor -  - screenonImmediately: false
,03-20 12:39:42.127  1943  1943 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-20 12:39:42.137  1019  1131 E Tethering: No numeric data
,03-20 12:39:42.137  1943  1943 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-20 12:39:42.137  1943  1943 D ScoverManager: serviceVersion : 16908288
,03-20 12:39:42.137  1019  1266 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-20 12:39:42.147  1943  1943 D InCall  : InCallUtils - isCoverClosed false
,03-20 12:39:42.147  1443  1443 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-20 12:39:42.147  1019  1446 E Tethering: No numeric data
,03-20 12:39:42.147  1019  1032 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-20 12:39:42.147  1943  1943 D InCall  : InCallUtils - isCoverClosed false
,03-20 12:39:42.147  1943  1943 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-20 12:39:42.147  1019  1496 E Tethering: No numeric data
,03-20 12:39:42.157  1019  3069 E Tethering: No numeric data
,03-20 12:39:42.157  1943  1943 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-20 12:39:42.167  1943  1943 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-20 12:39:42.167  1943  1943 I InCall  : CallSContextMotion - stopPutDownListening
,03-20 12:39:42.167  1943  1943 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-20 12:39:42.167  1019  1559 E Tethering: No numeric data
,03-20 12:39:42.177  1019  1131 E Tethering: No numeric data
,03-20 12:39:42.177  1019  1488 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-20 12:39:42.177  1943  1943 D InCall  : InCallUtils - isCoverClosed false
,03-20 12:39:42.177  3422  3422 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-20 12:39:42.177  3422  3422 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@357ec9fe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-20 12:39:42.177  3422  3422 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-20 12:39:42.187  1182  1182 D PhoneStatusBarView: setCallBackground:0
,03-20 12:39:42.207  3479  3479 E Zygote  : MountEmulatedStorage(),
03-20 12:39:42.207  3479  3479 E Zygote  : v2
03-20 12:39:42.207  3479  3479 I libpersona: KNOX_SDCARD checking this for 10003
03-20 12:39:42.207  3479  3479 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:42.207  3479  3479 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:42.217  3479  3479 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:42.217  3479  3479 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-20 12:39:42.217  1019  1019 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3479 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-20 12:39:42.237  3274  3327 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-20 12:39:42.237  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-20 12:39:42.247  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-20 12:39:42.247  1989  1989 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-20 12:39:42.257  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 12:39:42.257  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:42.257  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:42.257  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 12:39:42.257  3454  3454 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-20 12:39:42.257  1943  1943 D VideoCallManager: Instantiating VideoCallManager
,03-20 12:39:42.267  1943  1943 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-20 12:39:42.277  1943  1943 I GFX construct_block_size_descriptor_2d second part: took 2.416874ms for 0*0 texture 0
,03-20 12:39:42.277  1943  1943 I GFX generate_partition_tables: took 5.061718ms for 0*0 texture 0
,03-20 12:39:42.287  1943  1943 I GFX raster: took 11.441145ms for 176*144 texture 0
03-20 12:39:42.287  1943  1943 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76cf238 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb76ceb08 counterpartCT=4 counterpartW=176 counterparth=144
,03-20 12:39:42.297  3479  3479 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:42.297  3479  3479 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:42.297  1943  1943 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-20 12:39:42.307  1943  1943 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-20 12:39:42.307  1943  1943 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-20 12:39:42.307  1943  1943 I Adreno-EGL: Build Date: 04/06/15 Mon
03-20 12:39:42.307  1943  1943 I Adreno-EGL: Local Branch: 
03-20 12:39:42.307  1943  1943 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-20 12:39:42.307  1943  1943 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-20 12:39:42.307  1943  1943 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-20 12:39:42.327  3045  3266 D jxcore_app_log: JniHelper::setJavaVM(0xb732a450), pthread_self() = -1215985152
,03-20 12:39:42.337  1943  1943 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-20 12:39:42.347  3274  3327 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-20 12:39:42.347  3045  3266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-20 12:39:42.347  3045  3266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-20 12:39:42.347  3045  3266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-20 12:39:42.347  3045  3266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-20 12:39:42.347  3045  3266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-20 12:39:42.347  1943  1943 I glCompressedTexImage2D: took 0.341667ms for 320*61440 texture 37809
03-20 12:39:42.347  3045  3266 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17f82813 added. We now have 1 listener(s)
,03-20 12:39:42.357  3045  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:51:18:22
,03-20 12:39:42.357  3045  3266 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:51:18:22"
,03-20 12:39:42.367  3045  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-20 12:39:42.367  3045  3266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-20 12:39:42.367  1943  1943 I draw setup: took 11.571302ms for 320*240 texture 37809
03-20 12:39:42.367  1943  1943 E GFX GPU raster: drawn
,03-20 12:39:42.377  1943  1943 I GFX GPU raster ASTC: took 40.284684ms for 320*240 texture 12
03-20 12:39:42.377  1943  1943 I GFX raster: took 40.371091ms for 320*240 texture 0
03-20 12:39:42.377  1943  1943 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76cf1b8 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb76ced20 counterpartCT=4 counterpartW=320 counterparth=240
,03-20 12:39:42.387  1943  1943 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-20 12:39:42.387  1943  1943 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:51:18:22
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-20 12:39:42.397  3045  3266 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@282d714e added. We now have 1 listener(s)
,03-20 12:39:42.397  3045  3266 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-20 12:39:42.397  1943  1943 I glCompressedTexImage2D: took 0.355313ms for 480*122880 texture 37813
03-20 12:39:42.397  1943  1943 I draw setup: took 0.858229ms for 480*640 texture 37813
03-20 12:39:42.397  1943  1943 E GFX GPU raster: drawn
,03-20 12:39:42.397  1943  1943 I GFX GPU raster ASTC: took 7.254584ms for 480*640 texture 12
03-20 12:39:42.397  1943  1943 I GFX raster: took 7.333854ms for 480*640 texture 0
03-20 12:39:42.397  1943  1943 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76ced20 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb78fc3d0 counterpartCT=4 counterpartW=480 counterparth=640
,03-20 12:39:42.417  3045  3266 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-20 12:39:42.427  3045  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-20 12:39:42.427  3045  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-20 12:39:42.427  3045  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-20 12:39:42.427  3045  3266 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-20 12:39:42.447  1943  1943 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-20 12:39:42.447  1943  1943 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-20 12:39:42.447  1943  1943 I glCompressedTexImage2D: took 0.405365ms for 440*116864 texture 37809
03-20 12:39:42.447  1943  1943 I draw setup: took 0.901042ms for 440*330 texture 37809
03-20 12:39:42.447  1943  1943 E GFX GPU raster: drawn
,03-20 12:39:42.467  3045  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-20 12:39:42.467  1943  1943 I GFX GPU raster ASTC: took 4.994064ms for 440*330 texture 12
03-20 12:39:42.467  1943  1943 I GFX raster: took 5.077345ms for 440*330 texture 0
03-20 12:39:42.467  1943  1943 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7900628 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb79009e8 counterpartCT=4 counterpartW=440 counterparth=330
,03-20 12:39:42.477  3045  3266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:51:18:22
,03-20 12:39:42.487  3299  3416 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-20 12:39:42.487  3045  3266 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-20 12:39:42.487  3045  3266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-20 12:39:42.487  3045  3266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-20 12:39:42.487  3045  3266 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-20 12:39:42.487  3045  3266 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-20 12:39:42.487  3045  3266 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-20 12:39:42.487  3045  3266 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-20 12:39:42.487  3045  3266 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-20 12:39:42.487  3045  3266 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-20 12:39:42.487  3045  3266 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-20 12:39:42.487  3045  3266 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-20 12:39:42.497  1943  1943 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-20 12:39:42.497  1943  1943 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-20 12:39:42.497  1943  1943 I glCompressedTexImage2D: took 0.548281ms for 480*163840 texture 37811
03-20 12:39:42.497  1943  1943 I draw setup: took 0.967292ms for 480*640 texture 37811
03-20 12:39:42.497  1943  1943 E GFX GPU raster: drawn
,03-20 12:39:42.507  3439  3439 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,03-20 12:39:42.507  1943  1943 I GFX GPU raster ASTC: took 7.118333ms for 480*640 texture 12
03-20 12:39:42.507  1943  1943 I GFX raster: took 7.274375ms for 480*640 texture 0
03-20 12:39:42.507  1943  1943 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb793fff8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb78fc188 counterpartCT=4 counterpartW=480 counterparth=640
,03-20 12:39:42.537  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2496/cgroup.procs: No such file or directory
,03-20 12:39:42.537  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2507/cgroup.procs: No such file or directory,
03-20 12:39:42.537  1019  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_2537/cgroup.procs: No such file or directory
,03-20 12:39:42.537  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2526/cgroup.procs: No such file or directory
,03-20 12:39:42.547  3045  3045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-20 12:39:42.547  3045  3045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-20 12:39:42.547  3299  3416 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-20 12:39:42.557  1943  1943 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-20 12:39:42.557  1943  1943 I GFX construct_block_size_descriptor_2d second part: took 2.493855ms for 0*0 texture 0
,03-20 12:39:42.557  3299  3416 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-20 12:39:42.557  1019  1098 V AlarmManager: waitForAlarm result :4
,03-20 12:39:42.557  1019  1098 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,03-20 12:39:42.567  3299  3416 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-20 12:39:42.567  1943  1943 I GFX generate_partition_tables: took 7.438125ms for 0*0 texture 0
,03-20 12:39:42.567  1943  1943 I GFX raster: took 11.970156ms for 176*144 texture 0
03-20 12:39:42.567  1943  1943 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79005a8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb78f9be8 counterpartCT=4 counterpartW=176 counterparth=144
,03-20 12:39:42.577  1943  1943 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-20 12:39:42.577  1943  1943 I GFX construct_block_size_descriptor_2d second part: took 2.043125ms for 0*0 texture 0
,03-20 12:39:42.587  3045  3045 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-20 12:39:42.587  1943  1943 I GFX generate_partition_tables: took 6.135468ms for 0*0 texture 0
,03-20 12:39:42.587  1943  1943 I GFX raster: took 10.238125ms for 176*144 texture 0
03-20 12:39:42.587  1943  1943 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb78f9c50 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb78f9dd8 counterpartCT=4 counterpartW=176 counterparth=144
,03-20 12:39:42.597  1943  1943 D ScoverManager: registerListener
,03-20 12:39:42.597  1019  3068 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-20 12:39:42.597  1330  3298 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-20 12:39:42.597  1019  1446 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-20 12:39:42.597  1019  1446 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@af9803, pid : 1943, uid : 1001, type : 1
,03-20 12:39:42.597  3454  3454 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-20 12:39:42.597  3454  3454 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-20 12:39:42.597  3454  3454 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-20 12:39:42.607  3197  3295 D Volley  : [391] DiskBasedCache.clear: Cache cleared.
,03-20 12:39:42.607  1330  3298 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-20 12:39:42.607  3439  3439 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-20 12:39:42.627  3197  3384 D Volley  : [398] DiskBasedCache.clear: Cache cleared.
,03-20 12:39:42.627  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.627  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.627  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:42.627  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.627  3439  3439 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-20 12:39:42.627  3439  3439 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
03-20 12:39:42.627  3439  3439 D ShortcutReceiver:  shortcut migration not required 
,03-20 12:39:42.637  1019  1385 E Tethering: No numeric data
,03-20 12:39:42.637  1019  1266 E Tethering: No numeric data
03-20 12:39:42.637  3509  3509 E Zygote  : MountEmulatedStorage(),
03-20 12:39:42.637  3509  3509 E Zygote  : v2
03-20 12:39:42.637  3509  3509 I libpersona: KNOX_SDCARD checking this for 1000,
03-20 12:39:42.637  3509  3509 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:42.637  3509  3509 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:42.637  1019  1488 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3509 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-20 12:39:42.647  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-20 12:39:42.647  3197  3197 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-20 12:39:42.647  3197  3197 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-20 12:39:42.647  3509  3509 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:42.647  3509  3509 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:42.657  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:42.657  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.657  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:42.657  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.657  1019  3068 E Tethering: No numeric data
03-20 12:39:42.657  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:42.657  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:42.657  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.667  1019  1266 E Tethering: No numeric data
,03-20 12:39:42.677  3524  3524 E Zygote  : MountEmulatedStorage()
03-20 12:39:42.687  3524  3524 E Zygote  : v2
03-20 12:39:42.687  3524  3524 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:42.687  3524  3524 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:42.687  3524  3524 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:42.687  1019  1329 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3524 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-20 12:39:42.687  3524  3524 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:42.687  3524  3524 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:42.687  1019  1329 I ActivityManager: Killing 2558:com.wsomacp/u0a25 (adj 15): empty #31
,03-20 12:39:42.687  1019  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:42.697  3274  3326 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-20 12:39:42.697  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:42.697  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.697  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-20 12:39:42.707  1943  1943 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-20 12:39:42.707  1019  3069 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-20 12:39:42.707  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:42.707  1019  3069 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.707  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-20 12:39:42.707  3509  3509 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:42.707  3509  3509 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:42.717  1728  1728 V GLSUser : [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,03-20 12:39:42.717  1019  3068 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,03-20 12:39:42.717  1019  3068 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:42.717  1019  3068 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.717  1019  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:42.727  3274  3326 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-20 12:39:42.727  3197  3197 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-20 12:39:42.727  3524  3524 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:42.737  3524  3524 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:42.737  1019  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:42.747  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:42.747  1019  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.747  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:42.747  1019  3069 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:42.747  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:42.747  1019  3069 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.747  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:42.757  1989  1989 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,03-20 12:39:42.757  1019  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-20 12:39:42.757  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:42.757  1019  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.757  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:42.767  3479  3479 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-20 12:39:42.797  1019  1559 V VibratorService: hasVibrator - useVibetonz: true
,03-20 12:39:42.807  1330  3298 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-20 12:39:42.807  3524  3524 E KnoxSetupWizardClient: isShipMode : 1
03-20 12:39:42.807  3524  3524 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-20 12:39:42.807  1019  1482 V VibratorService: hasVibrator - useVibetonz: true
,03-20 12:39:42.817  1019  1266 V VibratorService: hasVibrator - useVibetonz: true
,03-20 12:39:42.827  1728  1728 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
03-20 12:39:42.827  3197  3197 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-20 12:39:42.837  1019  1131 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,03-20 12:39:42.847  1019  1131 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:42.847  1019  1131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.847  1019  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
03-20 12:39:42.847  1330  3298 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-20 12:39:42.847  3479  3479 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-20 12:39:42.847  3479  3479 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-20 12:39:42.847  3479  3479 D UserAnalysis: Create SecureDbHelper
,03-20 12:39:42.867  1019  1043 W libprocessgroup: failed to open /acct/uid_10025/pid_2558/cgroup.procs: No such file or directory
,03-20 12:39:42.867  2461  2461 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-20 12:39:42.867  2461  2461 I StatusChecker: onReceive : net.mt.init : DONE
,03-20 12:39:42.887  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.887  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:42.887  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.887  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.887  3274  3327 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-20 12:39:42.907  3551  3551 E Zygote  : MountEmulatedStorage()
03-20 12:39:42.907  3551  3551 I libpersona: KNOX_SDCARD checking this for 10116
03-20 12:39:42.907  3551  3551 E Zygote  : v2
,03-20 12:39:42.907  3551  3551 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:42.907  3551  3551 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:42.907  3551  3551 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:42.907  3551  3551 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:42.917  1019  1031 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3551 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
03-20 12:39:42.917  1019  2820 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
03-20 12:39:42.917  1019  1031 I ActivityManager: Killing 2598:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
03-20 12:39:42.917  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
03-20 12:39:42.917  3197  3197 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-20 12:39:42.917  1728  1728 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 12:39:42.927  1019  3069 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-20 12:39:42.927  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:42.927  1019  3069 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.927  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:42.947  3479  3479 D IntelligenceServiceApplication: onCreate()
,03-20 12:39:42.947  3551  3551 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:42.947  3551  3551 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:42.967  3479  3479 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-20 12:39:42.967  3274  3327 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-20 12:39:42.967  1019  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:42.977  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:42.977  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:42.977  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:42.977  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.977  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.977  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.977  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:42.987  3524  3545 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
03-20 12:39:42.987  3524  3545 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-20 12:39:42.987  3524  3545 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-20 12:39:42.987  3524  3545 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-20 12:39:42.987  3524  3545 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-20 12:39:42.987  3524  3545 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-20 12:39:42.987  3524  3545 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-20 12:39:42.987  3509  3509 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-20 12:39:42.987  3509  3509 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-20 12:39:42.997  3274  3327 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
03-20 12:39:42.997  3568  3568 E Zygote  : MountEmulatedStorage()
03-20 12:39:42.997  3568  3568 E Zygote  : v2
03-20 12:39:42.997  3568  3568 I libpersona: KNOX_SDCARD checking this for 10060
03-20 12:39:42.997  3568  3568 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:42.997  3568  3568 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:42.997  3568  3568 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:42.997  1019  1032 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3568 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-20 12:39:42.997  3568  3568 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:42.997  1019  1032 I ActivityManager: Killing 2647:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-20 12:39:43.007  3509  3509 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-20 12:39:43.037  1019  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:43.037  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:43.037  1019  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:43.037  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:43.047  3479  3479 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-20 12:39:43.047  3568  3568 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:43.047  3568  3568 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:43.047  1728  1739 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-20 12:39:43.047  1728  1739 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-20 12:39:43.047  1728  1739 I GLSUser : [GLSUser] Extracting token using key: Auth
03-20 12:39:43.047  1728  1739 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-20 12:39:43.047  3509  3523 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-20 12:39:43.057  1728  1739 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 12:39:43.057  1019  3068 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-20 12:39:43.067  3551  3551 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-20 12:39:43.077  3479  3479 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-20 12:39:43.077  1330  3298 D ScoverManager: serviceVersion : 16908288
,03-20 12:39:43.087  3551  3551 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-20 12:39:43.087  3454  3454 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-20 12:39:43.097  3454  3454 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-20 12:39:43.097  3454  3454 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-20 12:39:43.097  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2598/cgroup.procs: No such file or directory
03-20 12:39:43.097  1019  1043 W libprocessgroup: failed to open /acct/uid_10068/pid_2647/cgroup.procs: No such file or directory
,03-20 12:39:43.097  3479  3479 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-20 12:39:43.097  3479  3479 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-20 12:39:43.107  1019  1446 I ActivityManager: Killing 2677:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-20 12:39:43.157  1019  2882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 12:39:43.217  1019  1496 I art     : Explicit concurrent mark sweep GC freed 18731(986KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 2.745ms total 156.442ms
03-20 12:39:43.217  1019  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-20 12:39:43.217  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:43.217  1019  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:43.217  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:43.217  1019  1043 W libprocessgroup: failed to open /acct/uid_10069/pid_2677/cgroup.procs: No such file or directory
,03-20 12:39:43.227  1019  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.227  1019  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.227  1019  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.227  1019  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.227  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-20 12:39:43.227  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-20 12:39:43.227  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:43.227  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:43.227  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:43.227  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 12:39:43.237  3589  3589 E Zygote  : MountEmulatedStorage()
,03-20 12:39:43.237  3589  3589 E Zygote  : v2
03-20 12:39:43.247  3589  3589 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:43.247  3589  3589 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:43.247  1019  1482 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3589 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-20 12:39:43.247  3589  3589 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:43.247  1019  1482 I ActivityManager: Killing 2662:com.android.calendar/u0a135 (adj 15): empty #31
,03-20 12:39:43.247  1019  3068 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:43.247  3589  3589 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:43.247  1019  3068 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:43.247  3589  3589 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:43.247  1019  3068 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:43.247  1019  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-20 12:39:43.257  3551  3551 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-20 12:39:43.267  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.267  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.267  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.267  1019  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.267  2694  3186 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3186)  
,03-20 12:39:43.277  3605  3605 E Zygote  : MountEmulatedStorage()
03-20 12:39:43.277  3605  3605 E Zygote  : v2
03-20 12:39:43.277  3605  3605 I libpersona: KNOX_SDCARD checking this for 10125
03-20 12:39:43.277  3605  3605 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:43.277  3605  3605 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:43.277  3605  3605 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:43.287  1019  1559 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3605 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-20 12:39:43.287  3197  3197 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
03-20 12:39:43.287  3605  3605 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:43.297  1019  3069 I ActivityManager: Killing 2744:com.android.keychain/1000 (adj 15): empty #31
,03-20 12:39:43.297  3589  3589 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:43.297  3589  3589 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:43.297  3605  3605 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:43.297  3605  3605 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:43.327  1330  3298 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-20 12:39:43.337  3605  3605 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-20 12:39:43.347  3605  3605 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-20 12:39:43.347  3605  3605 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-20 12:39:43.347  3197  3197 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-20 12:39:43.357  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-20 12:39:43.377  1330  3298 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-20 12:39:43.397  1019  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_2662/cgroup.procs: No such file or directory
,03-20 12:39:43.407  3045  3504 W jxcore-log: Initializing JXcore engine
03-20 12:39:43.407  3045  3504 W jxcore-log: JXcore engine is ready
,03-20 12:39:43.417  3589  3589 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-20 12:39:43.417  3589  3589 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-20 12:39:43.457  1728  1728 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 12:39:43.477  1900  1900 E audit   : type=1400 msg=audit(1458473983.477:205): avc:  denied  { ioctl } for  pid=3504 comm="Thread-380" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
03-20 12:39:43.477  1900  1900 E audit   :  SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:43.477  1900  1900 E audit   : type=1300 msg=audit(1458473983.477:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9c4bb8f8 items=0 ppid=306 ppcomm=main pid=3504 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-380" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-20 12:39:43.477  1900  1900 E audit   : type=1320 msg=audit(1458473983.477:205): ,
,03-20 12:39:43.477  3605  3605 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
03-20 12:39:43.477  3509  3523 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-20 12:39:43.487  3605  3605 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-20 12:39:43.487  1019  1385 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:43.487  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:43.497  1019  1385 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:43.497  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:43.497  3045  3504 W jxcore-log: Starting JXcore engine
,03-20 12:39:43.507  3589  3589 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-20 12:39:43.507  1019  1559 D SettingsProvider: name = scon_is_running
03-20 12:39:43.507  1019  1559 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-20 12:39:43.507  1019  1559 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-20 12:39:43.507  1019  1559 D SettingsProvider: selectionArgs: false
03-20 12:39:43.507  1019  1559 D SettingsProvider: selectionArgs: 10125
03-20 12:39:43.507  1019  1559 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-20 12:39:43.507  1019  1559 D SettingsProvider: ret = -1
,03-20 12:39:43.507  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2744/cgroup.procs: No such file or directory
,03-20 12:39:43.517  1019  1559 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-20 12:39:43.517  3605  3605 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-20 12:39:43.527  3605  3605 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-20 12:39:43.527  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:43.527  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.537  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.537  3589  3589 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-20 12:39:43.537  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.537  1019  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.547  1728  1739 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-20 12:39:43.547  1728  1739 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-20 12:39:43.547  1728  1739 I GLSUser : [GLSUser] Extracting token using key: Auth
03-20 12:39:43.547  1728  1739 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-20 12:39:43.557  3623  3623 E Zygote  : MountEmulatedStorage()
,03-20 12:39:43.557  3623  3623 I libpersona: KNOX_SDCARD checking this for 10131
03-20 12:39:43.557  3623  3623 E Zygote  : v2
03-20 12:39:43.557  3623  3623 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:43.557  3623  3623 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:43.567  1019  1131 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3623 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-20 12:39:43.567  3623  3623 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:43.567  3623  3623 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:43.577  1728  1739 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 12:39:43.577  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-20 12:39:43.577  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:43.577  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-20 12:39:43.577  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:43.607  3623  3623 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:43.607  3623  3623 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:43.607  3299  3416 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-20 12:39:43.627  3568  3568 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-20 12:39:43.637  1019  1329 I ActivityManager: Killing 2369:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-20 12:39:43.647  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.647  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.647  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.647  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.647  3045  3504 W jxcore-log: Platform android
03-20 12:39:43.647  3045  3504 W jxcore-log: 
,03-20 12:39:43.647  3045  3504 W jxcore-log: Process ARCH arm
03-20 12:39:43.647  3045  3504 W jxcore-log: 
,03-20 12:39:43.657  3638  3638 E Zygote  : MountEmulatedStorage()
03-20 12:39:43.657  3638  3638 E Zygote  : v2
03-20 12:39:43.657  3638  3638 I libpersona: KNOX_SDCARD checking this for 10062
03-20 12:39:43.657  3638  3638 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:43.657  3623  3623 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-20 12:39:43.657  3623  3623 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-20 12:39:43.657  3623  3623 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-20 12:39:43.657  3623  3623 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
03-20 12:39:43.667  3638  3638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:43.667  3638  3638 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-20 12:39:43.667  3638  3638 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:43.667  1019  1446 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3638 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-20 12:39:43.697  1019  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-20 12:39:43.707  3638  3638 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:43.707  3638  3638 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:43.707  1728  1728 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 12:39:43.727  1019  1385 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:43.727  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:43.727  1019  1385 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:43.727  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:43.767  1728  1839 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-20 12:39:43.767  1728  1839 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-20 12:39:43.767  1728  1839 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-20 12:39:43.767  1728  1839 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-20 12:39:43.777  1019  1043 W libprocessgroup: failed to open /acct/uid_10044/pid_2369/cgroup.procs: No such file or directory
,03-20 12:39:43.777  3589  3589 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-20 12:39:43.777  1728  1839 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-20 12:39:43.787  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-20 12:39:43.787  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:43.787  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:43.787  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:43.797  3589  3589 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-20 12:39:43.797  3589  3589 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-20 12:39:43.807  3589  3589 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-20 12:39:43.807  3589  3589 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-20 12:39:43.807  3589  3589 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-20 12:39:43.807  3589  3589 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-20 12:39:43.817  3197  3197 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-20 12:39:43.837  3623  3623 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-20 12:39:43.857  1019  1559 I ActivityManager: Killing 2892:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-20 12:39:43.867  3623  3623 D ManifestProvider: onCreate()
,03-20 12:39:43.877  3328  3328 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-20 12:39:43.897  3328  3328 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-20 12:39:43.897  1019  3069 V VibratorService: hasVibrator - useVibetonz: true
,03-20 12:39:43.897  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.897  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.897  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.897  1019  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.907  3623  3623 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-20 12:39:43.907  3045  3504 I jxcore-log: JXcore Cordova bridge is ready!,
03-20 12:39:43.907  3045  3504 I jxcore-log: 
03-20 12:39:43.907  3045  3504 W jxcore-log: JXcore engine is started
03-20 12:39:43.907  3638  3638 I ExternalOEMControlProvider: onCreate
,03-20 12:39:43.917  3663  3663 E Zygote  : MountEmulatedStorage()
03-20 12:39:43.917  3663  3663 E Zygote  : v2
03-20 12:39:43.917  3663  3663 I libpersona: KNOX_SDCARD checking this for 10014
03-20 12:39:43.917  3663  3663 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:43.917  3663  3663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:43.917  3663  3663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:43.917  1019  1446 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3663 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-20 12:39:43.917  3663  3663 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-20 12:39:43.917  1019  1446 I ActivityManager: Killing 1570:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-20 12:39:43.927  3045  3266 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-20 12:39:43.927  3045  3045 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-20 12:39:43.937  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.937  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.937  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:43.937  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:43.937   289   289 E SMD     : DCD OFF
,03-20 12:39:43.947  3045  3504 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-20 12:39:43.947  3045  3504 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-20 12:39:43.957  3663  3663 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:43.957  3663  3663 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:43.957  3623  3623 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@3b5fe931
,03-20 12:39:43.967  3623  3623 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-20 12:39:43.967  3623  3623 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-20 12:39:43.967  3045  3045 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-20 12:39:43.967  1989  3584 D FileApkUtils: Spent 87ms computing apk sha1.
,03-20 12:39:43.967  1989  3584 D FileApkUtils: Module already staged or being staged:chimera-modules/MapsModule.apk
,03-20 12:39:43.967  1989  3584 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,03-20 12:39:43.977  3045  3045 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-20 12:39:43.977  3681  3681 E Zygote  : MountEmulatedStorage()
03-20 12:39:43.977  3681  3681 E Zygote  : v2
03-20 12:39:43.977  3681  3681 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:43.977  3681  3681 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:43.977  3681  3681 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:43.977  1019  3068 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3681 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-20 12:39:43.977  1019  3068 I ActivityManager: Killing 2281:flipboard.app/u0a98 (adj 15): empty #31
03-20 12:39:43.987  3681  3681 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:43.987  1989  3584 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
03-20 12:39:43.987  1989  3584 D DexOptUtils: Lollipop platform, using <isa> directory.
03-20 12:39:43.987  3681  3681 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:43.987  1989  3584 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-20 12:39:43.987  1989  3584 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-20 12:39:43.987  1019  1559 D FocusedStackFrame: Set to : 0
,03-20 12:39:43.987  1019  1559 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-20 12:39:43.987  1019  1559 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-20 12:39:43.997  1019  1559 D InputDispatcher: Focused application set to: xxxx
03-20 12:39:43.997  1019  1559 D InputDispatcher: Focus left window: 3045
,03-20 12:39:43.997  1019  1496 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-20 12:39:43.997  1019  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-20 12:39:43.997  1019  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-20 12:39:43.997  1019  1496 D SettingsProvider: selectionArgs: false
03-20 12:39:43.997  1019  1496 D SettingsProvider: selectionArgs: 10062
03-20 12:39:43.997  1019  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-20 12:39:43.997  1019  1496 D SettingsProvider: ret = -1
,03-20 12:39:44.007  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-20 12:39:44.007  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-20 12:39:44.007   258   428 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (173 us)
,03-20 12:39:44.007  1019  1496 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
03-20 12:39:44.007   306   306 I art     : Explicit concurrent mark sweep GC freed 8800(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 32.358ms
,03-20 12:39:44.017  1019  1329 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-20 12:39:44.017  1019  1329 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-20 12:39:44.017  1019  1329 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-20 12:39:44.017  1019  1329 D SettingsProvider: selectionArgs: false
03-20 12:39:44.017  1019  1329 D SettingsProvider: selectionArgs: 10062
03-20 12:39:44.017  1019  1329 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-20 12:39:44.017  1019  1329 D SettingsProvider: ret = -1
,03-20 12:39:44.027  1019  1329 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-20 12:39:44.027  3681  3681 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:44.027  3681  3681 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:44.037   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.249ms total 22.868ms
,03-20 12:39:44.047  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
03-20 12:39:44.057  3663  3663 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-20 12:39:44.057   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 19.289ms
,03-20 12:39:44.057  3045  3045 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,03-20 12:39:44.057  3045  3045 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-20 12:39:44.057  3045  3266 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 84ms. Plugin should use CordovaInterface.getThreadPool().
,03-20 12:39:44.067  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:44.067  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:44.067  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.067  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.067  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:44.087  3700  3700 E Zygote  : MountEmulatedStorage()
03-20 12:39:44.087  3700  3700 E Zygote  : v2
03-20 12:39:44.087  3700  3700 I libpersona: KNOX_SDCARD checking this for 10135
03-20 12:39:44.087  3700  3700 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:44.097  3700  3700 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:44.097  3700  3700 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:44.097  3700  3700 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:44.097  1019  3068 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3700 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
03-20 12:39:44.097  1019  3068 I ActivityManager: Killing 2943:com.sec.usbsettings/1000 (adj 15): empty #31
03-20 12:39:44.097  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
03-20 12:39:44.097  1019  1446 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:44.097  1019  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:44.097  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-20 12:39:44.107  1019  1559 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-20 12:39:44.107  1019  1559 W ActivityManager: mDVFSHelper.acquire()
,03-20 12:39:44.107  1019  1559 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-20 12:39:44.107  1019  1559 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-20 12:39:44.107  1019  1559 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-20 12:39:44.117  1019  1043 W libprocessgroup: failed to open /acct/uid_10099/pid_2892/cgroup.procs: No such file or directory
,03-20 12:39:44.127  3700  3700 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:44.127  3663  3715 V OneTimeService: OneTimeService.onHandleIntent
03-20 12:39:44.127  3700  3700 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:44.127  1493  1493 D Launcher: onRestart, Launcher: 996141361
,03-20 12:39:44.137  1019  1043 W libprocessgroup: failed to open /acct/uid_10004/pid_1570/cgroup.procs: No such file or directory
,03-20 12:39:44.147  1019  1043 W libprocessgroup: failed to open /acct/uid_10098/pid_2281/cgroup.procs: No such file or directory
,03-20 12:39:44.147  3681  3681 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-20 12:39:44.157  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:44.157  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.157  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.157  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:44.167  3692  3692 I dex2oat : ----------------------------------------------------
03-20 12:39:44.167  3692  3692 I dex2oat : <SS>: S T A R T I N G . . .
03-20 12:39:44.167  3692  3692 I dex2oat : <SS>: Zip is absent. Canceled.
03-20 12:39:44.167  3692  3692 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=94 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-20 12:39:44.177  3718  3718 E Zygote  : MountEmulatedStorage(),
03-20 12:39:44.177  3718  3718 E Zygote  : v2
03-20 12:39:44.177  3718  3718 I libpersona: KNOX_SDCARD checking this for 10015
03-20 12:39:44.177  3718  3718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:44.177  3718  3718 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:44.177  1019  1496 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3718 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-20 12:39:44.177  3718  3718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:44.177  3718  3718 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-20 12:39:44.177  1493  1493 D Launcher: onStart, Launcher: 996141361
,03-20 12:39:44.177  1493  1493 D Launcher.HomeView: onStart
03-20 12:39:44.177  1493  1493 D Launcher: onResume, Launcher: 996141361
,03-20 12:39:44.187  1019  1482 D SettingsProvider: name = kids_home_mode
03-20 12:39:44.187  1019  1482 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-20 12:39:44.187  1019  1482 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-20 12:39:44.187  1019  1482 D SettingsProvider: selectionArgs: false
03-20 12:39:44.187  1019  1482 D SettingsProvider: selectionArgs: 10007
03-20 12:39:44.187  1019  1482 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-20 12:39:44.187  1019  1482 D SettingsProvider: ret = -1
03-20 12:39:44.187  1493  1493 D Launcher.HomeView: onResume
,03-20 12:39:44.187  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2943/cgroup.procs: No such file or directory
,03-20 12:39:44.197  3681  3681 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-20 12:39:44.197  3681  3681 I ServiceMode: setReferenceIsDumpState : 0
,03-20 12:39:44.197  1493  1493 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-20 12:39:44.197  1019  1496 I ActivityManager: Killing 2735:com.google.android.apps.books/u0a75 (adj 15): empty #31
,03-20 12:39:44.207  1019  1019 D SensorService: [SO] activate (ident=0xb7a9c258, enabled=0)
03-20 12:39:44.207  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-20 12:39:44.207  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-20 12:39:44.207  1493  1493 D MenuAppsGridFragment: onResume
,03-20 12:39:44.207  3718  3718 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:44.217  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.217  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.217  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.217  3718  3718 D ActivityThread: Added TimaKeyStore provider
03-20 12:39:44.217  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:44.217  3700  3700 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-20 12:39:44.217  3700  3700 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-20 12:39:44.217  3700  3700 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-20 12:39:44.217  1019  1019 D SensorManager: unregisterListener ::   
03-20 12:39:44.217  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-20 12:39:44.217  1019  1019 D SensorService: [SO] changed settle time [0]
03-20 12:39:44.217  1019  1019 D SensorService: [SO] setDelay [200000000]
03-20 12:39:44.217  1019  1019 D SensorService: [SO] activate (ident=0xb7be1c78, enabled=1)
03-20 12:39:44.217  1019  1019 D SensorService: [SO] AR_init
03-20 12:39:44.217  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-20 12:39:44.227  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-20 12:39:44.237  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-20 12:39:44.237  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-20 12:39:44.237  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 12:39:44.237  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:44.237  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:44.237  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 12:39:44.237  3734  3734 E Zygote  : MountEmulatedStorage()
,03-20 12:39:44.237  3734  3734 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:44.237  3734  3734 E Zygote  : v2
03-20 12:39:44.237  3734  3734 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:44.237  3734  3734 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-20 12:39:44.237  1019  1329 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3734 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-20 12:39:44.247  1019  1329 I ActivityManager: Killing 2435:com.android.mms/u0a46 (adj 15): empty #31
,03-20 12:39:44.247  3734  3734 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:44.247  3734  3734 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:44.257  1019  3068 D ActivityManager: handle home activity for 0
03-20 12:39:44.267  1019  3068 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-20 12:39:44.267  1019  3068 D KnoxTimeoutHandler: post home show event for user 0
03-20 12:39:44.267  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-20 12:39:44.267  1019  3068 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-20 12:39:44.267  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-20 12:39:44.267  1019  3068 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-20 12:39:44.267  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-20 12:39:44.267  1019  3068 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-20 12:39:44.267  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-20 12:39:44.267   258   258 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-20 12:39:44.267  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-20 12:39:44.277  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-20 12:39:44.277  3734  3734 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:44.277  3734  3734 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:44.287  1019  1329 D InputDispatcher: Focus entered window: 1493
,03-20 12:39:44.287  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-20 12:39:44.287  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-20 12:39:44.287  1493  1493 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-20 12:39:44.327  1989  1989 W InstanceID/Rpc: Found 10012
,03-20 12:39:44.327  1493  1493 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-20 12:39:44.327  1019  1446 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-20 12:39:44.327  1019  3750 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-20 12:39:44.327  1182  1182 D PanelView: There is/are notification(s) 
,03-20 12:39:44.337  3045  3045 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-20 12:39:44.357  1772  1772 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-20 12:39:44.377  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-20 12:39:44.377  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:44.377  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:44.377  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-20 12:39:44.377  1019  3069 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-20 12:39:44.387  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:44.387  1019  3069 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:44.387  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-20 12:39:44.387  1019  1329 D CountryDetector: No listener is left
,03-20 12:39:44.397  1291  1660 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-20 12:39:44.407  1019  1043 W libprocessgroup: failed to open /acct/uid_10075/pid_2735/cgroup.procs: No such file or directory
,03-20 12:39:44.407  1019  1043 W libprocessgroup: failed to open /acct/uid_10046/pid_2435/cgroup.procs: No such file or directory
,03-20 12:39:44.407  3734  3734 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-20 12:39:44.407  3734  3734 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-20 12:39:44.417  1330  3298 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-20 12:39:44.427  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-20 12:39:44.467  3698  3698 D AndroidRuntime: 
03-20 12:39:44.467  3698  3698 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-20 12:39:44.467  3698  3698 D AndroidRuntime: CheckJNI is OFF
,03-20 12:39:44.467  3698  3698 D AndroidRuntime: readGMSProperty: start
03-20 12:39:44.467  3698  3698 D AndroidRuntime: readGMSProperty: already setted!!
03-20 12:39:44.467  3698  3698 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-20 12:39:44.467  3698  3698 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-20 12:39:44.467  3698  3698 D AndroidRuntime: readGMSProperty: end
03-20 12:39:44.467  3698  3698 D AndroidRuntime: addProductProperty: start
,03-20 12:39:44.467  1493  1493 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@350e842e time:40929
,03-20 12:39:44.497  1019  1050 D PersonaManager: isKioskContainerExistOnDevice
,03-20 12:39:44.527  1019  3068 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-20 12:39:44.527  1019  3068 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:44.527  1019  3068 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:44.527  1019  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-20 12:39:44.537  1019  1050 I ActivityManager: Displayed Component not be shown by security: +424ms
03-20 12:39:44.537  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-20 12:39:44.537  3734  3734 D NPS_WSSNPS: [] Service onCreate!!,
,03-20 12:39:44.547  1019  1446 W ActivityManager: userId = 0, bbcId = -10000,
03-20 12:39:44.547  1019  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:44.547  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-20 12:39:44.557  1019  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-20 12:39:44.567  1019  1488 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:44.567  1019  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:44.567  1019  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-20 12:39:44.567  3734  3768 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-20 12:39:44.567  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.567  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.567  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.567  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:44.587  3734  3734 D NPS_WSSNPS: [50.150321] smlDBHelper,
,03-20 12:39:44.597  1019  1329 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3771 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-20 12:39:44.597  3771  3771 E Zygote  : MountEmulatedStorage()
03-20 12:39:44.597  3771  3771 E Zygote  : v2
,03-20 12:39:44.597  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.597  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.597  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.597  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-20 12:39:44.607  3771  3771 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:44.607  3771  3771 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:44.607  3771  3771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:44.607  3771  3771 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:44.607  3771  3771 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:44.607  1019  1044 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-20 12:39:44.607  1019  1044 W ActivityManager: mDVFSHelper.release()
03-20 12:39:44.607  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-20 12:39:44.617  3299  3416 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-20 12:39:44.627  1019  1041 D SensorService: [SO] currT = 41081167000, prevT = 40631106000, diff = 450061000, [0.172 0.421 10.247]
03-20 12:39:44.627  1019  1041 D SensorService: [SO] 0.172 0.421 10.247
03-20 12:39:44.627  1019  1041 D SensorService: [SO] [100 -> 255]
,03-20 12:39:44.627  1019  1266 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3781 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-20 12:39:44.637  3698  3698 E AffinityControl: AffinityControl: registerfunction enter
,03-20 12:39:44.637  3781  3781 E Zygote  : MountEmulatedStorage()
03-20 12:39:44.637  3781  3781 I libpersona: KNOX_SDCARD checking this for 10042
03-20 12:39:44.637  3781  3781 E Zygote  : v2
03-20 12:39:44.637  3781  3781 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:44.637  3781  3781 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:44.647  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.647  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.647  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:44.647  1019  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:44.647  3771  3771 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:44.647  3771  3771 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:44.647  3781  3781 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-20 12:39:44.647  3781  3781 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-20 12:39:44.667  3698  3698 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-20 12:39:44.667  3798  3798 E Zygote  : MountEmulatedStorage()
,03-20 12:39:44.667  3798  3798 I libpersona: KNOX_SDCARD checking this for 10139
03-20 12:39:44.667  3798  3798 E Zygote  : v2
03-20 12:39:44.667  3798  3798 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:44.667  3798  3798 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:44.677  1019  1329 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3798 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
03-20 12:39:44.677  3798  3798 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:44.677  3798  3798 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:44.677  1019  1446 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:44.677  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
03-20 12:39:44.677  1019  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:44.677  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-20 12:39:44.687  3734  3734 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-20 12:39:44.687  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-20 12:39:44.687  1019  1032 D PackageManager: START PACKAGE DELETE: observer{915182123}
03-20 12:39:44.687  1019  1032 D PackageManager: pkg{<packageName>}
03-20 12:39:44.687  1019  1032 D PackageManager: user{0}
03-20 12:39:44.687  1019  1032 D PackageManager: caller{2000}
03-20 12:39:44.687  1019  1032 D PackageManager: flags{2}
03-20 12:39:44.687  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-20 12:39:44.687  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-20 12:39:44.687  1019  1032 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-20 12:39:44.687  1019  1032 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-20 12:39:44.687  1019  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-20 12:39:44.687  1019  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-20 12:39:44.687  1019  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-20 12:39:44.687  1019  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
03-20 12:39:44.687  1019  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-20 12:39:44.717  1019  1131 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-20 12:39:44.717  1019  1131 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:44.717  1019  1060 D PackageManager: !@killApplicatoin: 10174, uninstall pkg
03-20 12:39:44.717  3798  3798 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:44.717  1019  1131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:44.717  1019  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-20 12:39:44.717  3798  3798 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:44.727  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
,03-20 12:39:44.727  3734  3810 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-20 12:39:44.727  1019  1044 I ActivityManager: Killing 3045:com.test.thalitest/u0a174 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-20 12:39:44.727  3734  3810 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-20 12:39:44.727  3734  3810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-20 12:39:44.727  3781  3781 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:44.727  3781  3781 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:44.847  1019  3826 I WindowState: WIN DEATH: Window{2fc64292 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-20 12:39:44.857  1019  1060 W PackageSettings: Skipping PackageSetting{3de1f4d7 com.example.hello/10175} due to missing metadata
,03-20 12:39:44.887  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-20 12:39:44.897  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:44.897  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:44.897  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-20 12:39:44.897  3734  3734 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-20 12:39:44.897  3734  3734 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-20 12:39:44.897  3734  3734 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-20 12:39:44.907  3734  3734 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-20 12:39:44.907  3734  3734 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
,03-20 12:39:44.907  3734  3734 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-20 12:39:44.907  3734  3734 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
,03-20 12:39:44.907  3734  3734 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
,03-20 12:39:44.907  3734  3734 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
03-20 12:39:44.907  3734  3734 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-20 12:39:44.907  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-20 12:39:44.917   258  3476 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-20 12:39:44.917   258   428 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-20 12:39:44.917  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-20 12:39:44.917   258   430 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-20 12:39:44.917  1330  3298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-20 12:39:44.927  3798  3798 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-20 12:39:44.927  3798  3798 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-20 12:39:44.927  3798  3798 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-20 12:39:44.927  3798  3798 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-20 12:39:44.927  3798  3798 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-20 12:39:44.937  1019  1446 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:44.937  1019  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:44.937  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-20 12:39:44.937  1330  3298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
03-20 12:39:44.937  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{382a8df6 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:41397
,03-20 12:39:44.947  3781  3781 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-20 12:39:44.947  1019  3826 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-20 12:39:44.967  1330  3298 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-20 12:39:44.967  1019  1131 D SettingsProvider: name = access_control_enabled
,03-20 12:39:44.967  1019  3826 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:44.967  1019  3826 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:44.967  1019  3826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-20 12:39:44.967  1019  1060 I ActivityManager: Force stopping com.test.thalitest appid=10174 user=0: pkg removed
03-20 12:39:44.967  2579  2579 I Hs20UtilService: Starting #3
,03-20 12:39:44.967  2579  2594 I Hs20UtilService: Message received 5003
,03-20 12:39:45.007  3197  3659 W Finsky  : [412] PackageManagerRepository.createPackageState: Package com.test.thalitest not installed
,03-20 12:39:45.007  1019  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-20 12:39:45.047  3781  3781 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-20 12:39:45.057  1019  1107 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-20 12:39:45.067  1772  1772 E SamsungIME: mOCRHelper is null
,03-20 12:39:45.077  1791  2066 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-20 12:39:45.097  3734  3734 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-20 12:39:45.107  1468  1468 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-20 12:39:45.107  1454  1454 D RegisteredComponentCache: Collect Tech packages for Knox
,03-20 12:39:45.137  1019  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.137  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:45.137  1019  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:45.137  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.147  1454  1454 D PersonaManager: isKioskContainerExistOnDevice
,03-20 12:39:45.167  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:45.167  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.167  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.167  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:45.187  1019  1032 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3835 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-20 12:39:45.187  3835  3835 E Zygote  : MountEmulatedStorage()
03-20 12:39:45.187  3835  3835 E Zygote  : v2
03-20 12:39:45.187  3835  3835 I libpersona: KNOX_SDCARD checking this for 10019
03-20 12:39:45.187  3835  3835 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:45.187  3835  3835 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:45.197  1019  1329 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-20 12:39:45.197  1019  1329 D SecContentProvider2: mCursor = null
,03-20 12:39:45.197  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.197  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.197  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.197  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:45.197  3835  3835 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-20 12:39:45.207  3835  3835 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-20 12:39:45.217  3842  3842 E Zygote  : MountEmulatedStorage(),
03-20 12:39:45.217  3842  3842 E Zygote  : v2
03-20 12:39:45.217  3842  3842 I libpersona: KNOX_SDCARD checking this for 10069,
03-20 12:39:45.217  3842  3842 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:45.217  3842  3842 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-20 12:39:45.217  3842  3842 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:45.217  3842  3842 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:45.227  1019  1032 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3842 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-20 12:39:45.227  1019  1032 I ActivityManager: Killing 3079:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-20 12:39:45.227  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:45.227  1019  3069 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
03-20 12:39:45.227  1019  3069 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:45.227  1019  1133 V NetworkStats: removeUidsLocked() for UIDs [10174]
03-20 12:39:45.227  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-20 12:39:45.227  1019  1133 V NetworkStats: performPollLocked(flags=0x3)
03-20 12:39:45.227  1019  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-20 12:39:45.237  1019  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
03-20 12:39:45.237  1019  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-20 12:39:45.237  2694  2694 D FactoryTestApp: [DummyFtClient$onDestroy](2694) Destroy DummyFtClient service
,03-20 12:39:45.257  1019  1032 I ActivityManager: Killing 3034:com.sec.dsm.system/1000 (adj 15): empty #31
,03-20 12:39:45.257  1019  1032 I ActivityManager: Killing 2928:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,03-20 12:39:45.277  3835  3835 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:45.277  3835  3835 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:45.297  1019  3069 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.297  3842  3842 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:45.297  3842  3842 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:45.297  2694  2694 D FactoryTestApp: [Support$Values.getString](2694) id=MODEL_COMMUNICATION_MODE, value=gsm
03-20 12:39:45.297  2694  2694 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2694) mConnectionMode = gsm
03-20 12:39:45.297  2694  2694 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2694) RUNNING_FTCLIENT : false
03-20 12:39:45.297  2694  2694 D FactoryTestApp: [DummyFtClient$onDestroy](2694) kill process
03-20 12:39:45.297  2694  2694 I Process : Sending signal. PID: 2694 SIG: 9
,03-20 12:39:45.297  1019  3069 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:45.297  1019  3069 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-20 12:39:45.297  1019  3069 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.317  1454  1454 D PersonaManager: isKioskContainerExistOnDevice
,03-20 12:39:45.317  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.317  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.317  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.317  1019  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:45.317  1019  1019 D RCPManagerService: PackageReceiver onReceive()
03-20 12:39:45.317  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-20 12:39:45.317  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-20 12:39:45.317  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,03-20 12:39:45.327  3867  3867 E Zygote  : MountEmulatedStorage()
03-20 12:39:45.327  3867  3867 E Zygote  : v2
03-20 12:39:45.327  3867  3867 I libpersona: KNOX_SDCARD checking this for 10145
03-20 12:39:45.327  3867  3867 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:45.327  3867  3867 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-20 12:39:45.337  3867  3867 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-20 12:39:45.337  3867  3867 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:45.337  1019  3068 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3867 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
03-20 12:39:45.337  1019  1019 D OTPFW   : OtpDbHelper::getInstance New instance created
03-20 12:39:45.337  1019  1019 D OTPFW   : DBIntegrity::getInstance - New instance created
,03-20 12:39:45.337  1019  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-20 12:39:45.337  1019  1133 V NetworkStats: performPollLocked() took 110ms
,03-20 12:39:45.357  1019  1385 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.357  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:45.357  1019  1385 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:45.357  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.367  1454  1454 D RegisteredServicesCache: empty dynamic service
,03-20 12:39:45.397  1019  3826 I ActivityManager: Process com.sec.factory (pid 2694)(adj 0) has died(94,1083)
,03-20 12:39:45.397  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
,03-20 12:39:45.397  3867  3867 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:45.407  3867  3867 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:45.407  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,03-20 12:39:45.407  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-20 12:39:45.407  3835  3835 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Mar 20 12:39:45 GMT+01:00 2016
,03-20 12:39:45.407  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
03-20 12:39:45.407  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
,03-20 12:39:45.417  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-20 12:39:45.417  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-20 12:39:45.417  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,03-20 12:39:45.417  1019  1019 V EnterpriseBillingPolicy: uID is 10174
03-20 12:39:45.417  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-20 12:39:45.417  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-20 12:39:45.417  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-20 12:39:45.417  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-20 12:39:45.417  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-20 12:39:45.417  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-20 12:39:45.417  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-20 12:39:45.427  1019  3827 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.427  1019  3827 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:45.427  1019  3827 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:45.427  1019  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-20 12:39:45.427  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-20 12:39:45.427  3842  3842 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
03-20 12:39:45.427  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-20 12:39:45.427  1019  1019 V EnterpriseBillingPolicy: uID is 10174
03-20 12:39:45.427  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-20 12:39:45.427  1019  2820 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-20 12:39:45.427  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-20 12:39:45.427  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-20 12:39:45.427  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-20 12:39:45.427  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-20 12:39:45.427  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-20 12:39:45.427  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-20 12:39:45.437  3835  3835 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-20 12:39:45.457  3835  3835 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-20 12:39:45.477  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.477  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.477  3835  3835 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-20 12:39:45.477  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.477  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:45.477  3835  3835 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-20 12:39:45.487  3887  3887 E Zygote  : MountEmulatedStorage()
03-20 12:39:45.487  3887  3887 E Zygote  : v2
,03-20 12:39:45.487  3887  3887 I libpersona: KNOX_SDCARD checking this for 10022
03-20 12:39:45.487  3887  3887 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:45.487  3887  3887 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-20 12:39:45.487  1019  1031 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3887 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,03-20 12:39:45.497  3887  3887 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:45.497  3887  3887 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:45.507  3718  3718 I RlzPingService: Setting next ping for 1459078785520
,03-20 12:39:45.527  3835  3886 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-20 12:39:45.527  3887  3887 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:45.537  3887  3887 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:45.537  3867  3867 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-20 12:39:45.537  3867  3867 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-20 12:39:45.537  3867  3867 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-20 12:39:45.537  3867  3867 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-20 12:39:45.537  3867  3867 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-20 12:39:45.557  1019  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.567  3835  3886 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
,03-20 12:39:45.577  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:45.577  1019  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-20 12:39:45.587  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-20 12:39:45.617  3299  3416 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-20 12:39:45.627  3835  3835 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-20 12:39:45.647  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.657  1019  1446 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:45.657  1019  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:45.657  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.657  1019  1482 I ActivityManager: Killing 2112:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,03-20 12:39:45.657  2719  2808 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-20 12:39:45.667  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-20 12:39:45.677  1019  1019 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-20 12:39:45.677  1989  3908 I CheckinService: Disabling old GoogleServicesFramework version
,03-20 12:39:45.677  1019  1019 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:45.687  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:45.687  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.687  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:45.687  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:45.697  3911  3911 E Zygote  : MountEmulatedStorage(),
03-20 12:39:45.707  3911  3911 E Zygote  : v2
03-20 12:39:45.707  3911  3911 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:45.707  3911  3911 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:45.707  3911  3911 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:45.707  3911  3911 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-20 12:39:45.707  3911  3911 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-20 12:39:45.707  1019  1019 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3911 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-20 12:39:45.727  1019  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.727  1019  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.727  1019  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:45.727  1019  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:45.727   306   306 I art     : Explicit concurrent mark sweep GC freed 8731(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 21.554ms
,03-20 12:39:45.747  3911  3911 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:45.747  3911  3911 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:45.747   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 952us total 17.986ms
,03-20 12:39:45.767   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 19.995ms
,03-20 12:39:45.777  3274  3326 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-20 12:39:45.787  3927  3927 E Zygote  : MountEmulatedStorage()
03-20 12:39:45.787  3927  3927 E Zygote  : v2
03-20 12:39:45.787  3927  3927 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:45.787  3927  3927 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:45.787  3927  3927 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:45.787  3927  3927 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-20 12:39:45.787  3927  3927 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:45.787  1019  1482 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3927 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-20 12:39:45.787  1019  1482 I ActivityManager: Killing 3102:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-20 12:39:45.797  1019  3828 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.797  1019  1165 D TaskPersister: removeObsoleteFile: deleting file=236_task.xml
03-20 12:39:45.797  1019  1165 D TaskPersister: removeObsoleteFile: deleting file=236_task_thumbnail.png
,03-20 12:39:45.807  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.817  1019  1446 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:45.817  1019  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:45.817  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.837  1989  1989 D SystemUpdateService: onCreate
,03-20 12:39:45.837  3274  3326 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-20 12:39:45.837  3274  3326 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-20 12:39:45.837  3274  3326 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-20 12:39:45.847  3927  3927 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:45.847  3927  3927 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:45.847  1019  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.847  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:45.847  1019  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:45.847  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.867  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
03-20 12:39:45.867  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-20 12:39:45.867  1019  1043 W TextServicesManagerService: no available spell checker services found
,03-20 12:39:45.867  3274  3326 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-20 12:39:45.877  3274  3326 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-20 12:39:45.877  3274  3326 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-20 12:39:45.877  1019  1488 D RCPManagerService: exchangeData() failure , invalid userId
,03-20 12:39:45.877  1989  3833 D GCM     : COMPAT: Multi user not supported
,03-20 12:39:45.877  1019  1131 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.887  3274  3326 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-20 12:39:45.887  1019  1131 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:45.887  1019  1131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-20 12:39:45.897  1019  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.907  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.907  1019  3069 D RCPManagerService: exchangeData() failure , invalid userId
,03-20 12:39:45.917  1728  3945 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-20 12:39:45.917  1989  1989 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-20 12:39:45.917  1019  1446 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:45.917  1019  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-20 12:39:45.917  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.927  1493  1493 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-20 12:39:45.937  1019  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:45.937  1493  1493 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-20 12:39:45.937  1019  1446 D RCPManagerService: exchangeData() failure , invalid userId
,03-20 12:39:45.937  1019  1488 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:45.937  1019  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:45.937  1019  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.967  1728  1728 I ConfigService: onCreate
,03-20 12:39:45.967  1019  3827 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,03-20 12:39:45.967  1019  3827 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:45.967  1019  3827 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:45.967  1019  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.967  1989  1989 I ConfigFetchService: onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,03-20 12:39:45.977  3927  3927 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-20 12:39:45.977  1019  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:45.987  1019  1488 D RCPManagerService: exchangeData() failure , invalid userId
,03-20 12:39:45.987  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:45.987  1019  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:45.987  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:45.987  1019  1446 D SecContentProvider2: uri = 14 selection = getSealedState,
03-20 12:39:45.987  1019  1446 D SecContentProvider2: mCursor = null
,03-20 12:39:45.987  1019  3827 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-20 12:39:45.987  1019  3827 D SecContentProvider2: mCursor = null
,03-20 12:39:45.997  3927  3927 V MTPRx   : sealedState: false
03-20 12:39:45.997  3927  3927 V MTPRx   : sealedUsbMassStorageState: false
,03-20 12:39:46.017  1019  1329 D SettingsProvider: name = mtp_usb_connection_status
,03-20 12:39:46.037  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.037  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-20 12:39:46.037  1019  1446 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:46.037  3911  3911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
03-20 12:39:46.037  1019  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-20 12:39:46.037  1989  3909 I CheckinService: Checking schedule, now: 1458473986051 next: 1458756694030
03-20 12:39:46.037  1989  3909 I CheckinService: active receiver: disabled
,03-20 12:39:46.037  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:46.057  1019  1488 D SettingsProvider: name = media_player_mode
,03-20 12:39:46.077  1019  3828 D SettingsProvider: name = mtp_usb_conditions_met
,03-20 12:39:46.077  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.077  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-20 12:39:46.087  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-20 12:39:46.087  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-20 12:39:46.107  1019  1446 D RCPManagerService: exchangeData() failure , invalid userId
,03-20 12:39:46.107  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:46.107  1019  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:46.107  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-20 12:39:46.107  1019  1329 D SettingsProvider: name = mtp_running_status
,03-20 12:39:46.107  1019  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.117  1019  1482 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:46.117  1019  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-20 12:39:46.117  1019  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:46.127  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:46.127  1019  1496 D RCPManagerService: exchangeData() failure , invalid userId
,03-20 12:39:46.137  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:46.147  1019  1131 D SettingsProvider: name = media_mount_count
,03-20 12:39:46.147  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:46.177  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:46.177  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.177  3132  3140 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
03-20 12:39:46.177  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.177  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.177  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.187  3963  3963 E Zygote  : MountEmulatedStorage(),
03-20 12:39:46.197  3963  3963 E Zygote  : v2
03-20 12:39:46.197  3963  3963 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:46.197  3963  3963 I libpersona: KNOX_SDCARD not a persona,
,03-20 12:39:46.197  3963  3963 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-20 12:39:46.197  3963  3963 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:46.207  3963  3963 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-20 12:39:46.217  1019  1385 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3963 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-20 12:39:46.217  1019  1329 D SettingsProvider: name = mtp_sync_alive
,03-20 12:39:46.227  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.227  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:46.227  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:46.227  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-20 12:39:46.227  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:46.227  3963  3963 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:46.227  3963  3963 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:46.227  1019  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.237  1019  1496 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:46.237  1019  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-20 12:39:46.237  1019  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:46.247  1019  1329 D SettingsProvider: name = sdcard_launch
,03-20 12:39:46.247  1019  1131 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-20 12:39:46.247  1019  1131 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:46.247  1019  1131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:46.247  1019  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:46.257  1019  3069 D SettingsProvider: name = boot_time_connected
,03-20 12:39:46.257  1989  3833 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-20 12:39:46.257  1019  1385 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.257  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
,03-20 12:39:46.257  1019  1385 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:46.257  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:46.267  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:46.267  3963  3963 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-20 12:39:46.267  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:46.277  1989  3949 I SystemUpdateService: cancelUpdate (empty URL)
03-20 12:39:46.277  1989  3949 I SystemUpdateService: active receiver: disabled
,03-20 12:39:46.287  3132  3140 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-20 12:39:46.287  3132  3140 D BadgeProvider: sendNotify, [notify] : null
03-20 12:39:46.287  3132  3140 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-20 12:39:46.287  3132  3140 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-20 12:39:46.287  3132  3140 D BadgeProvider: update, [UpdateCount] : 1
,03-20 12:39:46.297  1493  1493 D Launcher.Model: reloadBadges entered.
,03-20 12:39:46.297  1989  3978 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-20 12:39:46.307  1989  3978 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-20 12:39:46.317  1019  1385 I ActivityManager: Killing 3142:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-20 12:39:46.327  1019  3827 D SettingsProvider: name = mtp_open_session
,03-20 12:39:46.327  1019  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:46.327  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:46.327  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:46.327  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:46.347  1019  1060 I art     : Explicit concurrent mark sweep GC freed 54362(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 30MB/46MB, paused 30.232ms total 1.254s
,03-20 12:39:46.347  1019  1266 I art     : WaitForGcToComplete blocked for 719.722ms for cause Explicit
,03-20 12:39:46.367  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.367  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.367  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.367  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.367  1182  1182 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-20 12:39:46.377  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-20 12:39:46.377  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-20 12:39:46.387  3692  3692 I dex2oat : dex2oat took 2.212s (threads: 4)
,03-20 12:39:46.387  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-20 12:39:46.397  3989  3989 E Zygote  : MountEmulatedStorage(),
03-20 12:39:46.397  3989  3989 E Zygote  : v2
03-20 12:39:46.397  3989  3989 I libpersona: KNOX_SDCARD checking this for 10146
03-20 12:39:46.397  3989  3989 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:46.397  3989  3989 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:46.407  1019  1488 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=3989 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-20 12:39:46.407  3989  3989 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:46.407  3989  3989 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:46.417  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-20 12:39:46.427  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-20 12:39:46.427  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-20 12:39:46.427  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-20 12:39:46.427  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-20 12:39:46.447  1791  1791 I GCoreUlr: DispatchingService.onCreate()
,03-20 12:39:46.457  3989  3989 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:46.457  3989  3989 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:46.457  1989  3584 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
03-20 12:39:46.457  1989  3584 D DexOptUtils: Set odex to world readable.
,03-20 12:39:46.457  1989  3584 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
,03-20 12:39:46.457  1989  3584 D FileApkUtils: Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
,03-20 12:39:46.467  1019  3827 I ActivityManager: Killing 3175:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-20 12:39:46.467  3509  3509 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-20 12:39:46.467  3509  3509 I PCWCLIENTTRACE_PushUtil: sales region : global
03-20 12:39:46.467  3509  3509 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-20 12:39:46.467  3509  3509 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-20 12:39:46.467  3509  3509 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-20 12:39:46.467  3509  3509 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-20 12:39:46.467  1019  1385 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-20 12:39:46.467  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:46.467  1019  1385 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:46.467  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:46.477  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-20 12:39:46.487  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-20 12:39:46.487  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 12:39:46.487  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:46.487  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-20 12:39:46.487  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-20 12:39:46.497  1019  1060 D PackageManager: delete codoeFile: 
,03-20 12:39:46.497  1019  1060 D AASAuninstall: userId = 0, info.removedAppID = 10174, info.uid = 10174, packageName = com.test.thalitest
03-20 12:39:46.497  1019  1060 I AASA_removePackage: UID=10174 Target=com.test.thalitest
,03-20 12:39:46.507  1019  1060 D PackageManager: result of delete: 1{915182123}
,03-20 12:39:46.507  1019  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.507  1019  1329 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:46.507  1019  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:46.507  1019  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:46.517  3509  3509 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-20 12:39:46.537  3698  3698 D AndroidRuntime: Shutting down VM
,03-20 12:39:46.537  1989  1989 I ConfigFetchService: service connected
,03-20 12:39:46.537  1989  1989 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-20 12:39:46.557  3509  3509 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-20 12:39:46.557  1019  1559 D TimaService: TIMA: in getTimaVersion
,03-20 12:39:46.567  3509  3509 I ReactiveServiceManager: Supported : 1
,03-20 12:39:46.567  3989  3989 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-20 12:39:46.567  1019  1131 D TimaService: TIMA3: KeyStore3_init
,03-20 12:39:46.567  1019  1032 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-20 12:39:46.567  1019  1131 D TimaService: TIMA: in getTimaVersion
,03-20 12:39:46.567  1019  1266 I art     : Explicit concurrent mark sweep GC freed 6081(309KB) AllocSpace objects, 1(1650KB) LOS objects, 33% free, 29MB/43MB, paused 3.171ms total 223.837ms
,03-20 12:39:46.567  1019  1032 D QSEECOMAPI: : App is not loaded in QSEE
,03-20 12:39:46.577  1019  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.587  1019  1482 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:46.587  1019  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-20 12:39:46.587  1019  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-20 12:39:46.597  3781  3781 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-20 12:39:46.597  1019  1131 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
,03-20 12:39:46.597  1019  1131 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-20 12:39:46.597  1019  1131 I TLC_TZ_KEYSTORE: : initializing ccm context...
,03-20 12:39:46.597  1019  1131 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
03-20 12:39:46.597  1019  1131 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
,03-20 12:39:46.597  1019  1131 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-20 12:39:46.597  1019  1131 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8,
03-20 12:39:46.597  1019  1131 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-20 12:39:46.597  1019  1131 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
,03-20 12:39:46.597  1019  1131 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880,
03-20 12:39:46.597  1019  1131 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
,03-20 12:39:46.607  1019  1032 D QSEECOMAPI: : Loaded image: APP id = 9
03-20 12:39:46.607  1019  1131 D QSEECOMAPI: : App is not loaded in QSEE
,03-20 12:39:46.607  1019  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-20 12:39:46.607  1019  1060 D PackageManager: userId{-1}
03-20 12:39:46.607  1019  1060 D PackageManager: andCode{true}
,03-20 12:39:46.617  1019  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.627  3299  3416 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-20 12:39:46.627  1019  1032 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-20 12:39:46.627  1019  1032 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-20 12:39:46.627  1019  1032 E terrier : handleString: Failed to handle string(-4)
03-20 12:39:46.627  1019  1032 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-20 12:39:46.637  3509  3509 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-20 12:39:46.637  3509  3509 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-20 12:39:46.657  3509  3509 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-20 12:39:46.657  3509  3509 I PCWCLIENTTRACE_PushUtil: sales region : global
03-20 12:39:46.657  3509  3509 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-20 12:39:46.657  3509  3509 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
03-20 12:39:46.657  1019  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.657  1019  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.657  1019  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.657  1019  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.657  1728  2821 I art     : Explicit concurrent mark sweep GC freed 11419(699KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/17MB, paused 1.229ms total 131.215ms
,03-20 12:39:46.667  4010  4010 E Zygote  : MountEmulatedStorage(),
03-20 12:39:46.667  4010  4010 E Zygote  : v2
03-20 12:39:46.667  4010  4010 I libpersona: KNOX_SDCARD checking this for 10004,
03-20 12:39:46.667  4010  4010 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:46.667  4010  4010 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:46.677  1019  1060 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4010 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
03-20 12:39:46.677  1019  1446 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.677  4010  4010 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:46.677  4010  4010 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:46.677  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-20 12:39:46.677  1019  1131 D QSEECOMAPI: : Loaded image: APP id = 10
,03-20 12:39:46.687  1019  1446 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:46.687  1019  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:46.687  1019  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-20 12:39:46.687  1791  4007 I art     : Explicit concurrent mark sweep GC freed 12398(767KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 10MB/17MB, paused 1.253ms total 100.683ms
,03-20 12:39:46.697  1019  1131 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
,03-20 12:39:46.697  1019  1131 I TLC_TZ_KEYSTORE: : ctx = 0xb7b8ea30, comm = 0xb7bdb478, sendmsg = 0xa0556000, recvmsg = 0xa0556440
03-20 12:39:46.697  1019  1131 I TZ_init: : TZ_init: sending initialization request...
,03-20 12:39:46.697  1019  1131 E TZ_init: : TZ_init Process: Secure memory is not initialized!
,03-20 12:39:46.697  1019  1131 E TZ_init: : trustlet initialization failed
,03-20 12:39:46.697  1019  1131 I TZ_init: : TZ_init_START...
,03-20 12:39:46.707  1019  1131 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-20 12:39:46.707  1019  1131 I TZ_init: : TZ_init: successful initialization
03-20 12:39:46.707  1019  1131 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-20 12:39:46.707  1019  1131 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-20 12:39:46.707  1019  1131 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-20 12:39:46.717  1019  3826 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-20 12:39:46.717  4010  4010 D TimaKeyStoreProvider: TimaSignature is unavailable
03-20 12:39:46.717  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-20 12:39:46.717  1019  3826 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-20 12:39:46.717  4010  4010 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:46.717  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.717  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.717  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.717  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.717  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,03-20 12:39:46.717  3911  3962 I AMMetaDataParserService: Resource data:Inside bundle  check
03-20 12:39:46.717  3911  3962 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-20 12:39:46.717  3911  3962 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-20 12:39:46.717  3911  3962 I AMMetaDataParserService: Resource data:2131165186
,03-20 12:39:46.727  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-20 12:39:46.727  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-20 12:39:46.737  4026  4026 E Zygote  : MountEmulatedStorage()
03-20 12:39:46.737  4026  4026 E Zygote  : v2
03-20 12:39:46.737  4026  4026 I libpersona: KNOX_SDCARD checking this for 10031
03-20 12:39:46.737  4026  4026 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:46.737  4026  4026 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-20 12:39:46.737  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-20 12:39:46.737  4026  4026 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:46.737  3911  3962 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-20 12:39:46.737  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-20 12:39:46.737  3911  3962 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-20 12:39:46.737  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-20 12:39:46.737  3911  3962 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-20 12:39:46.737  4026  4026 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-20 12:39:46.737  3911  3962 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-20 12:39:46.737  3911  3962 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-20 12:39:46.737  3911  3962 I AMMetaDataParserService: getResourceTypeNamexml
,03-20 12:39:46.747  1019  1032 D RCPManagerService: exchangeData() failure , invalid userId
,03-20 12:39:46.747  3698  3698 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-20 12:39:46.747  1019  1496 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4026 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,03-20 12:39:46.747  1019  1496 I ActivityManager: Killing 3214:com.google.android.configupdater/u0a86 (adj 15): empty #31
,03-20 12:39:46.757  1019  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.767  1019  3068 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.767  1019  3068 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:46.767  1019  3068 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:46.767  1019  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-20 12:39:46.767  1019  1496 I ActivityManager: Killing 3274:com.policydm/1000 (adj 15): empty #31
,03-20 12:39:46.777  1989  3584 D GmsModuleFndr: Beginning GMS chimera module scan
,03-20 12:39:46.787  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-20 12:39:46.787  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-20 12:39:46.787  1989  1989 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-20 12:39:46.787  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-20 12:39:46.797  3911  3962 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-20 12:39:46.797  1989  3584 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
03-20 12:39:46.797  1989  3584 D ChimeraCfgMgr: Beginning module configuration check
,03-20 12:39:46.797  1989  3584 D ChimeraCfgMgr: Module APKs unchanged, check complete
,03-20 12:39:46.807  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.807  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.807  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.807  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.827  4044  4044 E Zygote  : MountEmulatedStorage()
03-20 12:39:46.827  4044  4044 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:46.827  4044  4044 E Zygote  : v2
03-20 12:39:46.827  4044  4044 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:46.827  4044  4044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-20 12:39:46.827  1019  1496 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4044 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-20 12:39:46.827  4026  4026 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-20 12:39:46.827  4026  4026 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:46.827  4044  4044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-20 12:39:46.837  4044  4044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:46.837  1019  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.857  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-20 12:39:46.857  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-20 12:39:46.857  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.857  3911  3962 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-20 12:39:46.857  3963  3963 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
03-20 12:39:46.857  1019  1032 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-20 12:39:46.857  1019  3827 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.857  1019  3827 W ActivityManager: userId = 0, bbcId = -10000
03-20 12:39:46.857  1019  3827 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-20 12:39:46.857  1019  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-20 12:39:46.867  4044  4044 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:46.867  4044  4044 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:46.867  4026  4026 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-20 12:39:46.867  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.877  1019  1329 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-20 12:39:46.877  1019  1043 W libprocessgroup: failed to open /acct/uid_10085/pid_2928/cgroup.procs: No such file or directory
03-20 12:39:46.877  1019  1043 W libprocessgroup: failed to open /acct/uid_10048/pid_3079/cgroup.procs: No such file or directory
,03-20 12:39:46.877  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3034/cgroup.procs: No such file or directory
,03-20 12:39:46.877  3911  3962 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,03-20 12:39:46.877  1019  3828 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-20 12:39:46.887  1019  1496 I ActivityManager: Killing 3256:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-20 12:39:46.887  1019  1496 I ActivityManager: Killing 3312:com.sec.factory.camera/1000 (adj 15): empty #31
,03-20 12:39:46.887  3867  3985 I Process : Sending signal. PID: 3867 SIG: 9
,03-20 12:39:46.907  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.907  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.907  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:46.907  1019  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-20 12:39:46.907  3911  3962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
,03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
,03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity,
,03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity,
,03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity,
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
,03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
,03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-20 12:39:46.907  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,03-20 12:39:46.937  4061  4061 E Zygote  : MountEmulatedStorage(),
03-20 12:39:46.937  4061  4061 I libpersona: KNOX_SDCARD checking this for 1000
03-20 12:39:46.937  4061  4061 E Zygote  : v2
03-20 12:39:46.937  4061  4061 I libpersona: KNOX_SDCARD not a persona
03-20 12:39:46.937  4061  4061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-20 12:39:46.937  1019  1496 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4061 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-20 12:39:46.947   289   289 E SMD     : DCD OFF
03-20 12:39:46.947   255   255 E lowmemorykiller: Error writing /proc/3867/oom_score_adj; errno=22
03-20 12:39:46.947  4061  4061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-20 12:39:46.947  4061  4061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-20 12:39:46.957  1989  2137 I art     : Explicit concurrent mark sweep GC freed 25070(2MB) AllocSpace objects, 39(624KB) LOS objects, 39% free, 11MB/19MB, paused 2.680ms total 114.744ms
,03-20 12:39:46.967  3963  4060 E SQLiteLog: (10) unixWrite() File Descriptor : 30 gets errno : 30
,03-20 12:39:46.967  3963  4060 E SQLiteDatabase: Error inserting log=BBC_Controller>>sendResponseMsg() 1000/0/0/null
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at com.samsung.android.bbc.bbcagent.provider.BBCDBHelper.write_log(BBCDBHelper.java:722)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at com.samsung.android.bbc.bbcagent.bbccontroller.BBCController.sendResponseMsg(BBCController.java:116)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at com.samsung.android.bbc.bbcagent.bbccontroller.BBCController.checkContainerConsistency(BBCController.java:248)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService.onHandleIntent(BBCAgentService.java:154)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-20 12:39:46.967  3963  4060 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-20 12:39:46.967  3963  4060 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO debug_logs(log) VALUES (?)] disk I/O error
,03-20 12:39:46.967  3963  4060 E SQLiteDatabase: Error inserting log=BBCAgentService>>onHandleIntent/1/7
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at com.samsung.android.bbc.bbcagent.provider.BBCDBHelper.write_log(BBCDBHelper.java:722)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService.onHandleIntent(BBCAgentService.java:157)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-20 12:39:46.967  3963  4060 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-20 12:39:46.977  3963  3963 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-20 12:39:46.977  3963  3963 E SQLiteLog: (3850) statement aborts at 18: [select count(*) from bbc_apps where (option&16)<>0 and (option&1)<>0 and isInstalled=1] disk I/O error
,03-20 12:39:46.977  3963  3963 E SQLiteQuery: exception: disk I/O error (code 3850); query: select count(*) from bbc_apps where (option&16)<>0 and (option&1)<>0 and isInstalled=1
,03-20 12:39:46.977  1019  3826 I ActivityManager: Process com.android.email (pid 3867)(adj 9) has died(118,1083)
,03-20 12:39:46.977  3989  3989 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@11ebb19f
03-20 12:39:46.977  3989  3989 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@11ebb19f
,03-20 12:39:46.977  3963  3963 D AndroidRuntime: Shutting down VM
,03-20 12:39:46.987  3963  3963 E AndroidRuntime: FATAL EXCEPTION: main
03-20 12:39:46.987  3963  3963 E AndroidRuntime: Process: com.samsung.android.bbc.bbcagent, PID: 3963
03-20 12:39:46.987  3963  3963 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForCursorWindow(Native Method)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:1015)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.database.AbstractCursor.moveToPosition(AbstractCursor.java:197)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.database.AbstractCursor.moveToNext(AbstractCursor.java:245)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at com.samsung.android.bbc.bbcagent.seandroidmanager.SEAMSManagerBasic.isBBCContainerRequired(SEAMSManagerBasic.java:322)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at com.samsung.android.bbc.bbcagent.seandroidmanager.SEAMSManagerBasic.checkConsistencyForSharedContainer(SEAMSManagerBasic.java:370)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at com.samsung.android.bbc.bbcagent.seandroidmanager.SEAMSManagerBasic.doConsistencyCheck(SEAMSManagerBasic.java:388)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at com.samsung.android.bbc.bbcagent.seandroidmanager.SEAMSInterface.doConsistencyCheck(SEAMSInterface.java:82)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at com.samsung.android.bbc.bbcagent.bbccontroller.BBCController$ControllerHandler.handleMessage(BBCController.java:797)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-20 12:39:46.987  3963  3963 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-20 12:39:47.007  3911  3962 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,03-20 12:39:47.007  3911  3962 I AMMetaDataParserService: Resource data:Inside bundle  check
03-20 12:39:47.007  3911  3962 I AMMetaDataParserService: getResourcePackageName:assistant
03-20 12:39:47.007  3911  3962 I AMMetaDataParserService: Resource data:2131034113
,03-20 12:39:47.007  1019  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:47.007  1019  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:47.007  1019  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-20 12:39:47.007  1019  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-20 12:39:47.017  3911  3962 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-20 12:39:47.017  3911  3962 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-20 12:39:47.017  3911  3962 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-20 12:39:47.017  3911  3962 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-20 12:39:47.017  3911  3962 I AMMetaDataParserService: getResourceTypeNamexml
,03-20 12:39:47.017  4061  4061 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-20 12:39:47.017  3911  3962 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-20 12:39:47.017  4061  4061 D ActivityThread: Added TimaKeyStore provider
,03-20 12:39:47.017  3911  3962 I GFX construct_block_size_descriptor_2d second part: took 2.721667ms for 0*0 texture 0
,03-20 12:39:47.027  4076  4076 E Zygote  : MountEmulatedStorage()
03-20 12:39:47.027  4076  4076 I libpersona: KNOX_SDCARD checking this for 10145
03-20 12:39:47.027  4076  4076 E Zygote  : v2
03-20 12:39:47.027  4076  4076 I libpersona: KNOX_SDCARD not a persona
,03-20 12:39:47.027  4076  4076 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-20 12:39:47.027  1019  3827 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4076 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-20 12:39:47.027  1019  3826 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.bbc.bbcagent,
,03-20 12:39:47.037  4076  4076 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-20 12:39:47.037  3911  3962 I GFX generate_partition_tables: took 6.333437ms for 0*0 texture 0
,03-20 12:39:47.037  3911  3962 I GFX raster: took 10.257239ms for 96*96 texture 0
03-20 12:39:47.037  3911  3962 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76fd4a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76fd468 counterpartCT=4 counterpartW=96 counterparth=96
,03-20 12:39:47.047  4076  4076 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-20 12:39:47.047  1019  1044 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-20 12:39:47.047  1019  4082 E DropBoxManagerService: Can't write: system_app_crash
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-20 12:39:47.047  1019  4082 E DropBoxManagerService: 	... 5 more
,03-20 12:39:47.047  1019  1044 D PhoneWindow: *FMB* installDecor mIsFloating : true
03-20 12:39:47.047  1019  1044 D PhoneWindow: *FMB* installDecor flags : 8519682

```
