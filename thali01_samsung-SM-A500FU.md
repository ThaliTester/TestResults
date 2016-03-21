#### Test 62548124bd1cdb6_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
03-21 07:32:34.376  2690  2929 D BluetoothSocket: bindListen(): myUserId = 0
03-21 07:32:34.376  2690  2929 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-21 07:32:34.376  2690  2929 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-21 07:32:34.376  2690  2929 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 07:32:34.376  2690  2929 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 07:32:34.376  2690  2929 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2779bc90
03-21 07:32:34.376  2690  2929 D BluetoothSocket: channel: 5
03-21 07:32:34.456  1986  2926 W DriveInitializer: Background init thread ended
,--------- beginning of system
03-21 07:32:34.506  1017  2888 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 07:32:34.506  1017  2888 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.506  1017  2888 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:34.506  1017  2888 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-21 07:32:34.516  2806  2895 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:32:34.526  2906  2906 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-21 07:32:34.526  1017  1079 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 07:32:34.526  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.526  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:34.526  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-21 07:32:34.536  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 07:32:34.536  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.536  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:34.536  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-21 07:32:34.536  2906  2906 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-21 07:32:34.546  1017  2888 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
03-21 07:32:34.546  1017  2888 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
03-21 07:32:34.546  1017  1017 I DrmEventReceiver: DrmEventReceiver : onReceive
03-21 07:32:34.546  1017  1017 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-21 07:32:34.556  1017  1017 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-21 07:32:34.556  1017  1017 I System.out: start Service
03-21 07:32:34.556  1017  1708 I ActivityManager: Killing 1512:com.android.printspooler/u0a136 (adj 15): empty #31
03-21 07:32:34.556  1017  1017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-21 07:32:34.556  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
03-21 07:32:34.556  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.556  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.556  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.556  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.576  2960  2960 E Zygote  : MountEmulatedStorage()
03-21 07:32:34.576  2960  2960 E Zygote  : v2
03-21 07:32:34.576  2960  2960 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:34.576  2960  2960 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:34.576  1017  1043 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2960 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 07:32:34.576  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
03-21 07:32:34.576  2960  2960 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:34.586  1243  1243 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-21 07:32:34.586  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.586  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.586  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.586  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.586  2960  2960 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:34.586  2960  2960 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:34.596  2971  2971 E Zygote  : MountEmulatedStorage()
03-21 07:32:34.596  2971  2971 I libpersona: KNOX_SDCARD checking this for 10152
03-21 07:32:34.596  2971  2971 E Zygote  : v2
03-21 07:32:34.596  2971  2971 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:34.596  2971  2971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:34.606  1017  1043 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2971 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
03-21 07:32:34.606  1017  1017 D ActivityManager: startService callerProcessName:android, calleePkgName: android
03-21 07:32:34.606  1017  1017 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
03-21 07:32:34.606  1017  1396 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
03-21 07:32:34.606  1017  1396 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
03-21 07:32:34.616  1017  1396 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.616  1017  1396 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:34.616  1017  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-21 07:32:34.616  2971  2971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:34.616  2971  2971 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:34.626  2960  2960 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:34.626  2960  2960 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:34.626   303   303 I art     : Explicit concurrent mark sweep GC freed 8762(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 692us total 24.197ms
03-21 07:32:34.636   278   500 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 307
03-21 07:32:34.636   278   500 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 307
03-21 07:32:34.646   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 19.213ms
03-21 07:32:34.646  1017  1017 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-21 07:32:34.646  1017  2991 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-21 07:32:34.656   278   278 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-21 07:32:34.666  1017  1079 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-21 07:32:34.666  1017  1079 D SecContentProvider2: mCursor = null
03-21 07:32:34.666   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 16.912ms
03-21 07:32:34.666  1017  1042 W libprocessgroup: failed to open /acct/uid_10136/pid_1512/cgroup.procs: No such file or directory
03-21 07:32:34.666  2971  2971 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:34.666  1243  1243 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-21 07:32:34.666  2971  2971 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:34.676  1467  1467 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-21 07:32:34.676  1017  1488 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-21 07:32:34.676  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-21 07:32:34.686  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.686  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:34.686  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-21 07:32:34.686  1017  1029 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
03-21 07:32:34.686  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
03-21 07:32:34.686  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.686  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:34.686  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-21 07:32:34.696  1017  1510 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-21 07:32:34.696  1017  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-21 07:32:34.696  1017  1510 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.696  1017  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:34.696  1017  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-21 07:32:34.706  1017  2888 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
03-21 07:32:34.706  2960  2960 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-21 07:32:34.706  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.706  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.706  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.706  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.706   274   998 D EnterpriseController: uids 10120
03-21 07:32:34.706   274   998 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-21 07:32:34.706   274   998 D Netd    : getNetworkForDns: using netid 502 for uid 10120
03-21 07:32:34.716  2960  2960 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
03-21 07:32:34.726  2960  2960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
03-21 07:32:34.726  1467  1467 D CscUpdateService: onStart
03-21 07:32:34.726  1467  1467 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-21 07:32:34.726  1467  1467 I CscUpdateService: set_CSC_version
03-21 07:32:34.726  1467  1467 E CscParser: update(): xml file exist
03-21 07:32:34.736  2948  2948 D AndroidRuntime: 
03-21 07:32:34.736  2948  2948 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-21 07:32:34.746  2948  2948 D AndroidRuntime: CheckJNI is OFF
03-21 07:32:34.746  2948  2948 D AndroidRuntime: readGMSProperty: start
03-21 07:32:34.746  2948  2948 D AndroidRuntime: readGMSProperty: already setted!!
03-21 07:32:34.746  2948  2948 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 07:32:34.746  2948  2948 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 07:32:34.746  2948  2948 D AndroidRuntime: readGMSProperty: end
03-21 07:32:34.746  2948  2948 D AndroidRuntime: addProductProperty: start
03-21 07:32:34.756  2971  2971 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
03-21 07:32:34.756  3000  3000 E Zygote  : MountEmulatedStorage()
03-21 07:32:34.756  3000  3000 I libpersona: KNOX_SDCARD checking this for 10003
03-21 07:32:34.756  3000  3000 E Zygote  : v2
03-21 07:32:34.756  3000  3000 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:34.756  3000  3000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:34.766  1017  2888 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3000 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-21 07:32:34.766  1017  1232 D ActivityManager: startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
03-21 07:32:34.766  1017  1232 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
03-21 07:32:34.766  3000  3000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:34.766  3000  3000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:34.776  1017  1232 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.776  1017  1232 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:34.776  1017  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
03-21 07:32:34.776  1017  1708 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
03-21 07:32:34.776  1017  1708 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
03-21 07:32:34.776  1017  1708 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.776  1017  1708 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:34.776  1017  1708 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
03-21 07:32:34.796  1017  2888 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
03-21 07:32:34.796  1467  1467 I CscUtil : isWifiOnly = false
03-21 07:32:34.796  3000  3000 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:34.796  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.796  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.796  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.796  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.796  1467  1467 I System.out: HandDataNode = null
03-21 07:32:34.796  1467  1467 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-21 07:32:34.796  3000  3000 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:34.806  1467  1467 I CscUpdateService: This is normal boot : CSC not updated
03-21 07:32:34.806  1467  3024 E CscParser: update(): xml file exist
03-21 07:32:34.816  1243  2996 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-21 07:32:34.816  1467  3024 D CscGPS  : CSCGPS.updateParameters
03-21 07:32:34.816  1467  3024 D CscGPS  : supl host : null
03-21 07:32:34.816  1467  3024 D CscGPS  : SUPL Host is null or invalid
03-21 07:32:34.816  1467  3024 D CscGPS  : supl_ver : null
03-21 07:32:34.816  1467  3024 D CscGPS  : SUPL Ver is null or invalid
03-21 07:32:34.826  1467  3024 D CscGPS  : supl port : null
03-21 07:32:34.826  1467  3024 D CscGPS  : SUPL PORT is null or invalid
03-21 07:32:34.826  1467  3024 D CscGPS  : LPP : null
03-21 07:32:34.826  1467  3024 D CscGPS  : LPP is null or invalid
03-21 07:32:34.826  1467  3024 D CscGPS  : CSC don't have any AGPS value.
03-21 07:32:34.826  1467  1467 I CscUpdateService: same CSC Version
03-21 07:32:34.826  1467  1467 D CscUtil : Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
03-21 07:32:34.826  3027  3027 E Zygote  : MountEmulatedStorage()
03-21 07:32:34.826  3027  3027 E Zygote  : v2
03-21 07:32:34.826  3027  3027 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:34.826  3027  3027 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:34.836  1017  2888 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3027 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 07:32:34.836  3027  3027 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:34.836  1017  2888 I ActivityManager: Killing 1598:com.google.android.apps.maps/u0a107 (adj 15): empty #31
03-21 07:32:34.836  3027  3027 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:34.836  3027  3027 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:34.836  1467  1467 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-21 07:32:34.836  1467  1467 D BluetoothBDTestService: onCreate()
03-21 07:32:34.836  1467  1467 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-21 07:32:34.836  1467  1467 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
03-21 07:32:34.856  1467  1467 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
03-21 07:32:34.856  1017  2888 D ActivityManager: startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
03-21 07:32:34.856  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.856  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.856  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.856  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.866  3027  3027 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:34.866  3027  3027 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:34.866  3042  3042 E Zygote  : MountEmulatedStorage()
03-21 07:32:34.866  3042  3042 I libpersona: KNOX_SDCARD checking this for 1101
03-21 07:32:34.866  3042  3042 E Zygote  : v2
03-21 07:32:34.866  3042  3042 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:34.876  3042  3042 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:34.876  3042  3042 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:34.876  1017  2888 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3042 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-21 07:32:34.876  1017  1704 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-21 07:32:34.876  3042  3042 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:34.876  1017  1704 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
03-21 07:32:34.876  1017  1704 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.876  1017  1704 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:34.876  1017  1704 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-21 07:32:34.886  1017  2888 I ActivityManager: Killing 2110:com.android.vending/u0a28 (adj 15): empty #31
03-21 07:32:34.896  3042  3042 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:34.896  3042  3042 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:34.896  1017  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-21 07:32:34.896  1017  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
03-21 07:32:34.896  2948  2948 E AffinityControl: AffinityControl: registerfunction enter
03-21 07:32:34.906  1243  1243 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-21 07:32:34.916  1467  1706 D TP/MmsProvider: Update uri=content://mms, match=0
03-21 07:32:34.916  1467  1706 D TP/MmsProvider: update , handleReadChangedBroadcast
03-21 07:32:34.916  1467  1706 D TP/MmsSmsProvider: need read changed broadcast:false
03-21 07:32:34.916  2366  2366 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-21 07:32:34.916  3027  3027 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 07:32:34.916  2366  2366 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 4213.104999
03-21 07:32:34.916  2366  2366 I Mms/ReservationManager: resetAfterConnected()
03-21 07:32:34.926  2948  2948 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 07:32:34.926  3042  3042 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
03-21 07:32:34.926  1467  1753 D TP/MmsSmsProvider: query,matched:7, calling pid = 2366
03-21 07:32:34.926  2366  3058 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-21 07:32:34.926  2366  3058 D Mms/TelephonyPermission: isDefault true
03-21 07:32:34.926  1467  1753 D TP/MmsSmsProvider: match 7:Elapsed time : 3.148 ms
03-21 07:32:34.936  1467  1480 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2366
03-21 07:32:34.936  1017  1704 E PersonaManagerService: inState():  stateMachine is null !!
03-21 07:32:34.936  1017  1704 I PersonaManagerService: PersonaId don't exist
03-21 07:32:34.936  1017  1704 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-21 07:32:34.936  2366  2366 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-21 07:32:34.936  1017  1232 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
03-21 07:32:34.936  1017  1232 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
03-21 07:32:34.946  1017  1232 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.946  1017  1232 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:34.946  1017  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-21 07:32:34.946  3042  3042 V SmartcardService: main Received broadcast
03-21 07:32:34.946  1243  2996 E SQLiteLog: (283) recovered 339 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-21 07:32:34.946  3042  3042 V SmartcardService: Starting smartcard service after boot completed
03-21 07:32:34.946  1017  1704 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 07:32:34.956  1017  1704 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-21 07:32:34.966  1017  1704 W ActivityManager: mDVFSHelper.acquire()
03-21 07:32:34.966  1017  1704 D FocusedStackFrame: Set to : 0
03-21 07:32:34.976  1017  1704 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-21 07:32:34.976  1017  1704 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 07:32:34.976  1490  1490 D Launcher.HomeView: onPause
03-21 07:32:34.976  1017  1704 D InputDispatcher: Focused application set to: xxxx
03-21 07:32:34.976  1017  1704 D InputDispatcher: Focus left window: 1490
03-21 07:32:34.976  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-21 07:32:34.976  2948  2948 D AndroidRuntime: Shutting down VM
03-21 07:32:34.976  1017  1488 D ActivityManager: startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
03-21 07:32:34.976  1017  1488 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
03-21 07:32:34.976  1017  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 07:32:34.976  1017  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-21 07:32:34.986  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:34.986  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:34.986  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
03-21 07:32:34.986  1017  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:32:34.986  1017  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 07:32:34.986  1017  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 07:32:34.986  1017  1510 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
03-21 07:32:34.986  1017  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 07:32:34.986  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.986   256   256 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-21 07:32:34.986  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.986  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:34.986  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.006   294   294 E USB_UICC: Timeout! No signal received. Retry num = 30
03-21 07:32:35.006  1017  1042 W libprocessgroup: failed to open /acct/uid_10028/pid_2110/cgroup.procs: No such file or directory
03-21 07:32:35.006  1017  1042 W libprocessgroup: failed to open /acct/uid_10107/pid_1598/cgroup.procs: No such file or directory
03-21 07:32:35.006   311   311 I ServiceManager: Waiting for service AtCmdFwd...
03-21 07:32:35.016  3064  3064 E Zygote  : MountEmulatedStorage()
03-21 07:32:35.016  3064  3064 E Zygote  : v2
03-21 07:32:35.016  3064  3064 I libpersona: KNOX_SDCARD checking this for 10048
03-21 07:32:35.016  3064  3064 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:35.016  1017  1510 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3064 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-21 07:32:35.026  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.026  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.026  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.026  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.026  3064  3064 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:35.026  3064  3064 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:35.026  3064  3064 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:35.036  1243  2996 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-21 07:32:35.046  3076  3076 E Zygote  : MountEmulatedStorage()
03-21 07:32:35.046  3076  3076 E Zygote  : v2
03-21 07:32:35.046  3076  3076 I libpersona: KNOX_SDCARD checking this for 10155
03-21 07:32:35.046  3076  3076 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:35.046  3076  3076 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:35.046  1017  1489 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3076 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-21 07:32:35.056  3076  3076 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:35.056  3076  3076 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 07:32:35.066   294   294 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-21 07:32:35.066   294   294 E USB_UICC: usb_uicc_init_qmi failed ! 
03-21 07:32:35.066   294   294 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-21 07:32:35.066   294   294 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-21 07:32:35.076  1017  1079 D PersonaManagerService: getPersonasForUser(): returning null!
03-21 07:32:35.076  1017  1029 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
03-21 07:32:35.076  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
03-21 07:32:35.076  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:35.076  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:35.076  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-21 07:32:35.086  1467  1480 D TP/MmsSmsProvider: query,matched:200, calling pid = 2366
03-21 07:32:35.086  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{12d2f90 token=android.os.BinderProxy@e55fa58 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-21 07:32:35.086  3027  3027 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
03-21 07:32:35.086  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
03-21 07:32:35.096  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.096  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.096  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.096  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.096  3064  3064 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:35.096  3064  3064 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:35.096  1467  1480 D TP/MmsSmsProvider: match 200:Elapsed time : 10.101 ms
03-21 07:32:35.106  3027  3096 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458541955112
03-21 07:32:35.106  2366  2366 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-21 07:32:35.116  3104  3104 E Zygote  : MountEmulatedStorage()
03-21 07:32:35.116  3104  3104 E Zygote  : v2
03-21 07:32:35.116  3104  3104 I libpersona: KNOX_SDCARD checking this for 10157
03-21 07:32:35.116  3104  3104 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:35.116  2366  3084 D Mms/TelephonyPermission: isDefault true
03-21 07:32:35.116  2366  3084 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-21 07:32:35.116  2366  3084 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 197.808593
03-21 07:32:35.116  3104  3104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:35.116  1243  2996 V MediaScanner: processDirectory :  /system/media
03-21 07:32:35.116  3104  3104 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:35.126  3104  3104 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:35.126  3076  3076 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:35.126  1017  1488 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3104 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-21 07:32:35.126  3076  3076 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:35.126  3027  3027 I KnoxUsageLogPro: premStatus:2
03-21 07:32:35.136  1017  2040 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-21 07:32:35.136  1017  2040 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-21 07:32:35.136  1017  2040 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:35.136  1017  2040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:35.136  1017  2040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-21 07:32:35.136  3027  3027 I KnoxUsageLogPro: isEulaShown : false
03-21 07:32:35.136  3027  3027 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
03-21 07:32:35.146  1017  1510 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-21 07:32:35.146  1017  1510 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-21 07:32:35.146  1017  1510 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-21 07:32:35.146  1490  1490 D Launcher.HomeView: onStop
03-21 07:32:35.146  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{12d2f90 token=android.os.BinderProxy@e55fa58 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-21 07:32:35.156  3104  3104 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:35.156  3064  3064 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-21 07:32:35.156  3104  3104 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:35.156  3064  3064 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 07:32:35.156  3064  3064 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-21 07:32:35.156  1017  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-21 07:32:35.166  3027  3096 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 36632
03-21 07:32:35.166  1017  1510 D PersonaManager: isKioskContainerExistOnDevice
03-21 07:32:35.166  3000  3101 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
03-21 07:32:35.176  1243  2996 V MediaScanner:  prescan time: 254ms (DB items: 141)
03-21 07:32:35.176  1243  2996 V MediaScanner:     scan time: 64ms (Caching mode: true), (makeEntry time: 34ms ~53%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-21 07:32:35.176  1243  2996 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-21 07:32:35.176  1243  2996 V MediaScanner:    total time: 318ms
03-21 07:32:35.176  1243  2996 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
03-21 07:32:35.176  1243  2996 D MediaScanner: checkDefaultSounds
03-21 07:32:35.176  1243  2996 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-21 07:32:35.176  1017  1232 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-21 07:32:35.176  1017  1232 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-21 07:32:35.176  1017  1232 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:35.186  1017  1232 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:35.186  1017  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-21 07:32:35.186  2948  2948 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-21 07:32:35.206  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,03-21 07:32:35.206  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.206  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.206  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.206  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:35.226  3000  3101 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,03-21 07:32:35.226  1467  1753 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-21 07:32:35.226   329   329 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 3000
03-21 07:32:35.226   329   329 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
03-21 07:32:35.226  1467  1753 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
,03-21 07:32:35.226  3000  3101 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
03-21 07:32:35.226  3000  3101 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
03-21 07:32:35.226   329   329 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 3000
03-21 07:32:35.226   329   329 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,03-21 07:32:35.226  1467  1753 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-21 07:32:35.226  1467  1753 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
,03-21 07:32:35.236  1467  1753 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-21 07:32:35.236  1467  1753 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:35.236  3122  3122 I libpersona: KNOX_SDCARD checking this for 10085
03-21 07:32:35.236  1467  1753 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:35.236  3122  3122 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:35.236  1467  1753 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:35.236  1467  1753 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:35.236  1467  1753 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:35.236  1467  1753 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:35.236  3122  3122 E Zygote  : MountEmulatedStorage()
03-21 07:32:35.236  3122  3122 E Zygote  : v2
03-21 07:32:35.236  3122  3122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:35.236  3122  3122 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:35.246  1017  1488 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3122 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-21 07:32:35.246  1017  1488 I ActivityManager: Killing 2181:com.vlingo.midas/u0a31 (adj 15): empty #31,
,03-21 07:32:35.246  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-21 07:32:35.246  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
,03-21 07:32:35.246  1017  1017 D SensorService: [SO] activate (ident=0xb8df04d8, enabled=0)
,03-21 07:32:35.246  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-21 07:32:35.246  1467  1753 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-21 07:32:35.246  1467  1753 D TP/MmsSmsProvider: need read changed broadcast:false
,03-21 07:32:35.246  3122  3122 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:35.256  1017  1017 D SensorManager: unregisterListener ::   
,03-21 07:32:35.256  1017  1017 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-21 07:32:35.256  1017  1017 D SensorService: [SO] changed settle time [1]
03-21 07:32:35.256  1017  1017 D SensorService: [SO] setDelay [66000000]
03-21 07:32:35.256  1017  1017 D SensorService: [SO] activate (ident=0xb8df04d8, enabled=1)
03-21 07:32:35.256  1017  1017 D SensorService: [SO] AR_init
03-21 07:32:35.256  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-21 07:32:35.266  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.266  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.266  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.266  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:35.266  1490  1490 D Launcher: onTrimMemory. Level: 20
,03-21 07:32:35.266  1017  1017 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-21 07:32:35.286  1017  1488 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3135 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 07:32:35.286  3135  3135 E Zygote  : MountEmulatedStorage(),
03-21 07:32:35.286  3135  3135 E Zygote  : v2
03-21 07:32:35.286  3135  3135 I libpersona: KNOX_SDCARD checking this for 1000,
03-21 07:32:35.286  3135  3135 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:35.286  2366  3084 D Mms/Conversation: deleteTempConversation(),deleted=0
03-21 07:32:35.286  3135  3135 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:35.286  3135  3135 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:35.286  1017  1030 D SettingsProvider: name = block_emergency_message,
03-21 07:32:35.296  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:35.296  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:35.296  1017  1030 D SettingsProvider: selectionArgs: false
03-21 07:32:35.296  1017  1030 D SettingsProvider: selectionArgs: 10048
03-21 07:32:35.296  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:35.296  1017  1030 D SettingsProvider: ret = -1
03-21 07:32:35.296  1467  1482 D TP/SmsProvider: query,matched:0, calling pid = 2366
,03-21 07:32:35.296  1467  1482 D TP/SmsProvider: match 0:Elapsed time : 1.667 ms,
,03-21 07:32:35.296  1017  1232 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing,
,03-21 07:32:35.296  3135  3135 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:35.306  3122  3122 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:35.306  3122  3122 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:35.326  3104  3104 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 07:32:35.336  1017  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-21 07:32:35.336  1017  1042 W libprocessgroup: failed to open /acct/uid_10031/pid_2181/cgroup.procs: No such file or directory
,03-21 07:32:35.336  3135  3135 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:35.336  3135  3135 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:35.356  1467  1753 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-21 07:32:35.356  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-21 07:32:35.356  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:35.356  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.356  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.356  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:35.366  3076  3076 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-21 07:32:35.366  1467  1753 D TP/MmsSmsProvider: need read changed broadcast:false
,03-21 07:32:35.376  3152  3152 E Zygote  : MountEmulatedStorage(),
03-21 07:32:35.376  3152  3152 E Zygote  : v2
03-21 07:32:35.376  3152  3152 I libpersona: KNOX_SDCARD checking this for 10159
03-21 07:32:35.376  3152  3152 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:35.376  3152  3152 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:35.376  1017  1029 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3152 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 07:32:35.376  1017  1029 I ActivityManager: Killing 2230:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,03-21 07:32:35.376  3152  3152 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:35.386  3152  3152 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-21 07:32:35.386  1017  2040 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,03-21 07:32:35.386  1017  2040 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,03-21 07:32:35.386  2366  3084 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-21 07:32:35.386  2366  3084 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-21 07:32:35.396  2366  3084 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-21 07:32:35.396  1017  2040 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:35.396  1017  2040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:35.396  1017  2040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-21 07:32:35.406  1330  1330 I WifiCredService: onCreate
03-21 07:32:35.406  1017  1040 D SensorService: [SO] 0.134 0.402 10.113
03-21 07:32:35.406  1017  1040 D SensorService: [SO] [100 -> 255]
03-21 07:32:35.416  3076  3076 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6940-6942)
03-21 07:32:35.416  3076  3076 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 07:32:35.416  1467  1706 I art     : Explicit concurrent mark sweep GC freed 40113(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/13MB, paused 13.732ms total 94.604ms
,03-21 07:32:35.426  1467  1706 D TP/SmsProvider: query,matched:51, calling pid = 2366
,03-21 07:32:35.426  1467  1706 D TP/SmsProvider: match 51:Elapsed time : 1.803 ms
,03-21 07:32:35.436  1467  1482 D TP/SmsProvider: query,matched:26, calling pid = 2366
,03-21 07:32:35.446  3122  3122 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-21 07:32:35.446  3122  3122 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-21 07:32:35.446  3122  3122 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 07:32:35.446  3122  3122 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-21 07:32:35.446  3122  3122 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 07:32:35.446  3122  3122 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-21 07:32:35.446  3152  3152 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:35.446  3152  3152 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:35.446  1467  1482 D TP/SmsProvider: match 26:Elapsed time : 12.173 ms
,03-21 07:32:35.466  1017  1042 W libprocessgroup: failed to open /acct/uid_10050/pid_2230/cgroup.procs: No such file or directory
,03-21 07:32:35.476  3076  3076 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c6c9b01}
,03-21 07:32:35.476  3076  3076 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 07:32:35.476  3076  3076 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
03-21 07:32:35.476  2366  3058 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-21 07:32:35.476  1330  1330 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-21 07:32:35.476  1330  1330 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-21 07:32:35.476  1330  1330 D MY_TAG  : Action boot completed received
,03-21 07:32:35.476  1330  1330 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,03-21 07:32:35.486  1017  1396 I art     : Explicit concurrent mark sweep GC freed 141661(7MB) AllocSpace objects, 5(1821KB) LOS objects, 33% free, 26MB/39MB, paused 3.557ms total 293.330ms
,03-21 07:32:35.496  1017  1142 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
,03-21 07:32:35.496  1017  1142 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-21 07:32:35.496  1017  1142 E WifiNative-wlan0: invaild command id : 215
,03-21 07:32:35.496  2366  3084 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-21 07:32:35.496  2366  3084 D Mms/MessagingNotification: sDisableVibrateForCamera = false
,03-21 07:32:35.496  2366  3084 D Mms/TelephonyPermission: isDefault true
03-21 07:32:35.506  1243  2996 D MediaScanner: OK. alarm_alert is already exist in setting DB.
,03-21 07:32:35.506  1573  1584 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-21 07:32:35.506  1467  1706 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2366
,03-21 07:32:35.516  1243  2996 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
,03-21 07:32:35.516  3076  3076 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-21 07:32:35.526  3076  3076 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:32:35.526  3076  3076 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 07:32:35.526  1243  2996 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-21 07:32:35.536  1243  2996 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-21 07:32:35.536  1243  2996 D MediaScanner: OK. ringtone is already exist in setting DB.
,03-21 07:32:35.546  2668  2668 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2668) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-21 07:32:35.546  2668  2668 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2668) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-21 07:32:35.546  2668  2668 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2668) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-21 07:32:35.546  1243  2996 D MediaScannerService: !@done scanning volume internal
,03-21 07:32:35.546  3152  3152 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
03-21 07:32:35.546  1243  2996 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-21 07:32:35.546  3076  3076 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-21 07:32:35.546  3076  3076 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50556 len=3379
,03-21 07:32:35.546  3076  3076 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:7638088 len:1165478
,03-21 07:32:35.556  1330  1330 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
,03-21 07:32:35.556  1330  1330 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
03-21 07:32:35.556  1330  1330 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,03-21 07:32:35.556  1330  1330 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-21 07:32:35.556  1017  1489 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,03-21 07:32:35.556  1243  2996 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-21 07:32:35.556  3076  3076 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-21 07:32:35.556  3076  3076 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-21 07:32:35.556  3076  3076 I Adreno-EGL: Build Date: 04/06/15 Mon
03-21 07:32:35.556  3076  3076 I Adreno-EGL: Local Branch: 
03-21 07:32:35.556  3076  3076 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-21 07:32:35.556  3076  3076 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-21 07:32:35.556  3076  3076 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-21 07:32:35.556  1243  2996 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-21 07:32:35.556  1017  2888 D ActivityManager: startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,03-21 07:32:35.566  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.566  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.566  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.566  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:35.566  1467  1753 D TP/MmsSmsProvider: query,matched:200, calling pid = 2366
,03-21 07:32:35.566  1330  3179 V NearbySettings: MountReceiver.mPrefHandler - 7002
,03-21 07:32:35.566  1573  1589 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-21 07:32:35.566  1573  1589 D BadgeProvider: sendNotify, [notify] : null
03-21 07:32:35.566  1573  1589 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-21 07:32:35.566  1573  1589 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-21 07:32:35.566  1573  1589 D BadgeProvider: update, [UpdateCount] : 1
03-21 07:32:35.566  1490  1490 D Launcher.Model: reloadBadges entered.
,03-21 07:32:35.566  1467  1753 D TP/MmsSmsProvider: match 200:Elapsed time : 8.011 ms
,03-21 07:32:35.576  3181  3181 E Zygote  : MountEmulatedStorage()
,03-21 07:32:35.576  3181  3181 E Zygote  : v2,
03-21 07:32:35.576  3181  3181 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:35.576  3181  3181 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:35.576  3135  3135 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-21 07:32:35.576  3181  3181 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:35.586  1017  2888 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3181 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 07:32:35.586  1243  2996 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-21 07:32:35.586  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-21 07:32:35.586  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,03-21 07:32:35.586  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:35.586  3181  3181 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:35.586  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:35.586  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-21 07:32:35.586  3181  3181 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:35.606  2366  3058 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-21 07:32:35.616   256   438 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-21 07:32:35.616   256  1039 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-21 07:32:35.626  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:35.626  1243  2996 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-21 07:32:35.626  1243  2996 D MediaProvider: savePlaylistTableInBulkDeleter started
03-21 07:32:35.626  1330  1330 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-21 07:32:35.626  1330  1330 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-21 07:32:35.636  1243  2996 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,03-21 07:32:35.636  1243  2996 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,03-21 07:32:35.636  1243  2996 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-21 07:32:35.646  2366  3058 D Mms/MessagingNotification: remove alarm
,03-21 07:32:35.646  3181  3181 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:35.646  3181  3181 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:35.656  1243  2996 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-21 07:32:35.666  1017  2888 D SettingsProvider: name = personal_mode_enabled
,03-21 07:32:35.686  3135  3135 D DSM     : [Lines:107] Normal booted
03-21 07:32:35.686  3135  3135 D DSM     : [Lines:114] Boot completed
,03-21 07:32:35.686  2366  3205 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-21 07:32:35.696  1467  1482 D TP/SmsProvider: query,matched:0, calling pid = 2366
,03-21 07:32:35.716  1467  1482 D TP/SmsProvider: match 0:Elapsed time : 15.913 ms
,03-21 07:32:35.716  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,03-21 07:32:35.726  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:35.726  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:35.726  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:35.726  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:35.736  3211  3211 E Zygote  : MountEmulatedStorage()
03-21 07:32:35.736  3211  3211 E Zygote  : v2
03-21 07:32:35.736  3211  3211 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:35.736  3211  3211 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:35.736  3211  3211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:35.746  3211  3211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:35.746  3211  3211 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:35.746  1017  1488 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3211 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 07:32:35.756  1467  1467 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-21 07:32:35.756  1467  1467 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-21 07:32:35.756  1467  1467 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 07:32:35.756  1467  1467 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 07:32:35.756  1467  1467 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 07:32:35.756  1467  1467 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-21 07:32:35.756  1017  2040 I ActivityManager: Killing 2288:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,03-21 07:32:35.766   303   303 I art     : Explicit concurrent mark sweep GC freed 8727(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 19.751ms
,03-21 07:32:35.776  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast,
,03-21 07:32:35.776  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.776  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.776  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.776  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:35.786  3211  3211 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:35.786  3211  3211 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:35.786   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 595us total 16.857ms
,03-21 07:32:35.796  1467  1706 D TP/SmsProvider: query,matched:0, calling pid = 2366
,03-21 07:32:35.806  1243  2996 V MediaScanner: processDirectory :  /storage/emulated/0
,03-21 07:32:35.806  1467  1706 D TP/SmsProvider: match 0:Elapsed time : 1.554 ms
,03-21 07:32:35.806  1243  2996 D MediaScanner: Skipping:
03-21 07:32:35.806  1243  2996 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-21 07:32:35.806   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.056ms
,03-21 07:32:35.806  1243  2996 D MediaScanner: Skipping:
03-21 07:32:35.806  1243  2996 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,03-21 07:32:35.816  3076  3201 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-21 07:32:35.816  1243  2996 V MediaScanner: processDirectory :  /storage/extSdCard
03-21 07:32:35.816  1243  2996 W MediaScanner: Error opening directory, reason : Permission denied.
03-21 07:32:35.816  1243  2996 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-21 07:32:35.816  1243  2996 V MediaScanner:  prescan time: 160ms (DB items: 27),
03-21 07:32:35.816  1243  2996 V MediaScanner:     scan time: 16ms (Caching mode: true), (makeEntry time: 11ms ~68%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-21 07:32:35.816  1243  2996 V MediaScanner: postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-21 07:32:35.816  1243  2996 V MediaScanner:    total time: 178ms
03-21 07:32:35.816  1243  2996 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-21 07:32:35.816  1017  1488 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3228 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,03-21 07:32:35.826  3228  3228 E Zygote  : MountEmulatedStorage()
03-21 07:32:35.826  3228  3228 I libpersona: KNOX_SDCARD checking this for 10160
03-21 07:32:35.826  3228  3228 E Zygote  : v2
03-21 07:32:35.826  3228  3228 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:35.826  3228  3228 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:35.826  1017  1488 I ActivityManager: Killing 1631:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-21 07:32:35.826  3228  3228 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:35.826  3228  3228 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:35.846  1330  1330 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-21 07:32:35.846  1330  1330 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-21 07:32:35.846  2668  2668 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2668) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-21 07:32:35.856  2668  2668 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2668) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-21 07:32:35.856  2668  2668 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2668) ...
,03-21 07:32:35.856  2668  2668 D FactoryTestApp: [Support$Values.getString](2668) id=MODEL_COMMUNICATION_MODE, value=gsm
03-21 07:32:35.856  3211  3211 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-21 07:32:35.856  2668  2668 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2668) mConnectionMode = gsm
,03-21 07:32:35.856  2668  2668 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2668) Create IPCWriterToSecPhoneService
03-21 07:32:35.856  2668  2668 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2668)  
,03-21 07:32:35.856  2668  2668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-21 07:32:35.856  2366  3058 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 743.629271
,03-21 07:32:35.866  1017  1030 D SettingsProvider: name = next_alarm_formatted
03-21 07:32:35.866  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:35.866  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:35.866  1017  1030 D SettingsProvider: selectionArgs: false
03-21 07:32:35.866  1017  1030 D SettingsProvider: selectionArgs: 10085
03-21 07:32:35.866  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:35.866  1017  1030 D SettingsProvider: ret = -1
,03-21 07:32:35.866  1017  1030 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,03-21 07:32:35.876  1243  2996 D MediaScannerService: !@done scanning volume external
,03-21 07:32:35.876  3228  3228 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:35.886  1017  1488 D ActivityManager: bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
03-21 07:32:35.886  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 07:32:35.886  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-21 07:32:35.886  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:35.886  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:35.886  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-21 07:32:35.886  3228  3228 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:35.896  3076  3076 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:32:35.896  1330  1330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-21 07:32:35.896  1330  1330 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-21 07:32:35.916  1467  1482 D TP/SmsProvider: query,matched:51, calling pid = 2366
,03-21 07:32:35.916  3211  3211 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-21 07:32:35.926  3228  3228 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-21 07:32:35.926  1467  1482 D TP/SmsProvider: match 51:Elapsed time : 8.652 ms
03-21 07:32:35.926  2668  2668 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2668) connected done
03-21 07:32:35.926  2668  2668 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2668) Send Response Message to SecPhone
03-21 07:32:35.926  2668  2668 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2668) Response ��
,03-21 07:32:35.926  1017  1042 W libprocessgroup: failed to open /acct/uid_10113/pid_2288/cgroup.procs: No such file or directory
03-21 07:32:35.926  1017  1042 W libprocessgroup: failed to open /acct/uid_10015/pid_1631/cgroup.procs: No such file or directory
03-21 07:32:35.926  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-21 07:32:35.926  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,03-21 07:32:35.936  3211  3211 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
03-21 07:32:35.936  2366  3084 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-21 07:32:35.946  1573  1589 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-21 07:32:35.946  3076  3076 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 07:32:35.956   307  1075 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-21 07:32:35.956  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-21 07:32:35.956  2668  2668 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2668) Send BOOTING COMPLETED done
,03-21 07:32:35.956  3076  3076 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 07:32:35.956  3076  3076 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-21 07:32:35.966  3076  3076 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-21 07:32:35.976  3076  3076 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:32:35.976  3076  3076 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
,03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-21 07:32:35.976  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-21 07:32:35.986  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-21 07:32:35.986  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-21 07:32:35.986  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-21 07:32:35.986  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-21 07:32:35.986  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-21 07:32:35.986  3211  3211 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-21 07:32:35.986  3211  3211 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-21 07:32:35.986  1017  1708 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
03-21 07:32:35.986  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.986  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.986  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.986  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.996  3122  3122 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.<clinit>() took 106.615ms
03-21 07:32:35.996   286   286 E SMD     : DCD OFF
03-21 07:32:36.006   311   311 I ServiceManager: Waiting for service AtCmdFwd...
,03-21 07:32:36.016  3250  3250 E Zygote  : MountEmulatedStorage()
03-21 07:32:36.016  1017  1708 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3250 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 07:32:36.016  3250  3250 E Zygote  : v2
03-21 07:32:36.016  3250  3250 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:36.016  3250  3250 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:36.016  3250  3250 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:36.016  3250  3250 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:36.026  3250  3250 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:36.026  1986  3187 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,03-21 07:32:36.046  3250  3250 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:36.056  2690  2779 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-21 07:32:36.056   307  1075 D AT_Distributor: SetAtdStatus(), 1_1_0
03-21 07:32:36.056   307  1075 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-21 07:32:36.056  3250  3250 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:36.076  2690  2779 D BluetoothMediaBrowser: no now playing list
03-21 07:32:36.076  2690  2779 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-21 07:32:36.086  1017  1099 V AlarmManager: waitForAlarm result :8
,03-21 07:32:36.086  1017  1099 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 07:32:36.096  3228  3228 D [0]UMC:UMCContentProvider: @onCreate
,03-21 07:32:36.106  3076  3269 D OpenGLRenderer: Render dirty regions requested: true
,03-21 07:32:36.106  1017  1704 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-21 07:32:36.106  1017  1704 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 07:32:36.106  1017  1704 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-21 07:32:36.106  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-21 07:32:36.106  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 07:32:36.116   329   329 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,03-21 07:32:36.116  3076  3076 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 07:32:36.116  3076  3076 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-21 07:32:36.126   256   256 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-21 07:32:36.136  1017  1704 D InputDispatcher: Focus entered window: 3076
,03-21 07:32:36.136  3228  3228 D [0]UMC:Core: onCreate(): 
03-21 07:32:36.136  3228  3228 D [0]UMC:Core: @isManagedProfileUser
03-21 07:32:36.136  3228  3228 D [0]UMC:Core: userId: 0
,03-21 07:32:36.136  3122  3122 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 144.107ms
03-21 07:32:36.136  3228  3228 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-21 07:32:36.136  3228  3228 D [0]UMC:Core: userInfo.isManagedProfile() : false
,03-21 07:32:36.146  1017  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-21 07:32:36.146  3076  3076 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-21 07:32:36.146  1017  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 07:32:36.146  3076  3269 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 07:32:36.156  3076  3269 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-21 07:32:36.156  3076  3269 D OpenGLRenderer: Enabling debug mode 0
,03-21 07:32:36.176  3000  3101 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,03-21 07:32:36.176  3000  3101 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,03-21 07:32:36.196  1017  1232 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-21 07:32:36.206  1017  3272 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 07:32:36.206  1191  1191 I StatusBar: Icon Only
,03-21 07:32:36.206  1191  1191 D PanelView: There is/are notification(s) 
,03-21 07:32:36.206  1986  3187 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 185 ms
,03-21 07:32:36.216  3076  3076 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@396927e2 time:37744
,03-21 07:32:36.216  3228  3228 D [0]UMC:DeviceInfo: USA==US==
,03-21 07:32:36.226  1017  1050 I ActivityManager: Displayed Component not be shown by security: +1s200ms
,03-21 07:32:36.226  1017  1050 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,03-21 07:32:36.226  1017  1050 W ActivityManager: mDVFSHelper.release()
03-21 07:32:36.226  1017  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d0f63 u0 com.test.thalitest/.MainActivity t12} time:37752
,03-21 07:32:36.226  1017  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-21 07:32:36.236  1490  1490 D Launcher.Model: reloadBadges entered.
,03-21 07:32:36.236  1573  1589 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-21 07:32:36.236  1017  1708 I ActivityManager: Killing 2351:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-21 07:32:36.236  1573  1589 D BadgeProvider: sendNotify, [notify] : null
03-21 07:32:36.236  1573  1589 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-21 07:32:36.236  1573  1589 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-21 07:32:36.236  1573  1589 D BadgeProvider: update, [UpdateCount] : 1
,03-21 07:32:36.256  2366  3084 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-21 07:32:36.256  1815  1815 I SamsungIME: getCurrentCandidateView
,03-21 07:32:36.266  1017  1704 I ActivityManager: Killing 2390:com.sec.android.omc/1000 (adj 15): empty #31
,03-21 07:32:36.266  2366  3084 D Mms/MessagingNotification: remove alarm
,03-21 07:32:36.276  1467  1480 D TP/SmsProvider: query,matched:0, calling pid = 2366
,03-21 07:32:36.276  1467  1480 D TP/SmsProvider: match 0:Elapsed time : 2.594 ms
,03-21 07:32:36.276  2366  3084 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 418.464062
,03-21 07:32:36.286  1017  3209 I ActivityManager: Killing 2420:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,03-21 07:32:36.286  2366  3276 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-21 07:32:36.296  1330  1330 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-21 07:32:36.296  3250  3250 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-21 07:32:36.306  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2351/cgroup.procs: No such file or directory
,03-21 07:32:36.326  1330  1330 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-21 07:32:36.326  1330  1330 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-21 07:32:36.376  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2390/cgroup.procs: No such file or directory
,03-21 07:32:36.376  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2420/cgroup.procs: No such file or directory
,03-21 07:32:36.426  1330  1330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-21 07:32:36.426  1330  3282 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-21 07:32:36.436  1017  1396 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,03-21 07:32:36.436  1017  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:36.436  1017  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.436  1017  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.436  1017  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:36.446   256  1039 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-21 07:32:36.446   256   441 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-21 07:32:36.456  3283  3283 E Zygote  : MountEmulatedStorage()
03-21 07:32:36.456  3283  3283 E Zygote  : v2
03-21 07:32:36.456  3283  3283 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:36.456  3283  3283 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:36.456  3228  3228 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
03-21 07:32:36.456  3283  3283 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:36.466  1017  1396 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3283 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-21 07:32:36.466  3283  3283 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:36.466  3283  3283 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:36.476  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,03-21 07:32:36.476  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.476  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.476  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.476  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:36.486  3228  3228 D [0]UMC:AdminManager: init - start
,03-21 07:32:36.486  3297  3297 E Zygote  : MountEmulatedStorage()
03-21 07:32:36.486  3297  3297 E Zygote  : v2
03-21 07:32:36.486  3297  3297 I libpersona: KNOX_SDCARD checking this for 10150
03-21 07:32:36.486  3297  3297 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:36.486  3297  3297 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-21 07:32:36.496  1017  1029 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3297 uid=10150 gids={50150, 9997} abi=armeabi-v7a,
03-21 07:32:36.496  3297  3297 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:36.496  3283  3283 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-21 07:32:36.496  3297  3297 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-21 07:32:36.496  3283  3283 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:36.516  3283  3283 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 07:32:36.516  3297  3297 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:36.516  3297  3297 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:36.526  1017  1017 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,03-21 07:32:36.566  3228  3228 D [0]UMC:AdminManager: loadAdmins
,03-21 07:32:36.586  3228  3228 D [0]UMC:AdminManager: init - end
,03-21 07:32:36.586  3228  3228 D GSLBManager: migrateStoredUrlFromOldPref
,03-21 07:32:36.586  3228  3228 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-21 07:32:36.586  3228  3228 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-21 07:32:36.596  3228  3228 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-21 07:32:36.596  3228  3228 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-21 07:32:36.596  3228  3228 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-21 07:32:36.596  3228  3228 D [0]UMC:UMCAdmin: isContainer : 0
,03-21 07:32:36.596  1017  2888 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-21 07:32:36.596  3228  3228 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-21 07:32:36.596  3228  3228 D [0]UMC:UMCAdmin: isContainer : 0
,03-21 07:32:36.596  3228  3228 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-21 07:32:36.606  1017  1510 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
03-21 07:32:36.606  1017  1510 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-21 07:32:36.606  1017  1510 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:36.606  1017  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 07:32:36.606  1017  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-21 07:32:36.616  3228  3228 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-21 07:32:36.616  3228  3228 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
,03-21 07:32:36.626  3228  3228 D [0]UMC:CoreReceiver:  check PreETag 
,03-21 07:32:36.636  3000  3000 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 07:32:36.636  3000  3000 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-21 07:32:36.636  1017  1030 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,03-21 07:32:36.636  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-21 07:32:36.636  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:36.636  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 07:32:36.646  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-21 07:32:36.646  3000  3000 E BluetoothHeadset: BluetoothHeadset service is binded
,03-21 07:32:36.646  3000  3000 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-21 07:32:36.646  1017  1489 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,03-21 07:32:36.646  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-21 07:32:36.646  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:36.646  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:36.646  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-21 07:32:36.676  3228  3228 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-21 07:32:36.676  3228  3228 V [0]UMC:ProfileStorage: Enter loadList
,03-21 07:32:36.676  3228  3228 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-21 07:32:36.676  3228  3228 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-21 07:32:36.676  3228  3228 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-21 07:32:36.676  3228  3228 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-21 07:32:36.676  3228  3228 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-21 07:32:36.676  3228  3228 D [0]UMC:UMCAdmin: isContainer : 0
,03-21 07:32:36.676  1017  1704 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-21 07:32:36.676  3228  3228 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
,03-21 07:32:36.676  3228  3228 D [0]UMC:UMCAdmin: isContainer : 0
,03-21 07:32:36.686  3228  3228 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-21 07:32:36.686  3076  3076 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3076
,03-21 07:32:36.696  1815  1815 D SamsungIME: Dismiss ExpandCandiate
,03-21 07:32:36.726  3283  3283 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-21 07:32:36.736  3228  3228 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-21 07:32:36.746  3228  3228 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
,03-21 07:32:36.746  3228  3228 I [0]UMC:Core: shutdown
,03-21 07:32:36.746  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-21 07:32:36.746  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:36.746  1017  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:36.746  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-21 07:32:36.746  3228  3228 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-21 07:32:36.746  3250  3250 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-21 07:32:36.756  3228  3228 I art     : System.exit called, status: 0
,03-21 07:32:36.756  3228  3228 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-21 07:32:36.756  1017  1396 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,03-21 07:32:36.756  1017  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:36.766  1017  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:36.766  1017  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.766  1017  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:36.776  3250  3250 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,03-21 07:32:36.776  3326  3326 E Zygote  : MountEmulatedStorage()
,03-21 07:32:36.776  3326  3326 E Zygote  : v2
03-21 07:32:36.776  3326  3326 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:36.776  3326  3326 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:36.786  3326  3326 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-21 07:32:36.786  3326  3326 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-21 07:32:36.786  1017  1396 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3326 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 07:32:36.786  1017  1396 I ActivityManager: Killing 2432:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31,
,03-21 07:32:36.786  3326  3326 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:36.796  3250  3250 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-21 07:32:36.806  3250  3250 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-21 07:32:36.806  3250  3250 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-21 07:32:36.816  3250  3250 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-21 07:32:36.816  3326  3326 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:36.816  3326  3326 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:36.816  1017  1708 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3228)(adj 0) has died(212,1071)
,03-21 07:32:36.836  3283  3283 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-21 07:32:36.846  3283  3283 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-21 07:32:36.846  3283  3283 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-21 07:32:36.856  1017  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 07:32:36.866  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:36.866  1017  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:36.866  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-21 07:32:36.866  1017  1704 I ActivityManager: Killing 2342:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-21 07:32:36.886  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-21 07:32:36.886  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-21 07:32:36.886  1315  1315 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-21 07:32:36.906  3326  3326 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-21 07:32:36.906  1315  1315 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-21 07:32:36.916  1017  1079 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,03-21 07:32:36.926  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.926  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.926  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.926  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:36.926  1315  1315 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-21 07:32:36.936  1315  1315 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true,
,03-21 07:32:36.946  3344  3344 E Zygote  : MountEmulatedStorage(),
,03-21 07:32:36.946  3344  3344 E Zygote  : v2,
03-21 07:32:36.946  3344  3344 I libpersona: KNOX_SDCARD checking this for 1000
,03-21 07:32:36.946  3344  3344 I libpersona: KNOX_SDCARD not a persona,
,03-21 07:32:36.956  3344  3344 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-21 07:32:36.956  3344  3344 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-21 07:32:36.956  1017  1079 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3344 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 07:32:36.966  1315  1315 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-21 07:32:36.966  1315  1315 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-21 07:32:36.966  1315  1315 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-21 07:32:36.966  1315  1315 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-21 07:32:36.966  1315  1315 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-21 07:32:36.966  1315  1315 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-21 07:32:36.966  3344  3344 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:37.006  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,03-21 07:32:37.006  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:37.006  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:37.006  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:37.006  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.006  3344  3344 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:37.006   311   311 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-21 07:32:37.016  3344  3344 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:37.026  3076  3076 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 07:32:37.046  2170  2170 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,03-21 07:32:37.046  2170  2170 I dhcpcd  : wlan0: no IPv6 Routers available
,03-21 07:32:37.046  3360  3360 E Zygote  : MountEmulatedStorage(),
03-21 07:32:37.046  3360  3360 E Zygote  : v2,
03-21 07:32:37.046  1017  2888 D SettingsProvider: name = aw_daemon_service_key_version_check
03-21 07:32:37.046  1017  2888 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:37.046  1017  2888 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:37.056  3360  3360 I libpersona: KNOX_SDCARD checking this for 10086
03-21 07:32:37.046  1017  2888 D SettingsProvider: selectionArgs: false
03-21 07:32:37.056  3360  3360 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:37.046  1017  2888 D SettingsProvider: selectionArgs: 10162
03-21 07:32:37.046  1017  2888 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.046  1017  2888 D SettingsProvider: ret = -1
03-21 07:32:37.056  1017  2888 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
03-21 07:32:37.066  1017  1030 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3360 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
03-21 07:32:37.066  1017  1030 I ActivityManager: Killing 2464:com.wsomacp/u0a25 (adj 15): empty #31
03-21 07:32:37.076  1315  1315 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-21 07:32:37.096  1017  1042 W libprocessgroup: failed to open /acct/uid_10131/pid_2432/cgroup.procs: No such file or directory
,03-21 07:32:37.096  3360  3360 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:37.096  3360  3360 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:37.096  3360  3360 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 07:32:37.116  1017  2040 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 07:32:37.116  1017  1030 E Tethering: No numeric data
03-21 07:32:37.116  1017  2040 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:37.116  1017  2040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:37.116  1017  2040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-21 07:32:37.126  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:37.146  1017  1704 E Tethering: No numeric data
,03-21 07:32:37.146  3360  3360 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:37.146  3360  3360 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:37.176  3283  3283 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-21 07:32:37.176  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-21 07:32:37.186  3283  3283 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-21 07:32:37.186  1017  1030 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
03-21 07:32:37.186  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-21 07:32:37.186  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.186  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.186  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-21 07:32:37.196  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-21 07:32:37.196  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-21 07:32:37.196  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-21 07:32:37.206  1191  1191 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-21 07:32:37.206  1191  1191 D OverheatReceiver: into the SAFE_MODE_ACTION
03-21 07:32:37.206  1191  1191 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-21 07:32:37.206  1191  1191 D OverheatReceiver: isSafeMode = false
,03-21 07:32:37.206  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-21 07:32:37.206  3283  3283 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-21 07:32:37.206  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-21 07:32:37.216  3283  3283 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-21 07:32:37.216  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-21 07:32:37.216  3283  3283 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-21 07:32:37.216  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-21 07:32:37.216  3283  3283 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-21 07:32:37.226  1467  1467 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-21 07:32:37.226  3283  3283 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-21 07:32:37.226  1017  1489 D SettingsProvider: name = internet_call_settings_visibility
03-21 07:32:37.226  1017  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:37.226  1017  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:37.226  1017  1489 D SettingsProvider: selectionArgs: false
03-21 07:32:37.226  1017  1489 D SettingsProvider: selectionArgs: 1001
03-21 07:32:37.226  1017  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.226  1017  1489 D SettingsProvider: ret = -1
03-21 07:32:37.226  1467  1467 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-21 07:32:37.226  1017  2040 E Tethering: No numeric data
,03-21 07:32:37.236  3283  3341 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-21 07:32:37.236  1443  1443 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-21 07:32:37.236  1017  1029 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
03-21 07:32:37.236  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-21 07:32:37.236  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.236  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.236  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-21 07:32:37.236  3076  3281 D jxcore_app_log: JniHelper::setJavaVM(0xb852a450), pthread_self() = -1196881008
,03-21 07:32:37.236  1017  1029 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
03-21 07:32:37.236  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-21 07:32:37.236  3283  3283 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-21 07:32:37.236  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:37.236  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.236  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-21 07:32:37.246  1017  2888 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-21 07:32:37.246  1017  1488 E Tethering: No numeric data
,03-21 07:32:37.246  3076  3281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 07:32:37.246  3076  3281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 07:32:37.246  3076  3281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 07:32:37.246  3076  3281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 07:32:37.246  3076  3281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 07:32:37.246  3076  3281 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df73819 added. We now have 1 listener(s)
,03-21 07:32:37.246  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.246  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.246  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.246  1017  2888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.256  3283  3341 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
03-21 07:32:37.256  1017  1030 E Tethering: No numeric data
03-21 07:32:37.256  1017  1396 E Tethering: No numeric data
03-21 07:32:37.256  3283  3283 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
03-21 07:32:37.256  3283  3341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
03-21 07:32:37.256  3283  3283 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-21 07:32:37.266  3380  3380 E Zygote  : MountEmulatedStorage()
03-21 07:32:37.266  3380  3380 E Zygote  : v2
03-21 07:32:37.266  3380  3380 I libpersona: KNOX_SDCARD checking this for 10057
03-21 07:32:37.266  3380  3380 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:37.266  3380  3380 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:37.266  1017  2888 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3380 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-21 07:32:37.266  3380  3380 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:37.266  1017  2040 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
03-21 07:32:37.266  3380  3380 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 07:32:37.266  1017  2040 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
03-21 07:32:37.266  1017  2040 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:37.266  1017  2040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 07:32:37.266  1017  2040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-21 07:32:37.276  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-21 07:32:37.276  3076  3281 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-21 07:32:37.276  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-21 07:32:37.276  3076  3281 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,03-21 07:32:37.276  3076  3281 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 07:32:37.276  3283  3283 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
03-21 07:32:37.286  3076  3281 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 07:32:37.286  1443  1443 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 07:32:37.286  3076  3281 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18362d8c added. We now have 1 listener(s)
,03-21 07:32:37.286  3076  3281 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 07:32:37.296  1017  3209 I art     : Explicit concurrent mark sweep GC freed 17480(863KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 2.789ms total 195.283ms
,03-21 07:32:37.306  3076  3281 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-21 07:32:37.316  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2342/cgroup.procs: No such file or directory
,03-21 07:32:37.316  3076  3281 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-21 07:32:37.316  3076  3281 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-21 07:32:37.316  3076  3281 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,03-21 07:32:37.316  3076  3281 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-21 07:32:37.326  1017  1042 W libprocessgroup: failed to open /acct/uid_10025/pid_2464/cgroup.procs: No such file or directory
,03-21 07:32:37.326  3380  3380 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:37.326  3380  3380 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:37.326  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-21 07:32:37.336  3076  3281 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 07:32:37.336  3076  3281 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-21 07:32:37.346  3000  3000 D BluetoothA2dp: Proxy object connected
,03-21 07:32:37.356  3283  3283 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-21 07:32:37.366  3076  3281 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 07:32:37.366  3076  3281 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 07:32:37.366  3076  3281 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 07:32:37.366  3076  3281 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 07:32:37.366  3076  3281 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 07:32:37.366  3076  3281 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 07:32:37.366  3076  3281 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 07:32:37.366  3076  3281 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 07:32:37.366  3076  3281 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-21 07:32:37.366  3076  3281 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-21 07:32:37.366  3076  3281 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-21 07:32:37.366  1330  3282 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-21 07:32:37.376  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-21 07:32:37.376  1330  3282 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
03-21 07:32:37.376  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-21 07:32:37.376  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-21 07:32:37.376  3076  3076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 07:32:37.376  3076  3076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 07:32:37.376  1315  1315 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-21 07:32:37.406  3360  3360 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:37.406  3283  3283 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-21 07:32:37.416  1315  1315 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-21 07:32:37.416  1315  1315 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-21 07:32:37.426  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458541957424
,03-21 07:32:37.426  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458563520000
,03-21 07:32:37.426  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,03-21 07:32:37.426  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-21 07:32:37.426  1017  2888 E Tethering: No numeric data
,03-21 07:32:37.436  1017  1708 E Tethering: No numeric data
,03-21 07:32:37.436   280   698 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-21 07:32:37.436   280   698 D audio_hw_extn: audio_extn_get_parameters: returns 
03-21 07:32:37.436   280   698 V msm8974_platform: platform_get_parameters: exit: returns - 
03-21 07:32:37.436   280   698 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-21 07:32:37.436   280   698 I str_params: key: 'call_forwarding' value: ''
03-21 07:32:37.436  1968  1968 V InCall  : ProximitySensor -  - screenonImmediately: false
03-21 07:32:37.436  1968  1968 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-21 07:32:37.446  1968  1968 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-21 07:32:37.446  1017  2040 E Tethering: No numeric data
,03-21 07:32:37.446  1315  1315 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458563520000
,03-21 07:32:37.446  1315  1315 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
03-21 07:32:37.446  1315  1315 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458563520000
,03-21 07:32:37.446  1968  1968 D ScoverManager: serviceVersion : 16908288
,03-21 07:32:37.446  1017  1510 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 07:32:37.466  1968  1968 D InCall  : InCallUtils - isCoverClosed false
,03-21 07:32:37.466  1017  3209 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 07:32:37.466  1968  1968 D InCall  : InCallUtils - isCoverClosed false,
03-21 07:32:37.466  1968  1968 I InCall  : InCallPresenter -  - InCallState = NO_CALLS,
03-21 07:32:37.466  1968  1968 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-21 07:32:37.466  1968  1968 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-21 07:32:37.466  1443  1443 I Telecom : ProximitySensorManager: Proximity wake lock already released,
,03-21 07:32:37.476  3076  3076 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 07:32:37.486  1968  1968 I InCall  : CallSContextMotion - stopPutDownListening
,03-21 07:32:37.496  1968  1968 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-21 07:32:37.496  1017  1232 E Tethering: No numeric data
,03-21 07:32:37.496  1017  1030 I ActivityManager: Killing 2511:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,03-21 07:32:37.506  1017  2888 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-21 07:32:37.506  1968  1968 D InCall  : InCallUtils - isCoverClosed false
,03-21 07:32:37.506  1191  1191 D PhoneStatusBarView: setCallBackground:0
,03-21 07:32:37.556  1315  1315 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-21 07:32:37.556  1315  1315 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-21 07:32:37.566  3360  3360 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:37.566  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-21 07:32:37.576  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.586  3283  3341 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-21 07:32:37.586  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:37.586  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:37.586  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.606  1017  1488 V VibratorService: hasVibrator - useVibetonz: true
,03-21 07:32:37.616  3403  3403 E Zygote  : MountEmulatedStorage()
,03-21 07:32:37.616  3403  3403 E Zygote  : v2
03-21 07:32:37.616  3403  3403 I libpersona: KNOX_SDCARD checking this for 10166
03-21 07:32:37.616  3403  3403 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:37.616  3403  3403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:37.616  3403  3403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-21 07:32:37.626  1017  1030 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3403 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:32:37.626  3403  3403 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 07:32:37.646  1017  1042 W libprocessgroup: failed to open /acct/uid_10088/pid_2511/cgroup.procs: No such file or directory
,03-21 07:32:37.656  3403  3403 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:37.656  3403  3403 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:37.676  1017  3209 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-21 07:32:37.676  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.676  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:37.676  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.676  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.696  3422  3422 E Zygote  : MountEmulatedStorage(),
03-21 07:32:37.696  3422  3422 E Zygote  : v2
,03-21 07:32:37.696  3422  3422 I libpersona: KNOX_SDCARD checking this for 10009
03-21 07:32:37.696  3422  3422 I libpersona: KNOX_SDCARD not a persona,
,03-21 07:32:37.696  3422  3422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-21 07:32:37.696  1017  3209 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3422 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 07:32:37.706  3422  3422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:37.706  3422  3422 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-21 07:32:37.726  1330  3282 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-21 07:32:37.726  1017  1396 V VibratorService: hasVibrator - useVibetonz: true
,03-21 07:32:37.726  3422  3422 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:37.736  1968  1968 D VideoCallManager: Instantiating VideoCallManager
,03-21 07:32:37.736  3422  3422 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:37.736  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-21 07:32:37.736  1968  1968 I GFX construct_block_size_descriptor_2d second part: took 2.143541ms for 0*0 texture 0
,03-21 07:32:37.746  1968  1968 I GFX generate_partition_tables: took 5.125885ms for 0*0 texture 0
,03-21 07:32:37.756  1968  1968 I GFX raster: took 11.347812ms for 176*144 texture 0
03-21 07:32:37.756  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88ff888 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb890dc08 counterpartCT=4 counterpartW=176 counterparth=144
,03-21 07:32:37.756  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-21 07:32:37.766  1968  1968 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-21 07:32:37.766  1968  1968 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-21 07:32:37.766  1968  1968 I Adreno-EGL: Build Date: 04/06/15 Mon
03-21 07:32:37.766  1968  1968 I Adreno-EGL: Local Branch: 
03-21 07:32:37.766  1968  1968 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-21 07:32:37.766  1968  1968 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-21 07:32:37.766  1968  1968 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-21 07:32:37.766  1017  2780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-21 07:32:37.766  3344  3344 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-21 07:32:37.766  3344  3344 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-21 07:32:37.776  3360  3360 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:37.776  1815  1815 I SamsungIME: getDebugLevel  : 0x4f4c
,03-21 07:32:37.786  1968  1968 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-21 07:32:37.786  1968  1968 I glCompressedTexImage2D: took 0.269427ms for 320*61440 texture 37809
,03-21 07:32:37.796  1968  1968 I draw setup: took 10.125624ms for 320*240 texture 37809
03-21 07:32:37.796  1968  1968 E GFX GPU raster: drawn
,03-21 07:32:37.806  1968  1968 I GFX GPU raster ASTC: took 40.402862ms for 320*240 texture 12
03-21 07:32:37.806  1968  1968 I GFX raster: took 40.486040ms for 320*240 texture 0
03-21 07:32:37.806  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb890d1a0 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb88ff6a0 counterpartCT=4 counterpartW=320 counterparth=240
,03-21 07:32:37.806  3344  3432 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-21 07:32:37.806  3344  3344 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-21 07:32:37.816  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-21 07:32:37.816  1968  1968 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-21 07:32:37.816  1017  1510 V VibratorService: hasVibrator - useVibetonz: true
,03-21 07:32:37.826  1968  1968 I glCompressedTexImage2D: took 0.516250ms for 480*122880 texture 37813
03-21 07:32:37.826  1968  1968 I draw setup: took 0.997917ms for 480*640 texture 37813
03-21 07:32:37.826  1968  1968 E GFX GPU raster: drawn
,03-21 07:32:37.826  3360  3360 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:37.836  3360  3360 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:37.836  1968  1968 I GFX GPU raster ASTC: took 8.484219ms for 480*640 texture 12
03-21 07:32:37.836  1968  1968 I GFX raster: took 8.558333ms for 480*640 texture 0
03-21 07:32:37.836  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88ff6a0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8b3c8c0 counterpartCT=4 counterpartW=480 counterparth=640
,03-21 07:32:37.846  3344  3432 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-21 07:32:37.866  3360  3360 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:37.876  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-21 07:32:37.876  1968  1968 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-21 07:32:37.876  1968  1968 I glCompressedTexImage2D: took 0.320573ms for 440*116864 texture 37809
03-21 07:32:37.876  1968  1968 I draw setup: took 0.708906ms for 440*330 texture 37809
03-21 07:32:37.876  1968  1968 E GFX GPU raster: drawn
,03-21 07:32:37.886  1968  1968 I GFX GPU raster ASTC: took 5.439478ms for 440*330 texture 12
03-21 07:32:37.886  1968  1968 I GFX raster: took 5.517187ms for 440*330 texture 0
03-21 07:32:37.886  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b509e0 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8b50d08 counterpartCT=4 counterpartW=440 counterparth=330
,03-21 07:32:37.896  1330  3282 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 07:32:37.916  1017  1489 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,03-21 07:32:37.916  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.916  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-21 07:32:37.916  1968  1968 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-21 07:32:37.916  1968  1968 I glCompressedTexImage2D: took 0.425625ms for 480*163840 texture 37811
03-21 07:32:37.916  1968  1968 I draw setup: took 0.942916ms for 480*640 texture 37811
03-21 07:32:37.916  1968  1968 E GFX GPU raster: drawn
,03-21 07:32:37.916  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:37.916  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:37.916  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:37.926  1968  1968 I GFX GPU raster ASTC: took 6.388019ms for 480*640 texture 12
,03-21 07:32:37.926  1968  1968 I GFX raster: took 6.469946ms for 480*640 texture 0
03-21 07:32:37.926  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b65798 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8b40e98 counterpartCT=4 counterpartW=480 counterparth=640
,03-21 07:32:37.936  3449  3449 E Zygote  : MountEmulatedStorage(),
03-21 07:32:37.936  3449  3449 E Zygote  : v2
03-21 07:32:37.936  3449  3449 I libpersona: KNOX_SDCARD checking this for 10092,
03-21 07:32:37.936  3449  3449 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:37.936  3449  3449 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-21 07:32:37.936  1017  1489 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3449 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 07:32:37.936  1017  1489 I ActivityManager: Killing 2522:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-21 07:32:37.946  3344  3344 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-21 07:32:37.946  3449  3449 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:37.946  3449  3449 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-21 07:32:37.956   303   303 I art     : Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 674us total 24.763ms
,03-21 07:32:37.976   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 17.345ms
,03-21 07:32:37.986  3449  3449 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:37.986  3449  3449 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:37.996   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 18.707ms
,03-21 07:32:38.006  3344  3432 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-21 07:32:38.056  1330  3282 D ScoverManager: serviceVersion : 16908288
,03-21 07:32:38.076  3344  3344 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-21 07:32:38.076  3344  3344 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-21 07:32:38.096  3344  3344 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-21 07:32:38.106  3344  3344 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-21 07:32:38.106  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-21 07:32:38.106  3344  3344 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-21 07:32:38.106  1968  1968 I GFX construct_block_size_descriptor_2d second part: took 2.074739ms for 0*0 texture 0
,03-21 07:32:38.116  1968  1968 I GFX generate_partition_tables: took 7.399062ms for 0*0 texture 0
,03-21 07:32:38.116  1968  1968 I GFX raster: took 11.622500ms for 176*144 texture 0
03-21 07:32:38.116  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b3a160 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8b3a260 counterpartCT=4 counterpartW=176 counterparth=144
,03-21 07:32:38.126  1017  1042 W libprocessgroup: failed to open /acct/uid_10142/pid_2522/cgroup.procs: No such file or directory
,03-21 07:32:38.146  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-21 07:32:38.146  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.146  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.146  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.146  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.166  3472  3472 E Zygote  : MountEmulatedStorage()
03-21 07:32:38.166  3472  3472 E Zygote  : v2
03-21 07:32:38.166  3472  3472 I libpersona: KNOX_SDCARD checking this for 10015
03-21 07:32:38.166  3472  3472 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:38.166  3472  3472 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:38.166  3472  3472 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:38.166  3472  3472 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 07:32:38.166  1017  1029 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3472 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-21 07:32:38.186  1968  1968 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-21 07:32:38.186  1815  1815 I SamsungIME: getDebugLevel  : 0x4f4c
,03-21 07:32:38.186  1968  1968 I GFX construct_block_size_descriptor_2d second part: took 2.226197ms for 0*0 texture 0
,03-21 07:32:38.186  3472  3472 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:38.196  3472  3472 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:38.196  1968  1968 I GFX generate_partition_tables: took 6.127917ms for 0*0 texture 0
,03-21 07:32:38.216  1968  1968 I GFX raster: took 10.462239ms for 176*144 texture 0
03-21 07:32:38.216  1968  1968 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b3a048 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8b3c8c0 counterpartCT=4 counterpartW=176 counterparth=144
,03-21 07:32:38.216  1968  1968 D ScoverManager: registerListener
,03-21 07:32:38.216  3283  3341 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-21 07:32:38.226  1017  1232 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 07:32:38.226  1017  1488 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 07:32:38.226  1017  1488 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@ed1fd2f, pid : 1968, uid : 1001, type : 1
,03-21 07:32:38.236  1968  1968 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-21 07:32:38.246  1017  1079 D LocationManagerService: getProviders()=[passive]
,03-21 07:32:38.256  1017  1489 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,03-21 07:32:38.256  3403  3469 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 07:32:38.256  3403  3469 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 07:32:38.266  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.266  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.266  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.266  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.276  3076  3398 W jxcore-log: Initializing JXcore engine
03-21 07:32:38.276  3076  3398 W jxcore-log: JXcore engine is ready
,03-21 07:32:38.286  3490  3490 E Zygote  : MountEmulatedStorage()
03-21 07:32:38.286  3490  3490 E Zygote  : v2
03-21 07:32:38.286  3490  3490 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:38.286  3490  3490 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:38.286  3490  3490 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:38.286  1017  1489 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3490 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 07:32:38.286  1017  1489 I ActivityManager: Killing 2620:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-21 07:32:38.296  1815  1815 I SamsungIME: KeybaordView init() : load resources
03-21 07:32:38.296  1017  1489 I ActivityManager: Killing 2560:com.sec.android.app.camera/u0a139 (adj 15): empty #32
,03-21 07:32:38.296  3490  3490 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:38.296  3490  3490 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:38.306  3283  3341 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-21 07:32:38.346  3490  3490 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:38.346  3490  3490 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:38.346  1815  1815 I SamsungIME: getCurrentKeyboard
,03-21 07:32:38.346  1815  1815 I SamsungIME: getTextKeyboard
,03-21 07:32:38.366  1913  1913 E audit   : type=1400 msg=audit(1458541958.366:205): avc:  denied  { ioctl } for  pid=3398 comm="Thread-383" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-21 07:32:38.366  1913  1913 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:38.366  1913  1913 E audit   : type=1300 msg=audit(1458541958.366:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9dd438f8 items=0 ppid=303 ppcomm=main pid=3398 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-383" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-21 07:32:38.366  1913  1913 E audit   : type=1320 msg=audit(1458541958.366:205): 
,03-21 07:32:38.386  3076  3398 W jxcore-log: Starting JXcore engine
,03-21 07:32:38.396  3283  3341 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-21 07:32:38.396  3283  3341 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-21 07:32:38.406  1017  1042 W libprocessgroup: failed to open /acct/uid_10139/pid_2560/cgroup.procs: No such file or directory
03-21 07:32:38.406  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2620/cgroup.procs: No such file or directory
,03-21 07:32:38.436  1815  1815 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-21 07:32:38.496  1330  3282 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-21 07:32:38.506  3403  3469 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-21 07:32:38.516  3076  3398 W jxcore-log: Platform android
03-21 07:32:38.516  3076  3398 W jxcore-log: 
,03-21 07:32:38.516  3076  3398 W jxcore-log: Process ARCH arm
03-21 07:32:38.516  3076  3398 W jxcore-log: 
,03-21 07:32:38.526  1330  3282 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-21 07:32:38.586  3403  3469 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-21 07:32:38.586  3403  3469 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@da95989: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-21 07:32:38.586  3403  3469 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 07:32:38.586  3490  3490 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-21 07:32:38.616  3490  3490 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-21 07:32:38.616  3490  3490 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-21 07:32:38.616  3490  3490 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-21 07:32:38.636  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-21 07:32:38.636  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-21 07:32:38.636  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:38.636  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:38.636  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-21 07:32:38.646  1017  2040 I ActivityManager: Killing 2637:com.android.calendar/u0a135 (adj 15): empty #31
,03-21 07:32:38.656  1017  2888 I ActivityManager: Killing 2713:com.android.keychain/1000 (adj 15): empty #31
,03-21 07:32:38.656  1017  1510 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
,03-21 07:32:38.656  1017  1510 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-21 07:32:38.666  1017  1510 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:38.666  1017  1510 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-21 07:32:38.666  1017  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-21 07:32:38.666  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.666  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.666  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.666  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.686  3518  3518 E Zygote  : MountEmulatedStorage(),
03-21 07:32:38.686  3518  3518 E Zygote  : v2
,03-21 07:32:38.686  1017  1510 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3518 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-21 07:32:38.686  3518  3518 I libpersona: KNOX_SDCARD checking this for 10092,
03-21 07:32:38.686  1017  1708 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,03-21 07:32:38.686  3518  3518 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:38.686  3518  3518 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:38.696  3518  3518 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:38.696  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.696  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.696  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.696  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.696  3518  3518 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-21 07:32:38.726  3518  3518 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:38.726  3518  3518 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:38.756  3076  3398 I jxcore-log: JXcore Cordova bridge is ready!
03-21 07:32:38.756  3076  3398 I jxcore-log: 
,03-21 07:32:38.756  3076  3398 W jxcore-log: JXcore engine is started
,03-21 07:32:38.766  1017  1708 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3535 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 07:32:38.766  3535  3535 E Zygote  : MountEmulatedStorage()
03-21 07:32:38.766  3535  3535 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:38.766  3535  3535 E Zygote  : v2
03-21 07:32:38.766  3535  3535 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:38.776  3535  3535 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:38.776  3344  3432 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-21 07:32:38.776  3535  3535 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:38.776  3535  3535 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:38.776  3076  3281 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 07:32:38.786  3076  3076 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 07:32:38.786  3344  3432 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-21 07:32:38.796  3344  3432 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-21 07:32:38.796  3076  3398 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-21 07:32:38.796  3076  3398 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
03-21 07:32:38.796  3344  3432 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-21 07:32:38.806  1017  1396 I ActivityManager: Killing 2815:com.android.email/u0a145 (adj 15): empty #31
,03-21 07:32:38.806  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-21 07:32:38.806  3076  3076 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-21 07:32:38.806  3076  3076 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-21 07:32:38.806  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.806  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.806  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.806  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.816  3344  3432 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
03-21 07:32:38.816  3552  3552 E Zygote  : MountEmulatedStorage()
03-21 07:32:38.816  3552  3552 E Zygote  : v2
03-21 07:32:38.816  3552  3552 I libpersona: KNOX_SDCARD checking this for 10003
03-21 07:32:38.816  3552  3552 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:38.826  3552  3552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:38.826  3552  3552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:38.826  1017  1017 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3552 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-21 07:32:38.826  3552  3552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:38.826  1017  1030 D FocusedStackFrame: Set to : 0
03-21 07:32:38.826  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 07:32:38.826  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-21 07:32:38.826  1017  1030 D InputDispatcher: Focused application set to: xxxx
03-21 07:32:38.826  1017  1042 W libprocessgroup: failed to kill pid 2713: No such process
03-21 07:32:38.826  1017  1030 D InputDispatcher: Focus left window: 3076
,03-21 07:32:38.836  3535  3535 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:38.836  3535  3535 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:38.836  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-21 07:32:38.836  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-21 07:32:38.836  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 07:32:38.836  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 07:32:38.836  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 07:32:38.836  1017  2886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-21 07:32:38.836  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 07:32:38.846  1017  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:32:38.846  1017  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-21 07:32:38.846   256   441 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (405 us)
,03-21 07:32:38.856  3552  3552 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:38.866  3552  3552 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:38.876  3076  3076 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
03-21 07:32:38.876  3076  3076 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
03-21 07:32:38.876  3076  3281 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 75ms. Plugin should use CordovaInterface.getThreadPool().
,03-21 07:32:38.886  1017  1030 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-21 07:32:38.886  1017  1030 W ActivityManager: mDVFSHelper.acquire()
,03-21 07:32:38.896  1017  1030 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-21 07:32:38.896  1017  1030 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-21 07:32:38.896  1017  1030 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-21 07:32:38.916  1490  1490 D Launcher: onRestart, Launcher: 445048381
,03-21 07:32:38.926  2668  3245 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3245)  
,03-21 07:32:38.936  1490  1490 D Launcher: onStart, Launcher: 445048381
,03-21 07:32:38.936  1490  1490 D Launcher.HomeView: onStart
,03-21 07:32:38.936  1490  1490 D Launcher: onResume, Launcher: 445048381
,03-21 07:32:38.936  1017  1079 I ActivityManager: Killing 1939:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-21 07:32:38.946  1017  1029 D SettingsProvider: name = kids_home_mode
,03-21 07:32:38.946  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-21 07:32:38.946  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-21 07:32:38.946  1017  1029 D SettingsProvider: selectionArgs: false
,03-21 07:32:38.946  1017  1029 D SettingsProvider: selectionArgs: 10007
,03-21 07:32:38.946  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-21 07:32:38.946  1017  1029 D SettingsProvider: ret = -1
,03-21 07:32:38.946  1490  1490 D Launcher.HomeView: onResume
,03-21 07:32:38.956  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-21 07:32:38.956  1017  1017 D SensorService: [SO] activate (ident=0xb8df04d8, enabled=0)
03-21 07:32:38.956  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-21 07:32:38.976  1017  1017 D SensorManager: unregisterListener ::   
,03-21 07:32:38.976  1017  1017 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-21 07:32:38.976  1017  1017 D SensorService: [SO] changed settle time [0]
03-21 07:32:38.976  3344  3432 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-21 07:32:38.976  1017  1017 D SensorService: [SO] setDelay [200000000]
,03-21 07:32:38.976  1017  1017 D SensorService: [SO] activate (ident=0xb8df04d8, enabled=1)
,03-21 07:32:38.976  1017  1017 D SensorService: [SO] AR_init
,03-21 07:32:38.976  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-21 07:32:38.986  3449  3449 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-21 07:32:38.996  1017  1017 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-21 07:32:38.996  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-21 07:32:38.996   286   286 E SMD     : DCD OFF,
,03-21 07:32:38.996  1490  1490 D MenuAppsGridFragment: onResume
,03-21 07:32:39.006  1017  1029 D ActivityManager: handle home activity for 0
,03-21 07:32:39.006  1017  1029 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-21 07:32:39.006  1017  1029 D KnoxTimeoutHandler: post home show event for user 0
,03-21 07:32:39.006  1017  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-21 07:32:39.006  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,03-21 07:32:39.006  1017  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 07:32:39.006  1017  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-21 07:32:39.006  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,03-21 07:32:39.006  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-21 07:32:39.006  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 07:32:39.026   256   256 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-21 07:32:39.026  1017  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-21 07:32:39.026  1017  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-21 07:32:39.036  1017  1029 D InputDispatcher: Focus entered window: 1490
,03-21 07:32:39.046  1490  1490 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-21 07:32:39.056  3344  3432 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-21 07:32:39.066  3535  3535 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-21 07:32:39.066  3535  3535 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-21 07:32:39.066  1017  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:32:39.066  1017  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-21 07:32:39.066  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-21 07:32:39.066  1017  2888 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-21 07:32:39.076  3344  3432 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-21 07:32:39.086  1191  1191 I StatusBar: Icon Only
,03-21 07:32:39.086  1191  1191 D PanelView: There is/are notification(s) 
,03-21 07:32:39.086  1017  3578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 07:32:39.086  3076  3076 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 07:32:39.096  3535  3535 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-21 07:32:39.096  1815  1815 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-21 07:32:39.106  3449  3449 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-21 07:32:39.106  3569  3569 D AndroidRuntime: 
03-21 07:32:39.106  3569  3569 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-21 07:32:39.106  3569  3569 D AndroidRuntime: CheckJNI is OFF
,03-21 07:32:39.116  3569  3569 D AndroidRuntime: readGMSProperty: start
03-21 07:32:39.116  3569  3569 D AndroidRuntime: readGMSProperty: already setted!!
03-21 07:32:39.116  3569  3569 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 07:32:39.116  3569  3569 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 07:32:39.116  3569  3569 D AndroidRuntime: readGMSProperty: end
03-21 07:32:39.116  3569  3569 D AndroidRuntime: addProductProperty: start
,03-21 07:32:39.116  3344  3432 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-21 07:32:39.116  3344  3432 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-21 07:32:39.136  3380  3511 W art     : Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.a.vM() took 313.870ms
03-21 07:32:39.136  3344  3433 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-21 07:32:39.136  1490  1490 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e55fa58 time:40662
,03-21 07:32:39.136  1017  1050 D PersonaManager: isKioskContainerExistOnDevice
,03-21 07:32:39.146  3535  3544 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-21 07:32:39.146  3552  3552 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-21 07:32:39.156  1017  1050 I ActivityManager: Displayed Component not be shown by security: +266ms
,03-21 07:32:39.166  3380  3511 I SearchServiceFactory: refreshing internal icing corpora
,03-21 07:32:39.176  3490  3490 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-21 07:32:39.186  3490  3490 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
03-21 07:32:39.186  3490  3490 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-21 07:32:39.196  1017  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1],
,03-21 07:32:39.196  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast,
,03-21 07:32:39.206  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.206  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-21 07:32:39.206  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.206  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.216  3344  3432 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/25/14:07:31
,03-21 07:32:39.216  3344  3432 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/21/07:32:39
03-21 07:32:39.216  3344  3432 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-21 07:32:39.216  3344  3432 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
03-21 07:32:39.216  3344  3433 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-21 07:32:39.226  3344  3433 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-21 07:32:39.236  3588  3588 E Zygote  : MountEmulatedStorage(),
,03-21 07:32:39.236  3588  3588 E Zygote  : v2,
03-21 07:32:39.236  3588  3588 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:39.236  3588  3588 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:39.236  3588  3588 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-21 07:32:39.236  3588  3588 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-21 07:32:39.246  3344  3433 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-21 07:32:39.246  3588  3588 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:39.246  3344  3433 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-21 07:32:39.246  3344  3433 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-21 07:32:39.246  3344  3433 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-21 07:32:39.246  3344  3433 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-21 07:32:39.246  3344  3433 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-21 07:32:39.256  1017  1488 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3588 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 07:32:39.256  1017  1488 I ActivityManager: Killing 2791:com.samsung.android.sm/1000 (adj 15): empty #31
,03-21 07:32:39.256  1017  1488 I ActivityManager: Killing 2497:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-21 07:32:39.256  3380  3511 I SearchServiceFactory: checking for language pack updates
,03-21 07:32:39.256  3449  3449 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-21 07:32:39.286  3588  3588 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:39.286  3588  3588 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:39.286  3449  3449 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-21 07:32:39.296  3449  3449 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-21 07:32:39.296  3569  3569 E AffinityControl: AffinityControl: registerfunction enter,
,03-21 07:32:39.306  3344  3433 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-21 07:32:39.326  3569  3569 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-21 07:32:39.326  3344  3432 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-21 07:32:39.336  1017  2888 D PackageManager: START PACKAGE DELETE: observer{436654114}
03-21 07:32:39.336  1017  2888 D PackageManager: pkg{<packageName>}
03-21 07:32:39.336  1017  2888 D PackageManager: user{0}
03-21 07:32:39.336  1017  2888 D PackageManager: caller{2000}
03-21 07:32:39.336  1017  2888 D PackageManager: flags{2}
03-21 07:32:39.336  1017  2888 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-21 07:32:39.336  1017  2888 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-21 07:32:39.336  1017  2888 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-21 07:32:39.336  1017  2888 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 07:32:39.336  1017  2888 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-21 07:32:39.336  1017  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,03-21 07:32:39.346  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-21 07:32:39.346  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-21 07:32:39.346  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
,03-21 07:32:39.346  3552  3552 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-21 07:32:39.346  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-21 07:32:39.346  3552  3552 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-21 07:32:39.346  3552  3552 D UserAnalysis: Create SecureDbHelper
,03-21 07:32:39.346  1017  1058 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,03-21 07:32:39.346  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,03-21 07:32:39.346  1017  1043 I ActivityManager: Killing 3076:com.test.thalitest/u0a155 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-21 07:32:39.356  3344  3433 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-21 07:32:39.376  1017  1042 W libprocessgroup: failed to open /acct/uid_10135/pid_2637/cgroup.procs: No such file or directory
03-21 07:32:39.376  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2713/cgroup.procs: No such file or directory
,03-21 07:32:39.386  3552  3552 D IntelligenceServiceApplication: onCreate()
,03-21 07:32:39.386  1017  1043 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,03-21 07:32:39.386  1017  1043 W ActivityManager: mDVFSHelper.release()
03-21 07:32:39.386  1017  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-21 07:32:39.386  3552  3552 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-21 07:32:39.386  1017  1042 W libprocessgroup: failed to open /acct/uid_10145/pid_2815/cgroup.procs: No such file or directory
03-21 07:32:39.386  1017  1042 W libprocessgroup: failed to open /acct/uid_10004/pid_1939/cgroup.procs: No such file or directory
,03-21 07:32:39.396  1017  1040 D SensorService: [SO] currT = 40920072951, prevT = 40430130711, diff = 489942240, [0.134 0.402 10.113]
,03-21 07:32:39.396  1017  1040 D SensorService: [SO] 0.134 0.402 10.113
03-21 07:32:39.396  1017  1040 D SensorService: [SO] [100 -> 255]
,03-21 07:32:39.426  3449  3449 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-21 07:32:39.436  3552  3552 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-21 07:32:39.436  3283  3341 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-21 07:32:39.446  3449  3449 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-21 07:32:39.446  3344  3433 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-21 07:32:39.466  3344  3432 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-21 07:32:39.476  3403  3416 W art     : Suspending all threads took: 41.310ms
,03-21 07:32:39.566  1017  3608 I WindowState: WIN DEATH: Window{1d1ea987 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-21 07:32:39.566  1017  3209 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,03-21 07:32:39.566  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.576  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.576  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.576  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.576  3344  3433 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-21 07:32:39.586  3588  3588 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-21 07:32:39.596   256  3576 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-21 07:32:39.596  3344  3433 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-21 07:32:39.606  3588  3588 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-21 07:32:39.606  3611  3611 E Zygote  : MountEmulatedStorage()
,03-21 07:32:39.606  3611  3611 E Zygote  : v2
03-21 07:32:39.606  3611  3611 I libpersona: KNOX_SDCARD checking this for 10060
03-21 07:32:39.606  3611  3611 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:39.606  3611  3611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:39.616  3403  3603 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
03-21 07:32:39.616  3611  3611 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-21 07:32:39.616  3403  3603 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-21 07:32:39.616  3611  3611 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:39.616  1017  3209 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3611 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
03-21 07:32:39.616  1017  3209 I ActivityManager: Killing 2906:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-21 07:32:39.616  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2791/cgroup.procs: No such file or directory
,03-21 07:32:39.616  1017  1042 W libprocessgroup: failed to open /acct/uid_10044/pid_2497/cgroup.procs: No such file or directory
,03-21 07:32:39.626  1017  1510 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-21 07:32:39.626  1017  1058 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,03-21 07:32:39.626  3552  3552 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-21 07:32:39.626  3344  3432 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-21 07:32:39.646  3611  3611 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:39.646  3611  3611 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:39.666  1017  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-21 07:32:39.666  1017  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f7d160f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:41198
,03-21 07:32:39.666  1017  1232 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-21 07:32:39.676  1017  1232 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-21 07:32:39.676  1017  1232 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:39.676  1017  1232 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-21 07:32:39.676  1017  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-21 07:32:39.686  3552  3552 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-21 07:32:39.686  1017  1017 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,03-21 07:32:39.686  3552  3552 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-21 07:32:39.686  3449  3449 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-21 07:32:39.696  3535  3545 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-21 07:32:39.706  3380  3628 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 07:32:39.706  3380  3628 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_icing_corpora]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 07:32:39.706  3380  3628 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 07:32:39.706  3380  3628 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_language_packs]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
03-21 07:32:39.706  3380  3628 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 07:32:39.706  3380  3628 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_doodle]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 07:32:39.716  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-21 07:32:39.716  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,03-21 07:32:39.726  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.726  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:39.726  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-21 07:32:39.726  3380  3628 E TRThreadPoolExecutor: Queue length for executor Background Blocking with unbounded threads is now 4. Perhaps some tasks are too long, or the pool is too small.
,03-21 07:32:39.726  3380  3631 I SearchServiceFactory: refreshing search history.
,03-21 07:32:39.726  1815  3508 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-21 07:32:39.726  3380  3628 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_domain_and_cookies]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 07:32:39.736  3380  3635 I UpdateIcingCorporaServi: Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,03-21 07:32:39.746  3380  3632 I UpdateLanguagePacksTask: Checking for language pack updates.
,03-21 07:32:39.766  3449  3449 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-21 07:32:39.776  1017  1105 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 07:32:39.786  1815  1815 E SamsungIME: mOCRHelper is null
,03-21 07:32:39.796  1796  2099 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 07:32:39.806  1017  1043 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{2fb419ce u0 android.intent.action.PACKAGE_REMOVED} to ReceiverList{2845e4df 2906 flipboard.boxer.app/10099/u0 remote:4aa77e}: filter unregistered
,03-21 07:32:39.806  1467  1467 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 07:32:39.816  1017  1132 V NetworkStats: removeUidsLocked() for UIDs [10155]
03-21 07:32:39.816  1017  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 07:32:39.816  1017  1132 V NetworkStats: performPollLocked(flags=0x3)
,03-21 07:32:39.816  1017  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
03-21 07:32:39.816  1017  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-21 07:32:39.826  1017  1132 V NetworkStats: performPollLocked() took 5ms
03-21 07:32:39.826  1017  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 07:32:39.846  1452  1452 D RegisteredComponentCache: Collect Tech packages for Knox
,03-21 07:32:39.846  1017  1042 W libprocessgroup: failed to open /acct/uid_10099/pid_2906/cgroup.procs: No such file or directory
,03-21 07:32:39.846  3588  3588 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-21 07:32:39.866  3588  3588 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-21 07:32:39.876  1452  1452 D PersonaManager: isKioskContainerExistOnDevice
,03-21 07:32:39.926  1017  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 07:32:39.926  1017  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 07:32:39.966  1017  1489 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-21 07:32:39.966  1017  1489 D SecContentProvider2: mCursor = null
,03-21 07:32:40.006  1017  1079 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-21 07:32:40.006  1452  1452 D PersonaManager: isKioskContainerExistOnDevice
,03-21 07:32:40.006  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.006  1330  3282 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-21 07:32:40.006  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.006  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.006  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.026  3649  3649 E Zygote  : MountEmulatedStorage()
03-21 07:32:40.026  3649  3649 E Zygote  : v2
,03-21 07:32:40.026  3649  3649 I libpersona: KNOX_SDCARD checking this for 10094
03-21 07:32:40.026  3649  3649 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:40.026  3649  3649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-21 07:32:40.026  1017  1079 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3649 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-21 07:32:40.036  3649  3649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:40.036  1452  1452 D RegisteredServicesCache: empty dynamic service
,03-21 07:32:40.036  3649  3649 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.046  3611  3611 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-21 07:32:40.056  3380  3511 E File    : fail readDirectory() errno=2
,03-21 07:32:40.066  1017  1017 D RCPManagerService: PackageReceiver onReceive()
03-21 07:32:40.066  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-21 07:32:40.076  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-21 07:32:40.076   255   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache/
03-21 07:32:40.076  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-21 07:32:40.076   255   523 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 07:32:40.076  1017  1017 D OTPFW   : OtpDbHelper::getInstance New instance created
,03-21 07:32:40.076  1017  1017 D OTPFW   : DBIntegrity::getInstance - New instance created
,03-21 07:32:40.086  3649  3649 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:40.086  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,03-21 07:32:40.086  1017  3609 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
03-21 07:32:40.086  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,03-21 07:32:40.086  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-21 07:32:40.086  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 07:32:40.086  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 07:32:40.086  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,03-21 07:32:40.086  1017  1017 V EnterpriseBillingPolicy: uID is 10155
03-21 07:32:40.086  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 07:32:40.086  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-21 07:32:40.086  1017  3609 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.086  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 07:32:40.086  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 07:32:40.086  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 07:32:40.086  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-21 07:32:40.096  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-21 07:32:40.096  1017  3609 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.096  1017  3609 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.096  1017  3609 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.106  3649  3649 D ActivityThread: Added TimaKeyStore provider,
03-21 07:32:40.106  3588  3588 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-21 07:32:40.106  3380  3510 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache
,03-21 07:32:40.126  3671  3671 E Zygote  : MountEmulatedStorage()
03-21 07:32:40.126  3671  3671 I libpersona: KNOX_SDCARD checking this for 10062
03-21 07:32:40.126  3671  3671 E Zygote  : v2
03-21 07:32:40.126  3671  3671 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:40.126  3671  3671 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:40.126  3588  3588 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W,
03-21 07:32:40.126  3588  3588 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-21 07:32:40.126  3671  3671 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:40.126  3671  3671 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.136  1017  3609 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3671 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:32:40.136  3588  3588 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-21 07:32:40.146  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-21 07:32:40.146  3588  3588 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-21 07:32:40.146  1017  1017 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
03-21 07:32:40.146  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-21 07:32:40.146  1017  1017 V EnterpriseBillingPolicy: uID is 10155
03-21 07:32:40.146  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 07:32:40.146  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-21 07:32:40.146  1017  2780 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-21 07:32:40.146  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 07:32:40.146  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 07:32:40.146  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 07:32:40.146  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-21 07:32:40.156  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-21 07:32:40.166  3671  3671 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:40.166  3671  3671 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:40.166  3588  3588 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
03-21 07:32:40.166  3588  3588 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-21 07:32:40.216  1017  1079 I ActivityManager: Killing 1573:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-21 07:32:40.226  2690  2770 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-21 07:32:40.296  3649  3649 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-21 07:32:40.296  3649  3649 D elm:15183: ELMEngine.ELMEngine( context ).
,03-21 07:32:40.296  3449  3648 I System.out: Thread-454(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-21 07:32:40.296  3449  3648 I System.out: Thread-454(ApacheHTTPLog):isSBSettingEnabled false
03-21 07:32:40.296  3449  3648 I System.out: Thread-454(ApacheHTTPLog):isShipBuild true
03-21 07:32:40.296  3449  3648 I System.out: Thread-454(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-21 07:32:40.296  3449  3648 I System.out: Thread-454(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-21 07:32:40.306  3649  3649 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-21 07:32:40.316  1017  3610 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm,
03-21 07:32:40.316  1017  3610 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-21 07:32:40.316  3671  3671 I ExternalOEMControlProvider: onCreate,
,03-21 07:32:40.316   274   998 D EnterpriseController: uids 10092,
03-21 07:32:40.316   274   998 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-21 07:32:40.316   274   998 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-21 07:32:40.326  1017  3610 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.326  1017  3610 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:40.326  1017  3610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-21 07:32:40.326  3649  3649 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-21 07:32:40.336  3122  3141 W art     : Suspending all threads took: 9.946ms
,03-21 07:32:40.336  1017  3209 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,03-21 07:32:40.346  1428  1428 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-21 07:32:40.346  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.346  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.346  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.346  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.356  3649  3649 D elm:15183: ElmAgentService : onCreate()
,03-21 07:32:40.356  3649  3692 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) },
03-21 07:32:40.356  3649  3649 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-21 07:32:40.356  3649  3649 D elm:15183: BootCompletedState : startBootCompleted() call
,03-21 07:32:40.356  3649  3649 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-21 07:32:40.356  3380  3633 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121),
03-21 07:32:40.366  3649  3649 I elm:15183: Get License : 0
,03-21 07:32:40.366  3694  3694 E Zygote  : MountEmulatedStorage(),
03-21 07:32:40.366  3694  3694 E Zygote  : v2
03-21 07:32:40.366  3694  3694 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:40.366  3694  3694 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:40.366  3694  3694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:40.366  1017  3209 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3694 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-21 07:32:40.366  3694  3694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:40.376  1017  3209 I ActivityManager: Killing 2245:flipboard.app/u0a98 (adj 15): empty #31
,03-21 07:32:40.376  1428  1428 V EmergencyMode: [EmergencyBase] setBootTime
03-21 07:32:40.376  1428  1428 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
03-21 07:32:40.376  3694  3694 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-21 07:32:40.376  1490  1490 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true,
03-21 07:32:40.376  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
03-21 07:32:40.376  1490  1490 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-21 07:32:40.376  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.376  1490  1490 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-21 07:32:40.376  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.376  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.376  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.386  3641  3641 I dex2oat : ----------------------------------------------------
,03-21 07:32:40.386  3641  3641 I dex2oat : <SS>: S T A R T I N G . . .
03-21 07:32:40.386  3641  3641 I dex2oat : <SS>: Zip is absent. Canceled.
03-21 07:32:40.386  3641  3641 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1647741208.jar --oat-fd=28 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads1647741208.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
,03-21 07:32:40.396  3704  3704 E Zygote  : MountEmulatedStorage(),
03-21 07:32:40.396  3704  3704 E Zygote  : v2
03-21 07:32:40.396  3704  3704 I libpersona: KNOX_SDCARD checking this for 1000,
03-21 07:32:40.396  3704  3704 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:40.396  3704  3704 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-21 07:32:40.406  3704  3704 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:40.406  1017  1029 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3704 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 07:32:40.406  3380  3633 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 1924-1937)
,03-21 07:32:40.406  3380  3633 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 07:32:40.416  3704  3704 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.426  3649  3649 D elm:15183: ElmAgentService : onDestroy().
,03-21 07:32:40.426   303   303 I art     : Explicit concurrent mark sweep GC freed 8758(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 30.968ms
,03-21 07:32:40.436  3694  3694 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:40.436  3704  3704 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:40.436  3694  3694 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.436  3704  3704 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.436  1017  1232 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-21 07:32:40.436  1017  1232 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:40.436  1017  1232 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:40.436  1017  1232 D SettingsProvider: selectionArgs: false
03-21 07:32:40.436  1017  1232 D SettingsProvider: selectionArgs: 10062
,03-21 07:32:40.436  1017  1232 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:40.436  1017  1232 D SettingsProvider: ret = -1
,03-21 07:32:40.436  1017  1029 I ActivityManager: Killing 2960:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-21 07:32:40.446  3283  3341 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-21 07:32:40.446  1017  1232 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
03-21 07:32:40.446  1017  1173 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
03-21 07:32:40.446  1017  1173 D TaskPersister: removeObsoleteFile: deleting file=12_task_thumbnail.png
,03-21 07:32:40.456  1017  3608 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-21 07:32:40.456  1017  3608 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:40.456  1017  3608 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:40.456  1017  3608 D SettingsProvider: selectionArgs: false
,03-21 07:32:40.456  1017  3608 D SettingsProvider: selectionArgs: 10062
03-21 07:32:40.456  1017  3608 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-21 07:32:40.456  1017  3608 D SettingsProvider: ret = -1
,03-21 07:32:40.456   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 25.935ms
,03-21 07:32:40.466  1017  3608 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-21 07:32:40.476  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
03-21 07:32:40.476  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-21 07:32:40.476  1017  1042 W TextServicesManagerService: no available spell checker services found
,03-21 07:32:40.476  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:40.476  3422  3422 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-21 07:32:40.486   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 19.543ms
,03-21 07:32:40.486  3694  3694 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-21 07:32:40.506  3380  3633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:32:40.506  3380  3633 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 07:32:40.516  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:40.526  3422  3422 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-21 07:32:40.536  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.536  3694  3694 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-21 07:32:40.536  3694  3694 I ServiceMode: setReferenceIsDumpState : 0
,03-21 07:32:40.536  3422  3422 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-21 07:32:40.546  3403  3403 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
03-21 07:32:40.536  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.566  3422  3422 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-21 07:32:40.566  1017  1708 D ActivityManager: startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,03-21 07:32:40.566  3704  3704 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-21 07:32:40.566  3704  3704 I testFeature: Feature.Feature(context)
03-21 07:32:40.566  3704  3704 I testFeature: Feature.readInternalDefaultXml()
03-21 07:32:40.566  3704  3704 I testFeature: ResetFeatureValue
,03-21 07:32:40.566  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.566  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.566  3704  3704 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-21 07:32:40.566  3704  3704 I CameraApp: CameraApp.getAppFeature()...
,03-21 07:32:40.566  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.566  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.566  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.576  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-21 07:32:40.586  3737  3737 E Zygote  : MountEmulatedStorage(),
03-21 07:32:40.586  3737  3737 E Zygote  : v2
03-21 07:32:40.586  3737  3737 I libpersona: KNOX_SDCARD checking this for 10014,
03-21 07:32:40.586  3737  3737 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:40.586  3737  3737 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:40.586  3737  3737 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:40.586  1017  1708 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3737 uid=10014 gids={50014, 9997} abi=armeabi-v7a,
03-21 07:32:40.596  3737  3737 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-21 07:32:40.596  1017  1708 I ActivityManager: Killing 2971:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31,
,03-21 07:32:40.606  1017  1708 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,03-21 07:32:40.606  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.606  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.606  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.606  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.606  3641  3641 I dex2oat : dex2oat took 221.195ms (threads: 4)
,03-21 07:32:40.616  1017  1058 I art     : Explicit concurrent mark sweep GC freed 51686(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 30MB/45MB, paused 3.560ms total 884.783ms,
,03-21 07:32:40.636  3752  3752 E Zygote  : MountEmulatedStorage(),
03-21 07:32:40.636  3752  3752 E Zygote  : v2
03-21 07:32:40.636  3752  3752 I libpersona: KNOX_SDCARD checking this for 10100
03-21 07:32:40.636  3752  3752 I libpersona: KNOX_SDCARD not a persona,
03-21 07:32:40.636  3752  3752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:40.636  3752  3752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-21 07:32:40.636  1017  1708 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3752 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-21 07:32:40.636  3752  3752 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.646  3737  3737 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-21 07:32:40.646  3737  3737 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.656  1645  2216 I art     : Explicit concurrent mark sweep GC freed 3092(125KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 783us total 49.499ms
,03-21 07:32:40.656  1017  1708 D ActivityManager: startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,03-21 07:32:40.676  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.676  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.676  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.676  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.686  3752  3752 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:40.686  3752  3752 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.696  1017  1708 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3767 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 07:32:40.696  1017  1708 I ActivityManager: Killing 2402:com.sec.modem.settings/1000 (adj 15): empty #31
,03-21 07:32:40.696  3767  3767 E Zygote  : MountEmulatedStorage()
03-21 07:32:40.696  3767  3767 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:40.696  3767  3767 E Zygote  : v2
03-21 07:32:40.696  3767  3767 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:40.696  3767  3767 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:40.706  3767  3767 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-21 07:32:40.706  3767  3767 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.716  3380  3635 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 799 ms] updated apps [took 799 ms] 
,03-21 07:32:40.736  3767  3767 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:40.736  3767  3767 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.746  1330  3282 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-21 07:32:40.746  1330  3282 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-21 07:32:40.746  1017  1704 I ActivityManager: Killing 3042:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-21 07:32:40.746  1330  3282 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-21 07:32:40.756  3737  3737 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-21 07:32:40.756  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,03-21 07:32:40.756  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-21 07:32:40.756  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:40.756  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:40.756  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-21 07:32:40.766  3752  3752 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-21 07:32:40.766  3752  3752 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-21 07:32:40.766  3737  3784 V OneTimeService: OneTimeService.onHandleIntent
,03-21 07:32:40.766  1017  1079 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,03-21 07:32:40.766  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.766  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.766  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.766  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.786  3403  3403 I System.out: YouTube MDX: MDX video stage moved to NEW,
03-21 07:32:40.786  3403  3403 I System.out: YouTube MDX: MDX video player state moved to UNSTARTED
03-21 07:32:40.786  3403  3403 I System.out: YouTube MDX: MDX ad player state moved to UNSTARTED
,03-21 07:32:40.786  3380  3396 W art     : Suspending all threads took: 69.180ms
,03-21 07:32:40.796  3787  3787 E Zygote  : MountEmulatedStorage()
03-21 07:32:40.796  3787  3787 E Zygote  : v2,
03-21 07:32:40.796  3787  3787 I libpersona: KNOX_SDCARD checking this for 10101
03-21 07:32:40.796  3787  3787 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:40.796  1017  1079 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3787 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 07:32:40.796  3787  3787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-21 07:32:40.796  1017  3609 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1191 (0x0)
03-21 07:32:40.806  3787  3787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:40.806  1017  3209 I ActivityManager: Killing 2366:com.android.mms/u0a46 (adj 15): empty #31
03-21 07:32:40.806  3787  3787 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-21 07:32:40.806  1017  3209 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-21 07:32:40.806  1017  3209 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-21 07:32:40.806  1017  3209 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.806  1017  3209 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:40.806  1017  3209 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-21 07:32:40.806  1017  1232 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-21 07:32:40.806  1017  1232 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.806  1017  1232 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
03-21 07:32:40.806  1017  1232 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:40.806  1017  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-21 07:32:40.816  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-21 07:32:40.816  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
03-21 07:32:40.816  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.816  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:40.816  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-21 07:32:40.826  1017  1708 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-21 07:32:40.826  1017  1708 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-21 07:32:40.836  1017  1708 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.836  1017  1708 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:40.836  1017  1708 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-21 07:32:40.836  3787  3787 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:40.836  3787  3787 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.836  3767  3767 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-21 07:32:40.846  3767  3767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-21 07:32:40.846  3403  3416 W art     : Suspending all threads took: 25.327ms
,03-21 07:32:40.846  1017  1029 D ActivityManager: startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
03-21 07:32:40.846  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-21 07:32:40.846  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.846  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:40.846  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-21 07:32:40.856  3767  3767 D NPS_WSSNPS: [] Service onCreate!!
,03-21 07:32:40.856  1017  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-21 07:32:40.866  1017  1079 D CountryDetector: No listener is left
,03-21 07:32:40.866  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.866  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.866  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.866  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.886  3808  3808 E Zygote  : MountEmulatedStorage()
03-21 07:32:40.886  3808  3808 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:40.886  3808  3808 E Zygote  : v2
03-21 07:32:40.886  3808  3808 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:40.886  3808  3808 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:40.886  3808  3808 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:40.886  3808  3808 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-21 07:32:40.886  1017  1489 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3808 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 07:32:40.896  2668  2668 D FactoryTestApp: [DummyFtClient$onDestroy](2668) Destroy DummyFtClient service
,03-21 07:32:40.896  2668  2668 D FactoryTestApp: [Support$Values.getString](2668) id=MODEL_COMMUNICATION_MODE, value=gsm
03-21 07:32:40.896  2668  2668 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2668) mConnectionMode = gsm
03-21 07:32:40.896  2668  2668 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2668) RUNNING_FTCLIENT : false
03-21 07:32:40.896  2668  2668 D FactoryTestApp: [DummyFtClient$onDestroy](2668) kill process
03-21 07:32:40.896  2668  2668 I Process : Sending signal. PID: 2668 SIG: 9
,03-21 07:32:40.896  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-21 07:32:40.896  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-21 07:32:40.906  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.906  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:40.906  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-21 07:32:40.906  1017  3609 D ActivityManager: startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,03-21 07:32:40.906  1017  3609 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.906  1017  3609 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.906  1017  3609 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.906  1017  3609 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.906  3767  3820 D NPS_WSSNPS: [50.150621] NpsServiceTask Start
,03-21 07:32:40.916  3808  3808 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:40.916  3808  3808 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.916  3767  3767 D NPS_WSSNPS: [50.150621] smlDBHelper
,03-21 07:32:40.936  3831  3831 E Zygote  : MountEmulatedStorage(),
03-21 07:32:40.936  3831  3831 E Zygote  : v2
03-21 07:32:40.936  3831  3831 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:40.936  3831  3831 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:40.936  1017  3609 I ActivityManager: Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3831 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 07:32:40.936  3831  3831 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:40.936  3380  3631 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 07:32:40.936  3831  3831 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:40.946  3831  3831 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.946  1017  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 07:32:40.946  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.946  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:40.946  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-21 07:32:40.956  1017  3209 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 07:32:40.956  1017  3209 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.956  1017  3209 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:40.956  1017  3209 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-21 07:32:40.966  3808  3808 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 07:32:40.966  3831  3831 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:40.966  3831  3831 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.976  1017  1232 I ActivityManager: Process com.sec.factory (pid 2668)(adj 0) has died(121,1126)
,03-21 07:32:40.986  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-21 07:32:41.026  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:41.026  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:41.036  1017  1058 D PackageManager: delete codoeFile: 
,03-21 07:32:41.036  1017  1058 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
03-21 07:32:41.036  1017  1058 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,03-21 07:32:41.036  1017  1058 D PackageManager: result of delete: 1{436654114}
,03-21 07:32:41.056  3569  3569 D AndroidRuntime: Shutting down VM
,03-21 07:32:41.056  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:41.056  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 07:32:41.056  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 07:32:41.056  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 07:32:41.066  1017  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-21 07:32:41.066  1017  1058 D PackageManager: userId{-1}
03-21 07:32:41.066  1017  1058 D PackageManager: andCode{true}
,03-21 07:32:41.066  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:41.066  1017  1708 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-21 07:32:41.066  1017  1708 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-21 07:32:41.066  1017  1708 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:41.066  1017  1708 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 07:32:41.066  1017  1708 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-21 07:32:41.076  1017  1079 D ActivityManager: startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,03-21 07:32:41.076  3831  3831 I Hs20UtilService: onCreate
,03-21 07:32:41.076  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.076  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.076  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.076  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.076  3767  3767 I NPS_WSSNPS: [50.150621] AsyncBulkFlagCheck
,03-21 07:32:41.096  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-21 07:32:41.096  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-21 07:32:41.096  3851  3851 E Zygote  : MountEmulatedStorage(),
03-21 07:32:41.096  3851  3851 E Zygote  : v2
03-21 07:32:41.096  3851  3851 I libpersona: KNOX_SDCARD checking this for 10019,
03-21 07:32:41.096  3851  3851 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:41.096  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:32:41.096  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,03-21 07:32:41.106  1017  1079 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3851 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-21 07:32:41.106  3851  3851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-21 07:32:41.106  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.106  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-21 07:32:41.106  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
03-21 07:32:41.106  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 07:32:41.116  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
03-21 07:32:41.116  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 07:32:41.116  3851  3851 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-21 07:32:41.116  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:41.116  3851  3851 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:41.126  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-21 07:32:41.126  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.126  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.126  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.126  3767  3848 I NPS_WSSNPS: [50.150621] IsRemain_AsyncBulkCheck
03-21 07:32:41.126  3831  3831 I Hs20UtilService: Starting #1
,03-21 07:32:41.126  3831  3847 I Hs20UtilService: Message received 5003
,03-21 07:32:41.136  3767  3848 I NPS_WSSNPS: [50.150621] IsRemain_Asyncing nothing
03-21 07:32:41.136  3767  3848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-21 07:32:41.146  3869  3869 E Zygote  : MountEmulatedStorage(),
03-21 07:32:41.146  3869  3869 E Zygote  : v2
03-21 07:32:41.146  3869  3869 I libpersona: KNOX_SDCARD checking this for 10004
03-21 07:32:41.146  3869  3869 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:41.146  3869  3869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:41.146  3869  3869 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-21 07:32:41.146  3851  3851 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:41.146  3869  3869 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:41.146  3851  3851 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.146  1017  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=3869 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-21 07:32:41.156  1017  3608 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 07:32:41.156  1017  3608 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.156  1017  3608 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.156  1017  3608 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-21 07:32:41.156  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-21 07:32:41.156  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-21 07:32:41.156  1017  2040 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.156  1017  2040 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
03-21 07:32:41.156  1017  2040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:41.156  1017  1042 W libprocessgroup: failed to open /acct/uid_10072/pid_1573/cgroup.procs: No such file or directory
03-21 07:32:41.156  1017  2040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
03-21 07:32:41.156  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2960/cgroup.procs: No such file or directory
,03-21 07:32:41.156  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-21 07:32:41.156  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-21 07:32:41.156  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 07:32:41.166  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 07:32:41.166  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 07:32:41.166  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 07:32:41.166  3767  3767 D NPS_WSSNPS: [50.150621] Service onDestroy
,03-21 07:32:41.176  3869  3869 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.176  3869  3869 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.196  3767  3767 I NPS_WSSNPS: [50.150621] smlBRConfigurationDelete
,03-21 07:32:41.196  3767  3767 I NPS_WSSNPS: [50.150621] smlBRMessageDelete
,03-21 07:32:41.196  3767  3767 I NPS_WSSNPS: [50.150621] smlBREmailDelete
,03-21 07:32:41.196  3767  3767 I NPS_WSSNPS: [50.150621] smlBRNetworkDelete
03-21 07:32:41.196  3767  3767 I NPS_WSSNPS: [50.150621] smlBRCallLogDelete
,03-21 07:32:41.196  3767  3767 I NPS_WSSNPS: [50.150621] smlBRMiniDiaryDelete
03-21 07:32:41.196  3767  3767 I NPS_WSSNPS: [50.150621] smlBRPenMemoMDelete
,03-21 07:32:41.206  3767  3767 I NPS_WSSNPS: [50.150621] smlBRSMemoDelete
,03-21 07:32:41.206  3767  3767 I NPS_WSSNPS: [50.150621] verifier installed? false
,03-21 07:32:41.206  3767  3767 I NPS_WSSNPS: [50.150621] cpuBooster release : false
,03-21 07:32:41.216  3767  3767 D NPS_WSSNPS: [50.150621] dsServerSocket close
,03-21 07:32:41.226  1017  1488 I ActivityManager: Killing 3027:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-21 07:32:41.256  3851  3851 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 21 07:32:41 GMT+01:00 2016
,03-21 07:32:41.256  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-21 07:32:41.256  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.266  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:41.266  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:41.266  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-21 07:32:41.266  3569  3569 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-21 07:32:41.266  3851  3851 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-21 07:32:41.266  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,03-21 07:32:41.266  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.266  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.266  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.266  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.276  3851  3851 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-21 07:32:41.276  3851  3851 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-21 07:32:41.276  3851  3851 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-21 07:32:41.276  3851  3889 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-21 07:32:41.296  3891  3891 E Zygote  : MountEmulatedStorage()
03-21 07:32:41.296  3891  3891 I libpersona: KNOX_SDCARD checking this for 10022
03-21 07:32:41.296  3891  3891 E Zygote  : v2
03-21 07:32:41.296  3891  3891 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:41.296  3891  3891 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:41.296  1017  1029 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3891 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
03-21 07:32:41.296  3891  3891 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:41.296  1017  1042 W libprocessgroup: failed to open /acct/uid_10098/pid_2245/cgroup.procs: No such file or directory
03-21 07:32:41.296  3891  3891 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:41.296  1017  1042 W libprocessgroup: failed to open /acct/uid_10152/pid_2971/cgroup.procs: No such file or directory
03-21 07:32:41.296  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2402/cgroup.procs: No such file or directory
03-21 07:32:41.296  1017  1042 W libprocessgroup: failed to open /acct/uid_1101/pid_3042/cgroup.procs: No such file or directory
,03-21 07:32:41.296  1017  1042 W libprocessgroup: failed to open /acct/uid_10046/pid_2366/cgroup.procs: No such file or directory
03-21 07:32:41.296  3851  3889 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
,03-21 07:32:41.296  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3027/cgroup.procs: No such file or directory
,03-21 07:32:41.306  3380  3633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:32:41.316  3891  3891 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.316  3891  3891 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.356  1017  1704 D ActivityManager: bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
,03-21 07:32:41.356  1017  1704 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.356  1017  1704 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:41.356  1017  1704 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.356  1017  1704 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-21 07:32:41.416  1017  1510 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-21 07:32:41.416  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.416  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.416  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.416  1017  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.436  3918  3918 E Zygote  : MountEmulatedStorage()
03-21 07:32:41.436  1017  1510 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3918 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 07:32:41.436  3918  3918 E Zygote  : v2
03-21 07:32:41.436  3918  3918 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:41.436  3918  3918 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 07:32:41.436  3918  3918 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:41.436  1017  1510 I ActivityManager: Killing 3064:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-21 07:32:41.446  3918  3918 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:41.446  3851  3851 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-21 07:32:41.446  3283  3341 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-21 07:32:41.456  3918  3918 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:41.476   255   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-21 07:32:41.476   255   523 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 07:32:41.476  3403  3403 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-21 07:32:41.486  3918  3918 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.486  3918  3918 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.506   274   998 D EnterpriseController: uids 10057
03-21 07:32:41.506   274   998 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-21 07:32:41.506   274   998 D Netd    : getNetworkForDns: using netid 502 for uid 10057
,03-21 07:32:41.516  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-21 07:32:41.516  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.516  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:41.516  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.516  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-21 07:32:41.536  3918  3918 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-21 07:32:41.536  1017  1489 D SecContentProvider2: uri = 14 selection = getSealedState
,03-21 07:32:41.546  1017  1489 D SecContentProvider2: mCursor = null
,03-21 07:32:41.546  1017  1079 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-21 07:32:41.546  1017  1079 D SecContentProvider2: mCursor = null
03-21 07:32:41.546  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 07:32:41.546  1017  1030 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-21 07:32:41.546  3918  3918 V MTPRx   : sealedState: false
03-21 07:32:41.546  3918  3918 V MTPRx   : sealedUsbMassStorageState: false
,03-21 07:32:41.546  1017  3610 D SettingsProvider: name = mtp_usb_connection_status
,03-21 07:32:41.546  3472  3472 I RlzPingService: Setting next ping for 1459146761557
,03-21 07:32:41.556  1017  1030 D SettingsProvider: name = media_player_mode
,03-21 07:32:41.556  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:41.566  1017  1042 W libprocessgroup: failed to open /acct/uid_10048/pid_3064/cgroup.procs: No such file or directory
,03-21 07:32:41.566  1017  1708 D SettingsProvider: name = mtp_usb_conditions_met
,03-21 07:32:41.566  1017  1079 D SettingsProvider: name = mtp_running_status
,03-21 07:32:41.576  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:41.586  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:41.686  1017  1488 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-21 07:32:41.696  1017  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-21 07:32:41.706  3787  3945 I Gmail   : getAccountsCursor
,03-21 07:32:41.706  1017  2888 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-21 07:32:41.706  1017  2888 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.706  1796  1796 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:32:41.726  1017  3609 I AudioService: getStreamVolume 3 index 0
,03-21 07:32:41.726  1017  2040 I ActivityManager: Killing 3104:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-21 07:32:41.766  3787  3787 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-21 07:32:41.786  3449  3648 I System.out: pool-10-thread-1 calls detatch()
,03-21 07:32:41.796  1017  1708 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,03-21 07:32:41.796  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.796  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.796  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.796  1017  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.796  1017  1488 D SettingsProvider: name = media_mount_count
,03-21 07:32:41.806  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
03-21 07:32:41.816  3953  3953 E Zygote  : MountEmulatedStorage()
03-21 07:32:41.816  3953  3953 E Zygote  : v2,
03-21 07:32:41.816  3953  3953 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:41.816  3953  3953 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:41.816  3953  3953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-21 07:32:41.816  3953  3953 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:41.816  3953  3953 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:41.826  1017  1708 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3953 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-21 07:32:41.836  3953  3953 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:41.826  1017  1708 I ActivityManager: Killing 3152:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
03-21 07:32:41.836  3953  3953 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.846  1017  3609 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-21 07:32:41.846  1017  3609 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.846  1017  3609 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.846  1017  3609 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.846  1017  3609 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-21 07:32:41.846  1017  1042 W libprocessgroup: failed to open /acct/uid_10157/pid_3104/cgroup.procs: No such file or directory
,03-21 07:32:41.866   303   303 I art     : Explicit concurrent mark sweep GC freed 8766(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 871us total 38.234ms
,03-21 07:32:41.886   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 19.381ms
,03-21 07:32:41.896   255   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-21 07:32:41.896   255   523 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 07:32:41.896  3403  3403 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
03-21 07:32:41.896  3380  3633 W TRThreadPoolExecutor: Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
03-21 07:32:41.896   255   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-21 07:32:41.896   255   523 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 07:32:41.906  3403  3403 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-21 07:32:41.906   255   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-21 07:32:41.906   255   523 W Vold    : Returning OperationFailed - no handler for errno 0
03-21 07:32:41.906   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.158ms total 20.873ms
,03-21 07:32:41.906  3403  3403 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-21 07:32:41.916  1017  2888 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 07:32:41.916  1017  1042 W libprocessgroup: failed to open /acct/uid_10159/pid_3152/cgroup.procs: No such file or directory
03-21 07:32:41.916  1017  2888 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.916  1017  1232 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-21 07:32:41.916  1017  2888 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.916  1017  1232 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
03-21 07:32:41.916  1017  2888 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-21 07:32:41.916  1017  1232 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.916  1017  1232 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.916  1017  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-21 07:32:41.926  1017  3610 D ActivityManager: bindService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.gms, action: null
03-21 07:32:41.926  1017  3610 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-21 07:32:41.926  1017  3610 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.926  1017  3610 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.926  1017  3610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-21 07:32:41.926  1017  1079 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-21 07:32:41.926  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.926  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:41.926  1796  1796 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 07:32:41.926  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.926  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-21 07:32:41.936  1796  1796 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:32:41.936  1017  3209 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 07:32:41.936  1017  3209 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-21 07:32:41.966  1017  3609 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-21 07:32:41.966  1017  3609 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.966  3787  3997 I Gmail   : getAccountsCursor
03-21 07:32:41.966  3787  3985 E Gmail   : Error finding the version of the Email provider.....
03-21 07:32:41.966  3787  3985 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-21 07:32:41.966  3787  3985 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-21 07:32:41.966  3787  3985 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
03-21 07:32:41.966  3787  3985 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-21 07:32:41.966  3787  3985 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 07:32:41.966  3787  3985 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 07:32:41.966  3787  3985 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:41.966  3787  3985 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 07:32:41.966  3787  3985 W EmailMigration: We do not support migrating this version of the Email provider.
,03-21 07:32:41.966  1017  3609 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.966  1017  3609 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.966  1017  3609 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-21 07:32:41.966  1017  1079 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-21 07:32:41.966  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.976  3403  3972 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:41.976  3403  3972 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-21 07:32:41.976  1796  1796 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:32:41.976  1017  1396 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 07:32:41.976  1017  1396 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:41.976  1017  1396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.976  1017  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:32:41.986  1017  3209 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-21 07:32:41.986  1017  3209 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.986  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:41.986  3808  3948 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM usage_log WHERE strftime('%s','now', '-40 days')*1000 - start_time >= 0] disk I/O error
03-21 07:32:41.986  1017  3209 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.986  1017  3209 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:41.986  1017  3209 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-21 07:32:41.986  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:41.986  3808  3948 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM running_service_log WHERE strftime('%s','now', '-40 days')*1000 - captured_time >= 0] disk I/O error
,03-21 07:32:41.986  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:41.986  3808  3948 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM noti_info WHERE strftime('%s','now', '-40 days')*1000 - posted_date >= 0] disk I/O error
,03-21 07:32:41.986  1017  1029 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-21 07:32:41.986  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:41.986  3808  3948 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM screen_state_log WHERE strftime('%s','now', '-40 days')*1000 - time >= 0] disk I/O error
,03-21 07:32:41.986  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-21 07:32:41.986  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:41.986  3808  3948 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM debug_log_info WHERE strftime('%s','now', '-20 days')*1000 - created_At >= 0] disk I/O error
,03-21 07:32:41.996  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:41.996  3808  3948 E SQLiteLog: (3850) statement aborts at 3: [DELETE FROM system_env_info] disk I/O error
,03-21 07:32:41.996  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:41.996  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: Error inserting name=this value=SmartManager LowpowerContextEngine
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:183)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 07:32:41.996  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:41.996  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 07:32:41.996   286   286 E SMD     : DCD OFF
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: Error inserting name=now value=Mon Mar 21 07:32:42 GMT+01:00 2016
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-2,1 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:184)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:41.996  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 07:32:41.996  1017  1708 D SettingsProvider: name = access_control_enabled
,03-21 07:32:41.996  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:41.996  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-21 07:32:42.006  3808  3948 E SQLiteDatabase: Error inserting name=isSystemBuild value=false
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:185)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 07:32:42.006  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:42.006  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 07:32:42.006  1017  3608 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
03-21 07:32:42.006  1017  3608 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: Error inserting name=isDevelopVersion value=false
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:186)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 07:32:42.006  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:42.006  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-21 07:32:42.006  3808  3948 E SQLiteDatabase: Error inserting name=DBVersion value=2003
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:187)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 07:32:42.006  1017  3608 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.006  1017  3608 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 07:32:42.006  1017  3608 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-21 07:32:42.006  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:42.006  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-21 07:32:42.006  3403  3563 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 07:32:42.006  3403  3563 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-21 07:32:42.006  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:42.006  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-21 07:32:42.006  3808  3948 E SQLiteDatabase: Error inserting name=UT enabled value=false
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:189)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 07:32:42.006  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:42.006  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-21 07:32:42.006  3808  3948 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:190)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.006  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 07:32:42.006  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:42.006  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-21 07:32:42.016  3808  3948 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:191)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 07:32:42.016  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:42.016  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-21 07:32:42.016  3808  3948 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.0.2
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:192)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: ,	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 07:32:42.016  3808  3948 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 07:32:42.016  3808  3948 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: Error inserting name=status value=successfully initialized
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:193)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:124)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.016  3808  3948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 07:32:42.026  1017  3209 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,03-21 07:32:42.026  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.026  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.026  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.026  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.026  3787  3946 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-21 07:32:42.026  1645  4003 I GoogleHttpClient: GMS http client unavailable, use old client
,03-21 07:32:42.036  3787  3946 W GAV2    : Thread[AsyncTask #2,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,03-21 07:32:42.036  3787  3946 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #2
03-21 07:32:42.036  3787  3946 E AndroidRuntime: Process: com.google.android.gm, PID: 3787
03-21 07:32:42.036  3787  3946 E AndroidRuntime: java.lang.RuntimeException: An error occured while executing doInBackground()
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at com.android.email.provider.EmailProvider.a(SourceFile:512)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at com.android.email.provider.EmailProvider.c(SourceFile:589)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at com.android.email.provider.EmailProvider.e(SourceFile:1224)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at com.android.email.provider.EmailProvider.a(SourceFile:418)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at com.android.email.provider.EmailProvider.query(SourceFile:1431)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.content.ContentProvider.query(ContentProvider.java:993)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:489)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:64)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:42)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.content.AsyncTaskLoader.onLoadInBackground(AsyncTaskLoader.java:312)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:69)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:57)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.036  3787  3946 E AndroidRuntime: 	... 3 more
,03-21 07:32:42.046  4010  4010 E Zygote  : MountEmulatedStorage()
03-21 07:32:42.046  4010  4010 E Zygote  : v2
03-21 07:32:42.046  4010  4010 I libpersona: KNOX_SDCARD checking this for 10069
03-21 07:32:42.046  4010  4010 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:42.056  4010  4010 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 07:32:42.056  1017  3209 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4010 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 07:32:42.056  4010  4010 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 07:32:42.056  4010  4010 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:42.056  1017  3209 I ActivityManager: Killing 3181:com.sec.usbsettings/1000 (adj 15): empty #31
,03-21 07:32:42.056  1017  3609 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 07:32:42.056  1017  3609 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-21 07:32:42.056  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
03-21 07:32:42.056  1017  1029 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-21 07:32:42.066  1017  3209 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,03-21 07:32:42.066  1017  1396 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,03-21 07:32:42.066  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.066  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.066  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.066  1017  3209 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.086  1017  1232 D SettingsProvider: name = mtp_sync_alive
,03-21 07:32:42.086  4010  4010 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:42.086  4010  4010 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:42.096  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 07:32:42.096  4027  4027 E Zygote  : MountEmulatedStorage()
03-21 07:32:42.096  4027  4027 E Zygote  : v2
03-21 07:32:42.096  4027  4027 I libpersona: KNOX_SDCARD checking this for 10104
,03-21 07:32:42.096  4027  4027 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:42.096  3787  4020 I Gmail   : Observing account changes for notifications
,03-21 07:32:42.096  4027  4027 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-21 07:32:42.096  3787  3998 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gm/databases/internal.thalitester@gmail.com.db" with flag (131138) and mode_t (0) due to error (30),
03-21 07:32:42.096  4027  4027 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 07:32:42.096  1017  3209 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4027 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-21 07:32:42.106  4027  4027 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-21 07:32:42.106  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 07:32:42.106  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.106  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-21 07:32:42.106  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 07:32:42.116  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-21 07:32:42.116  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 07:32:42.116  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 07:32:42.116  1017  1030 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-21 07:32:42.116  1017  1079 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-21 07:32:42.116  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-21 07:32:42.116  3787  3998 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at com.google.android.gm.provider.bu.<init>(SourceFile:10995)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at com.google.android.gm.provider.bu.a(SourceFile:973)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at com.google.android.gm.provider.bu.b(SourceFile:1007)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at com.google.android.gm.GmailIntentService.a(SourceFile:2276)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:73)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.116  3787  3998 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 07:32:42.116  3787  3998 E GmailIS : Error handling intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gm/.GmailIntentService (has extras) }
03-21 07:32:42.116  3787  3998 E GmailIS : android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at com.google.android.gm.provider.bu.<init>(SourceFile:10995)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at com.google.android.gm.provider.bu.a(SourceFile:973)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at com.google.android.gm.provider.bu.b(SourceFile:1007)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at com.google.android.gm.GmailIntentService.a(SourceFile:2276)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:73)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.116  3787  3998 E GmailIS : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 07:32:42.116  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
,03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.116  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-21 07:32:42.126  1017  3610 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 07:32:42.126  1017  3610 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-21 07:32:42.126  1796  1796 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:32:42.126  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 07:32:42.136  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.136  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.136  4027  4027 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: Can't write: system_app_crash
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: 	at com.android.server.DropBoxManage,rService.add(DropBoxManagerService.java:211)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15989)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 07:32:42.136  1017  4037 E DropBoxManagerService: 	... 5 more
03-21 07:32:42.136  4027  4027 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.136  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-21 07:32:42.136  1017  4043 E android.os.Debug: ro.product_ship = true
03-21 07:32:42.136  1017  4043 E android.os.Debug: ro.debug_level = 0x4f4c
,03-21 07:32:42.146  1017  1043 D PhoneWindow: *FMB* installDecor mIsFloating : true
03-21 07:32:42.146  1017  1043 D PhoneWindow: *FMB* installDecor flags : 8519682
,03-21 07:32:42.146  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 07:32:42.146  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.146  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPoo,l.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.146  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.app.,ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.146  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.156  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.156  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.156  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.156  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.156  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.156  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.156  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.166  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.166  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.166  3787  4044 I Gmail   : getAccountsCursor
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.166  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.176  1017  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.166  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.166  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.176  1017  1043 D InputDispatcher: Focus left window: 1490
03-21 07:32:42.176  1017  1043 D InputDispatcher: Focus entered window: 1017
03-21 07:32:42.186  1017  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:32:42.186  1017  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 07:32:42.186  1017  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 07:32:42.186  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 07:32:42.186  1017  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 07:32:42.186  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3181/cgroup.procs: No such file or directory
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.186  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.196  3787  3787 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@f6f4d92 that was originally bound here
03-21 07:32:42.196  3787  3787 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@f6f4d92 that was originally bound here
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at com.android.emailcommon.service.ah.a(SourceFile:181)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at com.android.emailcommon.service.ah.e(SourceFile:224)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:161)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:173)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:117)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.196  3787  3787 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 07:32:42.196  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.196  1017  1489 I ActivityManager: Killing 3135:com.sec.dsm.system/1000 (adj 15): empty #31
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.196  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.206  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.206   256   256 I SurfaceFlinger: id=13 createSurf (97x97),1 flag=4, hm
03-21 07:32:42.206  4010  4010 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
03-21 07:32:42.206  4010  4010 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.FileShareServer/databases/inbound_transfer.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.206  2652  3279 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 07:32:42.206  2652  3279 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 07:32:42.206  4010  4010 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.FileShareServer/databases/inbound_transfer.db'.
03-21 07:32:42.206  4010  4010 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:32:42.206  4010  4010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)

```
