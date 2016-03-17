#### Test 62509094b685d58_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
03-17 12:28:20.847  2937  2937 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-17 12:28:20.847  2937  2937 E ActivityThread: Failed to find provider info for flipboard.auth.internal
--------- beginning of main
03-17 12:28:20.857  1017  1017 I DrmEventReceiver: DrmEventReceiver : onReceive
03-17 12:28:20.857  1017  1017 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-17 12:28:20.857  1017  1150 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
03-17 12:28:20.857  1017  1150 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
03-17 12:28:20.857  1017  1150 I ActivityManager: Killing 2190:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
03-17 12:28:20.867  1017  1017 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-17 12:28:20.867  1017  1017 I System.out: start Service
03-17 12:28:20.867  1017  1017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-17 12:28:20.867  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
03-17 12:28:20.867  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.867  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.867  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.867  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.877  1241  1241 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-17 12:28:20.887  2971  2971 E Zygote  : MountEmulatedStorage()
03-17 12:28:20.887  2971  2971 E Zygote  : v2
03-17 12:28:20.887  2971  2971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:20.887  2971  2971 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:20.887  2971  2971 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:20.897  2971  2971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:20.897  2971  2971 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:20.897  1017  1042 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:20.907  1017  1017 D ActivityManager: startService callerProcessName:android, calleePkgName: android
03-17 12:28:20.907  1017  1017 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
03-17 12:28:20.907  1017  1234 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
03-17 12:28:20.907  1017  1234 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
03-17 12:28:20.907  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.907  1017  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.907  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 12:28:20.907  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
03-17 12:28:20.907  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.907  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.907  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:20.907  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:20.927  2987  2987 E Zygote  : MountEmulatedStorage()
03-17 12:28:20.927  2987  2987 I libpersona: KNOX_SDCARD checking this for 10152
03-17 12:28:20.927  2987  2987 E Zygote  : v2
03-17 12:28:20.927  2987  2987 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:20.927  2987  2987 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:20.927  1017  1993 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 12:28:20.927  1017  1993 D SecContentProvider2: mCursor = null
03-17 12:28:20.927  2987  2987 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:20.927  2987  2987 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:20.927  1017  1042 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2987 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
03-17 12:28:20.937  2971  2971 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:20.937  2971  2971 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:20.937  1241  1241 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 12:28:20.947  1017  1993 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-17 12:28:20.947  1017  1993 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-17 12:28:20.957  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.957  1017  1993 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.957  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 12:28:20.957  2971  2971 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 12:28:20.957  2987  2987 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:20.957  2987  2987 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:20.967  1017  1476 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-17 12:28:20.967  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-17 12:28:20.967  2971  2971 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
03-17 12:28:20.967  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.967  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.967  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 12:28:20.977   279   509 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 1628
03-17 12:28:20.977   279   509 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 1628
03-17 12:28:20.977  1017  1041 W libprocessgroup: failed to open /acct/uid_10050/pid_2190/cgroup.procs: No such file or directory
03-17 12:28:20.977  2971  2971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
03-17 12:28:20.987  1017  1030 D ActivityManager: startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
03-17 12:28:20.987  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
03-17 12:28:20.987  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:20.987  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:20.987  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
03-17 12:28:20.987  1017  3004 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-17 12:28:20.987  1017  1017 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-17 12:28:20.997  1467  1467 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 12:28:20.997  1017  1993 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
03-17 12:28:20.997   279   279 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-17 12:28:20.997  1467  1467 D BluetoothBDTestService: onCreate()
03-17 12:28:20.997  1467  1467 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-17 12:28:20.997  1467  1467 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
03-17 12:28:21.007  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.007  1467  1467 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
03-17 12:28:21.007  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.007  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.007  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.017  3008  3008 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.017  3008  3008 E Zygote  : v2
03-17 12:28:21.017  3008  3008 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:21.017  3008  3008 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:21.017  3008  3008 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:21.027  3008  3008 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:21.027  3008  3008 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:21.037  1017  1993 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:21.037  1017  1993 I ActivityManager: Killing 2249:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
03-17 12:28:21.037  1017  1490 D ActivityManager: bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
03-17 12:28:21.037  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-17 12:28:21.037  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.037  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:21.037  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-17 12:28:21.047  1467  1467 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-17 12:28:21.047  1017  1476 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
03-17 12:28:21.047  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
03-17 12:28:21.057  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.057  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.057  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 12:28:21.057  2987  2987 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
03-17 12:28:21.057  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
03-17 12:28:21.067  3008  3008 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:21.067  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.067  3008  3008 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:21.067  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.067  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.067  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.067  1467  1467 D CscUpdateService: onStart
03-17 12:28:21.067  1467  1467 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-17 12:28:21.067  1467  1467 I CscUpdateService: set_CSC_version
03-17 12:28:21.067  1467  1467 E CscParser: update(): xml file exist
03-17 12:28:21.087  3023  3023 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.087  3023  3023 I libpersona: KNOX_SDCARD checking this for 10003
03-17 12:28:21.087  3023  3023 E Zygote  : v2
03-17 12:28:21.087  3023  3023 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:21.087  3023  3023 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:21.087  1017  1030 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3023 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-17 12:28:21.087  3023  3023 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:21.087  3023  3023 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:21.097  1241  3005 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-17 12:28:21.107  1467  1467 I CscUtil : isWifiOnly = false
03-17 12:28:21.107  1467  1467 I System.out: HandDataNode = null
03-17 12:28:21.107  1017  1150 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-17 12:28:21.107  1467  1467 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-17 12:28:21.107  1017  1150 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
03-17 12:28:21.107  1467  1467 I CscUpdateService: This is normal boot : CSC not updated
03-17 12:28:21.107  1017  1150 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.107  1017  1150 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.107  1017  1150 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 12:28:21.117  3008  3008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:21.127  1467  3038 E CscParser: update(): xml file exist
03-17 12:28:21.137  3023  3023 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:21.137  3023  3023 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:21.137  1467  3038 D CscGPS  : CSCGPS.updateParameters
03-17 12:28:21.137  1467  3038 D CscGPS  : supl host : null
03-17 12:28:21.137  1467  3038 D CscGPS  : SUPL Host is null or invalid
03-17 12:28:21.137  1467  3038 D CscGPS  : supl_ver : null
03-17 12:28:21.137  1467  3038 D CscGPS  : SUPL Ver is null or invalid
03-17 12:28:21.137  1467  3038 D CscGPS  : supl port : null
03-17 12:28:21.137  1467  3038 D CscGPS  : SUPL PORT is null or invalid
03-17 12:28:21.137  1467  3038 D CscGPS  : LPP : null
03-17 12:28:21.137  1467  3038 D CscGPS  : LPP is null or invalid
03-17 12:28:21.137  1467  3038 D CscGPS  : CSC don't have any AGPS value.
03-17 12:28:21.147  1467  1467 I CscUpdateService: same CSC Version
03-17 12:28:21.147  1467  1467 D CscUtil : Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
03-17 12:28:21.147  1017  1041 W libprocessgroup: failed to open /acct/uid_10113/pid_2249/cgroup.procs: No such file or directory
03-17 12:28:21.157  1017  1490 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
03-17 12:28:21.157  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
03-17 12:28:21.157  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.157  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.157  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
03-17 12:28:21.167  1241  1241 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-17 12:28:21.167  1467  1484 D TP/MmsProvider: Update uri=content://mms, match=0
03-17 12:28:21.167  1467  1484 D TP/MmsProvider: update , handleReadChangedBroadcast
03-17 12:28:21.167  1467  1484 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 12:28:21.177  2335  2335 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-17 12:28:21.177  1017  1342 D ActivityManager: startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
03-17 12:28:21.177  2335  2335 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 4190.443956
03-17 12:28:21.177  2335  2335 I Mms/ReservationManager: resetAfterConnected()
03-17 12:28:21.177  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.177  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.177  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.177  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.187  2335  3045 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 12:28:21.187  2335  3045 D Mms/TelephonyPermission: isDefault true
03-17 12:28:21.187  1467  1810 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2335
03-17 12:28:21.197  3048  3048 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.197  3048  3048 E Zygote  : v2
03-17 12:28:21.197  3048  3048 I libpersona: KNOX_SDCARD checking this for 1101
03-17 12:28:21.197  3048  3048 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:21.197  3048  3048 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:21.197  1017  1342 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3048 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-17 12:28:21.207  3048  3048 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:21.207  1241  3005 E SQLiteLog: (283) recovered 306 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-17 12:28:21.207  3048  3048 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:21.207  1017  1486 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 12:28:21.217  1467  1484 D TP/MmsSmsProvider: query,matched:7, calling pid = 2335
03-17 12:28:21.217  1467  1484 D TP/MmsSmsProvider: match 7:Elapsed time : 1.458 ms
03-17 12:28:21.227  1467  1482 D TP/MmsSmsProvider: query,matched:200, calling pid = 2335
03-17 12:28:21.227  2335  2335 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-17 12:28:21.227  1467  1482 D TP/MmsSmsProvider: match 200:Elapsed time : 1.672 ms
03-17 12:28:21.237  3008  3008 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
03-17 12:28:21.237  3008  3008 I KnoxUsageLogPro: premStatus:2
03-17 12:28:21.237  3006  3006 D AndroidRuntime: 
03-17 12:28:21.237  3006  3006 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 12:28:21.237  1017  1490 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
03-17 12:28:21.237  3008  3061 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458214101252
03-17 12:28:21.237  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
03-17 12:28:21.247  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.247  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.247  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-17 12:28:21.247  3008  3008 I KnoxUsageLogPro: isEulaShown : false
03-17 12:28:21.247  3006  3006 D AndroidRuntime: CheckJNI is OFF
03-17 12:28:21.247  3008  3008 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
03-17 12:28:21.247  3006  3006 D AndroidRuntime: readGMSProperty: start
03-17 12:28:21.247  3006  3006 D AndroidRuntime: readGMSProperty: already setted!!
03-17 12:28:21.247  3006  3006 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 12:28:21.247  3006  3006 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 12:28:21.247  3006  3006 D AndroidRuntime: readGMSProperty: end
03-17 12:28:21.247  3006  3006 D AndroidRuntime: addProductProperty: start
03-17 12:28:21.247  3048  3048 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:21.247  3048  3048 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:21.247  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
03-17 12:28:21.247  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.247  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.247  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.247  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.257  1467  1810 D TP/SmsProvider: query,matched:0, calling pid = 2335
03-17 12:28:21.257  1467  1810 D TP/SmsProvider: match 0:Elapsed time : 2.016 ms
03-17 12:28:21.267  3065  3065 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.267  1017  1030 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3065 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:28:21.267  3065  3065 E Zygote  : v2
03-17 12:28:21.267  3065  3065 I libpersona: KNOX_SDCARD checking this for 10085
03-17 12:28:21.267  3065  3065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:21.267  3065  3065 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:21.277  1241  3005 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 12:28:21.277  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
03-17 12:28:21.277  3065  3065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:21.277  3065  3065 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:21.277  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.277  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.277  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.277  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.287  3075  3075 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.287  3075  3075 E Zygote  : v2
03-17 12:28:21.287  3075  3075 I libpersona: KNOX_SDCARD checking this for 10048
03-17 12:28:21.287  3075  3075 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:21.297  3075  3075 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:21.297  1017  1030 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3075 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 12:28:21.297  3075  3075 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:21.297  3075  3075 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:21.307  1017  1486 I ActivityManager: Killing 1629:com.google.android.partnersetup/u0a15 (adj 15): empty #31
03-17 12:28:21.317  3008  3061 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 36607
03-17 12:28:21.327  3065  3065 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:21.327  3065  3065 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:21.337  1467  1484 D TP/SmsProvider: query,matched:51, calling pid = 2335
03-17 12:28:21.337  1467  1484 D TP/SmsProvider: match 51:Elapsed time : 1.346 ms
03-17 12:28:21.337  3075  3075 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:21.337  2335  2335 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-17 12:28:21.337  2335  3099 D Mms/TelephonyPermission: isDefault true
03-17 12:28:21.337  2335  3099 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 12:28:21.337  2335  3099 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 164.157553
03-17 12:28:21.347  3075  3075 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:21.347  3048  3048 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
03-17 12:28:21.347  2826  2958 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:28:21.357  2335  3045 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 12:28:21.367  3065  3065 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 12:28:21.367  3065  3065 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:28:21.367  1017  1490 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-17 12:28:21.367  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-17 12:28:21.367  3065  3065 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:21.367  3065  3065 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:28:21.367  3065  3065 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:21.367  3065  3065 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-17 12:28:21.377  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.377  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.377  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 12:28:21.377  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-17 12:28:21.377  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-17 12:28:21.377  3048  3048 V SmartcardService: main Received broadcast
03-17 12:28:21.377  1017  1041 W libprocessgroup: failed to open /acct/uid_10015/pid_1629/cgroup.procs: No such file or directory
03-17 12:28:21.377  3048  3048 V SmartcardService: Starting smartcard service after boot completed
03-17 12:28:21.377  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.377  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.377  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 12:28:21.377  1467  1482 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 12:28:21.377  1467  1482 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
03-17 12:28:21.387  1467  1482 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 12:28:21.387  1467  1482 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-17 12:28:21.397  2873  2886 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 12:28:21.397  1017  1030 D ActivityManager: startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
03-17 12:28:21.397  1017  1030 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
03-17 12:28:21.397  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.397  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.397  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
03-17 12:28:21.407  1467  1482 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-17 12:28:21.407  1467  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.407  1467  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.417  1467  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.417  1467  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.417  1467  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.417  1467  1482 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:21.417  3075  3075 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 12:28:21.417  3075  3075 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:21.417  3075  3075 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 12:28:21.417  1017  1395 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
03-17 12:28:21.417  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
03-17 12:28:21.417  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.417  1017  1395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.417  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 12:28:21.417  3006  3006 E AffinityControl: AffinityControl: registerfunction enter
03-17 12:28:21.417  1017  1150 D ActivityManager: startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
03-17 12:28:21.417  1467  1482 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 12:28:21.417  1467  1482 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 12:28:21.427  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.427  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.427  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.427  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.427  3023  3105 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
03-17 12:28:21.437  1492  1492 D Launcher.Model: reloadBadges entered.
03-17 12:28:21.437  2873  2886 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 12:28:21.437  2873  2886 D BadgeProvider: sendNotify, [notify] : null
03-17 12:28:21.437  2873  2886 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 12:28:21.437  2873  2886 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 12:28:21.437  2873  2886 D BadgeProvider: update, [UpdateCount] : 1
03-17 12:28:21.437  3113  3113 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.437  3113  3113 E Zygote  : v2
03-17 12:28:21.437  3113  3113 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:21.437  3113  3113 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:21.437  3113  3113 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:21.437  1017  1150 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3113 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:21.437  3113  3113 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:21.437  1017  1150 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
03-17 12:28:21.447  3113  3113 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:21.447  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.447  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.447  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.447  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.447  3006  3006 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 12:28:21.457  1017  1490 E PersonaManagerService: inState():  stateMachine is null !!
03-17 12:28:21.457  1017  1490 I PersonaManagerService: PersonaId don't exist
03-17 12:28:21.457  1017  1490 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 12:28:21.457  3128  3128 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.457  3128  3128 E Zygote  : v2
03-17 12:28:21.457  3128  3128 I libpersona: KNOX_SDCARD checking this for 10157
03-17 12:28:21.457  3128  3128 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:21.457  3128  3128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:21.467  1241  3005 V MediaScanner: processDirectory :  /system/media
03-17 12:28:21.467  3128  3128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:21.467  3128  3128 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:21.467  1017  1150 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3128 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-17 12:28:21.477  3113  3113 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:21.477  3113  3113 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:21.477  1017  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:28:21.487  1017  1490 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 12:28:21.497   301   301 I art     : Explicit concurrent mark sweep GC freed 8703(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 22.922ms
03-17 12:28:21.497  1017  1490 W ActivityManager: mDVFSHelper.acquire()
03-17 12:28:21.497  1241  3005 V MediaScanner:  prescan time: 241ms (DB items: 141)
03-17 12:28:21.497  1241  3005 V MediaScanner:     scan time: 81ms (Caching mode: true), (makeEntry time: 20ms ~24%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 12:28:21.497  1241  3005 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 12:28:21.497  1241  3005 V MediaScanner:    total time: 322ms
03-17 12:28:21.497  1241  3005 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
03-17 12:28:21.497  1017  1490 D FocusedStackFrame: Set to : 0
03-17 12:28:21.497  1241  3005 D MediaScanner: checkDefaultSounds
03-17 12:28:21.497  1241  3005 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-17 12:28:21.497  1492  1492 D Launcher.HomeView: onPause
03-17 12:28:21.497  1017  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 12:28:21.497  1017  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:28:21.497  1017  1490 D InputDispatcher: Focused application set to: xxxx
03-17 12:28:21.497  1017  1490 D InputDispatcher: Focus left window: 1492
03-17 12:28:21.507  1492  1492 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 12:28:21.507  3006  3006 D AndroidRuntime: Shutting down VM
03-17 12:28:21.507  1017  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 12:28:21.507  1017  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 12:28:21.507  2335  3099 D Mms/Conversation: deleteTempConversation(),deleted=0
03-17 12:28:21.507   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.108ms
03-17 12:28:21.507  1017  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:28:21.507  1017  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 12:28:21.517  3128  3128 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:21.517  3128  3128 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:21.517  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.517  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.517  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.517  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.517  1241  3005 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-17 12:28:21.527  1017  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 12:28:21.527  1017  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 12:28:21.527   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 18.402ms
03-17 12:28:21.527   256   256 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 12:28:21.527   294   294 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 12:28:21.537  1241  3005 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-17 12:28:21.547   311   311 I ServiceManager: Waiting for service AtCmdFwd...
03-17 12:28:21.557   275  1012 D EnterpriseController: uids 10120
03-17 12:28:21.557   275  1012 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:28:21.557   275  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10120
03-17 12:28:21.557  3150  3150 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.557  3150  3150 E Zygote  : v2
03-17 12:28:21.557  3150  3150 I libpersona: KNOX_SDCARD checking this for 10155
03-17 12:28:21.557  3150  3150 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:21.557  1017  1150 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3150 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 12:28:21.557  3150  3150 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:21.557  3150  3150 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:21.577  3023  3105 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
03-17 12:28:21.577  3150  3150 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 12:28:21.577  2335  3045 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 12:28:21.577   326   326 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 3023
03-17 12:28:21.577   326   326 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
03-17 12:28:21.587  2335  3045 D Mms/MessagingNotification: remove alarm
03-17 12:28:21.597  3023  3105 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
03-17 12:28:21.597  3023  3105 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
03-17 12:28:21.597   326   326 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 3023
03-17 12:28:21.597   326   326 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
03-17 12:28:21.607  3150  3150 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:21.607  3150  3150 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:21.617  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:21.617  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:21.617  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:21.617  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:21.617  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:21.617  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:21.627   294   294 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 12:28:21.627   294   294 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 12:28:21.627   294   294 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 12:28:21.627   294   294 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-17 12:28:21.717  3006  3006 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 12:28:21.717  1017  1486 I art     : Explicit concurrent mark sweep GC freed 138823(7MB) AllocSpace objects, 5(1830KB) LOS objects, 33% free, 26MB/39MB, paused 2.572ms total 187.005ms
,03-17 12:28:21.727  1241  3005 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-17 12:28:21.727  1241  3005 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-17 12:28:21.737  1017  3168 D SettingsProvider: name = block_emergency_message
03-17 12:28:21.737  1017  3168 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:21.737  1017  3168 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:21.737  1017  3168 D SettingsProvider: selectionArgs: false
03-17 12:28:21.737  1017  3168 D SettingsProvider: selectionArgs: 10048
03-17 12:28:21.737  1017  3168 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:21.737  1017  3168 D SettingsProvider: ret = -1
,03-17 12:28:21.737  1467  1482 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-17 12:28:21.737  1017  1342 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 12:28:21.737  1017  1342 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 12:28:21.737  1017  1342 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 12:28:21.747  1467  1482 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 12:28:21.747  3128  3128 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:21.757  1241  3005 D MediaScanner: OK. ringtone is already exist in setting DB.
,03-17 12:28:21.757  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 12:28:21.767  1017  1342 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:28:21.767  1492  1492 V ActivityThread: updateVisibility : ActivityRecord{1a94639d token=android.os.BinderProxy@13d86ebc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,03-17 12:28:21.767  1492  1492 D Launcher.HomeView: onStop
,03-17 12:28:21.767  1492  1492 V ActivityThread: updateVisibility : ActivityRecord{1a94639d token=android.os.BinderProxy@13d86ebc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,03-17 12:28:21.777  1017  1490 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,03-17 12:28:21.777  1492  1492 D Launcher: onTrimMemory. Level: 20
,03-17 12:28:21.787  1017  1486 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-17 12:28:21.787  3113  3113 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,03-17 12:28:21.787  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.787  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.787  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.787  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:21.787  1467  1482 D TP/SmsProvider: query,matched:0, calling pid = 2335
,03-17 12:28:21.797  1241  3005 D MediaScannerService: !@done scanning volume internal
,03-17 12:28:21.797  1467  1482 D TP/SmsProvider: match 0:Elapsed time : 5.992 ms
,03-17 12:28:21.807   275  1012 D EnterpriseController: uids 10120
03-17 12:28:21.807   275  1012 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:28:21.807   275  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10120
03-17 12:28:21.807  3176  3176 E Zygote  : MountEmulatedStorage()
03-17 12:28:21.807  3176  3176 I libpersona: KNOX_SDCARD checking this for 10159
03-17 12:28:21.807  3176  3176 E Zygote  : v2
03-17 12:28:21.807  3176  3176 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:21.817  3176  3176 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:21.817  3176  3176 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:21.817  3176  3176 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
03-17 12:28:21.817  1017  1486 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3176 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:21.817  1017  1486 I ActivityManager: Killing 2311:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 12:28:21.827  2335  3158 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 12:28:21.837  1241  3005 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-17 12:28:21.837  2654  2654 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2654) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 12:28:21.837  2654  2654 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2654) ACTION_MEDIA_SCANNER_FINISHED = /system/media
,03-17 12:28:21.837  2654  2654 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2654) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-17 12:28:21.837  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-17 12:28:21.847  1017  1017 D SensorService: [SO] activate (ident=0xb7be7ec0, enabled=0)
03-17 12:28:21.847  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 12:28:21.847  1017  1342 I ActivityManager: Killing 2353:com.sec.android.omc/1000 (adj 15): empty #31
03-17 12:28:21.847  2335  3099 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
,03-17 12:28:21.857  1017  1017 D SensorManager: unregisterListener ::   
,03-17 12:28:21.857  1017  1017 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-17 12:28:21.857  2335  3099 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
,03-17 12:28:21.857  1017  1017 D SensorService: [SO] changed settle time [1]
03-17 12:28:21.857  1017  1017 D SensorService: [SO] setDelay [66000000]
03-17 12:28:21.857  1017  1017 D SensorService: [SO] activate (ident=0xb7a60f78, enabled=1)
03-17 12:28:21.857  2335  3099 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-17 12:28:21.857  1017  1017 D SensorService: [SO] AR_init
03-17 12:28:21.857  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 12:28:21.857  3113  3113 D DSM     : [Lines:107] Normal booted
,03-17 12:28:21.857  3113  3113 D DSM     : [Lines:114] Boot completed
,03-17 12:28:21.867  1017  1017 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 12:28:21.867  2335  3045 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 526.042499
,03-17 12:28:21.867  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,03-17 12:28:21.867  3176  3176 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:21.867  3176  3176 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:21.877  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.877  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.877  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:21.877  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:21.877  1467  1810 D TP/SmsProvider: query,matched:26, calling pid = 2335
,03-17 12:28:21.877  1241  3005 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 12:28:21.877  1241  3005 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-17 12:28:21.887  1241  3005 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-17 12:28:21.887  1241  3005 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 12:28:21.887  1241  3005 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 12:28:21.887  1241  3005 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-17 12:28:21.887  1241  3005 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,03-17 12:28:21.887  3192  3192 E Zygote  : MountEmulatedStorage(),
03-17 12:28:21.887  3192  3192 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:21.887  3192  3192 E Zygote  : v2
03-17 12:28:21.887  3192  3192 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:21.887  3192  3192 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:21.897  3192  3192 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:21.897  3192  3192 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:21.897  1467  1810 D TP/SmsProvider: match 26:Elapsed time : 20.902 ms
03-17 12:28:21.897  1241  3005 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 12:28:21.897  1017  1029 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3192 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:21.897  1017  1029 I ActivityManager: Killing 2383:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-17 12:28:21.907  1017  1993 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
03-17 12:28:21.907  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:21.907  1017  1993 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
03-17 12:28:21.907  1017  1993 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:21.907  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,03-17 12:28:21.927  3192  3192 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:21.927  3192  3192 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:21.927  2335  3099 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 12:28:21.927  2335  3099 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 12:28:21.927  2335  3099 D Mms/TelephonyPermission: isDefault true
,03-17 12:28:21.937  3150  3150 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
03-17 12:28:21.937  1017  1039 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 12:28:21.937  1310  1310 I WifiCredService: onCreate
,03-17 12:28:21.947  1017  1150 D SettingsProvider: name = next_alarm_formatted
03-17 12:28:21.947  3150  3150 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 7315-7316)
,03-17 12:28:21.947  3150  3150 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 12:28:21.947  1017  1150 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:21.947  1017  1150 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:21.947  1017  1150 D SettingsProvider: selectionArgs: false
03-17 12:28:21.947  1017  1150 D SettingsProvider: selectionArgs: 10085
03-17 12:28:21.947  1017  1150 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:21.947  1017  1150 D SettingsProvider: ret = -1
,03-17 12:28:21.947  1467  1484 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2335
,03-17 12:28:21.957  2082  2082 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
03-17 12:28:21.957  2082  2082 I dhcpcd  : wlan0: no IPv6 Routers available
,03-17 12:28:21.957  1241  3005 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 12:28:21.967  1017  1150 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,03-17 12:28:21.977  3150  3150 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2eb9f895}
03-17 12:28:21.977  3150  3150 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 12:28:21.977  3150  3150 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 12:28:21.977  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2311/cgroup.procs: No such file or directory
03-17 12:28:21.977  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2353/cgroup.procs: No such file or directory
03-17 12:28:21.977  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2383/cgroup.procs: No such file or directory
,03-17 12:28:21.987  1310  1310 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 12:28:21.987  1310  1310 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 12:28:21.987  1310  1310 D MY_TAG  : Action boot completed received
,03-17 12:28:21.987  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:21.997  3176  3176 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
,03-17 12:28:22.007  1310  1310 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-17 12:28:22.007  1017  1039 D SensorService: [SO] 0.134 0.421 10.113
03-17 12:28:22.007  1017  1039 D SensorService: [SO] [100 -> 255]
,03-17 12:28:22.007  3150  3150 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-17 12:28:22.007  3150  3150 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:28:22.017  3150  3150 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 12:28:22.017  1017  1134 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 12:28:22.017  1017  1134 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 12:28:22.017  1017  1134 E WifiNative-wlan0: invaild command id : 215
,03-17 12:28:22.037  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-17 12:28:22.037  1017  1993 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-17 12:28:22.037  1310  2596 V NearbySettings: MountReceiver.mPrefHandler - 7002
,03-17 12:28:22.047  3192  3192 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 12:28:22.057  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:22.057  1310  1310 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,03-17 12:28:22.057  1310  1310 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-17 12:28:22.057  3150  3150 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-17 12:28:22.057  3150  3150 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,03-17 12:28:22.057  3150  3150 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,03-17 12:28:22.067  3150  3150 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
03-17 12:28:22.067  3150  3150 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:28:22.067  3150  3150 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:28:22.067  3150  3150 I Adreno-EGL: Local Branch: 
03-17 12:28:22.067  3150  3150 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:28:22.067  3150  3150 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:28:22.067  3150  3150 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 12:28:22.077  1017  3172 D SettingsProvider: name = personal_mode_enabled
,03-17 12:28:22.097  1017  1993 D ActivityManager: startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,03-17 12:28:22.097  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.097  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.097  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.097  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.107  1241  3005 V MediaScanner: processDirectory :  /storage/emulated/0,
,03-17 12:28:22.117  3217  3217 E Zygote  : MountEmulatedStorage(),
,03-17 12:28:22.117  3217  3217 E Zygote  : v2
,03-17 12:28:22.117  3217  3217 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 12:28:22.117  3217  3217 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:22.117  3217  3217 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 12:28:22.117  1017  1993 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3217 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:22.117  1017  1993 I ActivityManager: Killing 2398:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-17 12:28:22.127  3217  3217 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:22.127  3217  3217 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:22.147  3217  3217 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:22.147  3217  3217 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.157  1241  3005 D MediaScanner: Skipping:
,03-17 12:28:22.157  1241  3005 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-17 12:28:22.157  1241  3005 D MediaScanner: Skipping:
03-17 12:28:22.157  3192  3192 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 12:28:22.157  1241  3005 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,03-17 12:28:22.167  1241  3005 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 12:28:22.167  1241  3005 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 12:28:22.167  1241  3005 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-17 12:28:22.167  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-17 12:28:22.167  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,03-17 12:28:22.167  3192  3192 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,03-17 12:28:22.177  1241  3005 V MediaScanner:  prescan time: 207ms (DB items: 27)
03-17 12:28:22.177  1241  3005 V MediaScanner:     scan time: 63ms (Caching mode: true), (makeEntry time: 14ms ~22%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 12:28:22.177  1241  3005 V MediaScanner: postscan time: 6ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 12:28:22.177  1241  3005 V MediaScanner:    total time: 276ms
03-17 12:28:22.177  1241  3005 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-17 12:28:22.187  3065  3065 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 188.978ms
,03-17 12:28:22.197  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-17 12:28:22.207  1467  1467 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 12:28:22.207  1467  1467 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 12:28:22.207  1467  1467 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 12:28:22.207  1467  1467 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 12:28:22.207  1467  1467 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 12:28:22.207  1467  1467 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-17 12:28:22.217  3192,  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-17 12:28:22.217  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,03-17 12:28:22.227  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 12:28:22.227  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-17 12:28:22.227  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 12:28:22.227  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 12:28:22.227  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 12:28:22.227  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-17 12:28:22.227  3192  3192 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 12:28:22.227  3192  3192 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,03-17 12:28:22.257  1017  1098 V AlarmManager: waitForAlarm result :8
,03-17 12:28:22.257  1467  1482 I art     : Explicit concurrent mark sweep GC freed 40097(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 8MB/13MB, paused 1.162ms total 217.508ms
,03-17 12:28:22.257  1467  1482 D TP/MmsSmsProvider: query,matched:200, calling pid = 2335
,03-17 12:28:22.257  1467  1482 D TP/MmsSmsProvider: match 200:Elapsed time : 1.584 ms
,03-17 12:28:22.267  1017  1041 W libprocessgroup: failed to open /acct/uid_10131/pid_2398/cgroup.procs: No such file or directory
,03-17 12:28:22.307   326   326 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,03-17 12:28:22.307   256  1057 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-17 12:28:22.307  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
03-17 12:28:22.307   256   434 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
03-17 12:28:22.317  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.317  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.317  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.317  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.317  1241  3005 D MediaScannerService: !@done scanning volume external
,03-17 12:28:22.327  3241  3241 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.327  3241  3241 I libpersona: KNOX_SDCARD checking this for 10160
03-17 12:28:22.327  3241  3241 E Zygote  : v2
03-17 12:28:22.327  3241  3241 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:22.327  3241  3241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:22.337  1017  1491 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3241 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 12:28:22.337  3241  3241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:22.337  1017  1491 I ActivityManager: Killing 2305:com.sec.android.app.mt/1000 (adj 15): empty #31
03-17 12:28:22.337  3241  3241 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:22.337  2654  2654 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2654) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 12:28:22.337  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
03-17 12:28:22.337  2654  2654 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2654) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 12:28:22.337  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.337  2654  2654 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2654) ...
03-17 12:28:22.337  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.337  2654  2654 D FactoryTestApp: [Support$Values.getString](2654) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 12:28:22.347  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.337  2654  2654 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2654) mConnectionMode = gsm
03-17 12:28:22.347  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.347  2654  2654 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2654) Create IPCWriterToSecPhoneService
,03-17 12:28:22.347  2654  2654 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2654)  
,03-17 12:28:22.347  2654  2654 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-17 12:28:22.357  3241  3241 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:22.357  3257  3257 E Zygote  : MountEmulatedStorage(),
03-17 12:28:22.357  3257  3257 E Zygote  : v2
03-17 12:28:22.357  3257  3257 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:22.357  3257  3257 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:22.357  3257  3257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:22.357  3023  3105 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,03-17 12:28:22.367  3023  3105 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,03-17 12:28:22.367  3241  3241 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:22.367  3257  3257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:22.367  2692  2783 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-17 12:28:22.367  3257  3257 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:22.367  1017  1491 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3257 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:22.367  1017  1491 I ActivityManager: Killing 2443:com.wsomacp/u0a25 (adj 15): empty #31
,03-17 12:28:22.377  1310  1310 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 12:28:22.377  1310  1310 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-17 12:28:22.377  1017  1098 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:22.377  1017  3168 D ActivityManager: bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
,03-17 12:28:22.377  1017  3168 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-17 12:28:22.377  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:22.377  1017  3168 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:22.377  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-17 12:28:22.407  1310  1310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:28:22.417  1310  1310 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-17 12:28:22.417  3257  3257 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:22.417  3257  3257 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.427  3241  3241 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 12:28:22.437  2654  2654 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2654) connected done
03-17 12:28:22.447  2654  2654 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2654) Send Response Message to SecPhone
03-17 12:28:22.447  2654  2654 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2654) Response ��
,03-17 12:28:22.457  2692  2783 D BluetoothMediaBrowser: no now playing list
,03-17 12:28:22.457  2692  2783 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-17 12:28:22.467  1467  1484 D TP/SmsProvider: query,matched:0, calling pid = 2335
,03-17 12:28:22.467  1467  1484 D TP/SmsProvider: match 0:Elapsed time : 1.512 ms
,03-17 12:28:22.477   306  1075 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 12:28:22.477  2654  2654 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2654) Send BOOTING COMPLETED done
,03-17 12:28:22.497  1467  1810 D TP/SmsProvider: query,matched:51, calling pid = 2335
,03-17 12:28:22.497  1467  1810 D TP/SmsProvider: match 51:Elapsed time : 1.257 ms
,03-17 12:28:22.497  2335  3099 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 12:28:22.507  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2305/cgroup.procs: No such file or directory
03-17 12:28:22.507  1017  1041 W libprocessgroup: failed to open /acct/uid_10025/pid_2443/cgroup.procs: No such file or directory
,03-17 12:28:22.517  2873  3159 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 12:28:22.517  3150  3238 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-17 12:28:22.537   286   286 E SMD     : DCD OFF,
,03-17 12:28:22.557   311   311 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:28:22.577   306  1075 D AT_Distributor: SetAtdStatus(), 1_1_0,
03-17 12:28:22.577   306  1075 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 12:28:22.587  3257  3257 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 12:28:22.607  3150  3150 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:28:22.607  1310  1310 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-17 12:28:22.627  3241  3241 D [0]UMC:UMCContentProvider: @onCreate
,03-17 12:28:22.637  3241  3241 D [0]UMC:Core: onCreate(): 
,03-17 12:28:22.637  3241  3241 D [0]UMC:Core: @isManagedProfileUser
,03-17 12:28:22.637  3241  3241 D [0]UMC:Core: userId: 0
,03-17 12:28:22.637  3241  3241 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
,03-17 12:28:22.637  3241  3241 D [0]UMC:Core: userInfo.isManagedProfile() : false
,03-17 12:28:22.647  3150  3150 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 12:28:22.657  1310  1310 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
,03-17 12:28:22.657  1310  1310 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-17 12:28:22.657  3150  3150 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-17 12:28:22.657  3150  3150 D PhoneWindow: *FMB* installDecor flags : -2139027200
03-17 12:28:22.657  1310  1310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-17 12:28:22.657  3150  3150 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-17 12:28:22.667  1310  3285 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-17 12:28:22.667  3150  3150 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:28:22.667  3150  3150 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:28:22.667  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,03-17 12:28:22.667  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.667  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.667  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.677  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.687  3287  3287 E Zygote  : MountEmulatedStorage()
,03-17 12:28:22.687  3287  3287 E Zygote  : v2
03-17 12:28:22.687  3287  3287 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:22.687  3287  3287 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:22.687  3287  3287 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:22.687  1017  1030 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3287 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 12:28:22.687  3287  3287 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:22.697  3287  3287 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:22.697  1017  1395 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,03-17 12:28:22.697  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 12:28:22.697  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 12:28:22.697  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.697  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:22.707  3298  3298 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.707  3298  3298 E Zygote  : v2
03-17 12:28:22.707  3298  3298 I libpersona: KNOX_SDCARD checking this for 10150
03-17 12:28:22.707  3298  3298 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:22.717  3298  3298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:22.717  1017  1395 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3298 uid=10150 gids={50150, 9997} abi=armeabi-v7a,
03-17 12:28:22.717  3241  3241 D [0]UMC:DeviceInfo: USA==US==,
03-17 12:28:22.717  3287  3287 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 12:28:22.717  3298  3298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:22.717  3287  3287 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.717  3298  3298 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 12:28:22.747  3298  3298 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:22.747  3287  3287 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:22.747  3298  3298 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:22.757  3150  3320 D OpenGLRenderer: Render dirty regions requested: true
,03-17 12:28:22.757  1017  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 12:28:22.757  1017  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 12:28:22.757  1017  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 12:28:22.757  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 12:28:22.757  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 12:28:22.777  3150  3150 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-17 12:28:22.777  3150  3150 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 12:28:22.777   256   256 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 12:28:22.787  1017  1342 D InputDispatcher: Focus entered window: 3150
,03-17 12:28:22.797  1017  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:28:22.797  1017  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 12:28:22.797  3150  3150 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
03-17 12:28:22.797  3150  3320 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 12:28:22.807  3150  3320 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 12:28:22.807  3150  3320 D OpenGLRenderer: Enabling debug mode 0
,03-17 12:28:22.817  2873  2888 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
,03-17 12:28:22.817  1492  1492 D Launcher.Model: reloadBadges entered.
,03-17 12:28:22.817  2873  2888 D BadgeProvider: sendNotify, [notify] : null
03-17 12:28:22.817  2873  2888 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 12:28:22.817  2873  2888 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 12:28:22.817  2873  2888 D BadgeProvider: update, [UpdateCount] : 1
,03-17 12:28:22.817  2335  3099 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 12:28:22.827  2335  3099 D Mms/MessagingNotification: remove alarm
,03-17 12:28:22.827  2335  3322 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 12:28:22.837  1467  1810 D TP/SmsProvider: query,matched:0, calling pid = 2335
,03-17 12:28:22.837  1467  1810 D TP/SmsProvider: match 0:Elapsed time : 2.553 ms
,03-17 12:28:22.847  2335  3099 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 975.31901
,03-17 12:28:22.857  1017  3168 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 12:28:22.857  1191  1191 D PanelView: There is/are notification(s) 
,03-17 12:28:22.867  1017  1049 I ActivityManager: Displayed Component not be shown by security: +1s347ms
,03-17 12:28:22.867  1017  1049 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 12:28:22.867  1017  1042 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 12:28:22.867  1017  1049 D CustomFrequencyManagerService: FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,03-17 12:28:22.867  1017  3324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:28:22.867  1017  1049 W ActivityManager: mDVFSHelper.release()
03-17 12:28:22.867  1017  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2901bd43 u0 com.test.thalitest/.MainActivity t12} time:38236
,03-17 12:28:22.877  1814  1814 I SamsungIME: getCurrentCandidateView
,03-17 12:28:22.877  3150  3150 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3e43ad26 time:38244
,03-17 12:28:23.057  3241  3241 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-17 12:28:23.067  3241  3241 D [0]UMC:AdminManager: init - start
,03-17 12:28:23.077   256  3194 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 12:28:23.077   256   437 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 12:28:23.097  3287  3287 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 12:28:23.107  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,03-17 12:28:23.107  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.107  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.107  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.107  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.117  3241  3241 D [0]UMC:AdminManager: loadAdmins,
,03-17 12:28:23.127  3328  3328 E Zygote  : MountEmulatedStorage()
03-17 12:28:23.127  3328  3328 E Zygote  : v2
03-17 12:28:23.127  3328  3328 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:23.127  3328  3328 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:23.127  3328  3328 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:23.127  3328  3328 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:23.127  3328  3328 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:23.127  1017  1029 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3328 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:23.137  1017  1029 I ActivityManager: Killing 2523:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31,
,03-17 12:28:23.147  1814  1814 D SamsungIME: Dismiss ExpandCandiate
,03-17 12:28:23.157  3328  3328 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:23.157  3328  3328 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:23.167  1017  1017 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 12:28:23.167  3241  3241 D [0]UMC:AdminManager: init - end
,03-17 12:28:23.167  3241  3241 D GSLBManager: migrateStoredUrlFromOldPref
,03-17 12:28:23.177  3241  3241 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-17 12:28:23.177  3241  3241 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 12:28:23.187  3328  3328 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:28:23.197  3257  3257 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 12:28:23.197  3241  3241 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 12:28:23.197  3241  3241 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 12:28:23.197  3241  3241 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 12:28:23.197  3241  3241 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 12:28:23.217  3257  3257 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 12:28:23.217  1017  1030 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 12:28:23.227  3241  3241 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 12:28:23.227  3241  3241 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 12:28:23.237  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,03-17 12:28:23.237  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.237  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.237  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.237  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.247  3023  3023 E BluetoothHeadset: BTStateChangeCB is registed,
03-17 12:28:23.247  3287  3287 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 12:28:23.247  3023  3023 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-17 12:28:23.247  3348  3348 E Zygote  : MountEmulatedStorage()
03-17 12:28:23.247  3348  3348 E Zygote  : v2
,03-17 12:28:23.257  3348  3348 I libpersona: KNOX_SDCARD checking this for 10086
03-17 12:28:23.257  3348  3348 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:23.257  1017  1491 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3348 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a,
03-17 12:28:23.257  1017  1491 I ActivityManager: Killing 2541:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
03-17 12:28:23.257  3348  3348 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:23.257  3257  3257 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 12:28:23.257  3348  3348 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:23.267  3348  3348 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:23.267  3241  3241 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 12:28:23.267  3257  3257 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-17 12:28:23.267  3257  3257 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-17 12:28:23.267  3257  3257 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
03-17 12:28:23.267  3287  3287 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-17 12:28:23.267  1017  1490 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,03-17 12:28:23.267  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-17 12:28:23.267  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.267  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:23.267  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 12:28:23.267  3023  3023 E BluetoothHeadset: BluetoothHeadset service is binded
,03-17 12:28:23.277  3287  3287 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 12:28:23.277  1017  1476 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
,03-17 12:28:23.277  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 12:28:23.277  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:23.277  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:23.277  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 12:28:23.287  3241  3241 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-17 12:28:23.287  3023  3023 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-17 12:28:23.297  1017  1486 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,03-17 12:28:23.297  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-17 12:28:23.297  3241  3241 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 12:28:23.297  3241  3241 D [0]UMC:CoreReceiver:  check PreETag 
,03-17 12:28:23.297  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.297  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:23.297  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 12:28:23.297  3348  3348 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:23.297  3348  3348 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:23.307  3150  3150 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3150
,03-17 12:28:23.337  1017  1491 I ActivityManager: Killing 2574:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 12:28:23.347  3241  3241 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-17 12:28:23.347  3241  3241 V [0]UMC:ProfileStorage: Enter loadList
,03-17 12:28:23.347  3241  3241 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
,03-17 12:28:23.347  3241  3241 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 12:28:23.347  3241  3241 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 12:28:23.347  3241  3241 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,03-17 12:28:23.347  3241  3241 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
,03-17 12:28:23.347  3241  3241 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 12:28:23.367  1017  1476 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 12:28:23.367  3241  3241 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 12:28:23.367  3241  3241 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 12:28:23.367  3241  3241 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 12:28:23.387  3241  3241 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-17 12:28:23.387  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,03-17 12:28:23.387  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.397  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.397  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.397  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 12:28:23.407  3373  3373 E Zygote  : MountEmulatedStorage()
03-17 12:28:23.407  3373  3373 E Zygote  : v2
03-17 12:28:23.407  3373  3373 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:23.407  3373  3373 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:23.407  3373  3373 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:23.417  3373  3373 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:23.417  1017  1029 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3373 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:23.417  3373  3373 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:23.417  3241  3241 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
03-17 12:28:23.417  3241  3241 I [0]UMC:Core: shutdown
,03-17 12:28:23.417  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 12:28:23.417  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.417  1017  1395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:23.417  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 12:28:23.417  3241  3241 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-17 12:28:23.427  3241  3241 I art     : System.exit called, status: 0
,03-17 12:28:23.427   301   301 I art     : Explicit concurrent mark sweep GC freed 8775(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 655us total 21.360ms
,03-17 12:28:23.437  3241  3241 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-17 12:28:23.437  1017  1041 W libprocessgroup: failed to open /acct/uid_10088/pid_2523/cgroup.procs: No such file or directory
,03-17 12:28:23.447  3373  3373 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:23.447   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.325ms total 17.920ms
03-17 12:28:23.447  3373  3373 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:23.457  1017  1041 W libprocessgroup: failed to open /acct/uid_10142/pid_2541/cgroup.procs: No such file or directory
03-17 12:28:23.457  1017  1041 W libprocessgroup: failed to open /acct/uid_10139/pid_2574/cgroup.procs: No such file or directory
,03-17 12:28:23.467   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 17.257ms
,03-17 12:28:23.477  1017  1490 E Tethering: No numeric data
,03-17 12:28:23.477  1017  1491 E Tethering: No numeric data
,03-17 12:28:23.487  1017  1395 E Tethering: No numeric data
,03-17 12:28:23.487  1017  1234 E Tethering: No numeric data
,03-17 12:28:23.487  1017  1993 E Tethering: No numeric data
,03-17 12:28:23.497  3023  3023 D BluetoothA2dp: Proxy object connected
,03-17 12:28:23.497  3287  3287 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 12:28:23.497  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 12:28:23.497  3287  3287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 12:28:23.497  1017  3168 E Tethering: No numeric data
,03-17 12:28:23.507  1017  1150 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
03-17 12:28:23.507  1017  1150 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 12:28:23.507  1017  1150 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.507  1017  1150 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:23.507  1017  1150 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 12:28:23.517  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 12:28:23.517  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-17 12:28:23.517  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 12:28:23.527  1191  1191 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-17 12:28:23.527  1191  1191 D OverheatReceiver: into the SAFE_MODE_ACTION
,03-17 12:28:23.527  3150  3150 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-17 12:28:23.527  1191  1191 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
03-17 12:28:23.527  1191  1191 D OverheatReceiver: isSafeMode = false
,03-17 12:28:23.527  1017  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:23.527  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.527  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:23.527  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 12:28:23.527  3348  3348 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:23.537  1467  1467 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-17 12:28:23.537  1017  1490 D SettingsProvider: name = internet_call_settings_visibility
03-17 12:28:23.537  1017  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:23.537  1017  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:23.537  1017  1490 D SettingsProvider: selectionArgs: false
03-17 12:28:23.537  1017  1490 D SettingsProvider: selectionArgs: 1001
03-17 12:28:23.537  1017  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:23.537  1017  1490 D SettingsProvider: ret = -1
,03-17 12:28:23.537  1467  1467 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 12:28:23.547  3348  3348 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:23.547  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 12:28:23.547  1440  1440 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 12:28:23.547  1017  1395 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
,03-17 12:28:23.547  3287  3287 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-17 12:28:23.547  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-17 12:28:23.547  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.547  1017  1395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:23.547  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 12:28:23.547  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-17 12:28:23.557   311   311 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 12:28:23.557  1017  1030 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
,03-17 12:28:23.557  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-17 12:28:23.557  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:23.557  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:23.557  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 12:28:23.557  1017  1486 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-17 12:28:23.557  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.557  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.557  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.557  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.567  3287  3287 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-17 12:28:23.567  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-17 12:28:23.567  3287  3287 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-17 12:28:23.567  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-17 12:28:23.567  3287  3287 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-17 12:28:23.577  3287  3287 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-17 12:28:23.577  3287  3345 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
03-17 12:28:23.577  3396  3396 E Zygote  : MountEmulatedStorage()
03-17 12:28:23.577  3396  3396 E Zygote  : v2
03-17 12:28:23.577  3396  3396 I libpersona: KNOX_SDCARD checking this for 10057
03-17 12:28:23.577  3396  3396 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:23.577  3396  3396 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:23.587  3396  3396 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:23.587  1017  1486 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3396 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
03-17 12:28:23.587  3396  3396 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 12:28:23.587  3287  3287 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
03-17 12:28:23.597  3287  3287 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
03-17 12:28:23.597  3287  3287 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
03-17 12:28:23.597  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 12:28:23.607  3348  3348 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:23.607  3396  3396 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:23.607  3396  3396 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:23.617  3348  3348 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:23.627  1017  1150 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3241)(adj 0) has died(225,1060)
,03-17 12:28:23.637  1017  1342 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-17 12:28:23.637  3348  3348 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:23.637  3287  3345 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 12:28:23.637  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.637  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.637  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:23.637  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.657  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:23.657  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 12:28:23.657  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:23.657  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:23.667  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!,
,03-17 12:28:23.667  1814  1814 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 12:28:23.667  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 12:28:23.667  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 12:28:23.677  3418  3418 E Zygote  : MountEmulatedStorage()
03-17 12:28:23.677  3418  3418 E Zygote  : v2
03-17 12:28:23.677  3418  3418 I libpersona: KNOX_SDCARD checking this for 10009
03-17 12:28:23.677  3418  3418 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:23.687  1017  1342 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3418 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:23.687  3418  3418 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:23.687  3418  3418 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:23.687  3418  3418 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 12:28:23.697  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-17 12:28:23.697  1329  1329 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 12:28:23.697  1329  1329 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 12:28:23.697  1329  1329 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 12:28:23.697  1329  1329 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 12:28:23.697  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 12:28:23.697  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-17 12:28:23.707  3287  3345 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-17 12:28:23.707  3418  3418 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:23.707  3418  3418 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:23.737  1440  1440 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 12:28:23.747  1017  1030 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
,03-17 12:28:23.747  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 12:28:23.747  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:23.747  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:23.747  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 12:28:23.757  1017  1486 D SettingsProvider: name = aw_daemon_service_key_version_check
,03-17 12:28:23.767  1017  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:23.767  1017  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:23.767  1017  1486 D SettingsProvider: selectionArgs: false
03-17 12:28:23.767  1017  1486 D SettingsProvider: selectionArgs: 10162
03-17 12:28:23.767  1017  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:23.767  1017  1486 D SettingsProvider: ret = -1
,03-17 12:28:23.767  3348  3348 E UpdateRequestReceiver: ignoring update request
,03-17 12:28:23.767  1017  1993 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,03-17 12:28:23.777  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.777  1814  1814 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 12:28:23.777  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.777  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.777  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:23.797  3437  3437 E Zygote  : MountEmulatedStorage(),
03-17 12:28:23.797  3437  3437 E Zygote  : v2,
,03-17 12:28:23.797  3437  3437 I libpersona: KNOX_SDCARD checking this for 10092
03-17 12:28:23.797  3437  3437 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:23.797  3437  3437 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:23.797  1017  1486 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162,
03-17 12:28:23.797  1017  1993 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3437 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:23.797  1814  1814 I SamsungIME: KeybaordView init() : load resources
,03-17 12:28:23.797  3437  3437 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:23.807  1017  1993 I ActivityManager: Killing 2479:com.example.hello/u0a174 (adj 15): empty #31
03-17 12:28:23.807  3437  3437 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 12:28:23.807  1017  1234 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:23.817  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 12:28:23.827  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:23.827  1017  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:23.827  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:23.837  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:23.847  3287  3287 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 12:28:23.857  3437  3437 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:23.857  3437  3437 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:23.867  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 12:28:23.887  3150  3327 D jxcore_app_log: JniHelper::setJavaVM(0xb72b2450), pthread_self() = -1216255224
,03-17 12:28:23.887   280   984 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-17 12:28:23.887   280   984 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 12:28:23.887   280   984 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 12:28:23.887   280   984 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 12:28:23.887   280   984 I str_params: key: 'call_forwarding' value: ''
,03-17 12:28:23.887  1963  1963 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 12:28:23.887  1963  1963 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-17 12:28:23.897  1963  1963 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 12:28:23.897  3287  3287 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 12:28:23.897  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:23.897  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 12:28:23.897  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 12:28:23.897  1963  1963 D ScoverManager: serviceVersion : 16908288
,03-17 12:28:23.897  1017  1486 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 12:28:23.897  1963  1963 D InCall  : InCallUtils - isCoverClosed false
,03-17 12:28:23.897  1017  1476 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH,
,03-17 12:28:23.907  1963  1963 D InCall  : InCallUtils - isCoverClosed false
,03-17 12:28:23.907  1963  1963 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 12:28:23.907  1963  1963 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-17 12:28:23.907  1963  1963 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 12:28:23.907  1440  1440 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-17 12:28:23.907  3150  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 12:28:23.907  3150  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 12:28:23.907  3150  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 12:28:23.907  3150  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 12:28:23.907  3150  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 12:28:23.907  3150  3327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@effce2d added. We now have 1 listener(s)
,03-17 12:28:23.917  1310  3285 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 12:28:23.917  1963  1963 I InCall  : CallSContextMotion - stopPutDownListening
,03-17 12:28:23.917  1963  1963 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 12:28:23.917  3150  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-17 12:28:23.917  3150  3327 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,03-17 12:28:23.917  3150  3327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
03-17 12:28:23.917  3150  3327 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 12:28:23.917  3150  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 12:28:23.927  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 12:28:23.927  1191  1191 D PhoneStatusBarView: setCallBackground:0
,03-17 12:28:23.937  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 12:28:23.937  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 12:28:23.937  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 12:28:23.937  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-17 12:28:23.937  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 12:28:23.937  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 12:28:23.937  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 12:28:23.937  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 12:28:23.937  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 12:28:23.937  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-17 12:28:23.937  1310  3285 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 12:28:23.957  3150  3327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@942f9b0 added. We now have 1 listener(s)
,03-17 12:28:23.957  3150  3327 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 12:28:23.957  1017  3168 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 12:28:23.957  1963  1963 D InCall  : InCallUtils - isCoverClosed false
,03-17 12:28:23.957  3373  3373 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-17 12:28:23.957  3373  3373 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 12:28:23.957  1329  1329 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 12:28:23.967  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:23.977  3150  3327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 12:28:23.977  3150  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 12:28:23.977  3150  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 12:28:23.977  3150  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 12:28:23.977  3150  3327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 12:28:23.977  3150  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 12:28:23.977  3150  3327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-17 12:28:24.007  3150  3327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 12:28:24.007  3150  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 12:28:24.007  3150  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 12:28:24.007  3150  3327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 12:28:24.007  3150  3327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 12:28:24.007  3150  3327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 12:28:24.007  3150  3327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 12:28:24.007  3150  3327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 12:28:24.007  3150  3327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-17 12:28:24.017  3150  3327 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 12:28:24.017  1017  1041 W libprocessgroup: failed to open /acct/uid_10174/pid_2479/cgroup.procs: No such file or directory
,03-17 12:28:24.017  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458214103975
,03-17 12:28:24.017  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458226200000
03-17 12:28:24.017  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 12:28:24.017  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-17 12:28:24.027  1329  1329 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458226200000
,03-17 12:28:24.027  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-17 12:28:24.027  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458226200000
,03-17 12:28:24.067  3373  3373 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-17 12:28:24.077  3373  3373 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 12:28:24.097  1017  2782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 12:28:24.097  1017  1490 I art     : Explicit concurrent mark sweep GC freed 19043(955KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 3.213ms total 242.584ms
,03-17 12:28:24.097  3150  3150 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:28:24.107  3150  3150 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:28:24.117  3150  3150 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 12:28:24.127  3373  3434 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 12:28:24.127  1963  1963 D VideoCallManager: Instantiating VideoCallManager
,03-17 12:28:24.137  1329  1329 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-17 12:28:24.137  1329  1329 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 12:28:24.137  1963  1963 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 12:28:24.137  1963  1963 I GFX construct_block_size_descriptor_2d second part: took 2.135417ms for 0*0 texture 0
,03-17 12:28:24.137  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-17 12:28:24.147  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.147  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.147  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.147  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.147  1963  1963 I GFX generate_partition_tables: took 5.139792ms for 0*0 texture 0
,03-17 12:28:24.147  1963  1963 I GFX raster: took 11.127761ms for 176*144 texture 0,
,03-17 12:28:24.147  1963  1963 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb767bd68 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7693f78 counterpartCT=4 counterpartW=176 counterparth=144
03-17 12:28:24.157  1963  1963 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
03-17 12:28:24.157  1963  1963 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 12:28:24.157  1963  1963 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:28:24.157  1963  1963 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:28:24.157  1963  1963 I Adreno-EGL: Local Branch: 
03-17 12:28:24.157  1963  1963 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:28:24.157  1963  1963 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:28:24.157  1963  1963 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 12:28:24.167  3460  3460 E Zygote  : MountEmulatedStorage()
03-17 12:28:24.167  3460  3460 I libpersona: KNOX_SDCARD checking this for 10166
03-17 12:28:24.167  3460  3460 E Zygote  : v2
03-17 12:28:24.167  3460  3460 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:24.167  3460  3460 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:24.167  1017  1476 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3460 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:24.167  3460  3460 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:24.177  3460  3460 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:24.187  1963  1963 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 12:28:24.187  1963  1963 I glCompressedTexImage2D: took 0.465416ms for 320*61440 texture 37809
,03-17 12:28:24.207  1963  1963 I draw setup: took 12.086718ms for 320*240 texture 37809
,03-17 12:28:24.207  1963  1963 E GFX GPU raster: drawn
,03-17 12:28:24.207  1963  1963 I GFX GPU raster ASTC: took 42.107083ms for 320*240 texture 12
,03-17 12:28:24.207  1963  1963 I GFX raster: took 42.239635ms for 320*240 texture 0
03-17 12:28:24.207  1963  1963 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7693f78 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb76962b8 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 12:28:24.217  3460  3460 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:24.217  3460  3460 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:24.217  1017  1395 I ActivityManager: Killing 2598:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-17 12:28:24.227  3373  3373 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 12:28:24.237  3373  3373 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 12:28:24.237  1963  1963 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 12:28:24.237  1963  1963 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 12:28:24.237  3373  3373 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-17 12:28:24.237  3373  3373 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
03-17 12:28:24.237  1963  1963 I glCompressedTexImage2D: took 0.499844ms for 480*122880 texture 37813
03-17 12:28:24.237  1963  1963 I draw setup: took 1.034531ms for 480*640 texture 37813
03-17 12:28:24.237  1963  1963 E GFX GPU raster: drawn
,03-17 12:28:24.257  1963  1963 I GFX GPU raster ASTC: took 6.965156ms for 480*640 texture 12
03-17 12:28:24.257  1963  1963 I GFX raster: took 7.046146ms for 480*640 texture 0
03-17 12:28:24.257  1963  1963 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76962b8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb78c4748 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 12:28:24.257  3373  3373 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-17 12:28:24.287  3150  3167 I art     : Background sticky concurrent mark sweep GC freed 24658(1762KB) AllocSpace objects, 9(140KB) LOS objects, 7% free, 10MB/11MB, paused 1.189ms total 113.895ms
,03-17 12:28:24.287  3373  3434 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-17 12:28:24.307  1963  1963 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 12:28:24.307  1963  1963 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS,
,03-17 12:28:24.307  1963  1963 I glCompressedTexImage2D: took 0.431145ms for 440*116864 texture 37809
03-17 12:28:24.307  1963  1963 I draw setup: took 0.811145ms for 440*330 texture 37809
03-17 12:28:24.307  1963  1963 E GFX GPU raster: drawn
,03-17 12:28:24.307  1963  1963 I GFX GPU raster ASTC: took 4.491459ms for 440*330 texture 12
03-17 12:28:24.307  1963  1963 I GFX raster: took 4.580782ms for 440*330 texture 0
03-17 12:28:24.307  1963  1963 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb78c4748 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb78d8b38 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 12:28:24.337  1017  1491 E Tethering: No numeric data
,03-17 12:28:24.337  1017  1150 E Tethering: No numeric data
,03-17 12:28:24.337  1017  1029 E Tethering: No numeric data
,03-17 12:28:24.357  1963  1963 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 12:28:24.357  1963  1963 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 12:28:24.357  1963  1963 I glCompressedTexImage2D: took 0.409896ms for 480*163840 texture 37811
03-17 12:28:24.357  1963  1963 I draw setup: took 0.900313ms for 480*640 texture 37811
03-17 12:28:24.357  1963  1963 E GFX GPU raster: drawn
,03-17 12:28:24.367  1963  1963 I GFX GPU raster ASTC: took 5.720990ms for 480*640 texture 12
03-17 12:28:24.367  1963  1963 I GFX raster: took 5.801667ms for 480*640 texture 0
03-17 12:28:24.367  1963  1963 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb78c8948 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb78d8670 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 12:28:24.367  1814  1814 I SamsungIME: getCurrentKeyboard
03-17 12:28:24.367  1814  1814 I SamsungIME: getTextKeyboard
,03-17 12:28:24.387  3287  3345 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 12:28:24.407  1017  1476 E Tethering: No numeric data
,03-17 12:28:24.447  1963  1963 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 12:28:24.447  1963  1963 I GFX construct_block_size_descriptor_2d second part: took 2.057500ms for 0*0 texture 0
,03-17 12:28:24.447  3373  3434 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-17 12:28:24.457  1963  1963 I GFX generate_partition_tables: took 7.396250ms for 0*0 texture 0
,03-17 12:28:24.457  1963  1963 I GFX raster: took 11.396614ms for 176*144 texture 0
03-17 12:28:24.457  1963  1963 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb78c2008 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb78c2128 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 12:28:24.477  1017  1041 W libprocessgroup: failed to open /acct/uid_10068/pid_2598/cgroup.procs: No such file or directory
,03-17 12:28:24.537  1017  1150 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-17 12:28:24.537  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.537  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.537  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 12:28:24.547  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.557  3484  3484 E Zygote  : MountEmulatedStorage(),
03-17 12:28:24.557  3484  3484 E Zygote  : v2
03-17 12:28:24.557  3484  3484 I libpersona: KNOX_SDCARD checking this for 10015
03-17 12:28:24.557  3484  3484 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:24.557  3484  3484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:24.557  3484  3484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:24.557  3484  3484 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:24.557  1017  1150 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3484 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-17 12:28:24.587  3484  3484 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:24.587  3484  3484 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:24.597  1017  1490 D LocationManagerService: getProviders()=[passive]
,03-17 12:28:24.617  1017  2857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:28:24.627  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:24.627  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:24.627  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:24.627  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:24.627  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:24.627  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:24.647  1963  1963 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 12:28:24.647  1963  1963 I GFX construct_block_size_descriptor_2d second part: took 2.756198ms for 0*0 texture 0
,03-17 12:28:24.657  1963  1963 I GFX generate_partition_tables: took 6.386354ms for 0*0 texture 0
,03-17 12:28:24.667  1963  1963 I GFX raster: took 11.703648ms for 176*144 texture 0
03-17 12:28:24.667  1814  1814 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 12:28:24.667  1963  1963 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb78c2348 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb78c22e8 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 12:28:24.667  1963  1963 D ScoverManager: registerListener
,03-17 12:28:24.667  1017  1342 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 12:28:24.677  1017  1993 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 12:28:24.677  1017  1993 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@2ca40270, pid : 1963, uid : 1001, type : 1
,03-17 12:28:24.687  1963  1963 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 12:28:24.717  1017  1342 V VibratorService: hasVibrator - useVibetonz: true
,03-17 12:28:24.727  1310  3285 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 12:28:24.727  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,03-17 12:28:24.727  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.727  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.727  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.727  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.737  1017  3172 V VibratorService: hasVibrator - useVibetonz: true
,03-17 12:28:24.737  1017  1029 V VibratorService: hasVibrator - useVibetonz: true
,03-17 12:28:24.747  3511  3511 E Zygote  : MountEmulatedStorage()
,03-17 12:28:24.747  3511  3511 E Zygote  : v2
03-17 12:28:24.747  3511  3511 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:24.747  3511  3511 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:24.747  3511  3511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:24.757  3511  3511 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:24.757  3511  3511 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 12:28:24.767  1017  1030 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3511 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:24.767  1310  3285 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:28:24.767  1017  1030 I ActivityManager: Killing 2458:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
03-17 12:28:24.767  1017  1030 I ActivityManager: Killing 2614:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #32
,03-17 12:28:24.787  3511  3511 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:24.797  3511  3511 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:24.857  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-17 12:28:24.857  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-17 12:28:24.857  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:24.857  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:24.857  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 12:28:24.867  3460  3498 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:28:24.867  3460  3498 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:28:24.877  1017  1030 I ActivityManager: Killing 2673:com.android.calendar/u0a135 (adj 15): empty #31
,03-17 12:28:24.887  1017  1150 I ActivityManager: Killing 2712:com.android.keychain/1000 (adj 15): empty #31
,03-17 12:28:24.897  1017  1490 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
,03-17 12:28:24.897  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-17 12:28:24.897  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:24.897  1017  1490 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 12:28:24.897  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 12:28:24.897  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.897  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.897  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:24.897  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:24.897  1017  1041 W libprocessgroup: failed to open /acct/uid_10069/pid_2614/cgroup.procs: No such file or directory
,03-17 12:28:24.907  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2458/cgroup.procs: No such file or directory
,03-17 12:28:24.927  3150  3459 W jxcore-log: Initializing JXcore engine
03-17 12:28:24.927  3150  3459 W jxcore-log: JXcore engine is ready
,03-17 12:28:24.937  1017  1490 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3529 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 12:28:24.937  1310  3285 D ScoverManager: serviceVersion : 16908288
,03-17 12:28:24.947  3529  3529 E Zygote  : MountEmulatedStorage(),
03-17 12:28:24.947  3529  3529 E Zygote  : v2,
03-17 12:28:24.947  3529  3529 I libpersona: KNOX_SDCARD checking this for 10092,
03-17 12:28:24.947  3529  3529 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:24.947  3529  3529 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:24.947  3529  3529 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:24.957  3529  3529 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 12:28:24.967  3511  3511 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 12:28:24.977  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2712/cgroup.procs: No such file or directory
,03-17 12:28:24.977  1017  1041 W libprocessgroup: failed to open /acct/uid_10135/pid_2673/cgroup.procs: No such file or directory
,03-17 12:28:24.987  3529  3529 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:24.997  3529  3529 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:24.997  1930  1930 E audit   : type=1400 msg=audit(1458214104.997:205): avc:  denied  { ioctl } for  pid=3459 comm="Thread-418" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-17 12:28:24.997  1930  1930 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:24.997  1930  1930 E audit   : type=1300 msg=audit(1458214104.997:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9b34f8f8 items=0 ppid=301 ppcomm=main pid=3459 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-418" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 12:28:24.997  1930  1930 E audit   : type=1320 msg=audit(1458214104.997:205): 
,03-17 12:28:25.007  3511  3511 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 12:28:25.017  3511  3511 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 12:28:25.017  3511  3511 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 12:28:25.017  3150  3459 W jxcore-log: Starting JXcore engine
,03-17 12:28:25.057  3460  3498 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:28:25.067  1017  3168 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,03-17 12:28:25.067  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.067  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.067  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.067  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.087  3547  3547 E Zygote  : MountEmulatedStorage(),
,03-17 12:28:25.087  3547  3547 E Zygote  : v2
03-17 12:28:25.087  3547  3547 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 12:28:25.087  3547  3547 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:25.097  3547  3547 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:25.097  3547  3547 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:25.097  3547  3547 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:25.097  1017  3168 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3547 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:25.127  3547  3547 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.137  3547  3547 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.137  3460  3498 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 12:28:25.137  3460  3498 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a1d9c9d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 12:28:25.137  3460  3498 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:28:25.157  3150  3459 W jxcore-log: Platform android
03-17 12:28:25.157  3150  3459 W jxcore-log: 
,03-17 12:28:25.157  3150  3459 W jxcore-log: Process ARCH arm
03-17 12:28:25.157  3150  3459 W jxcore-log: 
,03-17 12:28:25.187  3547  3547 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 12:28:25.187  3547  3547 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 12:28:25.197  1017  1486 I ActivityManager: Killing 2513:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-17 12:28:25.197  3547  3547 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 12:28:25.207  3547  3561 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 12:28:25.217  3511  3511 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 12:28:25.217  3287  3345 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 12:28:25.217  3511  3511 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 12:28:25.217  3511  3511 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 12:28:25.217  1017  1490 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,03-17 12:28:25.217  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.217  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.227  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.227  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.227  3373  3434 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT,
,03-17 12:28:25.237  3373  3434 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:28:25.237  3563  3563 E Zygote  : MountEmulatedStorage(),
03-17 12:28:25.237  3563  3563 E Zygote  : v2
03-17 12:28:25.237  3563  3563 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 12:28:25.237  3563  3563 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:25.237  3563  3563 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 12:28:25.237  1017  1490 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3563 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:25.247  1017  1490 I ActivityManager: Killing 2791:com.samsung.android.sm/1000 (adj 15): empty #31
03-17 12:28:25.247  3563  3563 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:25.247  1017  1490 I ActivityManager: Killing 2808:com.android.email/u0a145 (adj 15): empty #32
,03-17 12:28:25.247  3563  3563 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:25.267  3373  3434 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-17 12:28:25.267  3373  3434 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-17 12:28:25.267  3373  3434 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-17 12:28:25.287  3563  3563 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.287  3563  3563 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.287  3287  3345 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 12:28:25.317  3437  3437 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 12:28:25.317  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-17 12:28:25.317  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.317  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.317  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.317  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.327  3287  3345 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 12:28:25.327  3287  3345 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 12:28:25.337  3582  3582 E Zygote  : MountEmulatedStorage(),
03-17 12:28:25.337  3582  3582 E Zygote  : v2
03-17 12:28:25.337  3582  3582 I libpersona: KNOX_SDCARD checking this for 10003
03-17 12:28:25.337  3582  3582 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:25.337  3582  3582 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:25.337  1017  1017 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3582 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
03-17 12:28:25.347  3582  3582 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:25.347  3582  3582 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:25.357  1017  1491 I ActivityManager: Killing 1932:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-17 12:28:25.387  3582  3582 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.387  3582  3582 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.397  3563  3563 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 12:28:25.407  3373  3434 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-17 12:28:25.407  3563  3563 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 12:28:25.417  3396  3504 W art     : Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.i.a(com.google.m.a.a.a.f, boolean) took 109.657ms
,03-17 12:28:25.427  3150  3459 I jxcore-log: JXcore Cordova bridge is ready!
03-17 12:28:25.427  3150  3459 I jxcore-log: 
,03-17 12:28:25.427  3150  3459 W jxcore-log: JXcore engine is started
,03-17 12:28:25.437  3150  3327 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 12:28:25.437  3150  3150 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 12:28:25.447  1310  3285 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 12:28:25.447  2654  3278 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3278)  
,03-17 12:28:25.457  3547  3561 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 12:28:25.457  3373  3434 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 12:28:25.487  3563  3563 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
03-17 12:28:25.487  3582  3582 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 12:28:25.487  3437  3437 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 12:28:25.507  3563  3563 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 12:28:25.507  1310  3285 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-17 12:28:25.517  3373  3434 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 12:28:25.517  3373  3434 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-17 12:28:25.517  3373  3455 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 12:28:25.537  3437  3437 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 12:28:25.537  3437  3437 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 12:28:25.537   286   286 E SMD     : DCD OFF
,03-17 12:28:25.547  3437  3437 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 12:28:25.557  3437  3437 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-17 12:28:25.567  3373  3434 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-17 12:28:25.567  3373  3455 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:28:25.577  3373  3455 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 12:28:25.577  3373  3455 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 12:28:25.587  3373  3434 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-17 12:28:25.587  3373  3455 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 12:28:25.587  3437  3437 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 12:28:25.597  3373  3434 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/17/12:28:25
,03-17 12:28:25.597  3373  3434 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-17 12:28:25.597  3373  3434 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-17 12:28:25.597  3373  3455 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 12:28:25.597  3373  3455 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 12:28:25.597  3373  3455 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-17 12:28:25.607  3373  3455 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 12:28:25.607  3373  3455 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 12:28:25.637  3373  3455 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 12:28:25.657  3437  3437 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 12:28:25.657  3373  3434 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-17 12:28:25.667  1017  1041 E libprocessgroup: failed to kill 1 processes for processgroup 2808
03-17 12:28:25.667  1017  1041 W libprocessgroup: failed to open /acct/uid_10044/pid_2513/cgroup.procs: No such file or directory
03-17 12:28:25.667  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2791/cgroup.procs: No such file or directory
,03-17 12:28:25.677  3582  3582 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 12:28:25.677  3582  3582 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 12:28:25.677  3582  3582 D UserAnalysis: Create SecureDbHelper
,03-17 12:28:25.677  3373  3455 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-17 12:28:25.757  3563  3563 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 12:28:25.757  3582  3582 D IntelligenceServiceApplication: onCreate()
,03-17 12:28:25.757  3582  3582 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 12:28:25.767  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,03-17 12:28:25.767  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.767  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.767  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:25.767  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:25.777  3606  3606 E Zygote  : MountEmulatedStorage(),
03-17 12:28:25.777  3606  3606 E Zygote  : v2
03-17 12:28:25.777  3606  3606 I libpersona: KNOX_SDCARD checking this for 10060
03-17 12:28:25.777  3606  3606 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:25.777  3606  3606 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:25.787  3396  3504 W art     : Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.a.vQ() took 361.886ms,
,03-17 12:28:25.787  3606  3606 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:25.787  3606  3606 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 12:28:25.787  1017  1029 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3606 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,03-17 12:28:25.787  3563  3563 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W,
03-17 12:28:25.797  3563  3563 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 12:28:25.797  3437  3437 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US)),
03-17 12:28:25.797  3563  3563 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-17 12:28:25.797  3563  3563 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 12:28:25.797  3563  3563 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 12:28:25.797  3563  3563 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 12:28:25.817   301   301 I art     : Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 5.222ms total 35.252ms
,03-17 12:28:25.827  3606  3606 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:25.827  3606  3606 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:25.837  3373  3434 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-17 12:28:25.837   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.980ms total 19.709ms
,03-17 12:28:25.847  3373  3434 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 12:28:25.857   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 725us total 18.134ms
,03-17 12:28:25.877  3582  3582 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 12:28:25.887  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-17 12:28:25.887  3582  3582 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 12:28:25.917  1017  1486 I ActivityManager: Killing 2937:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-17 12:28:25.927  3582  3582 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 12:28:25.927  3582  3582 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 12:28:25.927  3418  3418 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 12:28:25.937  3418  3418 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 12:28:25.937  3418  3418 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 12:28:25.997  3396  3504 W art     : Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.a.c(com.google.m.a.a.a.d) took 110.472ms
,03-17 12:28:26.007  3418  3418 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 12:28:26.007  1017  3172 D ActivityManager: startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,03-17 12:28:26.007  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.007  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.007  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.007  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.017  3632  3632 E Zygote  : MountEmulatedStorage(),
03-17 12:28:26.017  3632  3632 E Zygote  : v2
,03-17 12:28:26.017  3632  3632 I libpersona: KNOX_SDCARD checking this for 10014
03-17 12:28:26.027  3632  3632 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.027  3632  3632 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:26.027  1017  3172 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3632 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-17 12:28:26.027  3632  3632 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:26.027  1017  3172 I ActivityManager: Killing 2091:com.google.android.gms/u0a12 (adj 15): empty #31
03-17 12:28:26.027  3632  3632 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:26.047  3606  3606 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-17 12:28:26.067  3632  3632 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:26.067  3632  3632 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.077  3373  3455 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 12:28:26.077  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-17 12:28:26.077  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.087  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.087  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.087  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.097  3649  3649 E Zygote  : MountEmulatedStorage(),
03-17 12:28:26.097  3649  3649 E Zygote  : v2
03-17 12:28:26.097  3649  3649 I libpersona: KNOX_SDCARD checking this for 10062
03-17 12:28:26.097  3649  3649 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.097  3649  3649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:26.107  1017  1030 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3649 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 12:28:26.107  1017  1030 I ActivityManager: Killing 2207:flipboard.app/u0a98 (adj 15): empty #31
,03-17 12:28:26.107  3649  3649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:26.107  3649  3649 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:26.107  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
03-17 12:28:26.107  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.107  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.107  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.107  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.117  1017  1029 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3d540ab8)
,03-17 12:28:26.117  1017  1143 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-17 12:28:26.127  1017  1143 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-17 12:28:26.137  3663  3663 E Zygote  : MountEmulatedStorage()
,03-17 12:28:26.137  3663  3663 E Zygote  : v2
03-17 12:28:26.137  3663  3663 I libpersona: KNOX_SDCARD checking this for 10094
03-17 12:28:26.137  3663  3663 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.137  3663  3663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:26.137  3373  3455 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-17 12:28:26.147  3663  3663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:26.147  3460  3475 W art     : Suspending all threads took: 108.735ms
,03-17 12:28:26.147  3663  3663 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:26.157  1017  1030 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3663 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-17 12:28:26.157  1017  1030 I ActivityManager: Killing 2971:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-17 12:28:26.167  3649  3649 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:26.167  3649  3649 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.187  3663  3663 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:26.187  3663  3663 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.207  3396  3504 I SearchServiceFactory: checking for language pack updates
,03-17 12:28:26.237  3632  3632 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 12:28:26.237  1017  3172 D ActivityManager: startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,03-17 12:28:26.237  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-17 12:28:26.237  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:26.237  1017  3172 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:26.237  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 12:28:26.247  3632  3679 V OneTimeService: OneTimeService.onHandleIntent
,03-17 12:28:26.257  1017  1491 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 12:28:26.267  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-17 12:28:26.267  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:26.267  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:26.267  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:26.277  1017  1234 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 12:28:26.277  1017  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-17 12:28:26.277  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:26.277  1017  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:26.277  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:26.287  1017  3172 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 12:28:26.287  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-17 12:28:26.287  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:26.287  1017  3172 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:26.287  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:26.287  3663  3663 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 12:28:26.297  3663  3663 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 12:28:26.327  1017  3168 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 12:28:26.327  1017  3168 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-17 12:28:26.327  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:26.327  1017  3168 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:26.327  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:26.347  3663  3663 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 12:28:26.347  1017  1490 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm,
,03-17 12:28:26.347  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 12:28:26.347  1017  1490 W ActivityManager: userId = 0, bbcId = -10000,
03-17 12:28:26.347  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:26.347  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 12:28:26.357  3663  3663 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 12:28:26.367  1426  1426 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 12:28:26.377  3287  3345 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 12:28:26.387  1426  1426 V EmergencyMode: [EmergencyBase] setBootTime
03-17 12:28:26.387  1426  1426 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 12:28:26.397  3437  3648 I System.out: Thread-469(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 12:28:26.397  1017  3168 D ActivityManager: startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,03-17 12:28:26.397  3663  3663 D elm:15183: ElmAgentService : onCreate()
,03-17 12:28:26.397  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.397  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.397  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.397  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.407  3663  3689 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-17 12:28:26.407  3663  3663 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 12:28:26.407  3663  3663 D elm:15183: BootCompletedState : startBootCompleted() call
,03-17 12:28:26.407  3437  3648 I System.out: Thread-469(ApacheHTTPLog):isSBSettingEnabled false
03-17 12:28:26.407  3437  3648 I System.out: Thread-469(ApacheHTTPLog):isShipBuild true
03-17 12:28:26.407  3437  3648 I System.out: Thread-469(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 12:28:26.407  3437  3648 I System.out: Thread-469(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 12:28:26.407   275  1012 D EnterpriseController: uids 10092
03-17 12:28:26.407   275  1012 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:28:26.407   275  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 12:28:26.417  3696  3696 E Zygote  : MountEmulatedStorage()
03-17 12:28:26.417  3696  3696 E Zygote  : v2
03-17 12:28:26.417  3696  3696 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:26.417  3696  3696 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.417  3696  3696 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:26.427  3663  3663 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 12:28:26.427  3696  3696 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:26.427  3663  3663 I elm:15183: Get License : 0
03-17 12:28:26.427  1017  3168 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3696 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:26.437  3696  3696 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:26.437  3663  3663 D elm:15183: ElmAgentService : onDestroy().
,03-17 12:28:26.447  1017  3168 I ActivityManager: Killing 2987:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,03-17 12:28:26.447  3649  3649 I ExternalOEMControlProvider: onCreate
,03-17 12:28:26.447  1017  1476 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 12:28:26.447  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-17 12:28:26.457  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:26.457  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:26.457  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:26.457  3696  3696 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:26.457  3696  3696 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.467  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,03-17 12:28:26.477  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.477  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.477  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.477  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.477  3460  3460 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 12:28:26.487  3714  3714 E Zygote  : MountEmulatedStorage()
03-17 12:28:26.487  3714  3714 E Zygote  : v2
03-17 12:28:26.487  3714  3714 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:26.487  3714  3714 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.497  3714  3714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:26.497  3714  3714 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:26.497  3714  3714 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:26.497  1017  1491 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3714 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:26.507  1017  1491 I ActivityManager: Killing 2366:com.sec.modem.settings/1000 (adj 15): empty #31
,03-17 12:28:26.517  1017  1993 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 12:28:26.527  1017  1993 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 12:28:26.527  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:26.527  1017  1993 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:26.527  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:28:26.527  2427  2427 I Hs20UtilService: Starting #3
,03-17 12:28:26.527  2427  2442 I Hs20UtilService: Message received 5003
,03-17 12:28:26.527  3714  3714 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:26.527  3714  3714 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.537  3460  3581 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:28:26.537  3460  3581 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:28:26.547  1017  1234 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-17 12:28:26.547  1017  1234 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:26.547  1017  1234 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:26.547  1017  1234 D SettingsProvider: selectionArgs: false
03-17 12:28:26.547  1017  1234 D SettingsProvider: selectionArgs: 10062
03-17 12:28:26.547  1017  1234 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:26.547  1017  1234 D SettingsProvider: ret = -1
,03-17 12:28:26.547  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,03-17 12:28:26.557  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.557  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.557  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.557  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.567  1017  1234 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 12:28:26.567  3714  3714 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 12:28:26.567  1017  1030 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 12:28:26.567  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:26.567  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:26.567  1017  1030 D SettingsProvider: selectionArgs: false
03-17 12:28:26.567  1017  1030 D SettingsProvider: selectionArgs: 10062
03-17 12:28:26.567  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:26.567  1017  1030 D SettingsProvider: ret = -1
,03-17 12:28:26.587  3736  3736 E Zygote  : MountEmulatedStorage()
03-17 12:28:26.587  3736  3736 I libpersona: KNOX_SDCARD checking this for 10019
03-17 12:28:26.587  3736  3736 E Zygote  : v2
03-17 12:28:26.587  3736  3736 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.587  1017  1030 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 12:28:26.587  3736  3736 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:26.587  3736  3736 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:26.587  1017  1491 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3736 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 12:28:26.587  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:26.597  3736  3736 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:26.607  2692  2768 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 12:28:26.627  3714  3714 I ServiceMode: received = ACTION_BOOT_COMPLETED
,03-17 12:28:26.627  3714  3714 I ServiceMode: setReferenceIsDumpState : 0,
,03-17 12:28:26.637  3736  3736 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:26.637  3736  3736 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.647  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:26.647  1017  3172 D ActivityManager: startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,03-17 12:28:26.657  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.657  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.657  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.657  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.657  3696  3696 I CameraApp: CameraApp.onCreate()... mFeature : null,
,03-17 12:28:26.657  3696  3696 I testFeature: Feature.Feature(context)
03-17 12:28:26.657  3696  3696 I testFeature: Feature.readInternalDefaultXml()
03-17 12:28:26.657  3696  3696 I testFeature: ResetFeatureValue
,03-17 12:28:26.667  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:26.667  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:26.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:26.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:26.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:26.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:26.667  3696  3696 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 12:28:26.667  3696  3696 I CameraApp: CameraApp.getAppFeature()...
,03-17 12:28:26.667  3753  3753 E Zygote  : MountEmulatedStorage(),
03-17 12:28:26.667  3753  3753 E Zygote  : v2
03-17 12:28:26.667  3753  3753 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:26.667  3753  3753 I libpersona: KNOX_SDCARD not a persona,
03-17 12:28:26.677  1017  3172 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3753 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-17 12:28:26.677  3753  3753 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:26.677  1017  3172 I ActivityManager: Killing 3008:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-17 12:28:26.677  1017  3172 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,03-17 12:28:26.677  3753  3753 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:26.677  3753  3753 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:26.677  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.677  3460  3460 I System.out: YouTube MDX: MDX video stage moved to NEW
03-17 12:28:26.677  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.677  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.677  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:26.687  3460  3460 I System.out: YouTube MDX: MDX video player state moved to UNSTARTED
,03-17 12:28:26.687  3460  3460 I System.out: YouTube MDX: MDX ad player state moved to UNSTARTED
,03-17 12:28:26.707  3767  3767 E Zygote  : MountEmulatedStorage(),
03-17 12:28:26.707  3767  3767 E Zygote  : v2
,03-17 12:28:26.707  3767  3767 I libpersona: KNOX_SDCARD checking this for 10100
03-17 12:28:26.707  3767  3767 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 12:28:26.707  3767  3767 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.707  3767  3767 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:26.707  3767  3767 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 12:28:26.707  1017  3172 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3767 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 12:28:26.717  3753  3753 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:26.717  3753  3753 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.717  1017  3172 I ActivityManager: Killing 2335:com.android.mms/u0a46 (adj 15): empty #31
,03-17 12:28:26.727  3733  3733 I dex2oat : ----------------------------------------------------
03-17 12:28:26.727  3733  3733 I dex2oat : <SS>: S T A R T I N G . . .
03-17 12:28:26.727  3733  3733 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 12:28:26.727  3733  3733 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads511692419.jar --oat-fd=36 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads511692419.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 12:28:26.747  1017  1395 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 12:28:26.747  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,03-17 12:28:26.757  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:26.757  1017  1395 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:26.757  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:28:26.767  3767  3767 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:26.767  3767  3767 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.837  3736  3736 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 12:28:26 GMT+01:00 2016
,03-17 12:28:26.837  1017  1490 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-17 12:28:26.837  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-17 12:28:26.847  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:26.847  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:26.847  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 12:28:26.847  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-17 12:28:26.847  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 12:28:26.847  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:26.847  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:26.847  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 12:28:26.847  3733  3733 I dex2oat : dex2oat took 124.604ms (threads: 4)
,03-17 12:28:26.867  3736  3736 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 12:28:26.867  1017  1342 D ActivityManager: startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,03-17 12:28:26.877  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.877  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.877  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.877  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.897  3794  3794 E Zygote  : MountEmulatedStorage(),
03-17 12:28:26.897  3736  3736 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 12:28:26.897  3396  3792 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
03-17 12:28:26.897  3396  3792 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
03-17 12:28:26.897  3794  3794 E Zygote  : v2,
03-17 12:28:26.897  3396  3792 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_language_packs]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor,
03-17 12:28:26.897  3736  3736 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-17 12:28:26.897  3794  3794 I libpersona: KNOX_SDCARD checking this for 10022,
03-17 12:28:26.897  3794  3794 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.897  3794  3794 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:26.907  3396  3792 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor,
,03-17 12:28:26.907  3396  3792 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_gservices_config]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor,
,03-17 12:28:26.907  3396  3792 E TRThreadPoolExecutor: Queue length for executor Background Blocking with unbounded threads is now 4. Perhaps some tasks are too long, or the pool is too small.,
03-17 12:28:26.907  3396  3792 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_domain_and_cookies]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 12:28:26.917  1017  1342 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3794 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a,
,03-17 12:28:26.917  3794  3794 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:26.917  3794  3794 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 12:28:26.917  3753  3753 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
03-17 12:28:26.917  3753  3753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
03-17 12:28:26.917  3396  3796 I SearchServiceFactory: refreshing search history.
,03-17 12:28:26.927  1017  3168 D ActivityManager: startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
,03-17 12:28:26.927  1017  3168 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 12:28:26.927  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:26.927  1017  3168 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:26.927  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 12:28:26.937  3767  3767 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 12:28:26.937  1017  3172 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-17 12:28:26.947  3753  3753 D NPS_WSSNPS: [] Service onCreate!!
,03-17 12:28:26.947  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.947  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.947  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.957  3396  3803 I GservicesUpdateTask: Updating Gservices keys
03-17 12:28:26.957  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:26.967  3794  3794 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 12:28:26.967  3794  3794 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:26.977  3818  3818 E Zygote  : MountEmulatedStorage(),
03-17 12:28:26.977  3818  3818 E Zygote  : v2
03-17 12:28:26.977  3818  3818 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 12:28:26.977  3818  3818 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:26.977  3818  3818 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:26.977  3818  3818 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 12:28:26.977  3818  3818 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:26.977  1017  3172 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3818 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 12:28:26.987  3484  3484 I RlzPingService: Setting next ping for 1458818906953
,03-17 12:28:27.007  3818  3818 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:27.017  3818  3818 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:27.017  3753  3753 D NPS_WSSNPS: [50.150621] smlDBHelper
,03-17 12:28:27.027  3753  3829 D NPS_WSSNPS: [50.150621] NpsServiceTask Start
,03-17 12:28:27.027  3767  3767 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 12:28:27.027  1017  3168 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,03-17 12:28:27.037  1017  1490 D CountryDetector: No listener is left
,03-17 12:28:27.037  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:27.037  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:27.037  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:27.037  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:27.047  1017  3168 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3837 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 12:28:27.057  3837  3837 E Zygote  : MountEmulatedStorage(),
03-17 12:28:27.057  3736  3736 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 12:28:27.057  3837  3837 E Zygote  : v2,
,03-17 12:28:27.057  3837  3837 I libpersona: KNOX_SDCARD checking this for 10101
,03-17 12:28:27.067  3837  3837 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:27.067  3837  3837 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:27.067  3837  3837 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:27.067  3818  3818 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:27.077  3753  3753 I NPS_WSSNPS: [50.150621] AsyncBulkFlagCheck
,03-17 12:28:27.087  3837  3837 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:27.087   301   301 I art     : Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 35.438ms
,03-17 12:28:27.087  3753  3844 I NPS_WSSNPS: [50.150621] IsRemain_AsyncBulkCheck
,03-17 12:28:27.097  3753  3844 I NPS_WSSNPS: [50.150621] IsRemain_Asyncing nothing
,03-17 12:28:27.097  3753  3844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 12:28:27.097  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 12:28:27.097  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:27.097  1017  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:27.097  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 12:28:27.107   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 16.994ms
,03-17 12:28:27.117  3396  3804 I UpdateLanguagePacksTask: Checking for language pack updates.
,03-17 12:28:27.117  3753  3753 D NPS_WSSNPS: [50.150621] Service onDestroy
,03-17 12:28:27.117  3736  3793 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 12:28:27.127  3753  3753 I NPS_WSSNPS: [50.150621] smlBRConfigurationDelete
,03-17 12:28:27.127  3753  3753 I NPS_WSSNPS: [50.150621] smlBRMessageDelete
,03-17 12:28:27.127  3753  3753 I NPS_WSSNPS: [50.150621] smlBREmailDelete
,03-17 12:28:27.127  3753  3753 I NPS_WSSNPS: [50.150621] smlBRNetworkDelete
03-17 12:28:27.127   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 18.334ms
03-17 12:28:27.127  3753  3753 I NPS_WSSNPS: [50.150621] smlBRCallLogDelete
,03-17 12:28:27.127  3753  3753 I NPS_WSSNPS: [50.150621] smlBRMiniDiaryDelete
03-17 12:28:27.127  3753  3753 I NPS_WSSNPS: [50.150621] smlBRPenMemoMDelete
,03-17 12:28:27.127  3753  3753 I NPS_WSSNPS: [50.150621] smlBRSMemoDelete
,03-17 12:28:27.127  3753  3753 I NPS_WSSNPS: [50.150621] verifier installed? false
03-17 12:28:27.127  3753  3753 I NPS_WSSNPS: [50.150621] cpuBooster release : false
,03-17 12:28:27.137  3837  3837 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:27.137  1310  3285 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 12:28:27.137  3837  3837 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:27.137  1017  1342 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-17 12:28:27.137  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:27.137  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:27.147  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:27.147  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:27.157  3736  3793 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
03-17 12:28:27.157  3856  3856 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:27.157  3856  3856 E Zygote  : MountEmulatedStorage()
03-17 12:28:27.157  3856  3856 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:27.157  3856  3856 E Zygote  : v2
,03-17 12:28:27.157  3856  3856 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:27.157  1017  1342 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3856 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:27.167  1017  1342 I ActivityManager: Killing 3048:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 12:28:27.167  3856  3856 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:27.167  1017  1234 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 12:28:27.167  3856  3856 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:27.167  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:27.167  1017  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:27.167  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 12:28:27.167  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:27.167  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:27.167  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:27.177  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:27.197  3871  3871 E Zygote  : MountEmulatedStorage()
03-17 12:28:27.197  3871  3871 I libpersona: KNOX_SDCARD checking this for 10012
03-17 12:28:27.197  3871  3871 E Zygote  : v2
03-17 12:28:27.197  3871  3871 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:27.197  3871  3871 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:27.207  1017  1234 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=3871 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-17 12:28:27.207  3871  3871 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:27.207  3871  3871 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:27.207  3753  3753 D NPS_WSSNPS: [50.150621] dsServerSocket close
,03-17 12:28:27.237  1017  3172 I ActivityManager: Killing 3075:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-17 12:28:27.237  3736  3736 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 12:28:27.247  3856  3856 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:27.247  3871  3871 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:27.247  3871  3871 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:27.247  3856  3856 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:27.307  3871  3871 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:28:27.307  3871  3871 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:28:27.347  1017  1490 I ActivityManager: Killing 2873:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-17 12:28:27.357  1814  3505 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 12:28:27.377  3287  3345 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 12:28:27.397  2654  2654 D FactoryTestApp: [DummyFtClient$onDestroy](2654) Destroy DummyFtClient service
,03-17 12:28:27.407  2654  2654 D FactoryTestApp: [Support$Values.getString](2654) id=MODEL_COMMUNICATION_MODE, value=gsm
,03-17 12:28:27.407  2654  2654 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2654) mConnectionMode = gsm
,03-17 12:28:27.407  2654  2654 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2654) RUNNING_FTCLIENT : false
,03-17 12:28:27.407  2654  2654 D FactoryTestApp: [DummyFtClient$onDestroy](2654) kill process
,03-17 12:28:27.407  2654  2654 I Process : Sending signal. PID: 2654 SIG: 9
,03-17 12:28:27.497  1017  3172 I art     : Explicit concurrent mark sweep GC freed 22722(1235KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 2.848ms total 181.723ms
,03-17 12:28:27.507  1017  1993 D ActivityManager: bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
,03-17 12:28:27.507  1017  1993 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 12:28:27.517  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:27.517  1017  1993 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:27.517  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:27.517  3856  3856 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 12:28:27.527  1017  1486 I ActivityManager: Process com.sec.factory (pid 2654)(adj 0) has died(92,1116)
,03-17 12:28:27.537  1017  3172 D SecContentProvider2: uri = 14 selection = getSealedState
,03-17 12:28:27.547  1017  3172 D SecContentProvider2: mCursor = null
,03-17 12:28:27.557  1017  1234 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-17 12:28:27.557  1017  1234 D SecContentProvider2: mCursor = null
,03-17 12:28:27.557  3856  3856 V MTPRx   : sealedState: false
,03-17 12:28:27.557  3856  3856 V MTPRx   : sealedUsbMassStorageState: false
,03-17 12:28:27.567  1017  1476 D SettingsProvider: name = mtp_usb_connection_status
,03-17 12:28:27.597  3871  3871 W art     : Verification of void com.google.android.gms.common.app.GmsApplication.onCreate() took 193.097ms
,03-17 12:28:27.607  3871  3871 I MultiDex: VM with version 2.1.0 has multidex support
03-17 12:28:27.607  1017  1041 W libprocessgroup: failed to open /acct/uid_10004/pid_1932/cgroup.procs: No such file or directory
03-17 12:28:27.607  3871  3871 I MultiDex: install
03-17 12:28:27.607  3871  3871 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 12:28:27.627   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 12:28:27.627   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:27.627  3460  3460 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 12:28:27.627  1017  1395 D SettingsProvider: name = media_player_mode
,03-17 12:28:27.637  3396  3504 E File    : fail readDirectory() errno=2
,03-17 12:28:27.637  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:27.647  1017  1234 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 12:28:27.657  1017  3836 D SettingsProvider: name = mtp_running_status
,03-17 12:28:27.677  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:27.687  1310  3285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 12:28:27.687  1017  1041 W libprocessgroup: failed to open /acct/uid_10099/pid_2937/cgroup.procs: No such file or directory
03-17 12:28:27.687  1017  1041 W libprocessgroup: failed to open /acct/uid_10012/pid_2091/cgroup.procs: No such file or directory
03-17 12:28:27.687  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2971/cgroup.procs: No such file or directory
,03-17 12:28:27.687  1017  1150 D SettingsProvider: name = media_mount_count
,03-17 12:28:27.687  1310  3285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 12:28:27.687   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache/
03-17 12:28:27.687   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:27.707  1310  3285 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
03-17 12:28:27.707  3396  3507 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache
,03-17 12:28:27.707  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2366/cgroup.procs: No such file or directory
03-17 12:28:27.707  1017  1041 W libprocessgroup: failed to open /acct/uid_10152/pid_2987/cgroup.procs: No such file or directory
,03-17 12:28:27.707  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3008/cgroup.procs: No such file or directory
,03-17 12:28:27.707  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:27.717  1017  1342 D SettingsProvider: name = mtp_sync_alive
,03-17 12:28:27.717  3396  3798 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 12:28:27.717  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
,03-17 12:28:27.737  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:27.737  1017  1041 W libprocessgroup: failed to open /acct/uid_10046/pid_2335/cgroup.procs: No such file or directory
03-17 12:28:27.737  1017  1041 W libprocessgroup: failed to open /acct/uid_1101/pid_3048/cgroup.procs: No such file or directory
03-17 12:28:27.737  1017  1041 W libprocessgroup: failed to open /acct/uid_10048/pid_3075/cgroup.procs: No such file or directory
,03-17 12:28:27.737  1017  1041 W libprocessgroup: failed to open /acct/uid_10072/pid_2873/cgroup.procs: No such file or directory
03-17 12:28:27.737  1017  1041 W libprocessgroup: failed to open /acct/uid_10098/pid_2207/cgroup.procs: No such file or directory
,03-17 12:28:27.757  1017  3172 D SettingsProvider: name = sdcard_launch
,03-17 12:28:27.757  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:27.767  1017  1395 D SettingsProvider: name = boot_time_connected
,03-17 12:28:27.777  1017  1476 D SettingsProvider: name = mtp_open_session
,03-17 12:28:27.787  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:27.797  1017  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:27.797  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:27.797  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:27.797  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 12:28:27.817  3396  3798 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3182-3184)
03-17 12:28:27.817  3396  3798 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:28:27.827  1017  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:27.827  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:27.827  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:27.827  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 12:28:27.837  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:27.847  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,03-17 12:28:27.847  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:27.847  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:27.847  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:27.847  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:27.867  3907  3907 E Zygote  : MountEmulatedStorage(),
03-17 12:28:27.867  3907  3907 E Zygote  : v2
03-17 12:28:27.867  3907  3907 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:27.867  3907  3907 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:27.867  3907  3907 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:27.867  3907  3907 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:27.867  3907  3907 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:27.877  1017  1476 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-17 12:28:27.877  1017  1476 I ActivityManager: Killing 3128:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-17 12:28:27.897  3907  3907 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:27.897  3907  3907 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:27.917  3396  3798 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:28:27.937  3547  3547 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 12:28:27.937  3547  3547 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 12:28:27.937  3547  3547 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 12:28:27.937  3547  3547 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-17 12:28:27.937  3547  3547 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 12:28:27.937  3547  3547 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 12:28:27.937  3437  3648 I System.out: pool-10-thread-1 calls detatch()
,03-17 12:28:27.937  3396  3798 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 12:28:27.977  3396  3796 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 12:28:27.977  1017  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 12:28:27.977  1017  1486 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 12:28:27.987  3547  3547 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 12:28:28.007  3871  3871 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:28:28.017  1017  1041 W libprocessgroup: failed to open /acct/uid_10157/pid_3128/cgroup.procs: No such file or directory
,03-17 12:28:28.037  1017  3168 D SettingsProvider: name = access_control_enabled
,03-17 12:28:28.037  3547  3547 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 12:28:28.037  3547  3547 I ReactiveServiceManager: Supported : 1
,03-17 12:28:28.037  1017  1234 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,03-17 12:28:28.047  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.047  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.047  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.047  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.047  1017  1486 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 12:28:28.047  1017  1486 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 12:28:28.067  1017  1234 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3932 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:28.067  3932  3932 E Zygote  : MountEmulatedStorage()
03-17 12:28:28.067  3932  3932 E Zygote  : v2
03-17 12:28:28.067  3932  3932 I libpersona: KNOX_SDCARD checking this for 10069
03-17 12:28:28.067  3932  3932 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:28.067  3932  3932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:28.067  1017  1234 I ActivityManager: Killing 3113:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 12:28:28.067  3932  3932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:28.077  3932  3932 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:28.077  3871  3871 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 12:28:28.077  3871  3871 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@359ad128: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 12:28:28.077  3871  3871 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:28:28.087  1017  1486 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 12:28:28.097  1017  1486 D QSEECOMAPI: : QSEECom_dealloc_memory 
,03-17 12:28:28.097  1017  1486 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-17 12:28:28.107  3932  3932 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:28.107  3932  3932 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:28.107  1017  1486 E terrier : handleString: Failed to handle string(-4)
03-17 12:28:28.107  1017  1486 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-17 12:28:28.107  3547  3547 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 12:28:28.107  3547  3547 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 12:28:28.127  3547  3547 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
03-17 12:28:28.127  3547  3547 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 12:28:28.127  3547  3547 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM],
03-17 12:28:28.127  3547  3547 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 12:28:28.127  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,03-17 12:28:28.137  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.137  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.137  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.137  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.147  1017  1395 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,03-17 12:28:28.157  3949  3949 E Zygote  : MountEmulatedStorage()
,03-17 12:28:28.157  3949  3949 E Zygote  : v2
,03-17 12:28:28.157  3949  3949 I libpersona: KNOX_SDCARD checking this for 10031
03-17 12:28:28.157  3949  3949 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:28.157  3949  3949 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 12:28:28.157  1017  1476 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3949 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-17 12:28:28.157  1017  1476 I ActivityManager: Killing 3176:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,03-17 12:28:28.167  3949  3949 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:28.167  3949  3949 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:28.197  1017  3168 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:28.197  3932  3932 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 12:28:28.207  3949  3949 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:28.207  3949  3949 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:28.227  3949  3949 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 12:28:28.227  1017  1476 I AudioService: getStreamVolume 3 index 0
,03-17 12:28:28.347  3837  3968 I Gmail   : getAccountsCursor
,03-17 12:28:28.367   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 12:28:28.367   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:28.367  3460  3460 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 12:28:28.367   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 12:28:28.367   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:28.367  3460  3460 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 12:28:28.367   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 12:28:28.367   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:28.377  3460  3460 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 12:28:28.377  1017  1993 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 12:28:28.377  1017  1993 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.377  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:28.377  1017  1993 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.377  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:28.387  3287  3345 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 12:28:28.417  1017  1029 I ActivityManager: Killing 3192:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 12:28:28.427  1017  3172 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:28.427  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:28.427  1017  3172 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.427  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 12:28:28.427  1017  3168 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 12:28:28.427  1017  3168 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.437  3837  3837 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 12:28:28.447  1017  1017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 12:28:28.447  1017  1017 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
03-17 12:28:28.447  1017  1017 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:28.447  1864  1864 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:28.447  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,03-17 12:28:28.457  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:28.457  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:28.457  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:28.457  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.467  3987  3987 E Zygote  : MountEmulatedStorage(),
03-17 12:28:28.467  3987  3987 E Zygote  : v2
03-17 12:28:28.467  3987  3987 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 12:28:28.467  3987  3987 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:28.467  3987  3987 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:28.467  1017  1017 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3987 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:28.467  3987  3987 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:28.477  3987  3987 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:28.517  3987  3987 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:28.517  3987  3987 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:28.537  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 12:28:28.537  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.537  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:28.537  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.537  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:28.547   286   286 E SMD     : DCD OFF,
,03-17 12:28:28.557  1017  1486 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:28.577  1017  3172 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-17 12:28:28.577  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.577  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:28.577  1017  3172 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.577  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 12:28:28.587  1017  1476 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-17 12:28:28.587  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.587  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:28.587  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.587  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 12:28:28.597  3871  3960 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-17 12:28:28.597  1017  3836 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 12:28:28.597  1017  3836 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 12:28:28.617  1017  1017 I ActivityManager: Killing 3217:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 12:28:28.617  3987  3987 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:28:28.627  1017  3836 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,03-17 12:28:28.627  1017  3836 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.627  1017  3836 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:28.627  1017  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:28.627  1017  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 12:28:28.627  1017  1150 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 12:28:28.627  1017  1150 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.637  1017  1150 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:28.637  1017  1150 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.637  1017  1150 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:28.637  1017  1993 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,03-17 12:28:28.637  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.637  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:28.637  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:28.637  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.647  4025  4025 E Zygote  : MountEmulatedStorage()
03-17 12:28:28.647  4025  4025 E Zygote  : v2
03-17 12:28:28.647  4025  4025 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:28.647  4025  4025 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:28.647  4025  4025 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:28.657  3837  4020 E Gmail   : Error finding the version of the Email provider.....
03-17 12:28:28.657  3837  4020 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 12:28:28.657  3837  4020 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 12:28:28.657  3837  4020 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
03-17 12:28:28.657  3837  4020 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-17 12:28:28.657  3837  4020 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 12:28:28.657  3837  4020 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:28.657  3837  4020 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:28.657  3837  4020 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:28:28.657  4025  4025 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:28.657  3837  4020 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 12:28:28.657  4025  4025 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:28.667  1017  1993 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=4025 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 12:28:28.667  1017  1490 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 12:28:28.667  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.667  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:28.667  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.667  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:28.667  1017  1491 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-17 12:28:28.667  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.677  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:28.677  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.677  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 12:28:28.697  4025  4025 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:28.697  4025  4025 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:28.707  1017  1993 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 12:28:28.707  1017  1993 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.707  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:28.707  1017  1993 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.707  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:28.717  4025  4025 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-17 12:28:28.727  1948  1948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:28:28.727  1017  1476 D ActivityManager: startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
03-17 12:28:28.727  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.727  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:28.727  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:28.727  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 12:28:28.737  3837  4046 I Gmail   : getAccountsCursor
,03-17 12:28:28.737  1017  1150 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 12:28:28.737  1017  1150 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.737  1948  1948 D SecUISvc: Service started flags 0 startId 1
,03-17 12:28:28.737  1948  4048 D SecUISvc: Thread created.
,03-17 12:28:28.777  3396  3798 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:28:28.787  1017  1395 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,03-17 12:28:28.787  1864  1864 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:28.797  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.807  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:28.807  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:28.807  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.817  3460  4040 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
03-17 12:28:28.817  3460  4040 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 12:28:28.817  3460  4040 I System.out: Thread-526(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 12:28:28.817  3460  4040 I System.out: Thread-526(ApacheHTTPLog):isSBSettingEnabled false
03-17 12:28:28.817  3460  4040 I System.out: Thread-526(ApacheHTTPLog):isShipBuild true
,03-17 12:28:28.827  3460  4040 I System.out: Thread-526(ApacheHTTPLog):SMARTBONDING_ENABLED is false,
03-17 12:28:28.827  4053  4053 E Zygote  : MountEmulatedStorage()
03-17 12:28:28.827  3460  4040 I System.out: Thread-526(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 12:28:28.827  4053  4053 E Zygote  : v2,
03-17 12:28:28.827  4053  4053 I libpersona: KNOX_SDCARD checking this for 10028
03-17 12:28:28.827  4053  4053 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:28.827  4053  4053 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 12:28:28.827  1017  1395 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4053 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:28:28.827  1017  1490 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm,
03-17 12:28:28.827  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:28.827  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
03-17 12:28:28.827  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.827  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm,
,03-17 12:28:28.837   275  1012 D EnterpriseController: uids 10166,
03-17 12:28:28.837   275  1012 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:28:28.837  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
03-17 12:28:28.837   275  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10166
03-17 12:28:28.837  1017  1476 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 12:28:28.837  4053  4053 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:28.837  4053  4053 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 12:28:28.847  1017  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator,
03-17 12:28:28.847  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.867  3949  3949 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,03-17 12:28:28.887  1017  3168 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 12:28:28.887  1017  3168 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.917  4053  4053 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:28.917  4053  4053 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:28.917  3837  4060 I Gmail   : Observing account changes for notifications
,03-17 12:28:28.927  1017  1342 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
03-17 12:28:28.927  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.927  1864  1864 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:28.927  1017  1342 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:28.927  1017  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.927  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-17 12:28:28.947  1017  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:28.947  1017  1486 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 12:28:28.947  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,03-17 12:28:28.957  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.957  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:28.957  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.957  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:28.977  4076  4076 E Zygote  : MountEmulatedStorage(),
03-17 12:28:28.977  4076  4076 E Zygote  : v2
03-17 12:28:28.977  4076  4076 I libpersona: KNOX_SDCARD checking this for 10104
,03-17 12:28:28.977  4076  4076 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:28.987  4076  4076 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:28.987  4076  4076 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 12:28:28.987  4076  4076 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 12:28:28.987  1017  1491 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4076 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,03-17 12:28:28.987  1017  1490 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 12:28:28.997  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 12:28:28.997  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:28.997  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:28.997  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:28:29.017  4076  4076 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:29.017  4076  4076 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:29.017  3373  3434 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 12:28:29.027  3949  3949 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
03-17 12:28:29.027  1636  4074 I GoogleHttpClient: GMS http client unavailable, use old client
,03-17 12:28:29.037  3373  3434 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 12:28:29.037  1017  1395 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 12:28:29.037  1017  1395 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 12:28:29.037  3373  3434 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 12:28:29.037  3373  3434 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 12:28:29.037  3373  3434 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 12:28:29.037  3373  3434 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 12:28:29.047  1017  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:29.047  1017  1486 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 12:28:29.047  3837  3837 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@effce2d that was originally bound here
03-17 12:28:29.047  3837  3837 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@effce2d that was originally bound here
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at com.android.emailcommon.service.ah.a(SourceFile:181)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at com.android.emailcommon.service.ah.e(SourceFile:224)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:161)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:173)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:117)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:29.047  3837  3837 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:28:29.047  1017  1993 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@c9c4120
,03-17 12:28:29.067  4076  4076 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:28:29.077  1017  2782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-17 12:28:29.077  3837  4047 E SQLiteLog: (283) recovered 57 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 12:28:29.107  3373  3434 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 12:28:29.147   275  1012 D EnterpriseController: uids 10057
03-17 12:28:29.147   275  1012 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:28:29.147   275  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10057
,03-17 12:28:29.157  1017  3836 I ActivityManager: Killing 3257:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-17 12:28:29.157  1017  3836 I ActivityManager: Killing 3065:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #32
,03-17 12:28:29.177  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3113/cgroup.procs: No such file or directory
03-17 12:28:29.177  1017  1041 W libprocessgroup: failed to open /acct/uid_10159/pid_3176/cgroup.procs: No such file or directory
,03-17 12:28:29.177  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3192/cgroup.procs: No such file or directory
03-17 12:28:29.177  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3217/cgroup.procs: No such file or directory
,03-17 12:28:29.257  3949  3949 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 12:28:29.257  3949  3949 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 12:28:29.257  1017  2782 D SSRM:n  : SIOP:: AP = 390
,03-17 12:28:29.277  3949  3949 D DialogFlow: initQueue()
,03-17 12:28:29.297  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,03-17 12:28:29.297  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:28:29.297  1017  1041 W libprocessgroup: failed to open /acct/uid_10085/pid_3065/cgroup.procs: No such file or directory
,03-17 12:28:29.307  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3257/cgroup.procs: No such file or directory
,03-17 12:28:29.307  1017  3836 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,03-17 12:28:29.307  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:29.307  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:29.307  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:29.307  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:29.307  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:28:29.307  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 12:28:29.307  3987  4024 I AMMetaDataParserService: Resource data:2131165186
,03-17 12:28:29.317  3987  4024 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
03-17 12:28:29.317  3987  4024 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:29.317  3987  4024 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
03-17 12:28:29.317  3987  4024 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-17 12:28:29.317  3987  4024 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:28:29.317  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:29.327  4106  4106 E Zygote  : MountEmulatedStorage(),
,03-17 12:28:29.327  4106  4106 E Zygote  : v2
03-17 12:28:29.327  4106  4106 I libpersona: KNOX_SDCARD checking this for 10032
03-17 12:28:29.327  4106  4106 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:29.327  4106  4106 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:29.327  1017  3836 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4106 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-17 12:28:29.327  1017  3836 I ActivityManager: Killing 3298:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,03-17 12:28:29.337  4106  4106 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:29.337  4106  4106 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:29.347  3987  4024 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,03-17 12:28:29.367  3460  3474 W art     : Suspending all threads took: 133.991ms
,03-17 12:28:29.387  3287  3345 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 12:28:29.397  4106  4106 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:29.397  4106  4106 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:29.497  1017  3168 D TimaService: TIMA: in getTimaVersion
,03-17 12:28:29.497  1017  3836 D TimaService: TIMA3: KeyStore3_init
03-17 12:28:29.497  1017  3836 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
03-17 12:28:29.497  1017  3836 D TimaService: TIMA: in getTimaVersion
03-17 12:28:29.497  1017  3836 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-17 12:28:29.497  1017  3836 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-17 12:28:29.497  1017  3836 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
03-17 12:28:29.497  1017  3836 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
03-17 12:28:29.497  1017  3836 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-17 12:28:29.497  1017  3836 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
03-17 12:28:29.497  1017  3836 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-17 12:28:29.497  1017  3836 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-17 12:28:29.497  1017  3836 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
03-17 12:28:29.497  1017  3836 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
03-17 12:28:29.497  1017  3836 D QSEECOMAPI: : App is not loaded in QSEE
03-17 12:28:29.497  3987  4024 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-17 12:28:29.527  3460  4040 I System.out: Thread-526 calls detatch()
,03-17 12:28:29.577  1017  1041 W libprocessgroup: failed to open /acct/uid_10150/pid_3298/cgroup.procs: No such file or directory
,03-17 12:28:29.607  1017  3836 D QSEECOMAPI: : Loaded image: APP id = 10
,03-17 12:28:29.607  1017  3836 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
,03-17 12:28:29.607  1017  3836 I TLC_TZ_KEYSTORE: : ctx = 0xb7afcb68, comm = 0xb7b3cb58, sendmsg = 0x9f64d000, recvmsg = 0x9f64d440
,03-17 12:28:29.607  1017  3836 I TZ_init: : TZ_init: sending initialization request...
,03-17 12:28:29.617  3987  4024 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,03-17 12:28:29.617  1017  2857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:28:29.617  1017  3836 E TZ_init: : TZ_init Process: Secure memory is not initialized!
,03-17 12:28:29.617  1017  3836 E TZ_init: : trustlet initialization failed
,03-17 12:28:29.617  1017  3836 I TZ_init: : TZ_init_START...
,03-17 12:28:29.627  1017  3836 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-17 12:28:29.627  1017  3836 I TZ_init: : TZ_init: successful initialization
,03-17 12:28:29.627  1017  3836 D QSEECOMAPI: : QSEECom_dealloc_memory 
,03-17 12:28:29.627  1017  3836 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-17 12:28:29.627  1017  3836 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-17 12:28:29.637  1017  1395 I art     : Explicit concurrent mark sweep GC freed 23550(1365KB) AllocSpace objects, 5(86KB) LOS objects, 33% free, 26MB/39MB, paused 2.460ms total 169.645ms,
,03-17 12:28:29.657  3837  4047 E File    : fail readDirectory() errno=2
,03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 12:28:29.697  3987  4024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.,SelectBookmarkFolderActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
,03-17 12:28:29.697  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,03-17 12:28:29.707  1636  1649 I art     : Explicit concurrent mark sweep GC freed 4086(180KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 778us total 28.137ms
,03-17 12:28:29.717  1636  1654 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 12:28:29.727  3837  4130 I Gmail   : getAccountsCursor
,03-17 12:28:29.727  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-17 12:28:29.727  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:29.727  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:29.727  3987  4024 I AMMetaDataParserService: Resource data:2131034113
,03-17 12:28:29.727  1017  3172 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 12:28:29.727  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:28:29.747  1017  1395 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,03-17 12:28:29.747  1864  1864 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:29.747  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:29.747  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:29.747  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:29.747  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:29.757  4053  4053 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
03-17 12:28:29.757  3987  4024 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 12:28:29.757  3987  4024 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:29.757  3987  4024 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 12:28:29.757  3987  4024 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-17 12:28:29.757  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
03-17 12:28:29.757  4132  4132 E Zygote  : MountEmulatedStorage(),
03-17 12:28:29.757  4132  4132 E Zygote  : v2
,03-17 12:28:29.767  4132  4132 I libpersona: KNOX_SDCARD checking this for 10033
,03-17 12:28:29.767  4132  4132 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:29.767  3837  4072 I Gmail   : notifyAccountChanged
,03-17 12:28:29.767  4132  4132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:29.767  4132  4132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:29.767  4132  4132 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 12:28:29.777  1017  1395 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4132 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 12:28:29.777  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:29.777  3987  4024 I GFX construct_block_size_descriptor_2d second part: took 2.213802ms for 0*0 texture 0
,03-17 12:28:29.787  1017  3168 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
03-17 12:28:29.787  1017  3168 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 12:28:29.787  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:29.787  1017  3168 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:29.787  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 12:28:29.797  1864  1864 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-17 12:28:29.797   301   301 I art     : Explicit concurrent mark sweep GC freed 8758(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 31.756ms
,03-17 12:28:29.797  1864  1864 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-17 12:28:29.797  4132  4132 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:29.807  4132  4132 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:29.817  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,03-17 12:28:29.817  1017  1486 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
,03-17 12:28:29.817  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-17 12:28:29.817   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 664us total 20.791ms
,03-17 12:28:29.837  3987  4024 I GFX generate_partition_tables: took 6.322188ms for 0*0 texture 0
,03-17 12:28:29.837  3987  4024 I GFX raster: took 9.809114ms for 96*96 texture 0
,03-17 12:28:29.837  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7686f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7687350 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:29.837   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.007ms total 17.908ms
,03-17 12:28:29.847  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:29.847  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:29.847  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-17 12:28:29.857  1017  3172 D ActivityManager: startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,03-17 12:28:29.857  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:29.857  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:29.857  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:29.857  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:29.867  4150  4150 E Zygote  : MountEmulatedStorage()
,03-17 12:28:29.867  4150  4150 E Zygote  : v2
03-17 12:28:29.867  4150  4150 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 12:28:29.877  4150  4150 I libpersona: KNOX_SDCARD not a persona,
,03-17 12:28:29.877  4150  4150 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:29.877  4150  4150 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:29.877  4150  4150 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:29.877  1017  3172 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4150 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:29.887  1017  3168 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:29.887  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:29.887  1017  3168 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:29.887  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:29.897  3987  4024 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 12:28:29.907  4150  4150 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:29.907  4150  4150 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:29.917  1017  1029 I ActivityManager: Killing 3328:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-17 12:28:29.937  3837  4072 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 12:28:29.967  4150  4150 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 12:28:29.987  4150  4150 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:28:29.987  1017  1342 D ActivityManager: startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
03-17 12:28:29.987  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-17 12:28:29.987  1017  1342 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:29.987  1017  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:29.987  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 12:28:30.007  4150  4150 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 12:28:30.007  4150  4150 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 12:28:30.007  1017  3172 D ActivityManager: bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
03-17 12:28:30.007  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-17 12:28:30.017  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:30.017  1017  3172 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:30.017  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 12:28:30.037  4150  4150 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
,03-17 12:28:30.037  4150  4150 I F_PHONE : default registerAction()
,03-17 12:28:30.037  4150  4150 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 12:28:30.047  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3328/cgroup.procs: No such file or directory
,03-17 12:28:30.067  3837  4072 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing,
,03-17 12:28:30.157  3837  4072 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 12:28:30.157  3837  4072 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 12:28:30.187  4053  4053 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-17 12:28:30.197  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:30.207  3987  4024 I GFX raster: took 1.024479ms for 96*96 texture 0
,03-17 12:28:30.207  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7686f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb768f3e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:30.217  3987  4024 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 12:28:30.227  4132  4132 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 12:28:30.227  4132  4132 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:30.227  4132  4132 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 12:28:30.227  3547  3557 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-17 12:28:30.237  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{2c9e5a6d u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-17 12:28:30.237  1017  1993 W SEAMService:  hashset_to_int_array returning null
,03-17 12:28:30.247  4132  4132 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:28:30.247  4132  4132 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:30.247  4132  4132 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:30.267  4025  4025 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id),
03-17 12:28:30.267  1017  1486 W SEAMService:  hashset_to_int_array returning null
03-17 12:28:30.267  4025  4025 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
03-17 12:28:30.267  4132  4132 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:28:30.267  4132  4132 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 12:28:30.267  4132  4132 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-17 12:28:30.267  1017  1476 W SEAMService:  hashset_to_int_array returning null
,03-17 12:28:30.277  4053  4053 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:28:30.287  1017  1993 I ActivityManager: Killing 3373:com.policydm/1000 (adj 15): empty #31
,03-17 12:28:30.287  1017  3168 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:28:30.287  1017  3168 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4303, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,03-17 12:28:30.287  1017  3168 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,03-17 12:28:30.287  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 12:28:30.297  1017  1017 I MotionRecognitionService: Plugged
,03-17 12:28:30.297  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 12:28:30.307  4053  4053 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:28:30.307  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 12:28:30.307  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 12:28:30.317  1191  1191 D PowerUI : Cable  true --> true mBootCompleted : true
03-17 12:28:30.317  1191  1191 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-17 12:28:30.317  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 12:28:30.317  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 12:28:30.317  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:30.327  3987  4024 I GFX construct_block_size_descriptor_2d second part: took 2.552917ms for 0*0 texture 0
,03-17 12:28:30.347  2692  2692 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 12:28:30.347  2692  2781 D HeadsetStateMachine: Disconnected process message: 10
,03-17 12:28:30.347  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 12:28:30.347  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-17 12:28:30.347  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-17 12:28:30.357  3987  4024 I GFX generate_partition_tables: took 7.706303ms for 0*0 texture 0
,03-17 12:28:30.357  4076  4191 I Babel   : MmsConfig: mnc/mcc: 0/0
03-17 12:28:30.357  4076  4191 I Babel   : MmsConfig.loadMmsSettings
03-17 12:28:30.357  4076  4191 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
03-17 12:28:30.357  4076  4191 I Babel   : MmsConfig.loadFromDatabase
,03-17 12:28:30.367  3987  4024 I GFX raster: took 11.251928ms for 96*96 texture 0
03-17 12:28:30.367  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768c078 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768c1d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:30.387  3987  4024 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 12:28:30.397  3837  3968 I Gmail   : getAccountsCursor
,03-17 12:28:30.397  1017  3172 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 12:28:30.397  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:28:30.397  3287  3345 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 12:28:30.407  1864  1864 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:30.417  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:30.417  3987  4024 I GFX raster: took 0.605052ms for 96*96 texture 0
03-17 12:28:30.417  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768ffe8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7690140 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:30.457  3987  4024 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 12:28:30.467  4053  4179 D Volley  : [608] DiskBasedCache.clear: Cache cleared.,
03-17 12:28:30.467  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3373/cgroup.procs: No such file or directory
,03-17 12:28:30.477  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:30.477  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:30.477  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:30.477  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:30.487  4053  4159 D Volley  : [601] DiskBasedCache.clear: Cache cleared.
,03-17 12:28:30.487  1017  1342 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
03-17 12:28:30.487  4076  4191 E Babel   : canonicalizeMccMnc: invalid mccmnc 
03-17 12:28:30.487  4076  4191 I Babel   : MmsConfig.loadFromResources
,03-17 12:28:30.487  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,03-17 12:28:30.487  4076  4191 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 12:28:30.487  4076  4191 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,03-17 12:28:30.497  1017  1342 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:30.497  1017  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:30.497  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 12:28:30.507  1017  1476 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
03-17 12:28:30.507  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-17 12:28:30.507  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:30.507  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:30.507  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 12:28:30.537  3871  4195 D FileApkUtils: Optimizing (staging complete)
,03-17 12:28:30.537  3871  4195 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
,03-17 12:28:30.537  3871  4195 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-17 12:28:30.547  3871  4195 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
03-17 12:28:30.547  3871  4195 D DexOptUtils: Lollipop platform, using <isa> directory.
,03-17 12:28:30.547  3871  4195 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-17 12:28:30.547  3871  4195 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-17 12:28:30.547  4076  4076 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 12:28:30.557  4053  4193 D Ads     : Skipping gmscore version check
,03-17 12:28:30.557  4053  4053 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-17 12:28:30.557  4053  4053 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-17 12:28:30.567  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:28:30.567  3987  4024 I GFX raster: took 0.817656ms for 96*96 texture 0
03-17 12:28:30.567  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768dc18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768dd70 counterpartCT=4 counterpartW=96 counterparth=96
03-17 12:28:30.567  3987  4024 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 12:28:30.667  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:30.667  3987  4024 I GFX raster: took 0.637656ms for 96*96 texture 0
03-17 12:28:30.667  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768fcd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768c260 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:30.667  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 12:28:30.677  1017  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:30.677  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,03-17 12:28:30.677  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:30.677  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:30.677  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:30.677  1017  1993 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:30.677  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:30.677  1017  1993 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:30.677  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 12:28:30.707  1017  3172 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:30.707  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 12:28:30.707  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:30.707  1017  3172 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:30.707  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:30.747  4197  4197 I dex2oat : ----------------------------------------------------
03-17 12:28:30.747  4197  4197 I dex2oat : <SS>: S T A R T I N G . . .
03-17 12:28:30.747  4197  4197 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 12:28:30.747  4197  4197 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=35 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 12:28:30.767  4076  4076 I Babel_StickerModule: App launched.
,03-17 12:28:30.767  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:30.767  3987  4024 I GFX raster: took 0.721719ms for 96*96 texture 0
03-17 12:28:30.767  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76873e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768c260 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:30.777  1017  3172 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:30.777  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:30.777  1017  3172 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:30.777  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:30.777  4053  4053 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-17 12:28:30.787  1017  1491 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
03-17 12:28:30.787  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,03-17 12:28:30.787  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:30.787  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:30.787  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 12:28:30.797  3987  4024 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 12:28:30.807  4076  4091 W art     : Suspending all threads took: 16.404ms
,03-17 12:28:30.897  4053  4053 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-17 12:28:30.897  1864  1864 D ChimeraCfgMgr: Reading stored module config
,03-17 12:28:30.897  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:30.897  3987  4024 I GFX raster: took 0.526667ms for 96*96 texture 0
03-17 12:28:30.897  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768c260 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768fef8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:30.907  3987  4024 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 12:28:30.927  1864  1864 D WearableService: callingUid 10012, callindPid: 1864
,03-17 12:28:30.927  4076  4076 V Babel   : babel boot account: SMS
,03-17 12:28:30.947  3871  3871 W InstanceID/Rpc: Found 10012
,03-17 12:28:30.947  1864  1864 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 12:28:30.957  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-17 12:28:30.957  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:30.957  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:30.957  3987  4024 I AMMetaDataParserService: Resource data:2131034113
,03-17 12:28:30.957  3987  4024 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 12:28:30.957  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:30.957  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:30.957  3987  4024 I GFX raster: took 1.043073ms for 96*96 texture 0
03-17 12:28:30.957  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7686f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7690768 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:30.967  4076  4076 W Babel   : EsDatabaseHelper.static should not be called on main thread [called on main thread]
,03-17 12:28:30.967  4076  4076 W Babel   : java.lang.Exception
03-17 12:28:30.967  4076  4076 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 12:28:30.967  4076  4076 W Babel   : 	at aes.<clinit>(SourceFile:95)
03-17 12:28:30.967  4076  4076 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 12:28:30.967  4076  4076 W Babel   : 	at ckh.a(SourceFile:67)
03-17 12:28:30.967  4076  4076 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 12:28:30.967  4076  4076 W Babel   : 	at bhn.a(SourceFile:301)
03-17 12:28:30.967  4076  4076 W Babel   : 	at bhn.a(SourceFile:137)
03-17 12:28:30.967  4076  4076 W Babel   : 	at bhn.a(SourceFile:126)
03-17 12:28:30.967  4076  4076 W Babel   : 	at bhn.a(SourceFile:159)
03-17 12:28:30.967  4076  4076 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:30.967  4076  4076 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:30.967  4076  4076 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:30.967  4076  4076 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:30.967  4076  4076 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 12:28:30.967  4076  4076 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-17 12:28:30.967  4076  4076 W Babel   : java.lang.Exception
03-17 12:28:30.967  4076  4076 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 12:28:30.967  4076  4076 W Babel   : 	at aes.a(SourceFile:145)
03-17 12:28:30.967  4076  4076 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 12:28:30.967  4076  4076 W Babel   : 	at ckh.a(SourceFile:67)
03-17 12:28:30.967  4076  4076 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 12:28:30.967  4076  4076 W Babel   : 	at bhn.a(SourceFile:301)
03-17 12:28:30.967  4076  4076 W Babel   : 	at bhn.a(SourceFile:137)
03-17 12:28:30.967  4076  4076 W Babel   : 	at bhn.a(SourceFile:126)
03-17 12:28:30.967  4076  4076 W Babel   : 	at bhn.a(SourceFile:159)
03-17 12:28:30.967  4076  4076 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:30.967  4076  4076 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:30.967  4076  4076 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:30.967  4076  4076 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:30.967  4076  4076 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:30.967  4076  4076 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 12:28:30.977  3987  4024 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 12:28:31.007  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:31.007  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.007  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.007  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:31.007  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.007  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.007  3987  4024 I GFX raster: took 0.839218ms for 96*96 texture 0
03-17 12:28:31.007  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7686f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb768a2d8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.017  3987  4024 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 12:28:31.047  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:31.047  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.047  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:31.047  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.047  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.047  1017  1150 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 12:28:31.047  1017  1150 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.047  1017  1150 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.047  1017  1150 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:31.047  1017  1150 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 12:28:31.057  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:31.057  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.057  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.057  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:31.057  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.067  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 12:28:31.067  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.067  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.077  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.077  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 12:28:31.077  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 12:28:31.077  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.077  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:31.077  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.077  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 12:28:31.087  4076  4076 V Babel   : babel boot account: thalitester@gmail.com
,03-17 12:28:31.087  1017  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:31.087  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.087  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:31.087  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.087  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.097  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.097  3987  4024 I GFX raster: took 0.606250ms for 96*96 texture 0
03-17 12:28:31.097  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768a7e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73e7e40 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.107  3987  4024 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 12:28:31.117  4076  4076 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-17 12:28:31.117  4076  4076 W Babel   : java.lang.Exception
03-17 12:28:31.117  4076  4076 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 12:28:31.117  4076  4076 W Babel   : 	at aes.a(SourceFile:145)
03-17 12:28:31.117  4076  4076 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 12:28:31.117  4076  4076 W Babel   : 	at ckh.a(SourceFile:67)
03-17 12:28:31.117  4076  4076 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 12:28:31.117  4076  4076 W Babel   : 	at bhn.a(SourceFile:301)
03-17 12:28:31.117  4076  4076 W Babel   : 	at bhn.a(SourceFile:137)
03-17 12:28:31.117  4076  4076 W Babel   : 	at bhn.a(SourceFile:126)
03-17 12:28:31.117  4076  4076 W Babel   : 	at bhn.a(SourceFile:159)
03-17 12:28:31.117  4076  4076 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 12:28:31.117  4076  4076 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 12:28:31.117  4076  4076 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 12:28:31.117  4076  4076 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 12:28:31.117  4076  4076 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:31.117  4076  4076 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:31.117  4076  4076 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:31.117  4076  4076 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:31.117  4076  4076 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:31.117  4076  4076 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:31.117  4076  4076 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 12:28:31.137  3437  3639 I System.out: Thread-468(ApacheHTTPLog):isSBSettingEnabled false,
03-17 12:28:31.137  3437  3639 I System.out: Thread-468(ApacheHTTPLog):isShipBuild true
03-17 12:28:31.137  3437  3639 I System.out: Thread-468(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 12:28:31.137  3437  3639 I System.out: Thread-468(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 12:28:31.137   275  1012 D EnterpriseController: uids 10092
03-17 12:28:31.137   275  1012 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:28:31.137   275  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 12:28:31.167  4106  4123 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:28:31.177  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.177  3987  4024 I GFX raster: took 0.599844ms for 96*96 texture 0
03-17 12:28:31.177  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768f2f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb766eba8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.187  4132  4132 I Process : Sending signal. PID: 4132 SIG: 9
,03-17 12:28:31.187  3987  4024 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 12:28:31.197  1017  3836 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:31.197  1017  3836 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.197  1017  3836 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.197  1017  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.197  1017  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.207  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.207  3987  4024 I GFX raster: took 0.828542ms for 96*96 texture 0
03-17 12:28:31.207  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768fcd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7681b60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.207  1017  1342 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 12:28:31.207  3987  4024 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
03-17 12:28:31.207  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.217  1017  1342 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.217  1017  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:31.217  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 12:28:31.217  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 12:28:31.217  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.217  3437  4220 D GCMRegistrar: resetting backoff for com.dropbox.android
,03-17 12:28:31.227  3437  4220 V GCMRegistrar: Registering app com.dropbox.android of senders 735665981150
,03-17 12:28:31.237  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.237  3987  4024 I GFX raster: took 0.625625ms for 96*96 texture 0
03-17 12:28:31.237  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73e7e40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73e6570 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.247  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 12:28:31.247  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.257  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:31.257  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:28:31.257  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 12:28:31.257  3987  4024 I GFX raster: took 0.759583ms for 96*96 texture 0
03-17 12:28:31.257  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb764fd10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb764d8a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.257  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:31.257  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.257  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.257  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
,03-17 12:28:31.267  3987  4024 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 12:28:31.267  3871  4219 D GCM     : COMPAT: Multi user not supported,
,03-17 12:28:31.277  1017  3836 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 12:28:31.277  1017  3836 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.277  1017  3836 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.277  1017  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.277  1017  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 12:28:31.287  1017  1342 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:31.287  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.287  1017  1342 W ActivityManager: userId = 0, bbcId = -10000,
03-17 12:28:31.287  1017  1342 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
03-17 12:28:31.287  1017  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.287  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.287  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:31.287  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:31.287  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:31.287  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.297  4106  4123 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:28:31.297  4106  4123 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:28:31.297  1864  1864 D GCM     : COMPAT: Multi user not supported
03-17 12:28:31.297  4106  4123 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:31.307  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.307  3987  4024 I GFX raster: took 0.539323ms for 96*96 texture 0,
03-17 12:28:31.307  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb766ef70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73b9ef8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.317  3987  4024 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 12:28:31.327  4231  4231 E Zygote  : MountEmulatedStorage()
03-17 12:28:31.327  1017  1342 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4231 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:31.327  4231  4231 E Zygote  : v2
03-17 12:28:31.327  4231  4231 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:31.327  4231  4231 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:31.327  1017  1993 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:31.337  1017  1993 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.337  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:31.337  1017  1993 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.337  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:28:31.337  3987 , 4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:31.337  3987  4024 I AMMetaDataParserService: Resource data:2131034112
03-17 12:28:31.337  4231  4231 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:31.337  4231  4231 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:31.347  1017  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:31.347  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:31.347  1017  1490 I ActivityManager: Process com.sec.android.app.sns3 (pid 4132)(adj 0) has died(38,1110)
03-17 12:28:31.347  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.347  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 12:28:31.347  3987  4024 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-17 12:28:31.347  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
03-17 12:28:31.347  4231  4231 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:31.347  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:28:31.347  3987  4024 I GFX raster: took 0.602448ms for 96*96 texture 0
03-17 12:28:31.347  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768f2f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7681b60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.357  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,03-17 12:28:31.357  3987  4024 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
03-17 12:28:31.357  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:31.357  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:31.357  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:31.357  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.377  1017  1042 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4240 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
03-17 12:28:31.377  4240  4240 E Zygote  : MountEmulatedStorage()
03-17 12:28:31.377  4240  4240 I libpersona: KNOX_SDCARD checking this for 10034
03-17 12:28:31.377  4240  4240 E Zygote  : v2
03-17 12:28:31.377  4240  4240 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:31.377  4240  4240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:31.377   280   280 W QCamera2Factory: getCameraInfo: E, camera_id = 0
03-17 12:28:31.377   280   280 W QCamera2Factory: getCameraInfo: X
,03-17 12:28:31.387  1017  1039 D SensorService: [SO] 0.153 0.421 10.132
,03-17 12:28:31.387  4240  4240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:31.387  4240  4240 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:31.387   280   984 W QCamera2Factory: getCameraInfo: E, camera_id = 1
03-17 12:28:31.387   280   984 W QCamera2Factory: getCameraInfo: X
03-17 12:28:31.397  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.397  3987  4024 I GFX raster: took 0.613594ms for 96*96 texture 0
03-17 12:28:31.397  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768f2f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76678e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.397  3287  3345 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-17 12:28:31.407  4231  4231 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:31.407  4231  4231 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:31.407  3987  4024 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-17 12:28:31.427  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:31.427  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.437  3871  4264 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 12:28:31.437  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.437  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:31.437  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.437  1017  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:31.437  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.447  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.447  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:31.447  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.447  1017  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:31.447  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.457  4240  4240 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:31.457  4240  4240 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:31.457  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:31.457  3871  3871 D SystemUpdateService: onCreate
,03-17 12:28:31.457  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:31.457  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.477  1017  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:31.477  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.477  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:31.477  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.477  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.477  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.477  3987  4024 I GFX raster: took 0.648177ms for 96*96 texture 0
03-17 12:28:31.477  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb766eba8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb73e6570 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.487  4076  4076 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:28:31.497  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:31.497  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 12:28:31.497  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:31.497  4076  4076 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 12:28:31.497  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.497  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.507  4076  4076 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 12:28:31.507  3871  4219 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 12:28:31.517  1017  1342 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:31.517  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.517  1017  1342 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.517  1017  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.517  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.527  3987  4024 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-17 12:28:31.547  4076  4076 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 12:28:31.547   286   286 E SMD     : DCD OFF
,03-17 12:28:31.547  4076  4076 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 12:28:31.557  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.557  3987  4024 I GFX raster: took 0.752084ms for 96*96 texture 0
03-17 12:28:31.557  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73e7e40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb764d8a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.567  1017  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-17 12:28:31.567  4076  4076 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 12:28:31.567  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-17 12:28:31.577  4076  4076 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 12:28:31.597  4076  4076 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 12:28:31.597  4076  4076 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 12:28:31.607  3871  3871 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 12:28:31.647  1017  1150 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:31.647  1017  1150 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
,03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
,03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
,03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-17 12:28:31.647  1017  1150 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:31.647  1017  1150 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.647  1017  1150 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
,03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-17 12:28:31.647  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
,03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
,03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
,03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
,03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
,03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
,03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
,03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
,03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: Resource data:2131034113
,03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
,03-17 12:28:31.657  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:31.657  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.667  3987  4024 I GFX raster: took 0.921407ms for 96*96 texture 0
,03-17 12:28:31.667  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7686f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76678e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.677  4076  4076 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 12:28:31.697  4076  4076 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 12:28:31.697  3987  4024 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 12:28:31.707  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.707  3987  4024 I GFX raster: took 0.819114ms for 96*96 texture 0
03-17 12:28:31.707  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7686f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb768fb40 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.717  3871  4272 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 12:28:31.717  1017  1234 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,03-17 12:28:31.717  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.717  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.717  3987  4024 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
03-17 12:28:31.717  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:31.717  1017  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.727  4076  4076 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es,
,03-17 12:28:31.737  4274  4274 E Zygote  : MountEmulatedStorage(),
03-17 12:28:31.737  4274  4274 E Zygote  : v2
03-17 12:28:31.737  4274  4274 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 12:28:31.737  4274  4274 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:31.737  4274  4274 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:31.737  1017  1234 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4274 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:31.737  1017  1234 I ActivityManager: Killing 3348:com.google.android.configupdater/u0a86 (adj 15): empty #31
,03-17 12:28:31.747  4274  4274 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:31.747  4274  4274 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:31.747  4076  4076 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 12:28:31.747  1017  1395 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:31.747  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 12:28:31.747  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.757  3987  4024 I GFX raster: took 0.834636ms for 96*96 texture 0
,03-17 12:28:31.757  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768a7e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7681b60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.757  4076  4076 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 12:28:31.767  3987  4024 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 12:28:31.777  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.777  3987  4024 I GFX raster: took 0.600677ms for 96*96 texture 0
,03-17 12:28:31.777  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768f2f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73b9ef8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.777  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:31.787  1017  1395 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:31.787  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:31.787  4274  4274 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:31.787  4274  4274 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:31.797  4076  4076 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 12:28:31.807  3987  4024 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 12:28:31.807  4076  4076 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 12:28:31.807  1017  1150 D ActivityManager: startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,03-17 12:28:31.807  4076  4076 W VideoCapabilities: Unsupported mime video/mp43
,03-17 12:28:31.817  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.817  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.817  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.817  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.817  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:28:31.827  3987  4024 I GFX raster: took 0.858541ms for 96*96 texture 0
03-17 12:28:31.827  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb768fcd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73e6570 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.837  4289  4289 E Zygote  : MountEmulatedStorage(),
03-17 12:28:31.837  4289  4289 E Zygote  : v2
03-17 12:28:31.837  4289  4289 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 12:28:31.837  4289  4289 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:31.837  4289  4289 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 12:28:31.837  3987  4024 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 12:28:31.837  4289  4289 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:31.847  1017  1150 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4289 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:31.847  1017  1150 I ActivityManager: Killing 3437:com.dropbox.android/u0a92 (adj 15): empty #31
,03-17 12:28:31.847  4289  4289 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:31.847  4076  4076 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 12:28:31.867  4076  4076 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-17 12:28:31.887  3871  3871 D ChimeraCfgMgr: Reading stored module config
,03-17 12:28:31.887  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.897  3987  4024 I GFX raster: took 0.766563ms for 96*96 texture 0
03-17 12:28:31.897  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73e7e40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76678e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.897  4289  4289 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:31.897  4289  4289 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:31.897  4274  4274 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
03-17 12:28:31.897  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 12:28:31.947  4274  4274 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-17 12:28:31.957  4274  4274 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 12:28:31.967  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:31.967  3987  4024 I GFX raster: took 0.688333ms for 96*96 texture 0
03-17 12:28:31.967  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb764fd10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768fb40 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:31.967  4076  4076 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 12:28:31.967  3987  4024 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 12:28:31.977  4274  4274 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
,03-17 12:28:31.977  4274  4274 D ShortcutReceiver:  shortcut migration not required 
,03-17 12:28:31.977  3871  3885 W art     : Suspending all threads took: 35.838ms
,03-17 12:28:31.977  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,03-17 12:28:31.977  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.977  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.977  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:31.977  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:31.997  4308  4308 E Zygote  : MountEmulatedStorage(),
03-17 12:28:31.997  4308  4308 E Zygote  : v2
03-17 12:28:31.997  4308  4308 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 12:28:31.997  4308  4308 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:31.997  4308  4308 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:31.997  1017  1029 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4308 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 12:28:31.997  1017  1029 I ActivityManager: Killing 2826:com.google.android.apps.plus/u0a120 (adj 15): empty #31,
,03-17 12:28:32.007  4308  4308 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:32.007  4308  4308 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:32.027  4308  4308 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:32.027  4308  4308 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:32.057  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,03-17 12:28:32.057  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,03-17 12:28:32.057  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:32.057  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:32.057  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
03-17 12:28:32.057  4289  4289 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-17 12:28:32.067  4308  4308 E KnoxSetupWizardClient: isShipMode : 1
03-17 12:28:32.067  4308  4308 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 12:28:32.067  4289  4289 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 12:28:32.087  1017  1395 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,03-17 12:28:32.087  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:32.097  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:32.097  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:32.097  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:32.097  3871  4272 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED,
,03-17 12:28:32.107  4332  4332 E Zygote  : MountEmulatedStorage()
03-17 12:28:32.107  4332  4332 E Zygote  : v2
03-17 12:28:32.107  4332  4332 I libpersona: KNOX_SDCARD checking this for 10107
03-17 12:28:32.107  4332  4332 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:32.107  4332  4332 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:32.107  4332  4332 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:32.117  4332  4332 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:32.117  1017  1395 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4332 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 12:28:32.117  1017  1395 I ActivityManager: Killing 3511:com.fmm.dm/1000 (adj 15): empty #31
,03-17 12:28:32.117  1017  1234 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-17 12:28:32.117  1017  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 12:28:32.117  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:32.117  1017  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:32.117  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:32.147  4332  4332 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:32.157  4332  4332 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:32.177  4308  4328 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-17 12:28:32.177  4308  4328 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-17 12:28:32.177  4308  4328 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 12:28:32.177  4308  4328 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
03-17 12:28:32.177  4308  4328 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
03-17 12:28:32.177  4308  4328 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 12:28:32.177  4308  4328 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 12:28:32.197  1864  4348 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-17 12:28:32.197  4076  4330 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 12:28:32.217  4289  4323 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 12:28:32.217  4289  4289 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-17 12:28:32.217  4289  4323 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-17 12:28:32.217   275  1012 D EnterpriseController: uids 10012
03-17 12:28:32.217   275  1012 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:28:32.217   275  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,03-17 12:28:32.247  3871  3871 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-17 12:28:32.247  3871  3871 D BootCompletedReceiver: Got an BootCompleted event.
,03-17 12:28:32.247  3871  4265 I CheckinService: Checking schedule, now: 1458214112261 next: 1458246240395
03-17 12:28:32.247  3871  4265 I CheckinService: active receiver: disabled
,03-17 12:28:32.287  4076  4330 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 12:28:32.297  4289  4289 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 12:28:32.297  4076  4330 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 12:28:32.307  1864  1864 I GCoreUlr: DispatchingService.onCreate()
,03-17 12:28:32.327  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:32.327  3987  4024 I GFX raster: took 0.536718ms for 96*96 texture 0
03-17 12:28:32.327  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb766ef70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7681b60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:32.337  3987  4024 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 12:28:32.357  4076  4330 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 12:28:32.357  1864  4354 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
,03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-17 12:28:32.367  4289  4323 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
,03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
,03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
,03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:28:32.367  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 12:28:32.377  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
,03-17 12:28:32.377  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-17 12:28:32.377  3987  4024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 12:28:32.387  4076  4330 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 12:28:32.387  4289  4289 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 12:28:32.387  4289  4289 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 12:28:32.387  4289  4289 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-17 12:28:32.387  4289  4289 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 12:28:32.407  1017  1993 I ActivityManager: Killing 3529:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,03-17 12:28:32.417  3287  3345 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.Ac,countSecurity
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:32.417  3987  4024 I AMMetaDataParserService: Resource data:2131165203
,03-17 12:28:32.427  3987  4024 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 12:28:32.427  3987  4024 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:28:32.427  3987  4024 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:28:32.427  3987  4024 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:32.427  3987  4024 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:28:32.427  4289  4289 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-17 12:28:32.437  3987  4024 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-17 12:28:32.437  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:32.437  3871  4269 I SystemUpdateService: cancelUpdate (empty URL)
,03-17 12:28:32.437  3871  4269 I SystemUpdateService: active receiver: disabled
,03-17 12:28:32.457  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:32.457  3987  4024 I GFX construct_block_size_descriptor_2d second part: took 2.714427ms for 0*0 texture 0
,03-17 12:28:32.467  1017  1993 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,03-17 12:28:32.467  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:32.467  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:32.467  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:32.467  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:32.477  1864  4353 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED,
03-17 12:28:32.477  3871  4272 W BaseAppContext: Using Auth Proxy for data requests.
03-17 12:28:32.477  3871  3871 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-17 12:28:32.487  4355  4355 E Zygote  : MountEmulatedStorage()
,03-17 12:28:32.487  4355  4355 I libpersona: KNOX_SDCARD checking this for 10035
03-17 12:28:32.487  4355  4355 E Zygote  : v2
03-17 12:28:32.487  4355  4355 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:32.487  4355  4355 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:32.487  4355  4355 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:32.487  4355  4355 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,03-17 12:28:32.487  1017  1993 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4355 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 12:28:32.497  1017  1993 I ActivityManager: Killing 3563:com.fmm.ds/1000 (adj 15): empty #31,
,03-17 12:28:32.527  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 12:28:32.527  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:32.527  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:32.527  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:32.527  4355  4355 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:32.527  4355  4355 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:32.537  1864  4347 I GCM     : GCM config loaded
,03-17 12:28:32.567  3987  4024 I GFX generate_partition_tables: took 10.177033ms for 0*0 texture 0
,03-17 12:28:32.567  3987  4024 I GFX raster: took 13.766668ms for 96*96 texture 0
03-17 12:28:32.567  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7654858 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb766d7a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:32.567  3987  4024 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-17 12:28:32.587  1017  1051 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-17 12:28:32.587  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-17 12:28:32.587  1017  1051 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 12:28:32.587  1017  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 12:28:32.587  1017  1171 D lights  : lcd : 57 +
,03-17 12:28:32.607  1017  1171 D lights  : lcd : 57 -
03-17 12:28:32.607  1017  1171 D lights  : lcd : 23 +
,03-17 12:28:32.617  3871  4272 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-17 12:28:32.627  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 12:28:32.627  1017  1051 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 12:28:32.627  1017  1171 D lights  : lcd : 23 -
03-17 12:28:32.627  1017  1171 D lights  : lcd : 19 +
,03-17 12:28:32.637  1017  1171 D lights  : lcd : 19 -
,03-17 12:28:32.637  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 12:28:32.637  1017  1051 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 12:28:32.647   255   523 I SecDataIO: Write to block
,03-17 12:28:32.657  1017  1041 W libprocessgroup: failed to open /acct/uid_10086/pid_3348/cgroup.procs: No such file or directory
,03-17 12:28:32.657  1017  1041 W libprocessgroup: failed to open /acct/uid_10092/pid_3437/cgroup.procs: No such file or directory
03-17 12:28:32.657  1017  1041 W libprocessgroup: failed to open /acct/uid_10120/pid_2826/cgroup.procs: No such file or directory
03-17 12:28:32.657  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3511/cgroup.procs: No such file or directory
03-17 12:28:32.657  1017  1041 W libprocessgroup: failed to open /acct/uid_10092/pid_3529/cgroup.procs: No such file or directory
03-17 12:28:32.657  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3563/cgroup.procs: No such file or directory
,03-17 12:28:32.707  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:32.717  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-17 12:28:32.717  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:32.717  3987  4024 I GFX raster: took 0.819113ms for 96*96 texture 0
,03-17 12:28:32.717  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:32.717  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:32.717  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:32.727  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7656aa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7656b50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:32.757  2637  3281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-17 12:28:32.757  3987  4024 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 12:28:32.757  3287  3287 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-17 12:28:32.767  3287  3287 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-17 12:28:32.767  3287  3287 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
03-17 12:28:32.767  1017  3172 I art     : Explicit concurrent mark sweep GC freed 34427(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 26MB/40MB, paused 3.121ms total 202.319ms
,03-17 12:28:32.767  3871  4272 I AuthZen : Fetching signing key...
,03-17 12:28:32.777  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-17 12:28:32.777  2637  2637 I Process : Sending signal. PID: 2637 SIG: 9
,03-17 12:28:32.777  1017  1043 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
03-17 12:28:32.777  1017  1043 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 12:28:32.787  1017  1043 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 12:28:32.797  4355  4386 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-17 12:28:32.797  4355  4386 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-17 12:28:32.797  4355  4355 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-17 12:28:32.807  1017  3172 I ActivityManager: Process com.sec.android.app.sysscope (pid 2637)(adj 0) has died(37,1107)
,03-17 12:28:32.817  4289  4323 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 12:28:32.817  4289  4323 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:28:32.827  4355  4386 D SPPClientService: PushLog.txt file is not deleted.
03-17 12:28:32.827  4355  4386 D SPPClientService: PushLog.txt file is not deleted.
03-17 12:28:32.827  4355  4386 D SPPClientService: ============PushLog. stop!
,03-17 12:28:32.827  3871  4272 I AuthZen : Signing key fetched successfully!
03-17 12:28:32.827  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:32.827  3987  4024 I GFX raster: took 0.782708ms for 96*96 texture 0
03-17 12:28:32.827  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7656aa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb765a258 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:32.837  3871  4272 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 12:28:32.837  4289  4323 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-17 12:28:32.837  3987  4024 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 12:28:32.847  4289  4323 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-17 12:28:32.857  4289  4323 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-17 12:28:32.857  1017  3168 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:32.867  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:32.867  1017  3168 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:32.867  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:32.867  1017  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:32.877  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:32.877  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:32.877  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:32.887  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,03-17 12:28:32.887  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:32.887  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:32.887  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:32.887  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:32.907  4393  4393 E Zygote  : MountEmulatedStorage(),
03-17 12:28:32.907  4393  4393 I libpersona: KNOX_SDCARD checking this for 10041
03-17 12:28:32.907  4393  4393 E Zygote  : v2
,03-17 12:28:32.907  4393  4393 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:32.907  4393  4393 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:32.907  4393  4393 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 12:28:32.907  1017  1030 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4393 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:28:32.907  4393  4393 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
03-17 12:28:32.907  1017  1030 I ActivityManager: Killing 3582:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,03-17 12:28:32.917  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:32.917  3987  4024 I GFX raster: took 0.816667ms for 96*96 texture 0
03-17 12:28:32.917  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7656aa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb765b5f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:32.927  1017  1150 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:32.937  1017  1150 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:32.937  1017  1150 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:32.937  1017  1150 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:32.937  3987  4024 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 12:28:32.937  4393  4393 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:32.937  4393  4393 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:32.967  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:32.967  3987  4024 I GFX raster: took 0.655156ms for 96*96 texture 0
03-17 12:28:32.967  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb765d968 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb765f580 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:32.997  4289  4323 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-17 12:28:33.007  3871  4272 D a       : Opening database auth.proximity.permit_store...
,03-17 12:28:33.017  3871  3871 D SystemUpdateService: onDestroy
,03-17 12:28:33.027  3871  4272 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,03-17 12:28:33.027  3871  4272 D AuthZenTransactionCache: Clearing transaction cache
,03-17 12:28:33.037  4289  4323 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 12:28:33.047  3987  4024 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 12:28:33.057  1864  4353 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-17 12:28:33.067  3871  3871 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-17 12:28:33.067  3871  3871 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-17 12:28:33.077  4289  4323 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 12:28:33.077  4289  4323 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-17 12:28:33.087  4289  4323 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-17 12:28:33.097  4289  4324 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 12:28:33.097  4289  4323 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-17 12:28:33.097  4289  4323 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/17/12:28:33
,03-17 12:28:33.107  4289  4324 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:28:33.107  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.107  3987  4024 I GFX raster: took 0.601615ms for 96*96 texture 0
03-17 12:28:33.107  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb765d968 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768b008 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.107  4289  4323 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-17 12:28:33.117  4289  4324 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 12:28:33.117  4289  4324 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 12:28:33.117  3987  4024 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 12:28:33.117  4289  4324 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 12:28:33.117  4289  4324 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 12:28:33.127  4289  4323 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-17 12:28:33.137  4289  4324 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 12:28:33.137  1017  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-17 12:28:33.137  1017  1041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,03-17 12:28:33.137  4289  4324 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-17 12:28:33.147  4289  4324 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 12:28:33.147  4289  4324 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 12:28:33.157  1864  4354 I art     : Explicit concurrent mark sweep GC freed 26217(1914KB) AllocSpace objects, 37(592KB) LOS objects, 40% free, 12MB/20MB, paused 1.354ms total 799.383ms
,03-17 12:28:33.157  4393  4393 I SA      : [SSP] onCreated
,03-17 12:28:33.177  4289  4324 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-17 12:28:33.187  3987  4024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-17 12:28:33.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-17 12:28:33.207  1017  1041 W libprocessgroup: failed to open /acct/uid_10003/pid_3582/cgroup.procs: No such file or directory
,03-17 12:28:33.207  1017  1234 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:33.207  1017  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-17 12:28:33.207  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:33.207  1017  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:33.207  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:33.237  4289  4323 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-17 12:28:33.247  1864  1864 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-17 12:28:33.247  1017  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:33.247  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,03-17 12:28:33.247  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:33.247  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:33.247  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:33.257  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-17 12:28:33.257  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-17 12:28:33.257  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-17 12:28:33.257  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-17 12:28:33.257  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-17 12:28:33.257  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:33.257  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 12:28:33.257  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 12:28:33.257  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:33.257  3987  4024 I AMMetaDataParserService: Resource data:2131099648
03-17 12:28:33.257  1864  4353 I GCoreUlr: Unbound from all location providers
03-17 12:28:33.257  1864  4353 I GCoreUlr: Place inference reporting - stopped
,03-17 12:28:33.267  1864  1864 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:33.287  3987  4024 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 12:28:33.287  3987  4024 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:33.287  3987  4024 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:28:33.287  3987  4024 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:33.287  3987  4024 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 12:28:33.287  3987  4024 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 12:28:33.287  3987  4024 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:28:33.287  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:33.287  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.287  3987  4024 I GFX raster: took 0.691302ms for 96*96 texture 0
03-17 12:28:33.287  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7686cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb766e678 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.297  3987  4024 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 12:28:33.307  4289  4324 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-17 12:28:33.347  1864  1864 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-17 12:28:33.357  1017  1029 I ActivityManager: Killing 3606:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,03-17 12:28:33.367  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.367  3987  4024 I GFX construct_block_size_descriptor_2d second part: took 2.818437ms for 0*0 texture 0
,03-17 12:28:33.397  3987  4024 I GFX generate_partition_tables: took 8.924896ms for 0*0 texture 0
,03-17 12:28:33.397  3987  4024 I GFX raster: took 12.739897ms for 96*96 texture 0
03-17 12:28:33.397  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7679f30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb766e678 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.397  3987  4024 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:28:33.407  1864  1864 I GCoreUlr: DispatchingService.onDestroy()
,03-17 12:28:33.407  1864  1864 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-17 12:28:33.417  3287  3345 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-17 12:28:33.417  1636  1698 I art     : Explicit concurrent mark sweep GC freed 4618(177KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 775us total 35.360ms
,03-17 12:28:33.427  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.427  3987  4024 I GFX raster: took 0.628229ms for 96*96 texture 0
03-17 12:28:33.427  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb766e678 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7673458 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.427  4393  4393 I SA      : [TPM] There is no property file
,03-17 12:28:33.427  1017  1395 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,03-17 12:28:33.427  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-17 12:28:33.437  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:33.437  1017  1395 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:33.437  4393  4393 I SA      : [SCU] isHaveSA() - false
,03-17 12:28:33.437  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 12:28:33.437  4393  4393 I SA      : [TPM] getModelProperty : null
03-17 12:28:33.437  4393  4393 I SA      : [TPM] getCSCProperty : null
,03-17 12:28:33.437  4393  4393 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-17 12:28:33.437  4393  4393 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-17 12:28:33.437  4393  4393 I SA      : [DM] TFT FEATURE: false
,03-17 12:28:33.447  1864  1864 I GCoreUlr: Unbound from all location providers
03-17 12:28:33.447  1864  1864 I GCoreUlr: Place inference reporting - stopped
,03-17 12:28:33.447  3287  3345 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 12:28:33.457  1017  1041 W libprocessgroup: failed to open /acct/uid_10060/pid_3606/cgroup.procs: No such file or directory
,03-17 12:28:33.457  3837  3978 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 12:28:33.457  3287  3345 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-17 12:28:33.467  4393  4393 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0,
03-17 12:28:33.467  4393  4393 I SA      : [DM] init START
,03-17 12:28:33.467  3287  3345 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
03-17 12:28:33.467  3987  4024 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:28:33.497  3287  3345 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 12:28:33.517  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.517  3987  4024 I GFX raster: took 0.641615ms for 96*96 texture 0
,03-17 12:28:33.517  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7675bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7673458 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.527  1017  1993 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
03-17 12:28:33.527  4289  4323 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
03-17 12:28:33.527  1017  1993 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-17 12:28:33.527  4393  4393 I SA      : [DM] This device is not a Vodafone
,03-17 12:28:33.547  3287  3345 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-17 12:28:33.557  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:33.557  1017  1993 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:33.557  3287  3345 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
03-17 12:28:33.557  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:33.557  3287  3345 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,03-17 12:28:33.577  3287  3345 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,03-17 12:28:33.587  3287  3345 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized,
,03-17 12:28:33.587  3287  3346 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,03-17 12:28:33.597  4289  4323 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 12:28:33.597  4393  4393 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-17 12:28:33.597  1017  3836 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:33.597  1017  3836 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,03-17 12:28:33.607  4393  4393 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,03-17 12:28:33.607  4393  4393 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
03-17 12:28:33.607  1017  3836 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:33.607  4393  4393 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-17 12:28:33.607  4393  4393 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
03-17 12:28:33.607  4393  4393 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,03-17 12:28:33.607  4393  4393 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
03-17 12:28:33.607  1017  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:33.607  1017  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:33.607  4393  4393 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-17 12:28:33.627  3871  3871 I GAv4-SVC: Google Analytics 8.7.03 is starting up.
,03-17 12:28:33.637  3949  3962 W art     : Suspending all threads took: 417.332ms
,03-17 12:28:33.637  4393  4393 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-17 12:28:33.637  4393  4393 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,03-17 12:28:33.647  4393  4393 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-17 12:28:33.667  1864  4354 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-17 12:28:33.667  1864  4354 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 12:28:33.667  1864  4354 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 12:28:33.667  1864  4354 I System.out: (HTTPLog)-Thread-217-598637286: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 12:28:33.667  1864  4354 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 12:28:33.667   275  1012 D EnterpriseController: uids 10012
03-17 12:28:33.667   275  1012 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:28:33.667   275  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,03-17 12:28:33.687  3287  3345 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-17 12:28:33.687  3287  3346 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-17 12:28:33.697  3287  3345 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-17 12:28:33.697  3287  3345 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-17 12:28:33.707  3287  3346 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,03-17 12:28:33.727  4393  4393 I SA      : [SCU] isHaveSA() - false
03-17 12:28:33.727  4393  4393 I SA      : support phone number id : false
03-17 12:28:33.727  4393  4393 I SA      : [DM] Supports Ref Jpn : true
,03-17 12:28:33.727  4393  4393 I SA      : [DM] init END
,03-17 12:28:33.727  4393  4393 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
03-17 12:28:33.727  4393  4393 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-17 12:28:33.737  1017  1486 D ActivityManager: startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,03-17 12:28:33.737  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,03-17 12:28:33.737  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:33.737  1017  1486 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 12:28:33.737  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-17 12:28:33.747  1864  4354 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 12:28:33.747  4393  4393 I SA      : [OR] onReceive END
,03-17 12:28:33.757  1017  1490 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,03-17 12:28:33.757  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:33.757  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:33.757  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:33.757  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:33.767  4289  4324 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0],
,03-17 12:28:33.777  4434  4434 E Zygote  : MountEmulatedStorage()
03-17 12:28:33.777  4434  4434 E Zygote  : v2
03-17 12:28:33.777  4434  4434 I libpersona: KNOX_SDCARD checking this for 10042
03-17 12:28:33.777  4434  4434 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:33.777  4434  4434 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:33.787  3987  4024 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522,
,03-17 12:28:33.787  4434  4434 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:33.787  4434  4434 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,03-17 12:28:33.787  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.787  3987  4024 I GFX raster: took 0.630937ms for 96*96 texture 0
03-17 12:28:33.787  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73e7d70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76909c8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.797  1017  1490 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4434 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:33.797  4393  4393 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 12:28:33.797  4393  4393 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-17 12:28:33.797  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:28:33.807  3287  3346 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-17 12:28:33.817  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.817  3987  4024 I GFX raster: took 0.774271ms for 96*96 texture 0
03-17 12:28:33.817  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb72ba538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb764d8a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.817  4434  4434 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:33.817  4434  4434 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:33.817  3987  4024 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:28:33.827  1864  2112 W GCoreFlp: No location to return for getLastLocation()
,03-17 12:28:33.827  1864  2147 W FusedLocationProvider: location=null
,03-17 12:28:33.827  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-17 12:28:33.827  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-17 12:28:33.827  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:33.827  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:33.827  3987  4024 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:28:33.827  3987  4024 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:28:33.827  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:33.827  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.827  3987  4024 I GFX raster: took 0.689583ms for 96*96 texture 0
03-17 12:28:33.827  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7687178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7679f30 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.837  3987  4024 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 12:28:33.847  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:33.847  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,03-17 12:28:33.857  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:33.857  4434  4434 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 12:28:33.857  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:33.857  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:33.857  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.857  3987  4024 I GFX raster: took 0.629948ms for 96*96 texture 0
03-17 12:28:33.857  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb766c6a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb766e028 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.867  3987  4024 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:28:33.867  1864  2112 W GCoreFlp: No location to return for getLastLocation()
,03-17 12:28:33.867  1864  1877 W FusedLocationProvider: location=null
,03-17 12:28:33.867  3287  3346 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-17 12:28:33.877  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.877  3987  4024 I GFX raster: took 0.627396ms for 96*96 texture 0
03-17 12:28:33.877  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76909c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7690470 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.877  3987  4024 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:28:33.887  4393  4393 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-17 12:28:33.887  4393  4393 I SA      : [LBE] REF_JPN : true
,03-17 12:28:33.887  4393  4393 I SA      : [BDC] create
,03-17 12:28:33.897  1017  1491 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,03-17 12:28:33.897  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 12:28:33.907  3287  3346 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-17 12:28:33.907  4289  4324 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-17 12:28:33.937  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:33.937  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-17 12:28:33.937  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms,
,03-17 12:28:33.947  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:33.947  3987  4024 I GFX raster: took 0.643698ms for 96*96 texture 0
03-17 12:28:33.947  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7675bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7686cf0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:33.957  3287  3346 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-17 12:28:33.957  3287  3346 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,03-17 12:28:33.957  3287  3287 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-17 12:28:33.967  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-17 12:28:33.967  3987  4024 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:28:33.977  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-17 12:28:33.987  3287  3287 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-17 12:28:33.997  4393  4393 I SA      : [DBMV2] getEmailID
,03-17 12:28:33.997  3287  3346 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,03-17 12:28:33.997  4393  4393 I SA      : [DBMV2] getDataV02ForItems
,03-17 12:28:33.997  4393  4393 I SA      : [SSP] query invoked
03-17 12:28:33.997  3287  3287 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,03-17 12:28:34.007  3287  3287 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-17 12:28:34.007  3287  3287 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@3689590c
,03-17 12:28:34.017  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.017  3987  4024 I GFX raster: took 0.629218ms for 96*96 texture 0
03-17 12:28:34.017  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73e7d70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb73e6da0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.017  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:28:34.037  1017  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-17 12:28:34.037  1017  1041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,03-17 12:28:34.037  4434  4434 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-17 12:28:34.047  3287  3346 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,03-17 12:28:34.047  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.047  3987  4024 I GFX raster: took 0.728906ms for 96*96 texture 0
03-17 12:28:34.047  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb72ba538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768f1c8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.057  4393  4393 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-17 12:28:34.067  1017  1328 E Watchdog: !@Sync 1
,03-17 12:28:34.067  4393  4393 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-17 12:28:34.067  3987  4024 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:28:34.087  4393  4393 I SA      : [BDC] destroy
,03-17 12:28:34.087  3287  3346 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,03-17 12:28:34.087  1017  1490 I ActivityManager: Killing 3418:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,03-17 12:28:34.087  3287  3346 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,03-17 12:28:34.087  3287  3346 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,03-17 12:28:34.097  1017  1151 D SettingsProvider: name = audio_safe_volume_state
,03-17 12:28:34.107  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-17 12:28:34.107  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-17 12:28:34.107  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-17 12:28:34.107  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-17 12:28:34.107  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:34.107  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:34.107  3987  4024 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:28:34.107  3987  4024 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:28:34.107  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:34.107  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.107  3987  4024 I GFX raster: took 0.697709ms for 96*96 texture 0
03-17 12:28:34.107  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7687178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768b7f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.117  1017  1395 D SettingsProvider: name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,03-17 12:28:34.127  4332  4332 D StrictMode: StrictMode policy violation; ~duration=1789 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 12:28:34.127  4332  4332 D StrictMode: StrictMode policy violation; ~duration=1744 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps,.gmm.base.app.a.a(PG:1211)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 12:28:34.127  4332  4332 D StrictMode: StrictMode policy violation; ~duration=1237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.Activit,yThread.main(ActivityThread.java:6145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 12:28:34.127  4332  4332 D StrictMode: StrictMode policy violation; ~duration=1236 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 12:28:34.127  4332  4332 D StrictMode: StrictMode policy violation; ~duration=1235 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 12:28:34.127  4332  4332 D StrictMode: StrictMode policy violation; ~duration=1231 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.k.a(PG:2107)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.e.b(PG:170)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 12:28:34.127  4332  4332 D StrictMode: StrictMode policy violation; ~duration=1228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.k.b(PG:14147)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.k.c(PG:583)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.e.b(PG:170)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 12:28:34.127  4332  4332 D StrictMode: StrictMode policy violation; ~duration=1182 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 12:28:34.137  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
03-17 12:28:34.127  4332  4332 D StrictMode: StrictMode policy violation; ~duration=1182 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:28:34.127  4332  4332 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 12:28:34.137  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.137  3987  4024 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
03-17 12:28:34.137  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.137  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.147  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:34.137  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:34.167  4455  4455 E Zygote  : MountEmulatedStorage()
03-17 12:28:34.167  4455  4455 E Zygote  : v2
03-17 12:28:34.167  4455  4455 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:34.167  4455  4455 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:34.167  4455  4455 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:34.167  1017  1491 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4455 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:28:34.177  4455  4455 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:34.177  4455  4455 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:34.187  4455  4455 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:34.197  4455  4455 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:34.197   301   301 I art     : Explicit concurrent mark sweep GC freed 8759(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 846us total 27.388ms
,03-17 12:28:34.207  1017  1491 I ActivityManager: Killing 3649:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31,
,03-17 12:28:34.217   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 17.257ms
,03-17 12:28:34.227   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.688ms
,03-17 12:28:34.237  3287  3346 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-17 12:28:34.257  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.257  3987  4024 I GFX raster: took 0.637656ms for 96*96 texture 0
,03-17 12:28:34.257  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb766c6a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7686cf0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.257  3987  4024 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:28:34.267  4197  4256 W dex2oat : Verification of java.lang.Object com.google.android.gms.signin.internal.c.createFromParcel(android.os.Parcel) took 100.478ms
,03-17 12:28:34.277  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.277  3987  4024 I GFX raster: took 0.670312ms for 96*96 texture 0
03-17 12:28:34.277  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76909c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb768f480 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.287  3987  4024 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:28:34.297  3287  3346 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 12:28:34.297  4455  4455 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 12:28:34.307  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.307  3987  4024 I GFX raster: took 0.644531ms for 96*96 texture 0
03-17 12:28:34.307  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7675bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb764d8a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.317  4455  4455 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 12:28:34.317  3987  4024 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:28:34.317  1017  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,03-17 12:28:34.317  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:34.317  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.317  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.317  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:34.337  4474  4474 E Zygote  : MountEmulatedStorage()
03-17 12:28:34.337  4474  4474 E Zygote  : v2
03-17 12:28:34.337  4474  4474 I libpersona: KNOX_SDCARD checking this for 10116
03-17 12:28:34.337  4474  4474 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:34.337  4474  4474 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:34.337  4474  4474 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:34.337  4474  4474 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:34.337  1017  1490 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4474 uid=10116 gids={50116, 9997} abi=armeabi-v7a
03-17 12:28:34.337  1017  1490 I ActivityManager: Killing 3632:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,03-17 12:28:34.347  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.347  3987  4024 I GFX raster: took 0.742810ms for 96*96 texture 0
,03-17 12:28:34.347  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73e7d70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7690470 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.357  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
03-17 12:28:34.357  4474  4474 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:34.357  4474  4474 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:34.377  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.377  3987  4024 I GFX raster: took 0.734532ms for 96*96 texture 0
,03-17 12:28:34.377  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb72ba538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768d928 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.387  3987  4024 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:28:34.397  1017  1041 W libprocessgroup: failed to open /acct/uid_10009/pid_3418/cgroup.procs: No such file or directory
03-17 12:28:34.397  1017  1041 W libprocessgroup: failed to open /acct/uid_10062/pid_3649/cgroup.procs: No such file or directory
,03-17 12:28:34.407  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-17 12:28:34.407  4474  4474 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
03-17 12:28:34.407  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:34.407  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:34.407  3987  4024 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:28:34.407  3987  4024 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:28:34.407  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:34.407  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.407  3987  4024 I GFX raster: took 0.716614ms for 96*96 texture 0
03-17 12:28:34.407  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7687178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768f1c8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.417  4474  4474 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-17 12:28:34.417  1017  1993 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:34.417  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:34.417  1017  1993 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:34.417  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-17 12:28:34.417  4197  4197 W dex2oat : Verification of void com.google.maps.api.android.lib6.gmm6.streetview.ag.a(long) took 112.449ms
,03-17 12:28:34.417  1017  1342 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,03-17 12:28:34.417  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.417  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.417  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.417  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:34.427  4474  4474 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-17 12:28:34.437  4492  4492 E Zygote  : MountEmulatedStorage()
03-17 12:28:34.437  4492  4492 E Zygote  : v2
03-17 12:28:34.437  4492  4492 I libpersona: KNOX_SDCARD checking this for 10125
03-17 12:28:34.437  4492  4492 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:34.437  4492  4492 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:34.437  4492  4492 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:34.437  1017  1342 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4492 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-17 12:28:34.437  4492  4492 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:34.457  3987  4024 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 12:28:34.477  1017  1041 W libprocessgroup: failed to open /acct/uid_10014/pid_3632/cgroup.procs: No such file or directory
,03-17 12:28:34.477  4492  4492 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:34.477  4492  4492 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:34.487  1017  3836 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-17 12:28:34.487  1017  3836 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 12:28:34.487  1017  1017 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-17 12:28:34.487  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,03-17 12:28:34.497  1191  2029 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:34.507  1017  1476 I ActivityManager: Killing 3663:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-17 12:28:34.507  1017  1342 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-17 12:28:34.507  1017  1342 D SecContentProvider2: mCursor = null
,03-17 12:28:34.507  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.517  3987  4024 I GFX raster: took 0.738490ms for 96*96 texture 0
03-17 12:28:34.517  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb766c6a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb73e7f68 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.517  3987  4024 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:28:34.527  1017  1490 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 12:28:34.527  1017  1490 D SecContentProvider2: mCursor = null
,03-17 12:28:34.537  1017  3168 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
03-17 12:28:34.537  1017  3168 D SecContentProvider2: mCursor = null
,03-17 12:28:34.537  3287  3346 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,03-17 12:28:34.537  1017  1993 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-17 12:28:34.537  1017  1993 D SecContentProvider2: mCursor = null
,03-17 12:28:34.537  4492  4492 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:28:34.537  4492  4492 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 12:28:34.537  4492  4492 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 12:28:34.537  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.547  3987  4024 I GFX raster: took 0.749687ms for 96*96 texture 0
03-17 12:28:34.547  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76909c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb768b7f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.547   286   286 E SMD     : DCD OFF
,03-17 12:28:34.547  3987  4024 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:28:34.567  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.567  3987  4024 I GFX raster: took 0.654479ms for 96*96 texture 0
,03-17 12:28:34.567  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7675bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7681b60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.577  1191  1191 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-17 12:28:34.577  3987  4024 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:28:34.577  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.587  3987  4024 I GFX raster: took 0.721979ms for 96*96 texture 0
,03-17 12:28:34.587  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73e7d70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768f480 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.587  1191  1191 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-17 12:28:34.587  1191  1191 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-17 12:28:34.587  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 12:28:34.587  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:28:34.597  1191  1191 D PanelView: There is/are notification(s) 
,03-17 12:28:34.597  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 12:28:34.597  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:28:34.597  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:28:34.597  1191  1191 D PanelView: There is/are notification(s) 
,03-17 12:28:34.597  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 12:28:34.597  3287  3346 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 12:28:34.607  1017  1486 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-17 12:28:34.607  1017  1486 D SecContentProvider2: mCursor = null
,03-17 12:28:34.607  1017  3172 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
03-17 12:28:34.607  1017  3172 D SecContentProvider2: mCursor = null
,03-17 12:28:34.617  4197  4256 W dex2oat : Verification of void maps.ai.a.a(maps.bi.b, java.util.Map) took 103.951ms
,03-17 12:28:34.617  1017  1041 W libprocessgroup: failed to open /acct/uid_10094/pid_3663/cgroup.procs: No such file or directory
,03-17 12:28:34.617  1017  2857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:28:34.637  3287  4509 D OpenGLRenderer: Render dirty regions requested: true
,03-17 12:28:34.657  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.657  3987  4024 I GFX raster: took 0.730677ms for 96*96 texture 0
03-17 12:28:34.657  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb72ba538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7686cf0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.657   256   256 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=4, Uoast
,03-17 12:28:34.667  3287  3346 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,03-17 12:28:34.667  1191  1191 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
03-17 12:28:34.667  3287  3346 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,03-17 12:28:34.667  3287  3346 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,03-17 12:28:34.677  3987  4024 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:28:34.677  1017  1491 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,03-17 12:28:34.677  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-17 12:28:34.677  1017  1051 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 12:28:34.677  1017  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 12:28:34.677  3287  3287 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 12:28:34.687  3287  4509 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 12:28:34.687  3287  4509 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:28:34.687  3287  4509 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:28:34.687  3287  4509 I Adreno-EGL: Local Branch: 
03-17 12:28:34.687  3287  4509 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:28:34.687  3287  4509 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:28:34.687  3287  4509 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 12:28:34.687  1017  1029 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,03-17 12:28:34.687  3287  4509 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 12:28:34.687  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 12:28:34.687  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:34.687  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:34.687  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 12:28:34.697  1017  1171 D lights  : lcd : 47 +
,03-17 12:28:34.697  3287  4509 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 12:28:34.697  3287  4509 D OpenGLRenderer: Enabling debug mode 0
,03-17 12:28:34.707  4492  4492 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-17 12:28:34.707  4492  4492 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-17 12:28:34.707  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
,03-17 12:28:34.707  1017  1051 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 12:28:34.707  1017  1171 D lights  : lcd : 47 -
,03-17 12:28:34.707  1017  1171 D lights  : lcd : 60 +
,03-17 12:28:34.717  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-17 12:28:34.717  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:34.717  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:34.717  3987  4024 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:28:34.717  1017  1395 D SettingsProvider: name = scon_is_running
03-17 12:28:34.717  1017  1395 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:34.717  3987  4024 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:28:34.717  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:34.717  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:28:34.717  1017  1395 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:34.717  1017  1395 D SettingsProvider: selectionArgs: false
03-17 12:28:34.717  1017  1395 D SettingsProvider: selectionArgs: 10125
03-17 12:28:34.717  1017  1395 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:34.717  1017  1395 D SettingsProvider: ret = -1
03-17 12:28:34.717  3987  4024 I GFX raster: took 0.694739ms for 96*96 texture 0
03-17 12:28:34.717  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7687178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768b7f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.727  1017  1171 D lights  : lcd : 60 -
,03-17 12:28:34.727  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-17 12:28:34.727  1017  1051 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 12:28:34.727  1017  1395 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-17 12:28:34.737  4492  4492 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-17 12:28:34.737  4492  4492 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 12:28:34.737  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,03-17 12:28:34.737  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.737  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.737  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:34.737  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:34.737  3987  4024 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 12:28:34.757  4511  4511 E Zygote  : MountEmulatedStorage(),
03-17 12:28:34.757  4511  4511 E Zygote  : v2,
,03-17 12:28:34.757  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:28:34.767  4511  4511 I libpersona: KNOX_SDCARD checking this for 10131,
03-17 12:28:34.767  4511  4511 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:34.767  4511  4511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:34.767  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-17 12:28:34.767  3987  4024 I GFX raster: took 0.634011ms for 96*96 texture 0
03-17 12:28:34.767  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb766c6a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb768f1c8 counterpartCT=4 counterpartW=96 counterparth=96,
,03-17 12:28:34.777  4511  4511 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:34.777  4511  4511 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:34.777  3987  4024 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:28:34.787  4511  4511 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:34.797  4511  4511 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:34.797  1017  1491 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4511 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-17 12:28:34.807  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:28:34.807  3987  4024 I GFX raster: took 0.623750ms for 96*96 texture 0
03-17 12:28:34.807  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76909c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb73e7f68 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.807  3987  4024 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:28:34.827  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.827  3987  4024 I GFX raster: took 0.642552ms for 96*96 texture 0
03-17 12:28:34.827  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7675bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb765d968 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.827  4511  4511 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 12:28:34.827  4511  4511 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:34.827  4511  4511 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 12:28:34.827  4511  4511 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:28:34.837  3987  4024 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:28:34.867  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.867  3987  4024 I GFX raster: took 0.633646ms for 96*96 texture 0
03-17 12:28:34.867  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73e7d70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7681b60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.887  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:28:34.917  4332  4358 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,03-17 12:28:34.937  4511  4511 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-17 12:28:34.957  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.957  3987  4024 I GFX raster: took 0.733854ms for 96*96 texture 0
03-17 12:28:34.957  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb72ba538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb768f480 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.967  3987  4024 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:28:34.967  4511  4511 D ManifestProvider: onCreate()
,03-17 12:28:34.967  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-17 12:28:34.967  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:34.967  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:34.967  3987  4024 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:28:34.977  3987  4024 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:28:34.977  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:34.977  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:34.977  3987  4024 I GFX raster: took 0.699844ms for 96*96 texture 0
03-17 12:28:34.977  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7687178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb766e028 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:34.987  3987  4024 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 12:28:34.987  4511  4511 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-17 12:28:35.007  1017  1150 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:35.007  1017  1150 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:35.007  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:35.007  1017  1150 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:35.007  3987  4024 I GFX raster: took 0.629479ms for 96*96 texture 0
03-17 12:28:35.007  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb766c6a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7686cf0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:35.007  1017  1150 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-17 12:28:35.017  3987  4024 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:28:35.037  4511  4511 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@c8e8911
,03-17 12:28:35.037  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:35.037  3987  4024 I GFX raster: took 0.623854ms for 96*96 texture 0
,03-17 12:28:35.047  4511  4511 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
,03-17 12:28:35.047  4511  4511 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-17 12:28:35.047  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76909c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb768f1c8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:35.057  3987  4024 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:28:35.067  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,03-17 12:28:35.067  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:35.067  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:35.067  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:35.067  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:35.077  1017  1029 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4530 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-17 12:28:35.087  4530  4530 E Zygote  : MountEmulatedStorage()
03-17 12:28:35.087  4530  4530 E Zygote  : v2
03-17 12:28:35.087  4530  4530 I libpersona: KNOX_SDCARD checking this for 10135,
03-17 12:28:35.087  4530  4530 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:35.087  1017  1029 I ActivityManager: Killing 3696:com.sec.factory.camera/1000 (adj 15): empty #31
,03-17 12:28:35.097  4530  4530 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:35.097  4530  4530 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:35.107  4530  4530 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:35.107  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:35.107  3987  4024 I GFX raster: took 0.741042ms for 96*96 texture 0
03-17 12:28:35.107  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7675bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb73e7f68 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:35.117  3987  4024 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:28:35.117  1017  3168 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:35.127  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:35.127  1017  3168 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:35.127  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-17 12:28:35.137  4530  4530 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:35.137  4530  4530 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:35.137  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:35.137  3987  4024 I GFX raster: took 0.678282ms for 96*96 texture 0
03-17 12:28:35.137  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73e7d70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb765d968 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:35.147  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:28:35.167  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:35.167  3987  4024 I GFX raster: took 0.722813ms for 96*96 texture 0
03-17 12:28:35.167  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb72ba538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7681b60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:35.167  4530  4530 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:28:35.177  4530  4530 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:35.177  4530  4530 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:35.177  3987  4024 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android,.mms.ui.PushMessageDialog
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-17 12:28:35.197  3987  4024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
,03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
,03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top,
,03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog,
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-17 12:28:35.187  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-17 12:28:35.197  3987  4024 I AMM,etaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
,03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
,03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
,03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-17 12:28:35.197  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,03-17 12:28:35.217  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-17 12:28:35.217  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.217  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:35.217  3987  4024 I AMMetaDataParserService: Resource data:2131165197
,03-17 12:28:35.227  3987  4024 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:28:35.227  3987  4024 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:28:35.227  3987  4024 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 12:28:35.227  3987  4024 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:35.227  3987  4024 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,03-17 12:28:35.227  3987  4024 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:28:35.227  3987  4024 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 12:28:35.227  3987  4024 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:28:35.237  3987  4024 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-17 12:28:35.237  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:35.237  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3696/cgroup.procs: No such file or directory
,03-17 12:28:35.247  3987  4024 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 12:28:35.267  3987  4024 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 12:28:35.277  1329  1346 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:35.297  3987  4024 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 12:28:35.307  1017  1490 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,03-17 12:28:35.307  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 12:28:35.317  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:35.317  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:35.317  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 12:28:35.357  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 12:28:35.357  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,03-17 12:28:35.357  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:28:35.357  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-17 12:28:35.357  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
,03-17 12:28:35.367  3987  4024 I AMMetaDataParserService: Resource data:2131165197
,03-17 12:28:35.367  3987  4024 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-17 12:28:35.367  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:35.377  3987  4024 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 12:28:35.387  3987  4024 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 12:28:35.397  1017  1476 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,03-17 12:28:35.397  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 12:28:35.397  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:35.397  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:35.397  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 12:28:35.407  1017  1993 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,03-17 12:28:35.407  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:35.407  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:35.407  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:35.407  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:35.417  3987  4024 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 12:28:35.427  4552  4552 E Zygote  : MountEmulatedStorage()
03-17 12:28:35.427  4552  4552 E Zygote  : v2
03-17 12:28:35.427  4552  4552 I libpersona: KNOX_SDCARD checking this for 10139
03-17 12:28:35.427  4552  4552 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:35.427  4552  4552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:35.427  4552  4552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:35.427  1017  1993 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4552 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-17 12:28:35.427  4552  4552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:35.457  4552  4552 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:35.457  4552  4552 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:35.477  4552  4552 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 12:28:35.477  4552  4552 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:28:35.477  4552  4552 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,03-17 12:28:35.477  4552  4552 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 12:28:35.477  4552  4552 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:28:35.487  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624,
,03-17 12:28:35.497  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-17 12:28:35.497  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-17 12:28:35.497  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.497  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:35.497  3987  4024 I AMMetaDataParserService: Resource data:2131165197
,03-17 12:28:35.497  3987  4024 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 12:28:35.497  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:35.507  3987  4024 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 12:28:35.517  3987  4024 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 12:28:35.537  3987  4024 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 12:28:35.557  3987  4024 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 12:28:35.557  1017  1486 I ActivityManager: Killing 3714:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-17 12:28:35.577  1017  1395 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,03-17 12:28:35.577  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:35.577  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:35.577  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:35.577  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:35.587  1017  1395 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4571 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-17 12:28:35.587  3987  4024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-17 12:28:35.587  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-17 12:28:35.597  4571  4571 E Zygote  : MountEmulatedStorage()
03-17 12:28:35.597  4571  4571 I libpersona: KNOX_SDCARD checking this for 10145
03-17 12:28:35.597  4571  4571 E Zygote  : v2
,03-17 12:28:35.597  4571  4571 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:35.597  4571  4571 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:35.597  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-17 12:28:35.597  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:28:35.597  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable,
03-17 12:28:35.597  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 12:28:35.597  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
,03-17 12:28:35.597  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:35.597  3987  4024 I AMMetaDataParserService: Resource data:2131099648
03-17 12:28:35.597  4571  4571 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:35.597  4571  4571 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:35.597  3987  4024 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 12:28:35.597  3987  4024 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:28:35.597  3987  4024 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 12:28:35.597  3987  4024 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 12:28:35.597  3987  4024 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:28:35.617  3987  4024 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-17 12:28:35.617  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:35.627  4571  4571 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:35.627  4571  4571 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:35.627  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3714/cgroup.procs: No such file or directory
,03-17 12:28:35.637  3987  4024 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-17 12:28:35.657  4571  4571 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 12:28:35.657  4571  4571 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:28:35.667  4571  4571 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:28:35.667  4571  4571 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:35.667  4571  4571 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:28:35.687  3987  4024 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-17 12:28:35.697  4434  4434 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 12:28:35.697  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 12:28:35.697  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:35.697  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:35.697  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 12:28:35.707  1017  1486 I ActivityManager: Killing 3484:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 12:28:35.717  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,03-17 12:28:35.727  1017  1395 I ActivityManager: Killing 3767:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,03-17 12:28:35.747  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
,03-17 12:28:35.747  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-17 12:28:35.747  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,03-17 12:28:35.747  3987  4024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 12:28:35.797  4197  4197 W dex2oat : Verification of void maps.k.b$h.a(byte[], byte[]) took 117.234ms
,03-17 12:28:35.827  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
,03-17 12:28:35.827  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.827  3987  4024 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:28:35.827  3987  4024 I AMMetaDataParserService: Resource data:2131165220
,03-17 12:28:35.847  3987  4024 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 12:28:35.847  3987  4024 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 12:28:35.847  3987  4024 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:28:35.847  3987  4024 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:28:35.847  3987  4024 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:35.847  3987  4024 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 12:28:35.847  3987  4024 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
,03-17 12:28:35.847  3987  4024 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:28:35.857  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:35.857  3987  4024 I GFX raster: took 0.711874ms for 96*96 texture 0
,03-17 12:28:35.857  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7d8ab10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7d8a840 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:35.867  1017  1041 W libprocessgroup: failed to open /acct/uid_10015/pid_3484/cgroup.procs: No such file or directory
03-17 12:28:35.867  1017  1041 W libprocessgroup: failed to open /acct/uid_10100/pid_3767/cgroup.procs: No such file or directory
,03-17 12:28:35.867  3987  4024 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-17 12:28:35.887  1017  1150 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:35.887  3987  4024 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:28:35.887  3987  4024 I GFX raster: took 0.601094ms for 96*96 texture 0
03-17 12:28:35.887  3987  4024 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7d8a960 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7d9d380 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:28:35.897  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:35.897  3987  4024 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.,settings.wifi.WifiSecSetupActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
,03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
,03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
,03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-17 12:28:35.917  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
,03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
,03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:36.017  1017  1150 I ActivityManager: Killing 3396:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-17 12:28:35.927  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource dat,a:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-17 12:28:35.937  3987  4024 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-17 12:28:35.937  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:28:35.967  1017  1342 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:36.117  1017  1395 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,03-17 12:28:36.117  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:36.117  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.117  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.117  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:36.127  1017  1486 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:36.137  4595  4595 E Zygote  : MountEmulatedStorage()
,03-17 12:28:36.137  4595  4595 E Zygote  : v2,
03-17 12:28:36.137  4595  4595 I libpersona: KNOX_SDCARD checking this for 10072
,03-17 12:28:36.137  4595  4595 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:36.137  4595  4595 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:36.147  1017  1395 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4595 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
,03-17 12:28:36.147  1017  1234 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:36.147  4595  4595 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 12:28:36.147  1017  1993 D ActivityManager: startService callerProcessName:com.android.email, calleePkgName: com.android.email
03-17 12:28:36.147  1017  1993 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 12:28:36.147  4595  4595 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 12:28:36.157  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:36.157  1017  1993 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:36.157  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-17 12:28:36.177  1017  1342 D ActivityManager: startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,03-17 12:28:36.177  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.177  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.177  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.177  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:36.177  4595  4595 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:36.187  4595  4595 D ActivityThread: Added TimaKeyStore provider,
,03-17 12:28:36.187  4616  4616 E Zygote  : MountEmulatedStorage(),
03-17 12:28:36.187  4616  4616 E Zygote  : v2
,03-17 12:28:36.187  4616  4616 I libpersona: KNOX_SDCARD checking this for 10146
,03-17 12:28:36.187  4616  4616 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:36.197  1017  1342 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4616 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 12:28:36.197  4616  4616 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 12:28:36.197  1017  1342 I ActivityManager: Killing 3753:com.wssnps/1000 (adj 15): empty #31,
,03-17 12:28:36.197  4616  4616 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:36.207  4616  4616 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 12:28:36.207  1017  1234 I ActivityManager: Killing 3794:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,03-17 12:28:36.227  4616  4616 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:36.227  4616  4616 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:36.237  1017  1041 W libprocessgroup: failed to open /acct/uid_10057/pid_3396/cgroup.procs: No such file or directory
,03-17 12:28:36.307  1017  1041 W libprocessgroup: failed to open /acct/uid_10022/pid_3794/cgroup.procs: No such file or directory
,03-17 12:28:36.317  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3753/cgroup.procs: No such file or directory
,03-17 12:28:36.357  1017  1491 I art     : Explicit concurrent mark sweep GC freed 34608(1887KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 26MB/40MB, paused 2.530ms total 156.584ms
,03-17 12:28:36.377  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{160f1fcb u0 com.samsung.android.providers.context/.ContextService}
,03-17 12:28:36.377  4616  4616 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 12:28:36.387  4595  4595 D BadgeProvider: onCreate
,03-17 12:28:36.387  4595  4595 D BadgeProvider: DatabaseHelper
,03-17 12:28:36.407  4595  4609 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 12:28:36.417  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 12:28:36.417  1017  1491 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 12:28:36.417  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 12:28:36.417  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 12:28:36.427  1017  3836 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-17 12:28:36.447  4571  4608 I Process : Sending signal. PID: 4571 SIG: 9
,03-17 12:28:36.447  4595  4609 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 12:28:36.447  4595  4609 D BadgeProvider: sendNotify, [notify] : null
03-17 12:28:36.447  4595  4609 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 12:28:36.447  4595  4609 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 12:28:36.447  4595  4609 D BadgeProvider: update, [UpdateCount] : 1
,03-17 12:28:36.447  1492  1492 D Launcher.Model: reloadBadges entered.
,03-17 12:28:36.477  4197  4197 I dex2oat : dex2oat took 5.728s (threads: 4)
,03-17 12:28:36.497  3871  4195 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
,03-17 12:28:36.497  3871  4195 D DexOptUtils: Set odex to world readable.
,03-17 12:28:36.497  3871  4195 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
,03-17 12:28:36.497  1017  1476 I ActivityManager: Killing 3856:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-17 12:28:36.507  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:36.507  1017  3172 D ActivityManager: startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,03-17 12:28:36.517  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 12:28:36.517  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:36.517  1017  3172 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:36.517  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-17 12:28:36.517  1017  1150 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,03-17 12:28:36.517  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.517  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.517  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.517  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:36.537  4634  4634 E Zygote  : MountEmulatedStorage()
,03-17 12:28:36.537  4634  4634 E Zygote  : v2,
03-17 12:28:36.537  4634  4634 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 12:28:36.537  4634  4634 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:36.537  4634  4634 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:36.537  4634  4634 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:36.537  4634  4634 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 12:28:36.537  1017  1150 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4634 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:36.547   253   253 E lowmemorykiller: Error opening /proc/4571/oom_score_adj; errno=2
03-17 12:28:36.547  1017  1486 I ActivityManager: Process com.android.email (pid 4571)(adj 0) has died(51,1103)
03-17 12:28:36.547  4616  4633 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@cb4804c
,03-17 12:28:36.547  4616  4633 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@cb4804c
,03-17 12:28:36.557  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
,03-17 12:28:36.557  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:36.557  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.557  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:36.557  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:36.577  4648  4648 E Zygote  : MountEmulatedStorage(),
,03-17 12:28:36.577  4648  4648 E Zygote  : v2
,03-17 12:28:36.577  1017  1029 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4648 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
03-17 12:28:36.577  4648  4648 I libpersona: KNOX_SDCARD checking this for 10145
03-17 12:28:36.577  4648  4648 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:36.577  4648  4648 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:36.577  4634  4634 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:36.577  4634  4634 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:36.577  4648  4648 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:36.587  4648  4648 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:36.607  3949  4105 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-17 12:28:36.607  4648  4648 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:36.607  4648  4648 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:36.617  1017  1993 I ActivityManager: Killing 3547:com.sec.pcw.device/1000 (adj 15): empty #31
,03-17 12:28:36.627  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3856/cgroup.procs: No such file or directory
,03-17 12:28:36.627  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,03-17 12:28:36.627  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:36.627  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.627  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:36.627  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:36.627  4648  4648 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 12:28:36.627  4648  4648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:28:36.627  4648  4648 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:28:36.627  4648  4648 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:36.637  4648  4648 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:28:36.647  1017  1491 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4666 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:36.647  1017  1491 I ActivityManager: Killing 3907:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,03-17 12:28:36.647  4666  4666 E Zygote  : MountEmulatedStorage()
03-17 12:28:36.647  4666  4666 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:36.647  4666  4666 E Zygote  : v2
03-17 12:28:36.647  4666  4666 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:36.647  4666  4666 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:36.657  4666  4666 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:36.657  4666  4666 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:36.687   301   301 I art     : Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 11.199ms total 43.104ms
,03-17 12:28:36.687  4666  4666 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:36.687  4666  4666 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:36.697  3949  3963 W art     : Suspending all threads took: 10.197ms
,03-17 12:28:36.707   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 18.304ms
,03-17 12:28:36.727   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 16.810ms
,03-17 12:28:36.737  1017  1476 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:36.747  1017  3168 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:36.757  4666  4666 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 12:28:36.757  4666  4666 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 12:28:36.757  4666  4666 D SecurityLogAgent: StateMachine : Current State = 1
03-17 12:28:36.757  4666  4666 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-17 12:28:36.757  1017  1342 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 12:28:36.757  1017  1342 I ActivityManager: Killing 3932:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-17 12:28:36.767  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:36.767  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:36.767  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:28:36.767  4289  4323 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 12:28:36.767  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:36.767  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:36.767  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:28:36.767  4289  4323 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 12:28:36.767  4289  4323 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 12:28:36.767  4289  4323 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 12:28:36.777  4289  4323 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 12:28:36.777  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:36.777  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:36.777  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:28:36.777  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:36.777  4289  4323 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
03-17 12:28:36.777  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:36.777  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,03-17 12:28:36.777  3150  3459 I jxcore-log: INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
03-17 12:28:36.777  3150  3459 I jxcore-log: 
,03-17 12:28:36.787  4289  4323 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 12:28:36.787  3150  3459 I jxcore-log: INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-17 12:28:36.787  3150  3459 I jxcore-log: 
,03-17 12:28:36.787  3150  3459 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 12:28:36.787  3150  3459 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 12:28:36.787  3150  3459 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 12:28:36.787  3150  3459 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 12:28:36.787  3150  3459 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 12:28:36.787  3150  3459 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 12:28:36.787  3150  3459 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 12:28:36.787  3150  3459 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 12:28:36.797  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:36.797  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 12:28:36.797  3150  3459 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-17 12:28:36.797  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:36.797  3150  3459 I jxcore-log: INFO thaliMobileNativeWrapper Method networkChanged registered to native
03-17 12:28:36.797  3150  3459 I jxcore-log: 
,03-17 12:28:36.797  3150  3459 I jxcore-log: INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
03-17 12:28:36.797  3150  3459 I jxcore-log: 
,03-17 12:28:36.817  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:36.827  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 12:28:36.827  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,03-17 12:28:36.827  1329  1329 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 12:28:36.827  1329  1329 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-17 12:28:36.827  1329  1329 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 12:28:36.827  1329  1329 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 12:28:36.827  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-17 12:28:36.827  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,03-17 12:28:36.837  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:36.837  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 12:28:36.867  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,03-17 12:28:36.877  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
,03-17 12:28:36.877  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:750 [0:0] Cncl30MinRftAl
,03-17 12:28:36.877  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
,03-17 12:28:36.877  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:36.887  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:36.887  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 12:28:36.887  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 12:28:36.887  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1056 [0:0] == cityListItem Size : 0
,03-17 12:28:36.887  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:175 [0:0] ============== Start refreshType : 3
,03-17 12:28:36.897  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:36.897  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:206 [0:0] checkCuL:0, mCityDataList : 0
,03-17 12:28:36.897  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:36.907  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:904 [0:0] MR pcknme : Manual systemui
,03-17 12:28:36.907  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:36.907  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 12:28:36.907  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:257 [0:0] == rCL 1458214116920
,03-17 12:28:36.917  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{ffc7d33 u0 com.android.settings/.wifi.WifiCredService}
,03-17 12:28:36.917  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:36.917  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 12:28:36.927  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:36.927  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 12:28:36.927  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:36.927  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 12:28:36.927  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:273 [0:0] EUR
,03-17 12:28:36.927  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:36.937  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:278 [0:0] checkCuL:0, getRefreshType():3
,03-17 12:28:36.937  1017  1234 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:28:36.937  1329  1329 D daemonapp: [MSC_Daemon]>>> WMCL:455 [0:0] MCL pfGetCL@NP:false
,03-17 12:28:36.937  1329  1329 D daemonapp: [MSC_Daemon]>>> WMCL:461 [0:0] MCL pfL set:t
,03-17 12:28:36.937  1329  1329 D daemonapp: [MSC_Daemon]>>> WMCL:1895 [0:0] MCL getLLoc@
,03-17 12:28:36.937  1329  1329 D daemonapp: [MSC_Daemon]>>> WMCL:244 [0:0] MCL getCPrvdr@
,03-17 12:28:36.937  1329  1329 D daemonapp: [MSC_Daemon]>>> WMCL:1954 [0:0] PrvdrErr!!
,03-17 12:28:36.937  1329  1329 D daemonapp: [MSC_Daemon]>>> WMCL:1956 [0:0] PrvdrErr getPerformLoc:true
,03-17 12:28:36.937  1329  1329 D daemonapp: [MSC_Daemon]>>> WMCL:1958 [0:0] MCL pfL set:f
,03-17 12:28:36.937  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,03-17 12:28:36.937  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,03-17 12:28:36.947  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1458214116958
,03-17 12:28:36.947  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1458235716954
,03-17 12:28:36.947  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
,03-17 12:28:36.947  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,03-17 12:28:36.947  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1458235680000
,03-17 12:28:36.947  1329  1329 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458235680000
,03-17 12:28:36.947  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-17 12:28:36.947  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1458235680000
,03-17 12:28:36.957  1329  1329 D daemonapp: [MSC_Daemon]>>> AWCLRH:43 [0:0] ==============rLH=====================
,03-17 12:28:36.957  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 12:28:36.957  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:36.957  1017  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:36.957  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:28:36.957  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:36.957  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:36.957  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:36.957  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-17 12:28:36.957  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1314 [0:0] CL@AtRfr = 3
,03-17 12:28:36.957  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:36.967  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:36.967  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:36.967  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1321 [0:0]  AR_lasttime: 1458235680000
,03-17 12:28:36.967  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-17 12:28:36.967  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1615 [0:0] util getnext by widget 1458235680000
03-17 12:28:36.967  1329  1329 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458235680000
,03-17 12:28:36.967  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-17 12:28:36.967  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1332 [0:0] NextTime       :1458235680000
03-17 12:28:36.967  1329  1329 D daemonapp: [MSC_Daemon]>>> AWCLRH:242 [0:0] rLH /on rciclf
,03-17 12:28:36.967  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1480 [0:0]  retryCityIdCurrentlocationfail getRefreshType : 3
03-17 12:28:36.967  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1491 [0:0] send broad cast error to clock
,03-17 12:28:36.977  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:36.977  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:36.977  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:28:36.977  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:36.977  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 12:28:36.977  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 12:28:36.977  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,03-17 12:28:36.977  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:36.987  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:36.987  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:36.987  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:28:36.987  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,03-17 12:28:36.987  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 12:28:36.997  1017  3172 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 12:28:36.997  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 12:28:36.997  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:36.997  1017  3172 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:36.997  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:28:36.997  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 12:28:36.997  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 12:28:36.997  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 12:28:37.007  2427  2427 I Hs20UtilService: Starting #4
,03-17 12:28:37.007  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.007  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 12:28:37.007  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,03-17 12:28:37.007  1310  1310 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 12:28:37.007  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.017  2427  2442 I Hs20UtilService: Message received 5007
,03-17 12:28:37.017  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.017  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.017  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.017  1017  1150 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 12:28:37.017  1017  1150 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,03-17 12:28:37.017  1017  1150 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,03-17 12:28:37.017  1017  1150 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 12:28:37.027  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.027  1017  1150 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.027  1017  1150 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.027  1017  1150 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.037  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.037  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.037  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.047  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 12:28:37.047  1017  3836 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.047  1017  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.047  1017  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.057  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.057  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.067  4595  4609 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 12:28:37.067  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,03-17 12:28:37.067  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.077  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.077  4595  4609 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,03-17 12:28:37.077  4595  4609 D BadgeProvider: sendNotify, [notify] : null
03-17 12:28:37.077  4595  4609 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 12:28:37.077  4595  4609 D BadgeProvider: update, [BadgeCount] : badgecount=0
,03-17 12:28:37.077  4595  4609 D BadgeProvider: update, [UpdateCount] : 1
03-17 12:28:37.077  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,03-17 12:28:37.077  1492  1492 D Launcher.Model: reloadBadges entered.
,03-17 12:28:37.077  1017  3836 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:37.077  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,03-17 12:28:37.077  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,03-17 12:28:37.087  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,03-17 12:28:37.087  1329  1329 E daemonapp: [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,03-17 12:28:37.087  1017  1342 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:37.087  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,03-17 12:28:37.087  1191  1191 D AdaptiveEventManager: action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
,03-17 12:28:37.087  1191  1191 D AdaptiveEventManager: currentCityId is null
,03-17 12:28:37.087  1191  1191 D AdaptiveEventManager: NetWork disabled : Don't refresh weather info : 201
03-17 12:28:37.087  1191  1191 D AdaptiveEventManager: WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
03-17 12:28:37.087  1191  1191 D AdaptiveEventManager: Weather Visibility: Previous= 0 >> Now= 0
03-17 12:28:37.087  1191  1191 D AdaptiveEventManager: Widget Count: Previous= 0 >> Now= 0
03-17 12:28:37.087  1191  1191 D AdaptiveEventManager: mWeatherInfo is not reliable
03-17 12:28:37.087  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.087  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.087  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.097  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,03-17 12:28:37.117  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,03-17 12:28:37.117  1329  1329 E daemonapp: [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,03-17 12:28:37.117  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,03-17 12:28:37.117  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,03-17 12:28:37.137  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.137  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:37.137  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,03-17 12:28:37.137  1017  1486 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
,03-17 12:28:37.137  1329  1329 D daemonapp: [MSC_Daemon]>>> WDBH:4086 [0:0] ud SLS false
,03-17 12:28:37.147  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-17 12:28:37.147  1017  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:37.147  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.147  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.147  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.147  4616  4633 I Process : Sending signal. PID: 4616 SIG: 9
,03-17 12:28:37.157  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1344 [0:0] RhTy : 3, ResponseCount :1, Listsize : 0
03-17 12:28:37.157  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1349 [0:0] =======RefreshType:1 End RetThd Current===========
,03-17 12:28:37.157  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1236 [0:0] resetRefreshThread : 0
,03-17 12:28:37.157  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:37.157  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.157  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.157  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.167  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1441 [0:0] getBManualRefreshState : false, checkCurrentLocation : 0
,03-17 12:28:37.167  1329  1329 D daemonapp: [MSC_Daemon]>>> RM:1353 [0:0] send broad cast to clock Cur
,03-17 12:28:37.167  1017  3172 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:37.167  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.167  1017  3172 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.167  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.177  1864  1864 D WearableService: callingUid 10012, callindPid: 1864
,03-17 12:28:37.177  1017  1993 W ActivityManager: userId = 0, bbcId = -10000,
,03-17 12:28:37.177  1864  4690 E MDM     : [233] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-17 12:28:37.187  1017  1993 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.187  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.187  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:37.187  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.187  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.187  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.187  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.187  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.187  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.187  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.217  1017  1150 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.217  1017  1150 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.217  1017  1150 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.217  1017  1342 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:37.217  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 12:28:37.217  1017  1342 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.217  1017  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.217  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.217  3871  4691 D LocationInitializer: Restart initialization of location
,03-17 12:28:37.247  1017  3168 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:37.247  1017  3168 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.247  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.247  1017  3168 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.247  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.277  1467  1810 D TP/SmsProvider: query,matched:0, calling pid = 3871
,03-17 12:28:37.287  1467  1810 D TP/SmsProvider: match 0:Elapsed time : 2.784 ms
,03-17 12:28:37.287  1017  1490 I ActivityManager: Process com.android.exchange (pid 4616)(adj 13) has died(44,1105)
,03-17 12:28:37.297  1017  1342 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:37.297  1017  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.297  1017  1342 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.297  1017  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.297  1017  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.307  1467  1484 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 3871
,03-17 12:28:37.317  1467  1482 D TP/SmsProvider: query,matched:0, calling pid = 3871
,03-17 12:28:37.317  1467  1482 D TP/SmsProvider: match 0:Elapsed time : 1.663 ms
,03-17 12:28:37.337  1467  1810 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 3871
,03-17 12:28:37.407  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3907/cgroup.procs: No such file or directory
03-17 12:28:37.407  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3547/cgroup.procs: No such file or directory
03-17 12:28:37.407  1017  1041 W libprocessgroup: failed to open /acct/uid_10069/pid_3932/cgroup.procs: No such file or directory
,03-17 12:28:37.417  3871  4695 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-17 12:28:37.457  1017  1476 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-17 12:28:37.457  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.457  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.457  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.457  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.467  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.477  1864  1864 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 12:28:37.487  1864  1864 D a       : Opening database auth.proximity.permit_store...
,03-17 12:28:37.487  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.487  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.487  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.497  1017  3168 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:37.497  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.497  1017  3168 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.497  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.517  1017  3836 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.517  1017  3836 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 12:28:37.517  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.517  1017  1234 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.537  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:37.537  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.537  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.537  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.537  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.547  1017  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:37.547  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.547  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.547  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.547  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.547   286   286 E SMD     : DCD OFF
,03-17 12:28:37.557  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.557  1017  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.557  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.557  1864  1864 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:37.567  1017  1150 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.567  1017  1150 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.567  1017  1150 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.577  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:37.577  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.577  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.577  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.577  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.587  1017  1234 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 12:28:37.587  1017  1234 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 12:28:37.587  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.587  1017  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:37.587  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:28:37.587  2427  2427 I Hs20UtilService: Starting #5
,03-17 12:28:37.587  1864  2112 W GCoreFlp: No location to return for getLastLocation()
,03-17 12:28:37.587  1864  4703 W FusedLocationProvider: location=null
,03-17 12:28:37.597  2427  2442 I Hs20UtilService: Message received 5007
,03-17 12:28:37.597  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 12:28:37.597  1310  1310 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 12:28:37.617  1017  1029 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-17 12:28:37.617  1017  1029 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-17 12:28:37.617  1017  1029 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-17 12:28:37.617  1017  1029 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 12:28:37.637  1017  3172 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:37.637  1864  4713 E MDM     : [248] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 12:28:37.637  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.637  1017  3172 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.647  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.647  1017  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:37.647  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 12:28:37.647  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.647  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.657  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.657  3871  4714 D LocationInitializer: Restart initialization of location
,03-17 12:28:37.657  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:37.657  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.657  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.657  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.657  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.667  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:37.667  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:37.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:37.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:37.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:37.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:28:37.687  1864  1864 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 12:28:37.687  1017  3168 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:37.697  1017  3168 W ActivityManager: userId = 0, bbcId = -10000,
03-17 12:28:37.687  1017  3168 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
03-17 12:28:37.697  1017  3168 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:37.697  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,03-17 12:28:37.697  1864  1864 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:28:37.707  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 12:28:37.707  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.707  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.707  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:37.707  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:37.717  1017  3172 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 12:28:37.717  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
03-17 12:28:37.717  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:37.717  1017  3172 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:37.717  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:28:37.717  2427  2427 I Hs20UtilService: Starting #6
,03-17 12:28:37.717  2427  2442 I Hs20UtilService: Message received 5007
,03-17 12:28:37.727  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 12:28:37.727  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 12:28:37.727  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 12:28:37.727  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-17 12:28:37.727  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 12:28:37.727  1310  1310 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 12:28:37.727  1864  2112 W GCoreFlp: No location to return for getLastLocation()
,03-17 12:28:37.727  1864  4715 W FusedLocationProvider: location=null
,03-17 12:28:37.747  1017  1993 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 12:28:37.747  1017  1993 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 12:28:37.747  1017  1993 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.747  1017  1993 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:37.747  1017  1993 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:28:37.747  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 12:28:37.757  2427  2427 I Hs20UtilService: Starting #7
,03-17 12:28:37.757  1310  1310 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 12:28:37.757  2427  2442 I Hs20UtilService: Message received 5007
,03-17 12:28:37.757  1017  3168 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-17 12:28:37.767  1017  1030 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-17 12:28:37.767  1017  1030 D SecContentProvider2: mCursor = null
,03-17 12:28:37.767  1017  1395 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 12:28:37.767  1017  1395 D SecContentProvider2: mCursor = null
,03-17 12:28:37.767  1017  1490 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-17 12:28:37.767  1017  1490 D SecContentProvider2: mCursor = null
,03-17 12:28:37.777  1017  1234 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
03-17 12:28:37.777  1017  1234 D SecContentProvider2: mCursor = null
,03-17 12:28:37.777  1017  1993 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-17 12:28:37.777  1017  1993 D SecContentProvider2: mCursor = null
,03-17 12:28:37.777  1017  1029 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-17 12:28:37.777  1017  1029 D SecContentProvider2: mCursor = null
,03-17 12:28:37.787  1017  3836 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,03-17 12:28:37.787  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.787  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.787  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.787  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.797  1017  3836 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4718 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:37.797  4718  4718 E Zygote  : MountEmulatedStorage()
03-17 12:28:37.797  4718  4718 E Zygote  : v2
03-17 12:28:37.797  4718  4718 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 12:28:37.797  4718  4718 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:37.807  4718  4718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:37.807  4718  4718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:37.807  4718  4718 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:37.817  4718  4718 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:37.827  4718  4718 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:37.847  4718  4718 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-17 12:28:37.847  4718  4718 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 12:28:37.847  4718  4718 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 12:28:37.857  4718  4718 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 12:28:37.857  4718  4718 I PCWCLIENTTRACE_PushUtil: sales region : global
,03-17 12:28:37.867  4718  4718 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,03-17 12:28:37.867  4718  4718 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-17 12:28:37.867  1017  1491 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
,03-17 12:28:37.867  1017  1491 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-17 12:28:37.867  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,03-17 12:28:37.867  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.867  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.867  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.867  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.887  4734  4734 E Zygote  : MountEmulatedStorage()
,03-17 12:28:37.887  4734  4734 E Zygote  : v2,
,03-17 12:28:37.887  1017  1491 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4734 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 12:28:37.887  4734  4734 I libpersona: KNOX_SDCARD checking this for 10111
,03-17 12:28:37.887  4734  4734 I libpersona: KNOX_SDCARD not a persona,
,03-17 12:28:37.887  4734  4734 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:37.897  4734  4734 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:37.897  4734  4734 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:28:37.897  1747  1747 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 12:28:37.897  3736  3736 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 12:28:37 GMT+01:00 2016
,03-17 12:28:37.907  4666  4666 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 12:28:37.907  1329  1345 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
03-17 12:28:37.907  4666  4666 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 12:28:37.907  4666  4666 D SecurityLogAgent: StateMachine : Current State = 1
03-17 12:28:37.907  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-17 12:28:37.907  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 12:28:37.907  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:37.907  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:37.907  4666  4666 D SecurityLogAgent: StateMachine : Changed Current State = 1
03-17 12:28:37.907  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 12:28:37.907  1017  1342 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-17 12:28:37.907  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:37.907  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:37.907  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:37.907  1017  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.917  3736  3736 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 12:28:37.917  1747  1747 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-17 12:28:37.917  1747  1747 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,03-17 12:28:37.917  4734  4734 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:37.917  4734  4734 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:37.927  1747  1747 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-17 12:28:37.927  3736  3736 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
03-17 12:28:37.927  1747  1747 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-17 12:28:37.927  3736  3736 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 12:28:37.927  4750  4750 E Zygote  : MountEmulatedStorage(),
03-17 12:28:37.927  4750  4750 I libpersona: KNOX_SDCARD checking this for 10159
03-17 12:28:37.927  4750  4750 E Zygote  : v2
03-17 12:28:37.927  4750  4750 I libpersona: KNOX_SDCARD not a persona,
03-17 12:28:37.927  4750  4750 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:37.927  1017  1342 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4750 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:28:37.927  3736  3736 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-17 12:28:37.927  4750  4750 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:37.937  4750  4750 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
03-17 12:28:37.937  3736  4745 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 12:28:37.937  3736  4745 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-17 12:28:37.947  1747  1747 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 12:28:37.947  1747  1747 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 12:28:37.947  1017  3836 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,03-17 12:28:37.947  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.947  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:37.947  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:37.947  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:37.957  3736  4745 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-17 12:28:37.957  3736  4745 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,03-17 12:28:37.957  3736  4745 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,03-17 12:28:37.967  4761  4761 E Zygote  : MountEmulatedStorage(),
03-17 12:28:37.967  4761  4761 E Zygote  : v2
03-17 12:28:37.967  4761  4761 I libpersona: KNOX_SDCARD checking this for 10081
03-17 12:28:37.967  4761  4761 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:37.967  4761  4761 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:37.967  4761  4761 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:37.967  4750  4750 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:37.967  4761  4761 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
03-17 12:28:37.967  4750  4750 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:37.977  1017  3836 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4761 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:37.997  4761  4761 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:37.997  4761  4761 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:38.007  3736  4745 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-17 12:28:38.007  3736  4745 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,03-17 12:28:38.017  3736  3736 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 12:28:38.027  4289  4780 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:28:38.027  4289  4780 I DBG_POLICYDM: [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
03-17 12:28:38.027  4289  4780 E DBG_POLICYDM: [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,03-17 12:28:38.057  4289  4780 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 12:28:38.057  4289  4780 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 12:28:38.057  4289  4780 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 12:28:38.057  4289  4780 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 12:28:38.067  4289  4780 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 12:28:38.067  4289  4780 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
03-17 12:28:38.067  4289  4780 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml,
,03-17 12:28:38.067  4289  4780 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-17 12:28:38.077  4289  4780 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,03-17 12:28:38.087  4289  4780 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:28:38.097  4355  4355 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,03-17 12:28:38.097  4393  4393 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,03-17 12:28:38.097  4393  4393 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-17 12:28:38.097  4393  4393 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-17 12:28:38.147  1017  1234 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 53510
,03-17 12:28:38.147  1017  1234 D PowerManagerService: [s] UserActivityState : 2 -> 1
03-17 12:28:38.147  1017  1234 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
,03-17 12:28:38.147  1017  1234 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{1000}) (elapsedTime=3469)
,03-17 12:28:38.147   256   256 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-17 12:28:38.157  1017  1486 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,03-17 12:28:38.167  1191  1191 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 12:28:38.277  4393  4393 I SA      : [SLFUCHKMGR] constructor called
,03-17 12:28:38.287  4393  4393 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 12:28:38.287  4393  4393 I SA      : [OR] == isSIMCardReady false ==
,03-17 12:28:38.297  3871  4788 I iu.SyncManager: SYNC; picasa accounts
,03-17 12:28:38.327  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,03-17 12:28:38.337  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:38.337  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:38.337  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:38.337  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:38.337  4393  4393 I SA      : [SCU] == networkStateCheck == true
,03-17 12:28:38.337  4393  4393 I SA      : [DM] getCountryCodeFromCSC : PL
03-17 12:28:38.337  4393  4393 I SA      : isChinaCountryCode : false
03-17 12:28:38.337  4393  4393 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-17 12:28:38.337  4393  4393 I SA      : [OR] == networkStateCheck true ==
,03-17 12:28:38.347  3871  3871 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-17 12:28:38.347  4790  4790 E Zygote  : MountEmulatedStorage()
03-17 12:28:38.347  4790  4790 I libpersona: KNOX_SDCARD checking this for 10113
03-17 12:28:38.347  4790  4790 E Zygote  : v2
03-17 12:28:38.347  4790  4790 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:38.347  4790  4790 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:38.347  1017  1029 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4790 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 12:28:38.357  4790  4790 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:38.357  4393  4393 I SA      : [OR] GetMyCountryZoneTask
03-17 12:28:38.357  4393  4393 I SA      : [OR] onReceive END
,03-17 12:28:38.357  4790  4790 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 12:28:38.357  3871  3871 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-17 12:28:38.357  1017  1476 I ActivityManager: Killing 3818:com.samsung.android.sm/1000 (adj 15): empty #31
,03-17 12:28:38.367  1241  1241 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-17 12:28:38.377  1017  1030 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
03-17 12:28:38.377  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
03-17 12:28:38.377  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:38.377  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:38.377  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 12:28:38.387  4790  4790 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:38.387  4790  4790 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:38.397  1017  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:38.397  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
03-17 12:28:38.397  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:38.397  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:38.397  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:38.407  1017  1395 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,03-17 12:28:38.407  4393  4796 I SA      : [SRS] prepareGetMyCountryZone
,03-17 12:28:38.417  1017  1150 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 12:28:38.417  1017  1150 D SecContentProvider2: mCursor = null
,03-17 12:28:38.417  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:38.417  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:38.417  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:38.417  1017  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:38.417  3871  4788 I iu.UploadsManager: num queued entries: 0
,03-17 12:28:38.417  3871  4788 I iu.UploadsManager: num updated entries: 0
,03-17 12:28:38.417  3871  4788 I iu.SyncManager: NEXT; no task
,03-17 12:28:38.427  4393  4796 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 12:28:38.427  4393  4796 I SA      : [SSP] query invoked
,03-17 12:28:38.437  4809  4809 E Zygote  : MountEmulatedStorage()
03-17 12:28:38.437  4809  4809 I libpersona: KNOX_SDCARD checking this for 10010
03-17 12:28:38.437  4809  4809 E Zygote  : v2
03-17 12:28:38.437  4809  4809 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:38.437  4809  4809 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:38.437  4809  4809 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:38.447  4809  4809 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 12:28:38.447  1017  1395 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4809 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 12:28:38.447  1017  1490 I ActivityManager: Killing 3987:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-17 12:28:38.467  4809  4809 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:38.467  4809  4809 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:38.507  4734  4734 I MusicStore: Database version: 108
,03-17 12:28:38.517  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3818/cgroup.procs: No such file or directory
,03-17 12:28:38.547  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3987/cgroup.procs: No such file or directory
,03-17 12:28:38.557   311   311 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 12:28:38.577  1017  1486 I art     : Explicit concurrent mark sweep GC freed 19745(1200KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/40MB, paused 2.596ms total 147.346ms
,03-17 12:28:38.577  4393  4796 I SA      : [TPMU] GetMccFromDB : null
03-17 12:28:38.577  4393  4796 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-17 12:28:38.577  4393  4796 I SA      : [TPM] isNoProxy(default) : true
,03-17 12:28:38.597  1017  1486 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 12:28:38.597  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 12:28:38.597  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:38.597  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:38.597  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:28:38.597  4393  4796 E File    : fail readDirectory() errno=2
,03-17 12:28:38.697   256  1057 I SurfaceFlinger: id=12 Removed Uoast (8/9)
,03-17 12:28:38.697   256   437 I SurfaceFlinger: id=12 Removed Uoast (-2/9)
,03-17 12:28:38.767  4809  4809 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-17 12:28:38.857  4734  4734 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:28:38.857  4734  4734 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:28:38.887  4734  4734 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 12:28:38.907  4809  4809 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-17 12:28:38.907  1017  1150 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:38.907  1017  1150 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-17 12:28:38.947  4734  4734 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 12:28:38.947  4734  4734 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4bc6599: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 12:28:38.947  4734  4734 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 12:28:38.947  4734  4734 D AndroidMusic: GMSCore installation verified
,03-17 12:28:38.977  1017  1395 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 12:28:38.977  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,03-17 12:28:38.977  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:38.977  1017  1395 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:38.977  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:28:38.987  4734  4734 I ConfigStore: Config Database version: 1
,03-17 12:28:39.077   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 12:28:39.077   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:39.077  4734  4734 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 12:28:39.077   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 12:28:39.077   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:39.087  4734  4734 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 12:28:39.087   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 12:28:39.087   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:39.087  4734  4734 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 12:28:39.107  1017  1234 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,03-17 12:28:39.107  1017  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,03-17 12:28:39.107  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:39.107  1017  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:39.107  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:28:39.107   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 12:28:39.107   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:39.117  4790  4840 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 12:28:39.117  1017  3172 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,03-17 12:28:39.117  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-17 12:28:39.117  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:39.117  1017  3172 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 12:28:39.117  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-17 12:28:39.117   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 12:28:39.117   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:39.127  4790  4840 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 12:28:39.127  1017  1476 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 12:28:39.127  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-17 12:28:39.127  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:39.127  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:39.127  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:28:39.137  1017  1150 D ActivityManager: startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
,03-17 12:28:39.137  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:39.137  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:39.137  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:39.137  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:39.147  4809  4809 D hcjo    : AutoUpdateManager:IDLE:execute
,03-17 12:28:39.157  4846  4846 E Zygote  : MountEmulatedStorage()
03-17 12:28:39.157  4846  4846 I libpersona: KNOX_SDCARD checking this for 10174
03-17 12:28:39.157  4846  4846 E Zygote  : v2
03-17 12:28:39.157  4846  4846 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:39.157  4846  4846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:39.157  4846  4846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:39.167  1017  1150 I ActivityManager: Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4846 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
03-17 12:28:39.157  4846  4846 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 12:28:39.187  4846  4846 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:39.187  4846  4846 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:39.187   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 12:28:39.187   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 12:28:39.197  4790  4844 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 12:28:39.197   255   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 12:28:39.197   255   530 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:28:39.197  4790  4844 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 12:28:39.207  4809  4809 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-17 12:28:39.207  4809  4809 D InitializeManagerStateMachine: exit::IDLE
,03-17 12:28:39.207  4809  4809 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-17 12:28:39.207  1017  1234 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:39.207  4809  4809 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-17 12:28:39.207  4809  4809 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-17 12:28:39.207  4809  4809 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-17 12:28:39.207  4809  4809 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-17 12:28:39.207  4809  4809 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-17 12:28:39.207  4809  4809 D InitializeManagerStateMachine: entry::SUCCESS
03-17 12:28:39.207  4809  4809 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-17 12:28:39.217  4809  4809 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-17 12:28:39.217  1017  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:39.227  4809  4809 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
03-17 12:28:39.227  4809  4809 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,03-17 12:28:39.227  1017  1395 I AudioService: getStreamVolume 3 index 0,
,03-17 12:28:39.227  4734  4734 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-17 12:28:39.237  4809  4809 D InitializeManagerStateMachine: exit::SUCCESS
03-17 12:28:39.237  4809  4809 D InitializeManagerStateMachine: entry::IDLE
,03-17 12:28:39.237  4734  4734 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-17 12:28:39.247  4734  4734 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 12:28:39.257  4846  4846 D jxcore_app_log: JniHelper::setJavaVM(0xb72b2450), pthread_self() = -1225396536
,03-17 12:28:39.257  4846  4846 E JX-Cordova: JXcore wasn't initialized yet
,03-17 12:28:39.297  1017  3172 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 12:28:39.297  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 12:28:39.297  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:39.297  1017  3172 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:39.297  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:28:39.297  1017  1486 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 12:28:39.297  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,03-17 12:28:39.297  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:39.297  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:39.297  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:28:39.307  1017  1476 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 12:28:39.307  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,03-17 12:28:39.307  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:39.307  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:39.307  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:28:39.317  1017  2782 D SSRM:n  : SIOP:: AP = 400
03-17 12:28:39.317  1017  3836 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:28:39.327  4734  4734 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 12:28:39.327  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,03-17 12:28:39.327  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:39.327  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:39.327  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:39.327  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:39.347  4875  4875 E Zygote  : MountEmulatedStorage()
03-17 12:28:39.347  4875  4875 E Zygote  : v2
03-17 12:28:39.347  4875  4875 I libpersona: KNOX_SDCARD checking this for 10002
03-17 12:28:39.347  4875  4875 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:39.347  4875  4875 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:39.347  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4875 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:39.347  4875  4875 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:39.347  4875  4875 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:39.367  4875  4875 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:39.377  4875  4875 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:39.387  1017  3168 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
03-17 12:28:39.387  1017  3168 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-17 12:28:39.387  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:39.387  1017  3168 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:39.387  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-17 12:28:39.407  4734  4734 W GoogleHttpClient: Failed to load SSLCertificateSocketFactory from package
03-17 12:28:39.407  4734  4734 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,03-17 12:28:39.407  4734  4734 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,03-17 12:28:39.407  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 12:28:39.407  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 12:28:39.407  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:39.407  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:39.407  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:28:39.417  1017  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:39.417  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:39.417  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:39.417  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-17 12:28:39.427  4790  4790 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 12:28:39.437  4790  4790 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 4803-4804)
,03-17 12:28:39.437  4790  4790 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:28:39.447  1017  1030 I ActivityManager: Killing 3460:com.google.android.youtube/u0a166 (adj 15): empty #31
,03-17 12:28:39.497  4790  4790 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cbfbda4}
,03-17 12:28:39.497  4790  4790 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:28:39.497  4790  4790 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 12:28:39.507  1017  1098 V AlarmManager: waitForAlarm result :4
,03-17 12:28:39.527  4790  4790 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 12:28:39.527  4790  4790 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:28:39.527  1017  3172 I ActivityManager: Killing 3837:com.google.android.gm/u0a101 (adj 15): empty #31
,03-17 12:28:39.537  4790  4790 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 12:28:39.537  1017  1993 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,03-17 12:28:39.537  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:39.537  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:39.537  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:39.537  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:39.557  4896  4896 E Zygote  : MountEmulatedStorage()
,03-17 12:28:39.557  4896  4896 E Zygote  : v2
03-17 12:28:39.557  4896  4896 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:39.557  4896  4896 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:39.557  1017  1993 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4896 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:39.557   311   311 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:28:39.557  4896  4896 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:39.557  4896  4896 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:39.557  4896  4896 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:39.567  1017  1041 W libprocessgroup: failed to open /acct/uid_10166/pid_3460/cgroup.procs: No such file or directory
,03-17 12:28:39.577  4896  4896 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:39.577  4896  4896 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:39.597  4790  4790 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-17 12:28:39.597  4790  4790 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,03-17 12:28:39.597  4790  4790 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,03-17 12:28:39.607  4790  4790 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 12:28:39.607  4790  4790 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:28:39.607  4790  4790 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:28:39.607  4790  4790 I Adreno-EGL: Local Branch: 
03-17 12:28:39.607  4790  4790 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:28:39.607  4790  4790 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:28:39.607  4790  4790 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 12:28:39.617  1017  2857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:28:39.627  4896  4896 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 12:28:39.647  1017  1041 W libprocessgroup: failed to open /acct/uid_10101/pid_3837/cgroup.procs: No such file or directory
,03-17 12:28:39.677  4790  4790 I NSApplication: Starting up...
,03-17 12:28:39.697  1017  1486 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,03-17 12:28:39.697  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:39.697  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:39.697  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:39.697  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:39.697  4790  4922 W AudioManagerAndroid: Requires BLUETOOTH permission,
,03-17 12:28:39.717  4927  4927 E Zygote  : MountEmulatedStorage(),
03-17 12:28:39.717  4927  4927 E Zygote  : v2
,03-17 12:28:39.717  4927  4927 I libpersona: KNOX_SDCARD checking this for 10120
03-17 12:28:39.717  4927  4927 I libpersona: KNOX_SDCARD not a persona,
,03-17 12:28:39.717  4927  4927 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:39.727  4927  4927 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 12:28:39.727  4927  4927 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 12:28:39.727  1017  1486 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4927 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:39.737  1017  1486 I ActivityManager: Killing 4025:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,03-17 12:28:39.737  1017  1486 I ActivityManager: Killing 3949:com.vlingo.midas/u0a31 (adj 15): empty #32
,03-17 12:28:39.777  4927  4927 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:39.777  4927  4927 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:39.777  4896  4896 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 12:28:39.787  4896  4896 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 12:28:39.797  4896  4896 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-17 12:28:39.797  4896  4896 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 12:28:39.797  4896  4896 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-17 12:28:39.797  4896  4896 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 12:28:39.807  4927  4927 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:28:39.837  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4025/cgroup.procs: No such file or directory
03-17 12:28:39.837  1017  1041 W libprocessgroup: failed to open /acct/uid_10031/pid_3949/cgroup.procs: No such file or directory
,03-17 12:28:39.887  1017  1491 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-17 12:28:39.887  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:39.887  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 12:28:39.887  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:39.887  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 12:28:39.897  4946  4946 E Zygote  : MountEmulatedStorage()
,03-17 12:28:39.897  4946  4946 E Zygote  : v2
03-17 12:28:39.897  4946  4946 I libpersona: KNOX_SDCARD checking this for 10009
03-17 12:28:39.897  4946  4946 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:39.897  4946  4946 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:39.907  4946  4946 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:39.907  4946  4946 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 12:28:39.917  1017  1491 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4946 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:39.927  4946  4946 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:39.937  4946  4946 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:39.937   301   301 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 682us total 26.253ms
,03-17 12:28:39.957   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 16.991ms
,03-17 12:28:39.957  4393  4796 I SA      : [RC New] Execute method=[GET] start
,03-17 12:28:39.967   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.262ms
,03-17 12:28:40.007  4393  4796 I SA      : [RC New] Security=[true]
,03-17 12:28:40.007  4393  4796 I System.out: Thread-660(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 12:28:40.007  4393  4796 I System.out: Thread-660(ApacheHTTPLog):isSBSettingEnabled false
03-17 12:28:40.007  4393  4796 I System.out: Thread-660(ApacheHTTPLog):isShipBuild true
03-17 12:28:40.007  4393  4796 I System.out: Thread-660(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 12:28:40.007  4393  4796 I System.out: Thread-660(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 12:28:40.007   275  1012 D EnterpriseController: uids 10041
03-17 12:28:40.007   275  1012 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:28:40.007   275  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,03-17 12:28:40.027  1017  3172 I ActivityManager: Killing 4053:com.android.vending/u0a28 (adj 15): empty #31
,03-17 12:28:40.027  4946  4946 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 12:28:40.037  4946  4946 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 12:28:40.037  4946  4946 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 12:28:40.047  4946  4946 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 12:28:40.047  1017  1395 I ActivityManager: Killing 4231:com.samsung.helphub/1000 (adj 15): empty #31
,03-17 12:28:40.147  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4231/cgroup.procs: No such file or directory
,03-17 12:28:40.147  1017  1041 W libprocessgroup: failed to open /acct/uid_10028/pid_4053/cgroup.procs: No such file or directory
,03-17 12:28:40.217  4492  4492 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-17 12:28:40.217  4492  4492 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-17 12:28:40.217  4492  4492 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 12:28:40.227  1017  3172 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:40.227  1017  1993 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:28:40.237  1017  3168 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 12:28:40.237  1017  3168 I ActivityManager: Killing 4274:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-17 12:28:40.237  1017  1017 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
03-17 12:28:40.237  1017  1017 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-17 12:28:40.247  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
03-17 12:28:40.247  4946  4946 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 12:28:40.247  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.247  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.247  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.247  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.267  4968  4968 E Zygote  : MountEmulatedStorage(),
03-17 12:28:40.267  4968  4968 I libpersona: KNOX_SDCARD checking this for 10062
03-17 12:28:40.267  4968  4968 E Zygote  : v2,
03-17 12:28:40.267  4968  4968 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:40.267  4968  4968 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:40.267  1017  1042 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4968 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 12:28:40.277  4968  4968 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:40.277  1017  1486 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-17 12:28:40.277  4968  4968 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:40.277  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
03-17 12:28:40.287  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:40.287  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:40.287  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 12:28:40.287  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:40.287  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 12:28:40.287  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:40.297  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:28:40.297  4968  4968 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:40.297  4968  4968 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:40.307  1017  1030 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-17 12:28:40.307  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 12:28:40.307  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:40.307  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:40.307  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 12:28:40.307  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 12:28:40.307  4946  4946 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-17 12:28:40.307  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,03-17 12:28:40.317  1329  1329 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 12:28:40.317  1329  1329 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 12:28:40.317  1329  1329 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 12:28:40.317  1329  1329 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 12:28:40.317  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-17 12:28:40.317  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 12:28:40.317  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 12:28:40.327  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:28:40.327  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 12:28:40.327  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 12:28:40.327  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 12:28:40.327  4666  4666 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 12:28:40.337  4666  4666 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-17 12:28:40.337  4666  4666 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 12:28:40.337  1017  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:28:40.337  1017  1491 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4311, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-17 12:28:40.337  1017  1491 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-17 12:28:40.337  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 12:28:40.337  3736  3736 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Mar 17 12:28:40 GMT+01:00 2016
,03-17 12:28:40.347  1017  1017 I MotionRecognitionService: Plugged
,03-17 12:28:40.347  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 12:28:40.347  1329  1329 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 12:28:40.347  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 12:28:40.347  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 12:28:40.347  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 12:28:40.347  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 12:28:40.347  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4274/cgroup.procs: No such file or directory
,03-17 12:28:40.357  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 12:28:40.357  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 12:28:40.357  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-17 12:28:40.367  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-17 12:28:40.367  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 12:28:40.367  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:40.367  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:40.367  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 12:28:40.367  2692  2692 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 12:28:40.377  2692  2781 D HeadsetStateMachine: Disconnected process message: 10
,03-17 12:28:40.377  1017  1150 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,03-17 12:28:40.377  4968  4968 I ExternalOEMControlProvider: onCreate
,03-17 12:28:40.377  3736  3736 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 12:28:40.377  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.377  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.377  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.377  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.387  3736  3736 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 12:28:40.387  3736  3736 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,03-17 12:28:40.397  3736  3736 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 12:28:40.397  4987  4987 I libpersona: KNOX_SDCARD checking this for 10157
03-17 12:28:40.397  4987  4987 E Zygote  : MountEmulatedStorage()
03-17 12:28:40.397  4987  4987 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:40.397  4987  4987 E Zygote  : v2
03-17 12:28:40.397  4987  4987 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:40.397  1017  1150 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4987 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,03-17 12:28:40.407  4987  4987 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:40.407  4987  4987 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:40.407  4393  4393 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-17 12:28:40.417  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-17 12:28:40.417  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.417  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.417  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.417  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.427  1329  1329 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,03-17 12:28:40.427  1329  1329 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 12:28:40.427  3736  4986 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-17 12:28:40.427  5000  5000 E Zygote  : MountEmulatedStorage(),
03-17 12:28:40.427  5000  5000 E Zygote  : v2
03-17 12:28:40.437  5000  5000 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 12:28:40.437  5000  5000 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:40.437  5000  5000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 12:28:40.437  1017  1030 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=5000 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:40.437  5000  5000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:40.447  5000  5000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:40.447  4987  4987 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:40.447  4987  4987 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:40.447  3736  4986 I KLMS-2.5.183: : KLMSIntentService(): TIME_CHANGED
,03-17 12:28:40.447  3736  4986 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().START : Thu Mar 17 12:28:40 GMT+01:00 2016
,03-17 12:28:40.457  4968  4996 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-17 12:28:40.457  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,03-17 12:28:40.457  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.457  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.457  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.457  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.467  5000  5000 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:40.467  5000  5000 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:40.467  3736  4986 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().END
,03-17 12:28:40.477  5018  5018 E Zygote  : MountEmulatedStorage()
,03-17 12:28:40.477  5018  5018 E Zygote  : v2
03-17 12:28:40.477  5018  5018 I libpersona: KNOX_SDCARD checking this for 10046
03-17 12:28:40.477  5018  5018 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:40.477  5018  5018 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:40.477  5018  5018 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 12:28:40.477  1017  1030 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=5018 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
03-17 12:28:40.477  5018  5018 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 12:28:40.487  4987  4987 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:40.487  1017  3172 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:40.487  1017  3172 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 12:28:40.497  1017  3172 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:40.497  1017  3172 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:40.497  1017  3172 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:40.507  3736  3736 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 12:28:40.507  1017  3168 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,03-17 12:28:40.517  5000  5000 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:40.517  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.517  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.517  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.517  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.527  5030  5030 E Zygote  : MountEmulatedStorage(),
03-17 12:28:40.527  5030  5030 E Zygote  : v2
03-17 12:28:40.527  5030  5030 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:40.527  5030  5030 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:40.527  5030  5030 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:40.537  1017  3168 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5030 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:40.537  5018  5018 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:40.537  5030  5030 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:40.537  5018  5018 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:40.537  5030  5030 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:40.557   286   286 E SMD     : DCD OFF
,03-17 12:28:40.557   311   311 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:28:40.557  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 12:28:40.557  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 12:28:40.557  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:40.557  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:28:40.567  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:40.577  5018  5018 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-17 12:28:40.577  5018  5018 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:40.577  5018  5018 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:28:40.577  5018  5018 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:28:40.577  5018  5018 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 12:28:40.577  5018  5018 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 12:28:40.587  5030  5030 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:40.587  5030  5030 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:40.597  1747  1747 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-17 12:28:40.597  1747  1747 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 12:28:40.597  1017  3836 I ActivityManager: Killing 4308:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-17 12:28:40.597  1017  3172 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,03-17 12:28:40.607  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.607  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:40.607  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.607  1017  3172 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:40.617  5049  5049 E Zygote  : MountEmulatedStorage(),
03-17 12:28:40.617  5049  5049 E Zygote  : v2
03-17 12:28:40.617  5049  5049 I libpersona: KNOX_SDCARD checking this for 10085
03-17 12:28:40.617  5049  5049 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:40.617  5049  5049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:40.617  5049  5049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 12:28:40.617  1017  3172 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=5049 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:28:40.617  5049  5049 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:40.647  1017  1342 I ActivityManager: Killing 4332:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,03-17 12:28:40.647  5049  5049 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:40.657  5049  5049 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:40.667  5049  5049 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 12:28:40.667  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:28:40.667  5049  5049 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:28:40.667  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:28:40.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:40.667  5049  5049 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:28:40.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:40.667  5049  5049 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:28:40.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:40.667  5049  5049 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:40.667  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:28:40.667  5049  5049 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 12:28:40.677  5030  5030 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458214120687,
03-17 12:28:40.677  5030  5030 D         : TimeServiceNative: User Time to be set is 1458214120687
03-17 12:28:40.677  5030  5030 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2,
03-17 12:28:40.677  5030  5030 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-17 12:28:40.677  5030  5030 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458214120687
03-17 12:28:40.677   313   556 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-17 12:28:40.677   313  5064 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458214120687
03-17 12:28:40.677   313  5064 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458214120687, operation = 0
03-17 12:28:40.677   313  5064 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/16/70 9:33:54
03-17 12:28:40.677   313  5064 D QC-time-services: Daemon:Value read from RTC seconds = 22325634000
03-17 12:28:40.677   313  5064 D QC-time-services: Daemon:new time 1458214120687 
03-17 12:28:40.677   313  5064 D QC-time-services: Daemon: delta 1435888486687 genoff 1435888486687 
03-17 12:28:40.677   313  5064 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1435888486687 to memory
03-17 12:28:40.677   313  5064 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-17 12:28:40.677   313  5064 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-17 12:28:40.677  5030  5030 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-17 12:28:40.707  5018  5018 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-17 12:28:40.727  1017  3172 D SettingsProvider: name = next_alarm_formatted
,03-17 12:28:40.727  1017  3172 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:40.727  1017  3172 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:40.727  1017  3172 D SettingsProvider: selectionArgs: false
,03-17 12:28:40.727  1017  3172 D SettingsProvider: selectionArgs: 10085
,03-17 12:28:40.727  1017  3172 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:40.727  1017  3172 D SettingsProvider: ret = -1
,03-17 12:28:40.747   313  5064 D QC-time-services: Updating the TOD offset
03-17 12:28:40.747   313  5064 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1435888486687 to memory
03-17 12:28:40.747   313  5064 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 12:28:40.747   313  5064 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 12:28:40.747   313  5064 E QC-time-services: Daemon:Update to modem bit set
03-17 12:28:40.747   313  5064 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-17 12:28:40.747   313  5064 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1119923686687
,03-17 12:28:40.747   313   554 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-17 12:28:40.747   313   556 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-17 12:28:40.757  5030  5030 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-17 12:28:40.757  1017  1342 I ActivityManager: Killing 4455:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 12:28:40.777  1017  3836 I ActivityManager: Killing 4511:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-17 12:28:40.797  4393  4796 I SA      : [RC New] [v2liruge] api execute + 790
03-17 12:28:40.797  4393  4796 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-17 12:28:40.797  4393  4796 I System.out: AsyncTask #1 calls detatch()
,03-17 12:28:40.827  1017  1041 W libprocessgroup: failed to open /acct/uid_10107/pid_4332/cgroup.procs: No such file or directory
,03-17 12:28:40.827  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4308/cgroup.procs: No such file or directory
,03-17 12:28:40.827  4393  4796 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-17 12:28:40.827  4393  4796 I SA      : [OCP] update openData : PL
,03-17 12:28:40.837  4393  4796 I SA      : [TPMU] getNetworkMcc : 
,03-17 12:28:40.837  4393  4796 I SA      : [SCU] saveMccToPreferece Start
,03-17 12:28:40.837  4393  4796 I SA      : [SCU] RegionMCC : 260
,03-17 12:28:40.837  4393  4796 I SA      : [SSP] query invoked
,03-17 12:28:40.897  5049  5049 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 155.033ms
,03-17 12:28:40.897  5018  5018 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 137.190ms
,03-17 12:28:40.907  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4455/cgroup.procs: No such file or directory
03-17 12:28:40.907  1017  1041 W libprocessgroup: failed to open /acct/uid_10131/pid_4511/cgroup.procs: No such file or directory
,03-17 12:28:40.987  1017  1029 I art     : Explicit concurrent mark sweep GC freed 18382(1035KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/40MB, paused 2.612ms total 143.836ms
,03-17 12:28:40.987  5018  5065 D Mms/ArtClassLoader: init before art
,03-17 12:28:40.987  5018  5018 D Mms/TelephonyPermission: start operation mode monitor
,03-17 12:28:40.997  4393  4796 I SA      : [TPMU] GetMccFromDB : null
,03-17 12:28:40.997  4393  4796 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-17 12:28:40.997  4393  4796 I SA      : [SCU] saveMccToPreferece End
,03-17 12:28:40.997  4393  4796 I SA      : [RC New] executeRequest [v2liruge] end. 1042
,03-17 12:28:40.997  4393  4796 I SA      : [RC New] Execute end
,03-17 12:28:40.997  4393  4393 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,03-17 12:28:40.997  4393  4393 I SA      : [OR] GetMyCountryZoneTask Success
,03-17 12:28:41.007  1017  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-17 12:28:41.007  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.007  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.007  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.007  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:41.007  5018  5018 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:28:41.017  1017  1486 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5066 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-17 12:28:41.027  1017  1486 I ActivityManager: Killing 4552:com.sec.android.app.camera/u0a139 (adj 15): empty #31
03-17 12:28:41.027  5066  5066 E Zygote  : MountEmulatedStorage()
,03-17 12:28:41.027  5066  5066 E Zygote  : v2
,03-17 12:28:41.027  5066  5066 I libpersona: KNOX_SDCARD checking this for 10094
03-17 12:28:41.027  5066  5066 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:41.027  5066  5066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:41.027  5066  5066 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:41.027  5066  5066 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:41.037  5018  5018 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-17 12:28:41.037  5018  5018 D Mms/TelephonyPermission: isDefault true
,03-17 12:28:41.037  5018  5018 D Mms/MmsApp: onCreate() com.android.mms
,03-17 12:28:41.057  5066  5066 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:41.057  5066  5066 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:41.077  5018  5018 D Mms/MmsApp: [start]    initCountryIso consume time = 370.723802
,03-17 12:28:41.087  1017  1993 D CountryDetector: The first listener is added
,03-17 12:28:41.087  5018  5018 D Mms/MmsApp: [end]    initCountryIso consume time = 7.612031
,03-17 12:28:41.087  5018  5018 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.678281
,03-17 12:28:41.097  5018  5018 D Mms/MmsConfig: before partial update
,03-17 12:28:41.097  5066  5066 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-17 12:28:41.097  5066  5066 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 12:28:41.097  5066  5066 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 12:28:41.097  1017  1234 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,03-17 12:28:41.097  1017  1234 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 12:28:41.107  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:41.107  1017  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:41.107  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 12:28:41.107  1017  1476 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,03-17 12:28:41.107  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,03-17 12:28:41.107  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:41.107  1017  1476 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 12:28:41.117  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-17 12:28:41.117  5018  5018 D Mms/MmsConfig: Load Resize quality : 80
,03-17 12:28:41.117  5066  5066 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-17 12:28:41.117  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,03-17 12:28:41.127  5018  5018 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-17 12:28:41.127  5018  5018 D EasySignUpManager_1.0.1: isAuth is false
,03-17 12:28:41.127  5018  5018 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
03-17 12:28:41.127  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.127  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:41.127  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.127  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:41.127  5066  5066 D elm:15183: ElmAgentService : onCreate()
,03-17 12:28:41.127  5066  5084 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-17 12:28:41.137  5066  5084 D elm:15183: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,03-17 12:28:41.137  5066  5066 D elm:15183: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,03-17 12:28:41.137  5066  5066 D elm:15183: ModuleBase.ModifySetAlarm()
03-17 12:28:41.137  5066  5066 D elm:15183: MDMBridge.getInstance()
03-17 12:28:41.137  5066  5066 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 12:28:41.147  5086  5086 E Zygote  : MountEmulatedStorage()
,03-17 12:28:41.147  5086  5086 E Zygote  : v2
03-17 12:28:41.147  5086  5086 I libpersona: KNOX_SDCARD checking this for 10134
,03-17 12:28:41.147  5086  5086 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:41.147  5086  5086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:41.147  5086  5086 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:41.147  5086  5086 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 12:28:41.157  1017  1491 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5086 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,03-17 12:28:41.157  5066  5066 D elm:15183: ElmAgentService : onDestroy().
,03-17 12:28:41.167  1467  1810 D TP/MmsSmsProvider: query,matched:2117, calling pid = 5018
,03-17 12:28:41.167  1467  1810 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.241 ms
,03-17 12:28:41.167  1017  1476 I ActivityManager: Killing 4595:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-17 12:28:41.177  5018  5018 D EasySignUpManager_1.0.1: isAuth is false
,03-17 12:28:41.177  5018  5018 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-17 12:28:41.187  5018  5018 E CscParser: mps_code.dat does not exist
03-17 12:28:41.187  5018  5018 E CscParser: customer_path =/system/csc/customer.xml
03-17 12:28:41.187  5018  5018 E CscParser: fileName + /system/csc/customer.xml
,03-17 12:28:41.187  5086  5086 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:41.187  5086  5086 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:41.197  5018  5018 E CscParser: mps_code.dat does not exist
03-17 12:28:41.197  5018  5018 E CscParser: customer_path =/system/csc/customer.xml
03-17 12:28:41.197  5018  5018 E CscParser: fileName + /system/csc/customer.xml
,03-17 12:28:41.197  1017  1041 W libprocessgroup: failed to open /acct/uid_10139/pid_4552/cgroup.procs: No such file or directory
,03-17 12:28:41.207  5086  5086 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:41.207  5086  5086 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-17 12:28:41.207  5018  5018 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-17 12:28:41.207  5018  5018 D Mms/MmsConfig:  enable multiwindow = true
,03-17 12:28:41.217  5018  5018 E Mms/MessageUtils: setCountryDetector : update country detector info 
,03-17 12:28:41.217  5018  5018 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-17 12:28:41.227  5018  5018 D Mms/MmsConfig: [end]    init() consume time = 139.526615
,03-17 12:28:41.227  5018  5018 D Mms/Contact: [start]    init() consume time = 1.533229
,03-17 12:28:41.237  1017  1486 I ActivityManager: Killing 4634:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 12:28:41.257  1467  1484 D TP/MmsSmsProvider: query,matched:13, calling pid = 5018
,03-17 12:28:41.257  1467  1484 D TP/MmsSmsProvider: match 13:Elapsed time : 1.334 ms
,03-17 12:28:41.257  5018  5018 D Mms/Contact: [end]    init consume time = 28.901042
,03-17 12:28:41.267  5018  5106 D Mms/DraftCache: [start]    rebuildCache consume time = 8.607604
,03-17 12:28:41.267  1017  1041 W libprocessgroup: failed to open /acct/uid_10072/pid_4595/cgroup.procs: No such file or directory
,03-17 12:28:41.277  5018  5018 D Mms/MethodReflector: getSubId is called
03-17 12:28:41.277  5018  5018 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 12:28:41.277  1467  1810 D TP/MmsSmsProvider: query,matched:12, calling pid = 5018
,03-17 12:28:41.277  1467  1810 D TP/MmsSmsProvider: match 12:Elapsed time : 2.683 ms
,03-17 12:28:41.277  5018  5018 D Mms/MethodReflector: getTelephonyProperty is called
03-17 12:28:41.277  5018  5018 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 12:28:41.277  5018  5018 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 12:28:41.277  5018  5018 D Mms/DownloadManager: auto download without roaming -> true
03-17 12:28:41.277  5018  5018 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,03-17 12:28:41.277  5018  5018 D Mms/MethodReflector: getSubId is called
,03-17 12:28:41.277  5018  5018 D Mms/MethodReflector: getDefaultSmsSubId is called
03-17 12:28:41.277  5018  5018 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-17 12:28:41.277  5018  5018 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-17 12:28:41.277  5018  5018 D Mms/MethodReflector: getTelephonyProperty is called
03-17 12:28:41.277  5018  5018 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-17 12:28:41.277  5018  5018 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-17 12:28:41.277  5018  5018 D Mms/DownloadManager: auto download without roaming -> true
03-17 12:28:41.277  5018  5018 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-17 12:28:41.277  5018  5018 D Mms/DownloadManager: auto download during roaming secondary -> false
03-17 12:28:41.277  5018  5018 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 12:28:41.287  5018  5106 D Mms/DraftCache: [end]    rebuildCache consume time = 17.036614
,03-17 12:28:41.287  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4634/cgroup.procs: No such file or directory
,03-17 12:28:41.337  5018  5018 D ComposerPerformance: 1458214121347 ms / [DONE] Composer constructor
,03-17 12:28:41.337  5018  5109 D Mms/Conversation: [start]    init() consume time = 53.955
,03-17 12:28:41.337  5018  5018 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-17 12:28:41.337  5018  5018 I Mms/ReservationManager: ReservationManager()
,03-17 12:28:41.337  5018  5018 I Mms/ReservationManager: resetAfterConnected()
,03-17 12:28:41.337  1467  1810 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-17 12:28:41.347  1467  1482 D TP/MmsSmsProvider: query,matched:7, calling pid = 5018
,03-17 12:28:41.347  1467  1810 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 12:28:41.347  1467  1810 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-17 12:28:41.347  1467  1482 D TP/MmsSmsProvider: match 7:Elapsed time : 4.242 ms
,03-17 12:28:41.357  5018  5018 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 12:28:41.357  1467  1810 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-17 12:28:41.357  5018  5018 D Mms/MmsApp: [end]    onCreate() consume time = 18.101198
,03-17 12:28:41.357  1467  1810 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:28:41.357  1467  1810 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:28:41.357  1467  1810 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:28:41.357  1467  1810 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:28:41.357  1467  1810 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:28:41.357  1467  1810 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:28:41.357  5018  5018 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-17 12:28:41.357  1017  1476 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,03-17 12:28:41.367  5018  5018 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-17 12:28:41.367  5018  5018 D Mms/MethodReflector: getSubId is called
03-17 12:28:41.367  5018  5018 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 12:28:41.367  5018  5018 D Mms/MethodReflector: getTelephonyProperty is called
,03-17 12:28:41.367  5018  5018 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 12:28:41.367  5018  5018 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 12:28:41.367  5018  5018 D Mms/DownloadManager: auto download without roaming -> true
03-17 12:28:41.367  5018  5018 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-17 12:28:41.367  5018  5018 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 12:28:41.367  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:41.367  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:41.367  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 12:28:41.367  1467  1810 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-17 12:28:41.367  1467  1810 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 12:28:41.367  1017  1476 I ActivityManager: Killing 4718:com.sec.pcw.device/1000 (adj 15): empty #31
,03-17 12:28:41.377  5018  5109 D Mms/Conversation: [end]    init consume time = 17.997969
,03-17 12:28:41.377  5018  5109 D Mms/MessagingNotification: [start]    init() consume time = 0.830885
,03-17 12:28:41.377  5018  5109 D Mms/MessagingNotification: [end]    init consume time = 3.490313
,03-17 12:28:41.387  1467  1482 D TP/MmsSmsProvider: query,matched:0, calling pid = 5018
03-17 12:28:41.387  1467  1482 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-17 12:28:41.387  1467  1482 D TP/MmsSmsProvider: match 0:Elapsed time : 1.251 ms
,03-17 12:28:41.387  5018  5111 D Mms/Synchronizer: [start]    doSync consume time = 6.834948
,03-17 12:28:41.387  1017  1234 D ActivityManager: startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
03-17 12:28:41.387  1017  1234 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,03-17 12:28:41.387  1017  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:41.387  1467  1484 D TP/MmsSmsProvider: update, matched:300, calling pid = 5018
03-17 12:28:41.387  1467  1484 V TP/MmsSmsProvider: syncDBData start
03-17 12:28:41.387  1017  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:41.387  1017  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 12:28:41.387  1467  1484 V TP/MmsSmsProvider: syncDBData sms end
,03-17 12:28:41.387  1467  1484 V TP/MmsSmsProvider: syncDBData mms end
,03-17 12:28:41.387  1467  1484 V TP/MmsSmsProvider: syncDBData end
,03-17 12:28:41.397  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:41.397  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:41.397  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:28:41.397  5018  5111 D Mms/Synchronizer: [end]    doSync consume time = 11.643542
,03-17 12:28:41.407  5018  5110 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 5.321822
,03-17 12:28:41.407  1017  1150 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,03-17 12:28:41.407  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.407  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.407  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.407  1017  1150 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:41.417  5113  5113 E Zygote  : MountEmulatedStorage(),
03-17 12:28:41.417  5113  5113 I libpersona: KNOX_SDCARD checking this for 10072,
,03-17 12:28:41.417  5113  5113 E Zygote  : v2,
03-17 12:28:41.417  5113  5113 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:41.427  5113  5113 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 12:28:41.427  1017  1150 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5113 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
,03-17 12:28:41.427  5113  5113 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:41.427  5113  5113 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 12:28:41.437  1467  1482 D TP/MmsSmsProvider: query,matched:400, calling pid = 5018
,03-17 12:28:41.437  5018  5110 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 37.043073
,03-17 12:28:41.447  5018  5065 D Mms/ArtClassLoader: init [DONE] art
,03-17 12:28:41.447  1017  3836 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:41.447  1017  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:41.447  1017  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-17 12:28:41.457  5113  5113 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:41.457  5113  5113 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:41.467  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:41.467  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 12:28:41.467  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 12:28:41.477  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4718/cgroup.procs: No such file or directory
,03-17 12:28:41.497  1017  1993 I ActivityManager: Killing 4106:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,03-17 12:28:41.507  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:41.507  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 12:28:41.507  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 12:28:41.507  1864  1864 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-17 12:28:41.507  1017  3836 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:41.507  1017  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 12:28:41.507  1017  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 12:28:41.517  1017  3168 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:28:41.517  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:41.517  5113  5113 D BadgeProvider: onCreate
,03-17 12:28:41.517  1017  3168 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:28:41.517  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:28:41.517  5113  5113 D BadgeProvider: DatabaseHelper
,03-17 12:28:41.527  1017  3836 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-17 12:28:41.527  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.527  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.527  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.527  1017  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:41.537  5129  5129 E Zygote  : MountEmulatedStorage(),
03-17 12:28:41.537  5129  5129 E Zygote  : v2
,03-17 12:28:41.537  5129  5129 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 12:28:41.537  5129  5129 I libpersona: KNOX_SDCARD not a persona
,03-17 12:28:41.547  5129  5129 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 12:28:41.547  1017  3836 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5129 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:28:41.547  5129  5129 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:41.547  5129  5129 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:41.557   311   311 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:28:41.567  5018  5109 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-17 12:28:41.567  1467  1484 D TP/SmsProvider: query,matched:26, calling pid = 5018
,03-17 12:28:41.567  1467  1484 D TP/SmsProvider: match 26:Elapsed time : 1.152 ms
,03-17 12:28:41.577  5129  5129 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:41.577  5129  5129 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:41.587  1467  1482 D TP/MmsSmsProvider: query,matched:6, calling pid = 5018
,03-17 12:28:41.587  1467  1482 D TP/MmsSmsProvider: match 6:Elapsed time : 1.706 ms
,03-17 12:28:41.607  1017  1993 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,03-17 12:28:41.607  5018  5018 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-17 12:28:41.607  1017  1017 I ValidateNoPeople: mEvictionCount: 0
03-17 12:28:41.607  5018  5018 D Mms/Contact: performUpdate:widgetCount=0
,03-17 12:28:41.607  5018  5144 D Mms/ContactsCache: [start]    invalidate() consume time = 167.794479
03-17 12:28:41.607  5018  5144 D Mms/ContactsCache: [end]    invalidate() consume time = 0.141615
,03-17 12:28:41.607  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.607  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.607  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.607  1017  1993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:41.617  1017  1041 W libprocessgroup: failed to open /acct/uid_10032/pid_4106/cgroup.procs: No such file or directory,
,03-17 12:28:41.617  5129  5129 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE,
,03-17 12:28:41.627  5145  5145 E Zygote  : MountEmulatedStorage()
03-17 12:28:41.627  5145  5145 E Zygote  : v2
03-17 12:28:41.627  5145  5145 I libpersona: KNOX_SDCARD checking this for 10025
03-17 12:28:41.627  5145  5145 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:41.627  5145  5145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:41.627  5145  5145 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 12:28:41.627  1017  1993 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5145 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,03-17 12:28:41.627  5145  5145 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:41.637  1017  1029 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 12:28:41.637  1017  1029 D SecContentProvider2: mCursor = null
,03-17 12:28:41.637  1017  1476 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-17 12:28:41.637  1017  1476 D SecContentProvider2: mCursor = null
,03-17 12:28:41.637  5129  5129 V MTPRx   : sealedState: false
03-17 12:28:41.637  5129  5129 V MTPRx   : sealedUsbMassStorageState: false
03-17 12:28:41.637  5129  5129 E MTPRx   : check value of boot_completed is1
03-17 12:28:41.637  5129  5129 E MTPRx   : check booting is completed_sys.boot_completed
,03-17 12:28:41.647  5129  5129 E MTPRx   : Sd-Card path/storage/extSdCard
03-17 12:28:41.647  5129  5129 E MTPRx   : Status for mount/Unmount :removed
03-17 12:28:41.647  5129  5129 E MTPRx   : SDcard is not available
,03-17 12:28:41.647  1017  3836 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 57015
,03-17 12:28:41.647  1017  3836 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
03-17 12:28:41.647  1017  3836 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=3489)
,03-17 12:28:41.647   301   301 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 718us total 24.860ms
,03-17 12:28:41.647  5129  5129 W MTPRx   : value of connected istrue
,03-17 12:28:41.657  5129  5129 W MTPRx   : value of configured istrue
,03-17 12:28:41.657  5129  5129 W MTPRx   : value of mtpEnabled istrue
,03-17 12:28:41.657  5129  5129 W MTPRx   : value of ptpEnabled isfalse
,03-17 12:28:41.667  5129  5129 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
03-17 12:28:41.667  5145  5145 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:41.667  5145  5145 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:41.667   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 802us total 18.792ms
,03-17 12:28:41.667  5129  5129 E MTPRx   : mFirstTime: false
,03-17 12:28:41.677  1017  1490 I ActivityManager: Killing 4240:com.sec.android.soagent/u0a34 (adj 15): empty #31
,03-17 12:28:41.697   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 18.489ms,
,03-17 12:28:41.697  5129  5129 D         : MTP: reading debug level property
,03-17 12:28:41.697  5145  5145 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 12:28:41.697  5129  5129 E MTPJNIInterface: Getting CryptionKey from JAVA
03-17 12:28:41.697  5129  5129 E MTPRx   : currentUserId is 0
,03-17 12:28:41.707  5129  5129 E MTPRx   : Start observing USB_STATE_MATCH 
,03-17 12:28:41.707  5129  5129 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-17 12:28:41.707  5129  5129 E MTPRx   : is_Privatemode is NOT 1
,03-17 12:28:41.707  1017  1029 D SettingsProvider: name = boot_time_connected
,03-17 12:28:41.717  5129  5129 E MTPRx   : Sending NORMAL_BOOT to stack
03-17 12:28:41.717  5129  5129 E MTPJNIInterface: noti = 17
,03-17 12:28:41.717  1017  1491 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 12:28:41.727  1017  1490 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-17 12:28:41.727  5129  5129 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-17 12:28:41.737  1017  3168 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,03-17 12:28:41.737  1017  3168 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 12:28:41.737  1017  3168 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:41.737  1017  3168 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:41.737  1017  3168 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 12:28:41.737  5145  5145 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-17 12:28:41.747  1017  1486 D SettingsProvider: name = mtp_running_status
,03-17 12:28:41.757  1017  1342 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 12:28:41.757  5129  5129 E MTPRx   : else part ... so first time!!!
,03-17 12:28:41.757  5129  5129 E MTPPlaObsrvr: inside setContext()
03-17 12:28:41.757  5129  5129 E MTPPlaObsrvr:  inside createplafiles
,03-17 12:28:41.757  1017  1041 W libprocessgroup: failed to open /acct/uid_10034/pid_4240/cgroup.procs: No such file or directory
,03-17 12:28:41.757  5018  5109 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-17 12:28:41.767  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:28:41.767  5129  5129 E MTPPlaObsrvr: playlist count is0
,03-17 12:28:41.767  5129  5129 E MTPPlaObsrvr:  inside try branch createplafiles
,03-17 12:28:41.767  5129  5129 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-17 12:28:41.777  5129  5129 E MTPPlaObsrvr: Inside registerContentObserver
,03-17 12:28:41.777  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-17 12:28:41.777  5129  5129 E MtpAdbObserver: inside setContext()
03-17 12:28:41.777  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-17 12:28:41.777  5129  5129 E MtpAdbObserver: Inside registerContentObserver
,03-17 12:28:41.777  5129  5129 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-17 12:28:41.777  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-17 12:28:41.787  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-17 12:28:41.787  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-17 12:28:41.787  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-17 12:28:41.787  1017  1395 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,03-17 12:28:41.787  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
03-17 12:28:41.787  1017  1395 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 12:28:41.787  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-17 12:28:41.787  1017  1395 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:28:41.787  5129  5162 V MtpMediaDBManager: inside deleteAllDB
03-17 12:28:41.787  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-17 12:28:41.787  1017  1395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:28:41.787  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
03-17 12:28:41.787  1017  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 12:28:41.797  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-17 12:28:41.797  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-17 12:28:41.797  1017  1395 D SettingsProvider: name = mtp_running_status
,03-17 12:28:41.797  5145  5145 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-17 12:28:41.797  1017  1490 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 12:28:41.797  1017  1486 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-17 12:28:41.797  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
03-17 12:28:41.797  5129  5129 E MtpService: onCreate.
03-17 12:28:41.797  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:28:41.797  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:28:41.797  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 12:28:41.807  1241  1241 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 12:28:41.817  5129  5129 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-17 12:28:41.827  1310  1310 D BluetoothNotiBroadcastReceiver: onReceive
,03-17 12:28:41.827  1191  1191 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,03-17 12:28:41.827  1191  1191 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
03-17 12:28:41.827  5129  5129 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-17 12:28:41.837  1017  3168 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-17 12:28:41.837  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:41.837  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:41.837  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:41.837  1017  3168 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:28:41.847  5129  5162 V MtpMediaDBManager: inside Thread updateDB
,03-17 12:28:41.847  5164  5164 E Zygote  : MountEmulatedStorage(),
03-17 12:28:41.847  5164  5164 I libpersona: KNOX_SDCARD checking this for 10003
03-17 12:28:41.847  5164  5164 E Zygote  : v2
03-17 12:28:41.847  5164  5164 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:41.847  5164  5164 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 12:28:41.857  5164  5164 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 12:28:41.857  5164  5164 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:41.857  1017  3168 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5164 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-17 12:28:41.857  5129  5129 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
03-17 12:28:41.857  5129  5129 E MtpService: onStartCommand.
03-17 12:28:41.857  5129  5129 W MTPRx   : calling native method
03-17 12:28:41.857  5129  5129 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-17 12:28:41.867  5129  5163 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-17 12:28:41.867  5129  5162 E MtpMediaDBManager: count : 27
,03-17 12:28:41.867  5129  5129 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-17 12:28:41.867  5129  5129 E MTPJNIInterface: noti = 10
03-17 12:28:41.867  5129  5129 E MtpService: onStartCommand.
03-17 12:28:41.867  5129  5129 W MTPRx   : calling native method
03-17 12:28:41.867  5129  5129 E MTPRx   : Checking the driver time out
03-17 12:28:41.867  5129  5129 E MTPJNIInterface: noti = 2
03-17 12:28:41.867  5129  5129 D         : deleting sockets before message queue initialization
,03-17 12:28:41.867  5129  5129 D         : event handler thread is created, so set the flag
,03-17 12:28:41.867  5129  5129 E MTPRx   : called native method
03-17 12:28:41.867  5129  5129 E MTPJNIInterface: setting Media scanner status0
03-17 12:28:41.867  5129  5129 E MTPJNIInterface: After setting Media scanner status0
,03-17 12:28:41.877  5129  5163 E MtpService: handleMessage. msg= { when=-4ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-17 12:28:41.877  5129  5174 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-17 12:28:41.877  5129  5174 E MTPJNIInterface: Getting media scanner status0
,03-17 12:28:41.887  5129  5129 W MTPRx   : notification from stack 1
,03-17 12:28:41.887  5129  5174 E MTPJNIInterface: DeviceName is A5-1
,03-17 12:28:41.897  5164  5164 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:28:41.897  5164  5164 D ActivityThread: Added TimaKeyStore provider
,03-17 12:28:41.907  1017  1039 D SensorService: [SO] 0.134 0.421 10.132
,03-17 12:28:41.907  5129  5162 W MtpMediaDBManager: sending db update complete noti to stack
,03-17 12:28:41.907  5129  5162 E MTPJNIInterface: noti = 29
,03-17 12:28:41.917  5129  5174 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 12:28:41.917  5129  5174 E MTPJNIInterface: SDcard is not available
,03-17 12:28:41.927  5164  5164 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 12:28:41.937  5129  5174 E         : lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,03-17 12:28:41.947  5129  5174 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-17 12:28:41.947  5129  5174 E MTPJNIInterface: Status for mount/Unmount :removed
,03-17 12:28:41.947  5129  5174 E MTPJNIInterface: SDcard is not available
,03-17 12:28:41.947  5129  5174 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 12:28:41.947  5129  5174 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 12:28:41.947  5129  5174 E SQLiteLog: (21) API call with NULL database connection pointer
,03-17 12:28:41.947  5129  5174 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
,03-17 12:28:41.947  5129  5174 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 12:28:41.957  5129  5174 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 12:28:41.957  5129  5174 E SQLiteLog: (21) API call with NULL database connection pointer
,03-17 12:28:41.957  5129  5174 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-17 12:28:41.957  5129  5129 W MTPRx   : notification from stack 2
,03-17 12:28:41.957  5129  5180 D         : [mtp_init_device] Library open with 32 bits.
,03-17 12:28:41.957  5129  5180 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-17 12:28:41.957  5129  5180 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
,03-17 12:28:41.957  5129  5180 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,03-17 12:28:41.957  5129  5180 E         :  [sua_support_present:1287] returning false 
03-17 12:28:41.957  5129  5180 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-17 12:28:41.967  5164  5164 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 12:28:41.967  5164  5164 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 12:28:41.967  5164  5164 D UserAnalysis: Create SecureDbHelper

```
