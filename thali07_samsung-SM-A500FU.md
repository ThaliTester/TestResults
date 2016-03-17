#### Test 62754403d2f0346_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
03-17 13:26:06.177  1951  1951 I GFX GPU raster ASTC: took 8.779895ms for 480*640 texture 12
03-17 13:26:06.177  1951  1951 I GFX raster: took 8.847968ms for 480*640 texture 0
03-17 13:26:06.177  1951  1951 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8649178 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8876828 counterpartCT=4 counterpartW=480 counterparth=640
--------- beginning of system
03-17 13:26:06.177  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.177  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.177  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.177  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.197  3299  3299 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.197  3299  3299 E Zygote  : v2
03-17 13:26:06.197  3299  3299 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:06.197  3299  3299 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:06.197  3299  3299 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.197  3299  3299 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.207  3299  3299 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.207  3082  3145 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
03-17 13:26:06.207  3239  3239 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-17 13:26:06.207  1690  3298 I GoogleHttpClient: GMS http client unavailable, use old client
03-17 13:26:06.207  1021  1305 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3299 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:06.207  1021  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
03-17 13:26:06.207  1021  1021 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:06.217  1744  1744 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
03-17 13:26:06.217  1690  2781 I art     : Explicit concurrent mark sweep GC freed 27961(1643KB) AllocSpace objects, 5(140KB) LOS objects, 40% free, 10MB/17MB, paused 1.231ms total 198.017ms
03-17 13:26:06.227  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.227  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:06.227  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:06.227  1951  1951 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
03-17 13:26:06.227  1951  1951 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 13:26:06.227  1021  3140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:06.237  1951  1951 I glCompressedTexImage2D: took 0.647761ms for 440*116864 texture 37809
03-17 13:26:06.237  1951  1951 I draw setup: took 1.229376ms for 440*330 texture 37809
03-17 13:26:06.237  1951  1951 E GFX GPU raster: drawn
03-17 13:26:06.237  1951  1951 I GFX GPU raster ASTC: took 5.028231ms for 440*330 texture 12
03-17 13:26:06.237  1951  1951 I GFX raster: took 5.089117ms for 440*330 texture 0
03-17 13:26:06.237  1951  1951 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb887aa80 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb887ae40 counterpartCT=4 counterpartW=440 counterparth=330
03-17 13:26:06.237  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:06.237  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:06.237  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:06.237  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:06.237  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:06.237  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:06.237  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.237  1021  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:06.247  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:06.247  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 13:26:06.257  1690  1703 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-17 13:26:06.267  3299  3299 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.267  3299  3299 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.267   289   289 E SMD     : DCD OFF
03-17 13:26:06.277  1349  3078 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 13:26:06.287  1021  1391 V VibratorService: hasVibrator - useVibetonz: true
03-17 13:26:06.297  1021  1377 V VibratorService: hasVibrator - useVibetonz: true
03-17 13:26:06.307  1349  3078 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 13:26:06.317  3082  3145 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
03-17 13:26:06.317  1951  1951 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-17 13:26:06.317  1951  1951 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 13:26:06.317  1951  1951 I glCompressedTexImage2D: took 0.448385ms for 480*163840 texture 37811
03-17 13:26:06.317  1951  1951 I draw setup: took 0.933854ms for 480*640 texture 37811
03-17 13:26:06.317  1951  1951 E GFX GPU raster: drawn
03-17 13:26:06.317  3082  3145 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-17 13:26:06.327  1951  1951 I GFX GPU raster ASTC: took 6.217605ms for 480*640 texture 12
03-17 13:26:06.327  1951  1951 I GFX raster: took 6.291824ms for 480*640 texture 0
03-17 13:26:06.327  1951  1951 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88ba450 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb88765e0 counterpartCT=4 counterpartW=480 counterparth=640
03-17 13:26:06.327  3082  3145 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
03-17 13:26:06.327  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.327  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.327  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.327  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.337  3327  3327 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.337  3327  3327 E Zygote  : v2
03-17 13:26:06.337  3327  3327 I libpersona: KNOX_SDCARD checking this for 10009
03-17 13:26:06.337  3327  3327 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.337  3327  3327 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:06.347  3327  3327 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:06.347  1021  1377 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3327 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:06.347  3327  3327 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 13:26:06.347  3228  3228 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
03-17 13:26:06.357  3228  3228 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-17 13:26:06.367  3228  3324 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 13:26:06.367  3228  3228 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
03-17 13:26:06.367  3228  3228 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
03-17 13:26:06.377  3228  3228 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
03-17 13:26:06.377  1951  1951 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 13:26:06.377  1951  1951 I GFX construct_block_size_descriptor_2d second part: took 2.331458ms for 0*0 texture 0
03-17 13:26:06.377  3327  3327 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.387  3228  3324 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
03-17 13:26:06.387  3327  3327 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.387  1951  1951 I GFX generate_partition_tables: took 8.712084ms for 0*0 texture 0
03-17 13:26:06.387  1951  1951 I GFX raster: took 13.030001ms for 176*144 texture 0
03-17 13:26:06.387  1951  1951 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb887aa00 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8874040 counterpartCT=4 counterpartW=176 counterparth=144
03-17 13:26:06.397  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2361/cgroup.procs: No such file or directory
03-17 13:26:06.397  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2400/cgroup.procs: No such file or directory
03-17 13:26:06.397  1021  1045 D LocationProviderProxy: applying state to connected service
03-17 13:26:06.397  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2414/cgroup.procs: No such file or directory
03-17 13:26:06.397  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2430/cgroup.procs: No such file or directory
03-17 13:26:06.397  3228  3324 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-17 13:26:06.407  3228  3228 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
03-17 13:26:06.407  3228  3228 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
03-17 13:26:06.407  1951  1951 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 13:26:06.407  1951  1951 I GFX construct_block_size_descriptor_2d second part: took 2.349220ms for 0*0 texture 0
03-17 13:26:06.407  3228  3228 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
03-17 13:26:06.407  3228  3228 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-17 13:26:06.407  3228  3228 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
03-17 13:26:06.417  3228  3228 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-17 13:26:06.417  3228  3228 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
03-17 13:26:06.417  3228  3228 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
03-17 13:26:06.417  1951  1951 I GFX generate_partition_tables: took 6.276932ms for 0*0 texture 0
03-17 13:26:06.427  1951  1951 I GFX raster: took 10.843650ms for 176*144 texture 0
03-17 13:26:06.427  1951  1951 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88740a8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8874230 counterpartCT=4 counterpartW=176 counterparth=144
03-17 13:26:06.427  1951  1951 D ScoverManager: registerListener
03-17 13:26:06.427  1021  1133 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 13:26:06.427  1021  3138 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 13:26:06.427  1021  3138 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@2f11550e, pid : 1951, uid : 1001, type : 1
03-17 13:26:06.427  3280  3280 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
03-17 13:26:06.437  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.437  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.437  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.437  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.447  2175  2175 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-17 13:26:06.447  2175  2175 I dhcpcd  : wlan0: no IPv6 Routers available
03-17 13:26:06.457  1021  1305 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3346 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:06.457  1021  1305 I ActivityManager: Killing 2440:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
03-17 13:26:06.457  3346  3346 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.457  3346  3346 E Zygote  : v2
03-17 13:26:06.457  3346  3346 I libpersona: KNOX_SDCARD checking this for 10062
03-17 13:26:06.457  3346  3346 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.467  3346  3346 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:06.467  1951  1951 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
03-17 13:26:06.467  3346  3346 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:06.467  3346  3346 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.487  3346  3346 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.487  3346  3346 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.537  3239  3239 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-17 13:26:06.537  3239  3239 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
03-17 13:26:06.567  1021  1045 W libprocessgroup: failed to open /acct/uid_10131/pid_2440/cgroup.procs: No such file or directory
03-17 13:26:06.577  3334  3334 D AndroidRuntime: 
03-17 13:26:06.577  3334  3334 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 13:26:06.577  3334  3334 D AndroidRuntime: CheckJNI is OFF
03-17 13:26:06.577  3334  3334 D AndroidRuntime: readGMSProperty: start
03-17 13:26:06.577  3334  3334 D AndroidRuntime: readGMSProperty: already setted!!
03-17 13:26:06.577  3334  3334 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 13:26:06.577  3334  3334 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 13:26:06.577  3334  3334 D AndroidRuntime: readGMSProperty: end
03-17 13:26:06.577  3334  3334 D AndroidRuntime: addProductProperty: start
03-17 13:26:06.617  3228  3247 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 13:26:06.627  3346  3346 I ExternalOEMControlProvider: onCreate
03-17 13:26:06.627  3228  3247 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 13:26:06.627  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.627  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.627  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.627  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.647  3378  3378 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.647  3378  3378 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.647  3378  3378 E Zygote  : v2
03-17 13:26:06.647  3378  3378 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.647  3378  3378 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:06.647  3378  3378 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:06.657  3378  3378 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.657  1021  1133 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3378 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:06.657  1021  1133 I ActivityManager: Killing 2475:com.wsomacp/u0a25 (adj 15): empty #31
03-17 13:26:06.657  3228  3247 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
03-17 13:26:06.667  1021  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.667  1021  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.667  1021  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.667  1021  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.667  1349  3078 D ScoverManager: serviceVersion : 16908288
03-17 13:26:06.677  1021  3141 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-17 13:26:06.677  1021  3141 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:06.677  1021  3141 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:06.677  1021  3141 D SettingsProvider: selectionArgs: false
03-17 13:26:06.677  1021  3141 D SettingsProvider: selectionArgs: 10062
03-17 13:26:06.677  1021  3141 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:06.677  1021  3141 D SettingsProvider: ret = -1
03-17 13:26:06.677  1021  3141 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
03-17 13:26:06.677  3228  3324 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-17 13:26:06.687  1021  1377 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 13:26:06.687  1021  1377 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:06.687  1021  1377 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:06.687  1021  1377 D SettingsProvider: selectionArgs: false
03-17 13:26:06.687  1021  1377 D SettingsProvider: selectionArgs: 10062
03-17 13:26:06.687  1021  1377 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:06.687  1021  1377 D SettingsProvider: ret = -1
03-17 13:26:06.687  3228  3324 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 13:26:06.687  1021  1498 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3390 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:06.687  1021  1498 I ActivityManager: Killing 2538:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
03-17 13:26:06.697  1021  1377 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
03-17 13:26:06.697  3390  3390 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.697  3390  3390 E Zygote  : v2
03-17 13:26:06.697  3390  3390 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.697  3390  3390 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.697  3390  3390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:06.697  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 13:26:06.697  3390  3390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:06.697  3390  3390 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.707  3228  3324 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
03-17 13:26:06.707  3228  3324 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
03-17 13:26:06.707  3228  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 13:26:06.707  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 13:26:06.707  3228  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 13:26:06.717  3378  3378 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.717  3378  3378 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.717  3228  3254 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
03-17 13:26:06.717  3228  3324 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
03-17 13:26:06.737  3390  3390 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.737  3390  3390 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.737  3182  3182 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
03-17 13:26:06.747  3378  3378 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 13:26:06.767  3228  3324 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
03-17 13:26:06.767  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.767  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.767  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.767  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.777  3334  3334 E AffinityControl: AffinityControl: registerfunction enter
03-17 13:26:06.787  3228  3324 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
03-17 13:26:06.797  1021  1305 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3411 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:06.797  1021  1305 I ActivityManager: Killing 2625:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
03-17 13:26:06.797  1021  1305 I ActivityManager: Killing 2352:com.sec.android.app.mt/1000 (adj 15): empty #32
03-17 13:26:06.797  1021  1305 I ActivityManager: Killing 2556:com.sec.android.app.camera/u0a139 (adj 15): empty #33
03-17 13:26:06.797  1021  1045 W libprocessgroup: failed to open /acct/uid_10025/pid_2475/cgroup.procs: No such file or directory
03-17 13:26:06.797  3378  3378 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-17 13:26:06.797  3378  3378 I ServiceMode: setReferenceIsDumpState : 0
03-17 13:26:06.807  3411  3411 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.807  3411  3411 E Zygote  : v2
03-17 13:26:06.807  3411  3411 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.807  3411  3411 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.807  3411  3411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:06.807  3411  3411 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:06.807  3411  3411 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.817  3334  3334 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 13:26:06.827   309   309 I art     : Explicit concurrent mark sweep GC freed 8797(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 4.165ms total 35.559ms
03-17 13:26:06.837  1021  1033 E PersonaManagerService: inState():  stateMachine is null !!
03-17 13:26:06.837  1021  1033 I PersonaManagerService: PersonaId don't exist
03-17 13:26:06.837  1021  1033 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 13:26:06.847   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.924ms
03-17 13:26:06.847   324   324 I ServiceManager: Waiting for service AtCmdFwd...
03-17 13:26:06.847  1021  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 13:26:06.857  3411  3411 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.857  3411  3411 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.867  1021  1033 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 13:26:06.867  1021  1033 W ActivityManager: mDVFSHelper.acquire()
03-17 13:26:06.867   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 17.384ms
03-17 13:26:06.867  3228  3324 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
03-17 13:26:06.867  1021  1033 D FocusedStackFrame: Set to : 0
03-17 13:26:06.867  3228  3324 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
03-17 13:26:06.867  3228  3324 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
03-17 13:26:06.877  3228  3325 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-17 13:26:06.877  3228  3325 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 13:26:06.877  1021  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 13:26:06.877  1021  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 13:26:06.877  1021  1033 D InputDispatcher: Focused application set to: xxxx
03-17 13:26:06.877  1021  1052 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 13:26:06.877  1021  1052 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 13:26:06.877  1021  1033 D InputDispatcher: Focus left window: 1501
03-17 13:26:06.877  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
03-17 13:26:06.887  3334  3334 D AndroidRuntime: Shutting down VM
03-17 13:26:06.887  1501  1501 D Launcher.HomeView: onPause
03-17 13:26:06.887  3228  3324 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
03-17 13:26:06.887  1501  1501 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 13:26:06.887  3228  3324 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/13:26:06
03-17 13:26:06.887  3228  3324 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
03-17 13:26:06.887  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.887  1021  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:06.887  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
03-17 13:26:06.887  3228  3324 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
03-17 13:26:06.887  1021  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:06.887  1021  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 13:26:06.887  1021  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 13:26:06.897  1021  1497 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.897  1021  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:06.897  1021  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:06.897  1021  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 13:26:06.897  1021  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 13:26:06.897   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 13:26:06.907  2682  2760 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
03-17 13:26:06.907  1021  1045 W libprocessgroup: failed to open /acct/uid_10142/pid_2538/cgroup.procs: No such file or directory
03-17 13:26:06.907  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2352/cgroup.procs: No such file or directory
03-17 13:26:06.907  3228  3325 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-17 13:26:06.907  3228  3325 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-17 13:26:06.917  3228  3325 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
03-17 13:26:06.917  3228  3325 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-17 13:26:06.917  3228  3325 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-17 13:26:06.917  3228  3325 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-17 13:26:06.917  3228  3325 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
03-17 13:26:06.917  3228  3325 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
03-17 13:26:06.917  3390  3390 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
03-17 13:26:06.917  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2625/cgroup.procs: No such file or directory
03-17 13:26:06.927  1021  1045 W libprocessgroup: failed to open /acct/uid_10139/pid_2556/cgroup.procs: No such file or directory
03-17 13:26:06.937  3228  3324 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
03-17 13:26:06.947  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.947  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.947  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.947  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.947  3390  3390 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
03-17 13:26:06.967  3228  3325 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
03-17 13:26:06.967  3390  3390 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
03-17 13:26:06.967  3390  3390 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
03-17 13:26:06.967  3390  3390 D ShortcutReceiver:  shortcut migration not required 
03-17 13:26:06.967  3438  3438 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.967  3438  3438 I libpersona: KNOX_SDCARD checking this for 10174
03-17 13:26:06.967  3438  3438 E Zygote  : v2
03-17 13:26:06.967  3438  3438 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.967  3438  3438 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:06.977  3438  3438 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:06.977  3438  3438 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 13:26:06.977  1021  1305 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3438 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 13:26:06.987  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.987  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.987  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.987  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.997  3438  3438 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.997  3438  3438 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:07.017  3453  3453 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.017  3453  3453 E Zygote  : v2
03-17 13:26:07.017  3453  3453 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.017  3453  3453 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:07.017  3453  3453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:07.017  3453  3453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:07.017  3453  3453 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:07.027  1021  1497 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3453 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:07.027  1021  1497 I ActivityManager: Killing 2661:com.android.calendar/u0a135 (adj 15): empty #31
03-17 13:26:07.027  1021  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 13:26:07.027  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.027  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.027  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:07.027  3228  3325 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
03-17 13:26:07.027  3411  3411 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
03-17 13:26:07.037  1021  1133 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:07.037  1021  1133 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 13:26:07.037  1021  1133 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:07.047  3411  3411 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
03-17 13:26:07.047  3411  3411 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
03-17 13:26:07.047  3411  3411 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
03-17 13:26:07.047  1021  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 13:26:07.057  1021  1133 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:07.067  3228  3324 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
03-17 13:26:07.077  3453  3453 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.077  3453  3453 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:07.087  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.087  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.087  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.087  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.097  3334  3334 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 13:26:07.117  3470  3470 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.117  1021  1497 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3470 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:07.117  3470  3470 E Zygote  : v2
03-17 13:26:07.117  3470  3470 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.117  3470  3470 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.117  3470  3470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:07.117  3470  3470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:07.117  3470  3470 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:07.117  1021  1497 I ActivityManager: Killing 2712:com.android.keychain/1000 (adj 15): empty #31
,03-17 13:26:07.137  3228  3324 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 13:26:07.137  1021  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 13:26:07.137  1021  1391 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.137  1021  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.137  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:07.157  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.157  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.157  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.157  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.167  3484  3484 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.167  3484  3484 E Zygote  : v2
,03-17 13:26:07.167  3484  3484 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.167  3484  3484 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.167  3484  3484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:07.177  3484  3484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:07.177  3484  3484 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:07.177  1021  1034 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:07.177  3228  3325 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 13:26:07.187  1021  1021 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-17 13:26:07.187  1021  1021 D SensorService: [SO] activate (ident=0xb8755570, enabled=0)
03-17 13:26:07.187  1021  1021 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-17 13:26:07.187  3470  3470 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.187  3470  3470 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.187  1021  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 13:26:07.187  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.187  1021  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-17 13:26:07.187  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:07.197  1894  1894 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-17 13:26:07.207  1021  1021 D SensorManager: unregisterListener ::   
03-17 13:26:07.207  1021  1021 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-17 13:26:07.207  1021  1021 D SensorService: [SO] changed settle time [1]
03-17 13:26:07.207  1021  1021 D SensorService: [SO] setDelay [66000000]
03-17 13:26:07.207  1021  1021 D SensorService: [SO] activate (ident=0xb8755570, enabled=1)
03-17 13:26:07.207  1021  1021 D SensorService: [SO] AR_init
03-17 13:26:07.207  1021  1021 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 13:26:07.217  3228  3325 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 13:26:07.217  1021  1021 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 13:26:07.227  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 13:26:07.237  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:07.237  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:07.237  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:07.247  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:07.247  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:07.247  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:07.247  3228  3325 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
03-17 13:26:07.247  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:07.247  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:07.247  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:07.247  3484  3484 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.257  3484  3484 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.257  1021  1045 W libprocessgroup: failed to open /acct/uid_10135/pid_2661/cgroup.procs: No such file or directory
,03-17 13:26:07.257  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2712/cgroup.procs: No such file or directory
,03-17 13:26:07.267  3470  3470 E KnoxSetupWizardClient: isShipMode : 1
03-17 13:26:07.267  3470  3470 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 13:26:07.287  3438  3438 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-17 13:26:07.287  1021  1043 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 13:26:07.287  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.287  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.287  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.287  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.307  3512  3512 E Zygote  : MountEmulatedStorage()
,03-17 13:26:07.307  3512  3512 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.307  3512  3512 E Zygote  : v2
03-17 13:26:07.307  3512  3512 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:07.307  3512  3512 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:07.307  3512  3512 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:07.307  1021  1305 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3512 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:07.307  1021  1305 I ActivityManager: Killing 2804:com.android.email/u0a145 (adj 15): empty #31
,03-17 13:26:07.307  3512  3512 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:07.327  3484  3484 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 13:26:07.327  3484  3484 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 13:26:07.327  3484  3484 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 13:26:07.327  3438  3438 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8280-8283)
03-17 13:26:07.327  3438  3438 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:07.327  3512  3512 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.327  3512  3512 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.347  3182  3182 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-17 13:26:07.347  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 13:26:07.357  1021  1043 D SensorService: [SO] currT = 38311088000, prevT = 38001134000, diff = 309954000, [0.172 0.421 10.266]
03-17 13:26:07.357  1021  1043 D SensorService: [SO] 0.172 0.421 10.266
03-17 13:26:07.357  1021  1043 D SensorService: [SO] [100 -> 255]
,03-17 13:26:07.357  3453  3453 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 13:26:07.357  3453  3453 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:07.357  1021  3141 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 13:26:07.367  3470  3507 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
03-17 13:26:07.367  3470  3507 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-17 13:26:07.367  3470  3507 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 13:26:07.367  3470  3507 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-17 13:26:07.367  3470  3507 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-17 13:26:07.367  3470  3507 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 13:26:07.367  3470  3507 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
03-17 13:26:07.367  1021  3141 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.367  1021  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:07.367  1021  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 13:26:07.367  3453  3453 D NPS_WSSNPS: [] Service onCreate!!
,03-17 13:26:07.367  3484  3498 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 13:26:07.377  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.377  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.377  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.377  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.377  3438  3438 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {17d250e3}
03-17 13:26:07.377  3438  3438 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 13:26:07.377  3438  3438 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 13:26:07.387  1349  3078 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
03-17 13:26:07.387  3534  3534 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.387  3534  3534 E Zygote  : v2
03-17 13:26:07.387  3534  3534 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.387  3534  3534 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:07.387  3534  3534 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:07.387  1021  1732 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3534 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:07.387  3534  3534 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:07.387  3534  3534 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:07.397  3411  3411 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
03-17 13:26:07.397  3411  3411 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
03-17 13:26:07.397  3411  3411 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 13:26:07.407  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.407  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.407  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.407  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.417  1349  3078 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-17 13:26:07.417  3438  3438 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 13:26:07.417  3438  3438 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:07.417  3438  3438 E SysUtils: ApplicationContext is null in ApplicationStatus
03-17 13:26:07.417  3453  3541 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-17 13:26:07.417  3551  3551 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.417  3551  3551 E Zygote  : v2
03-17 13:26:07.417  3551  3551 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.417  3551  3551 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.417  3551  3551 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:07.427  1021  1732 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3551 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:07.427  3551  3551 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:07.427  1021  1732 I ActivityManager: Killing 2843:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-17 13:26:07.427  3551  3551 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:07.437  1021  1732 I ActivityManager: Killing 2510:com.sec.android.gallery3d/u0a44 (adj 15): empty #32
,03-17 13:26:07.437  3534  3534 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.447  3534  3534 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.447  3453  3453 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-17 13:26:07.457  1021  3140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:07.457  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:07.457  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.457  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 13:26:07.457  3438  3438 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 13:26:07.467  3438  3438 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 13:26:07.467  3438  3438 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 13:26:07.467  3438  3438 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 13:26:07.467  3438  3438 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:26:07.467  3438  3438 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:26:07.467  3438  3438 I Adreno-EGL: Local Branch: 
03-17 13:26:07.467  3438  3438 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:26:07.467  3438  3438 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:26:07.467  3438  3438 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 13:26:07.467  3512  3512 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 13:26:07.477  3551  3551 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.477  3551  3551 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.487  3512  3512 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 13:26:07.497  3453  3453 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-17 13:26:07.497  1021  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.497  1021  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.497  1021  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.497  1021  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.517  3574  3574 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.517  3574  3574 E Zygote  : v2
03-17 13:26:07.517  3574  3574 I libpersona: KNOX_SDCARD checking this for 10116
03-17 13:26:07.517  3574  3574 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.517  3574  3574 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:07.517  3574  3574 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:07.517  1021  3139 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3574 uid=10116 gids={50116, 9997} abi=armeabi-v7a
03-17 13:26:07.517  3574  3574 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:07.527   258  1106 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
03-17 13:26:07.527   258   434 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-17 13:26:07.537  3453  3573 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-17 13:26:07.537  3453  3573 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-17 13:26:07.537  3453  3573 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 13:26:07.537  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 13:26:07.537  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:07.537  1021  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:07.537  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 13:26:07.547  3453  3453 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-17 13:26:07.557  3551  3551 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 13:26:07.557  3574  3574 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.557  3574  3574 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.567  3551  3551 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 13:26:07.577  1021  1045 W libprocessgroup: failed to open /acct/uid_10145/pid_2804/cgroup.procs: No such file or directory
03-17 13:26:07.577  1021  1045 W libprocessgroup: failed to open /acct/uid_10099/pid_2843/cgroup.procs: No such file or directory
03-17 13:26:07.577  1021  1045 W libprocessgroup: failed to open /acct/uid_10044/pid_2510/cgroup.procs: No such file or directory
,03-17 13:26:07.577  1021  2829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:07.597  3484  3498 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 13:26:07.597  3551  3551 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 13:26:07.607  3574  3574 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-17 13:26:07.607  3551  3551 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 13:26:07.617  3453  3453 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-17 13:26:07.617  3453  3453 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-17 13:26:07.617  3453  3453 I NPS_WSSNPS: [50.150321] smlBREmailDelete
03-17 13:26:07.617  3182  3182 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 13:26:07.617  3453  3453 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-17 13:26:07.617  3182  3182 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 13:26:07.617  3574  3574 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
03-17 13:26:07.617  3453  3453 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
,03-17 13:26:07.617  3453  3453 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
03-17 13:26:07.617  3453  3453 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
03-17 13:26:07.617  3453  3453 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
,03-17 13:26:07.617  3453  3453 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-17 13:26:07.637  1021  2792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 13:26:07.727  3438  3438 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:07.757  3551  3551 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 13:26:07.757  3551  3551 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 13:26:07.757  3551  3551 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 13:26:07.757  3551  3551 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 13:26:07.767  3551  3551 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 13:26:07.767  3551  3551 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 13:26:07.767  3551  3551 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 13:26:07.767  1021  1732 I art     : Explicit concurrent mark sweep GC freed 37063(1859KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 2.544ms total 156.468ms
,03-17 13:26:07.767  1021  3140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:07.767  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.767  1021  3140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:07.767  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
03-17 13:26:07.777  3574  3574 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-17 13:26:07.777  3453  3453 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-17 13:26:07.787  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.787  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.787  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.787  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.787  3438  3438 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 13:26:07.787  1021  1306 D SettingsProvider: name = access_control_enabled
,03-17 13:26:07.797  3438  3438 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 13:26:07.797  3438  3438 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 13:26:07.807  3614  3614 E Zygote  : MountEmulatedStorage()
,03-17 13:26:07.807  3614  3614 E Zygote  : v2
03-17 13:26:07.807  3614  3614 I libpersona: KNOX_SDCARD checking this for 10125
03-17 13:26:07.807  3614  3614 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.807  3614  3614 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:07.807  1021  3140 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3614 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,03-17 13:26:07.807  3614  3614 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:07.807  3614  3614 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:07.807  3438  3438 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 13:26:07.807  1021  1033 I ActivityManager: Killing 2283:flipboard.app/u0a98 (adj 15): empty #31
,03-17 13:26:07.827  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.827  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.827  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.827  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.827  3327  3327 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 13:26:07.837  3629  3629 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.837  3629  3629 E Zygote  : v2
03-17 13:26:07.837  3629  3629 I libpersona: KNOX_SDCARD checking this for 10069
03-17 13:26:07.837  3629  3629 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.837  3629  3629 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:07.847  3629  3629 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:07.847  3614  3614 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.847  1021  3140 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3629 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:07.847  3614  3614 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.847  1021  3140 I ActivityManager: Killing 2908:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 13:26:07.847  3629  3629 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:07.847  3438  3438 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 13:26:07.847  3438  3438 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:07.847   324   324 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 13:26:07.877  3629  3629 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.877  3629  3629 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.877  1021  1498 V VibratorService: hasVibrator - useVibetonz: true
,03-17 13:26:07.877  3327  3327 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 13:26:07.887  3614  3614 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:07.887  3614  3614 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 13:26:07.887  3614  3614 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 13:26:07.887  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.887  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.887  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.887  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.897  3182  3424 D Volley  : [391] DiskBasedCache.clear: Cache cleared.
,03-17 13:26:07.897  3182  3502 D Volley  : [398] DiskBasedCache.clear: Cache cleared.
,03-17 13:26:07.897  3649  3649 E Zygote  : MountEmulatedStorage(),
03-17 13:26:07.897  3649  3649 E Zygote  : v2
03-17 13:26:07.897  3649  3649 I libpersona: KNOX_SDCARD checking this for 10014
03-17 13:26:07.897  3649  3649 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.897  3649  3649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:07.907  3649  3649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:07.907  1021  1133 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3649 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-17 13:26:07.907  3649  3649 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:07.907  1021  1133 I ActivityManager: Killing 2382:com.android.mms/u0a46 (adj 15): empty #31
,03-17 13:26:07.907  1021  1133 I ActivityManager: Killing 2972:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-17 13:26:07.927  1021  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-17 13:26:07.927  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.927  1021  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.927  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:07.927   309   309 I art     : Explicit concurrent mark sweep GC freed 8777(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 27.817ms
,03-17 13:26:07.937  1690  1690 V GLSUser : [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
03-17 13:26:07.937  1021  1517 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:07.947  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.947  1021  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.947  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 13:26:07.947  3629  3629 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
03-17 13:26:07.947  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
03-17 13:26:07.947  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.947  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.947  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:07.947   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 18.190ms
,03-17 13:26:07.957  3649  3649 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.957  3649  3649 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.967  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-17 13:26:07.967  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.967  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.967  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 13:26:07.967   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 18.845ms
,03-17 13:26:07.977  1894  1894 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,03-17 13:26:07.977  1021  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 13:26:07.987  1021  1045 W libprocessgroup: failed to open /acct/uid_10098/pid_2283/cgroup.procs: No such file or directory
,03-17 13:26:07.987  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.987  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.987  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:07.987  1021  3140 D CountryDetector: No listener is left
,03-17 13:26:07.987  1021  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:07.997  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:07.997  1021  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.997  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:08.017  3438  3669 D OpenGLRenderer: Render dirty regions requested: true
,03-17 13:26:08.017  1021  3139 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 13:26:08.017  1021  3139 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 13:26:08.017  1021  3139 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 13:26:08.017  1021  1021 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 13:26:08.017  1021  1021 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 13:26:08.017  3438  3590 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 13:26:08.027  3438  3438 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 13:26:08.027  3438  3438 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 13:26:08.027  1690  1690 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-17 13:26:08.047   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 13:26:08.047  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2908/cgroup.procs: No such file or directory
,03-17 13:26:08.047  1021  1045 W libprocessgroup: failed to open /acct/uid_10046/pid_2382/cgroup.procs: No such file or directory
03-17 13:26:08.047  1021  1045 W libprocessgroup: failed to open /acct/uid_10048/pid_2972/cgroup.procs: No such file or directory
,03-17 13:26:08.057  3614  3614 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-17 13:26:08.057  3614  3614 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-17 13:26:08.057  1021  3141 D InputDispatcher: Focus entered window: 3438
,03-17 13:26:08.067  1021  1732 D SettingsProvider: name = scon_is_running
,03-17 13:26:08.067  1021  1732 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:08.067  1021  1732 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:08.067  1021  1732 D SettingsProvider: selectionArgs: false
03-17 13:26:08.067  1021  1732 D SettingsProvider: selectionArgs: 10125
03-17 13:26:08.067  1021  1732 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:08.067  1021  1732 D SettingsProvider: ret = -1
,03-17 13:26:08.067  1021  1732 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-17 13:26:08.067  3614  3614 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-17 13:26:08.067  1021  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:08.067  1021  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:08.067  3438  3438 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 13:26:08.067  3438  3669 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 13:26:08.077  3438  3669 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 13:26:08.077  3438  3669 D OpenGLRenderer: Enabling debug mode 0
,03-17 13:26:08.077  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:08.087  3649  3649 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 13:26:08.087  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.087  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.087  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.087  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 13:26:08.097  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.097  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.097  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.097  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.097  3649  3673 V OneTimeService: OneTimeService.onHandleIntent
,03-17 13:26:08.107  3675  3675 E Zygote  : MountEmulatedStorage()
,03-17 13:26:08.107  3675  3675 I libpersona: KNOX_SDCARD checking this for 10015
03-17 13:26:08.107  3675  3675 E Zygote  : v2
03-17 13:26:08.107  3675  3675 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.117  1021  1496 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3675 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a,
,03-17 13:26:08.127  1021  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:08.127  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.127  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.127  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:08.137  1349  3078 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 13:26:08.187  3675  3675 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:08.187  3675  3675 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:08.187  3675  3675 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:08.197  3182  3182 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-17 13:26:08.197  3182  3182 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-17 13:26:08.217  1021  1034 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 13:26:08.217  3614  3614 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 13:26:08.217  3675  3675 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.217  3675  3675 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.217  1021  3692 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:08.227  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.227  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.227  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.227  3182  3182 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
03-17 13:26:08.227  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.227  1196  1196 I StatusBar: Icon Only
,03-17 13:26:08.227  1196  1196 D PanelView: There is/are notification(s) 
,03-17 13:26:08.237  3438  3438 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b1b16c5 time:39193
,03-17 13:26:08.237  3694  3694 E Zygote  : MountEmulatedStorage()
03-17 13:26:08.237  3694  3694 E Zygote  : v2
03-17 13:26:08.237  3694  3694 I libpersona: KNOX_SDCARD checking this for 10131
03-17 13:26:08.237  3694  3694 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:08.247  3694  3694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:08.247  3694  3694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:08.247  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:08.247  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:08.247  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:08.247  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:08.247  3694  3694 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:08.247  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:08.247  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:08.247  1021  3141 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3694 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-17 13:26:08.247  1021  3141 I ActivityManager: Killing 2682:com.google.android.apps.books/u0a75 (adj 15): empty #31
,03-17 13:26:08.247  1809  1809 I SamsungIME: getCurrentCandidateView
,03-17 13:26:08.257  1021  1052 I ActivityManager: Displayed Component not be shown by security: +1s322ms
,03-17 13:26:08.257  1021  1052 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@7
03-17 13:26:08.267  1021  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b3258c3 u0 com.test.thalitest/.MainActivity t236} time:39220
03-17 13:26:08.267  1021  1052 W ActivityManager: mDVFSHelper.release()
03-17 13:26:08.267  1021  1046 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:08.277  1501  1501 D Launcher.HomeView: onStop
,03-17 13:26:08.277  1501  1501 V ActivityThread: updateVisibility : ActivityRecord{25507288 token=android.os.BinderProxy@21f2d84d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,03-17 13:26:08.277  1501  1501 D Launcher: onTrimMemory. Level: 20
,03-17 13:26:08.287  3694  3694 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.287  3694  3694 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.297  1021  1517 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.297  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.297  1021  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.297  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 13:26:08.307  1809  1809 D SamsungIME: Dismiss ExpandCandiate
,03-17 13:26:08.317  3694  3694 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 13:26:08.317  3694  3694 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:08.317  3694  3694 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 13:26:08.317  3694  3694 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:08.317  1021  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.317  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.317  1021  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.317  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:08.327  1021  3138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.327  1809  1809 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 13:26:08.327  1021  3138 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.327  1021  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.327  1021  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:08.337  1021  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.337  1021  1497 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.347  1021  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.347  1021  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:08.347  1021  1391 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:08.357  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 13:26:08.357  1021  1391 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.357  1021  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.357  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:08.367  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.367  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.367  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.367  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:08.387  1021  1045 W libprocessgroup: failed to open /acct/uid_10075/pid_2682/cgroup.procs: No such file or directory
,03-17 13:26:08.407  2645  3174 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3174)  
,03-17 13:26:08.427  3438  3438 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3438
,03-17 13:26:08.437  1894  1894 W InstanceID/Rpc: Found 10012
,03-17 13:26:08.447  3694  3694 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-17 13:26:08.477  1021  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.477  1021  1391 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.477  1021  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.477  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:08.487   258   434 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 13:26:08.487   258   437 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 13:26:08.487  1021  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:08.487  1809  1809 I SamsungIME: getDebugLevel  : 0x4f4c
03-17 13:26:08.487  1021  1496 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.487  1021  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:08.487  1021  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:08.497  1349  3078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 13:26:08.497  2607  2607 I Hs20UtilService: Starting #2
,03-17 13:26:08.507  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.507  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.507  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.507  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.507  2607  2622 I Hs20UtilService: Message received 5003
,03-17 13:26:08.507  3694  3694 D ManifestProvider: onCreate()
,03-17 13:26:08.517  3728  3728 E Zygote  : MountEmulatedStorage()
,03-17 13:26:08.517  3728  3728 E Zygote  : v2
03-17 13:26:08.517  3728  3728 I libpersona: KNOX_SDCARD checking this for 10019
03-17 13:26:08.517  3728  3728 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.517  3728  3728 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:08.517  1021  3138 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3728 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 13:26:08.527  1809  1809 I SamsungIME: KeybaordView init() : load resources,
,03-17 13:26:08.527  3728  3728 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:08.527  1021  1497 I ActivityManager: Killing 2891:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
03-17 13:26:08.527  3728  3728 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:08.537  3694  3694 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-17 13:26:08.547  1349  3078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 13:26:08.557  1349  3078 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 13:26:08.557  3182  3182 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-17 13:26:08.567  1021  1021 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:08.577  3728  3728 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.577  3728  3728 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.607  3182  3182 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-17 13:26:08.617  1021  1045 W libprocessgroup: failed to open /acct/uid_10085/pid_2891/cgroup.procs: No such file or directory
,03-17 13:26:08.617  1809  1809 I SamsungIME: getCurrentKeyboard
03-17 13:26:08.617  1809  1809 I SamsungIME: getTextKeyboard
,03-17 13:26:08.627  1021  1497 I ActivityManager: Killing 3026:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-17 13:26:08.637  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.637  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.637  1021  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.637  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:08.637  1021  1033 I ActivityManager: Killing 3060:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 13:26:08.637  1021  1033 I ActivityManager: Killing 2998:com.sec.dsm.system/1000 (adj 15): empty #32
,03-17 13:26:08.637  1809  1809 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 13:26:08.647  3694  3694 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@30f50c5e
,03-17 13:26:08.657  3694  3694 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
,03-17 13:26:08.657  1021  1021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 13:26:08.657  3694  3694 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-17 13:26:08.667  1021  1021 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 13:26:08.667  1021  1021 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:08.677  1021  1021 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.677  1021  1021 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.677  1021  1021 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.677  1021  1021 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.687  3438  3438 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-17 13:26:08.687  3749  3749 E Zygote  : MountEmulatedStorage()
03-17 13:26:08.687  3749  3749 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:08.687  3749  3749 E Zygote  : v2
03-17 13:26:08.687  3749  3749 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:08.687  3749  3749 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:08.697  1021  1021 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3749 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:08.697  3749  3749 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:08.697  3749  3749 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:08.697  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.697  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.697  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.697  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.717  3759  3759 E Zygote  : MountEmulatedStorage()
03-17 13:26:08.717  3759  3759 E Zygote  : v2
03-17 13:26:08.717  3759  3759 I libpersona: KNOX_SDCARD checking this for 10135
03-17 13:26:08.717  3759  3759 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.717  3759  3759 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:08.717  1021  1033 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3759 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-17 13:26:08.727  3759  3759 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:08.727  3759  3759 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:08.727  1021  1033 I ActivityManager: Killing 1599:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-17 13:26:08.747  3749  3749 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.757  3749  3749 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.757  3759  3759 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.757  3759  3759 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.797  3728  3728 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 13:26:08 GMT+01:00 2016
,03-17 13:26:08.797  1021  1377 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.797  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.797  1021  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:08.797  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 13:26:08.817  3728  3728 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 13:26:08.817  1894  3713 D FileApkUtils: Spent 40ms computing apk sha1.
,03-17 13:26:08.817  1894  3713 D FileApkUtils: Module already staged or being staged:chimera-modules/MapsModule.apk
,03-17 13:26:08.817  1894  3713 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,03-17 13:26:08.817  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.817  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.817  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.817  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.827  1894  3713 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
03-17 13:26:08.827  1894  3713 D DexOptUtils: Lollipop platform, using <isa> directory.
,03-17 13:26:08.827  1894  3713 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-17 13:26:08.827  1894  3713 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-17 13:26:08.837  3728  3728 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 13:26:08.837  3728  3728 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 13:26:08.837  3781  3781 E Zygote  : MountEmulatedStorage()
,03-17 13:26:08.847  3781  3781 E Zygote  : v2
03-17 13:26:08.847  3781  3781 I libpersona: KNOX_SDCARD checking this for 10022
03-17 13:26:08.847  3781  3781 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.847  3781  3781 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:08.847  3781  3781 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:08.847  1021  3138 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3781 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
03-17 13:26:08.847  3781  3781 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:08.847  3759  3759 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:08.847  3759  3759 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:08.847  3759  3759 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:08.877  3781  3781 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.877  3781  3781 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.887  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3060/cgroup.procs: No such file or directory
03-17 13:26:08.887  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2998/cgroup.procs: No such file or directory
,03-17 13:26:08.897  3728  3728 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 13:26:08.907  3783  3783 I dex2oat : ----------------------------------------------------
03-17 13:26:08.907  3783  3783 I dex2oat : <SS>: S T A R T I N G . . .
03-17 13:26:08.907  3783  3783 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 13:26:08.907  3783  3783 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=94 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 13:26:08.917  3728  3780 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 13:26:08.917  3675  3675 I RlzPingService: Setting next ping for 1458822368932
,03-17 13:26:08.937  3728  3780 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
,03-17 13:26:08.957  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.957  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.957  1021  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.957  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:08.987  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.987  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.987  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.987  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.027  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3026/cgroup.procs: No such file or directory
,03-17 13:26:09.037  1021  1045 W libprocessgroup: failed to open /acct/uid_10072/pid_1599/cgroup.procs: No such file or directory
,03-17 13:26:09.037  1021  1133 I ActivityManager: Killing 3099:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,03-17 13:26:09.047  3749  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:09.057  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.057  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.057  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.057  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.057  3728  3728 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 13:26:09.077  3805  3805 E Zygote  : MountEmulatedStorage(),
03-17 13:26:09.077  3805  3805 E Zygote  : v2
03-17 13:26:09.077  3805  3805 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:09.077  3805  3805 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:09.077  3805  3805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 13:26:09.077  3805  3805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:09.077  1021  1133 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3805 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:09.077  1021  1133 I ActivityManager: Killing 3120:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-17 13:26:09.077  3805  3805 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:09.077  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.077  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.077  1021  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:09.077  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 13:26:09.087  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.087  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.087  1021  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.087  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.097  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.097  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.097  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.097  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.107  3438  3697 D jxcore_app_log: JniHelper::setJavaVM(0xb82a6450), pthread_self() = -1199726352
,03-17 13:26:09.117  3821  3821 E Zygote  : MountEmulatedStorage(),
03-17 13:26:09.117  3821  3821 E Zygote  : v2
03-17 13:26:09.117  3821  3821 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:09.117  3821  3821 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:09.117  3821  3821 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:09.117  3821  3821 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 13:26:09.117  3821  3821 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:09.117  3438  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 13:26:09.117  3438  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 13:26:09.117  3438  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 13:26:09.117  3438  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
,03-17 13:26:09.117  3438  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 13:26:09.117  3438  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf1f058 added. We now have 1 listener(s)
03-17 13:26:09.117  1021  1133 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3821 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:09.117  3805  3805 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:09.117  3805  3805 D ActivityThread: Added TimaKeyStore provider,
03-17 13:26:09.117  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
03-17 13:26:09.127  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.127  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.127  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:09.127  3438  3697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:51:18:22
,03-17 13:26:09.127  3438  3697 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
,03-17 13:26:09.137  3438  3697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
03-17 13:26:09.137  3438  3697 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 13:26:09.137  3438  3697 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 13:26:09.137  1021  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:51:18:22
03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 13:26:09.147  3438  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@158bb617 added. We now have 1 listener(s)
,03-17 13:26:09.147  3438  3697 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 13:26:09.147  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.157  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.157  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.157  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.167  1021  1517 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.167  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.167  1021  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.167  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.167  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.177  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.177  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.177  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.177  1313  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:09.177  3821  3821 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:09.187  1894  3800 D GCM     : COMPAT: Multi user not supported
03-17 13:26:09.187  3821  3821 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:09.187  1021  3140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
03-17 13:26:09.187  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.187  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.187  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:09.187  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
03-17 13:26:09.187  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.197  3438  3697 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-17 13:26:09.197  1021  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.197  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:09.197  1690  3845 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
03-17 13:26:09.207  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
03-17 13:26:09.207  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.207  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.207  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:09.207  3805  3805 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
03-17 13:26:09.217  3438  3697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-17 13:26:09.217  3438  3697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-17 13:26:09.227  3438  3697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 13:26:09.227  3438  3697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-17 13:26:09.227  1021  1305 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 13:26:09.227  1021  1305 D SecContentProvider2: mCursor = null
,03-17 13:26:09.237  1021  3141 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.237  1021  3141 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
03-17 13:26:09.237  1021  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:09.237  1021  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 13:26:09.257  3438  3697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 13:26:09.257  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 13:26:09.257  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:09.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:09.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:09.267  1021  1305 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 13:26:09.267  1021  1305 D SecContentProvider2: mCursor = null
03-17 13:26:09.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:09.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:09.267  3805  3805 V MTPRx   : sealedState: false
03-17 13:26:09.267  3805  3805 V MTPRx   : sealedUsbMassStorageState: false
,03-17 13:26:09.267   289   289 E SMD     : DCD OFF
,03-17 13:26:09.267  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3120/cgroup.procs: No such file or directory
,03-17 13:26:09.267  3438  3697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:51:18:22
,03-17 13:26:09.267  1021  1045 W libprocessgroup: failed to open /acct/uid_10150/pid_3099/cgroup.procs: No such file or directory
,03-17 13:26:09.277  1894  3853 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 13:26:09.307  1894  3855 I CheckinService: Checking schedule, now: 1458217569327 next: 1458225725438
,03-17 13:26:09.317  1894  3855 I CheckinService: active receiver: disabled
,03-17 13:26:09.327  1021  1497 D SettingsProvider: name = mtp_usb_connection_status
,03-17 13:26:09.337  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.347  3438  3697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 13:26:09.347  3438  3697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 13:26:09.347  3438  3697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 13:26:09.347  3438  3697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 13:26:09.347  3438  3697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 13:26:09.347  3438  3697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 13:26:09.347  3438  3697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 13:26:09.347  3438  3697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 13:26:09.347  3438  3697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 13:26:09.347  3438  3697 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 13:26:09.347  1021  1391 D SettingsProvider: name = media_player_mode
,03-17 13:26:09.357  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.357  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.357  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.357  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 13:26:09.377  1021  1391 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:09.397  1021  1133 D SettingsProvider: name = mtp_running_status
,03-17 13:26:09.397  1021  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.397  1021  1497 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.397  1021  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:09.397  1021  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 13:26:09.397  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:09.397  1021  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.407  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:09.417  3821  3821 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-17 13:26:09.417  3438  3438 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 13:26:09.427  1021  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.427  1021  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.427  1021  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.437  1021  1391 D SettingsProvider: name = media_mount_count
,03-17 13:26:09.447  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.447  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.447  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 13:26:09.447  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.447  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.447  3438  3438 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 13:26:09.447  3438  3438 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 13:26:09.447  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:09.457  1021  1033 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3860 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 13:26:09.467  1021  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:09.467  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.467  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.467  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.467  3860  3860 E Zygote  : MountEmulatedStorage()
03-17 13:26:09.467  3860  3860 E Zygote  : v2
03-17 13:26:09.467  3860  3860 I libpersona: KNOX_SDCARD checking this for 10042
03-17 13:26:09.467  1021  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 13:26:09.467  3860  3860 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:09.467  1021  1305 D SettingsProvider: name = mtp_sync_alive
,03-17 13:26:09.467  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:09.467  3860  3860 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:09.467  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.467  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.467  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.477  1894  3800 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}],
03-17 13:26:09.477  1021  1517 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.487  3860  3860 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:09.487  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:09.487  3860  3860 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,03-17 13:26:09.487  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.487  1021  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.487  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.507  1021  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.507  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.507  1021  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.507  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.517  1894  1894 D SystemUpdateService: onCreate
,03-17 13:26:09.557  1894  1894 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 13:26:09.567  1021  1377 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:09.567  3860  3860 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:09.577  3860  3860 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:09.577  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.577  1021  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.577  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.577  1690  1690 I ConfigService: onCreate
,03-17 13:26:09.597  2692  2763 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 13:26:09.607  1894  1894 I ConfigFetchService: onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,03-17 13:26:09.607  1021  1377 D SettingsProvider: name = sdcard_launch
,03-17 13:26:09.607  1021  3138 D SettingsProvider: name = boot_time_connected
,03-17 13:26:09.617  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.617  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.627  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.627  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.647  1021  1306 I art     : Explicit concurrent mark sweep GC freed 24304(1266KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 2.921ms total 356.488ms
,03-17 13:26:09.647  1021  1377 D SettingsProvider: name = mtp_open_session
,03-17 13:26:09.647  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:09.657  1894  3883 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 13:26:09.657  1894  3883 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-17 13:26:09.687  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:09.697  3887  3887 E Zygote  : MountEmulatedStorage()
03-17 13:26:09.697  3887  3887 E Zygote  : v2
03-17 13:26:09.697  3887  3887 I libpersona: KNOX_SDCARD checking this for 10139
03-17 13:26:09.697  3887  3887 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:09.697  3887  3887 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:09.707  3887  3887 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:09.707  3887  3887 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:09.707  1021  1034 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3887 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-17 13:26:09.707  3860  3860 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 13:26:09.717  1021  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:09.717  1021  1497 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.717  1021  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:09.717  1021  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.717  1021  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.727  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.727  1021  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.727  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.747  3438  3451 I art     : Background sticky concurrent mark sweep GC freed 26863(1877KB) AllocSpace objects, 10(174KB) LOS objects, 7% free, 10MB/11MB, paused 1.479ms total 190.859ms
,03-17 13:26:09.757  1894  3883 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 13:26:09.777  3887  3887 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:09.777  3887  3887 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:09.797  1894  1894 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-17 13:26:09.847  3484  3484 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 13:26:09.847  3484  3484 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:26:09.847  3484  3484 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:26:09.847  3484  3484 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-17 13:26:09.847  3484  3484 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 13:26:09.847  3484  3484 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 13:26:09.847  1894  1894 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-17 13:26:09.867  1894  3883 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,03-17 13:26:09.867  1894  1894 I ConfigFetchService: service connected
,03-17 13:26:09.887  1894  3883 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,03-17 13:26:09.907  1021  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.907  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.907  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.907  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.907  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.907  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.907  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.907  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.927  1021  1732 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3912 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 13:26:09.937  3912  3912 E Zygote  : MountEmulatedStorage()
03-17 13:26:09.937  3912  3912 I libpersona: KNOX_SDCARD checking this for 10104
03-17 13:26:09.937  3912  3912 E Zygote  : v2
03-17 13:26:09.937  3912  3912 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:09.937  3912  3912 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:09.937  3912  3912 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:09.937  3912  3912 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:09.957   309   309 I art     : Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 754us total 30.172ms
,03-17 13:26:09.967  1894  1894 D ConfigFetchService: ConfigApi connection successful.
,03-17 13:26:09.977   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 21.964ms,
,03-17 13:26:09.987  3912  3912 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 13:26:09.987  3912  3912 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:09.997   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 18.874ms,
,03-17 13:26:10.067  1690  2781 I art     : Explicit concurrent mark sweep GC freed 7567(421KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 10MB/17MB, paused 1.015ms total 69.319ms
,03-17 13:26:10.117  1021  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 13:26:10.117  1021  1497 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.117  1021  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:10.117  1021  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:10.117  3484  3484 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 13:26:10.127  3887  3887 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-17 13:26:10.127  3887  3887 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:10.127  3887  3887 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 13:26:10.127  3887  3887 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 13:26:10.127  3887  3887 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:10.187  1894  3883 I art     : Explicit concurrent mark sweep GC freed 35531(2MB) AllocSpace objects, 40(640KB) LOS objects, 40% free, 11MB/19MB, paused 1.609ms total 203.411ms
,03-17 13:26:10.257  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:10.257  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:10.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:10.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:10.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:10.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:10.257  1744  1744 I GCoreUlr: DispatchingService.onCreate()
,03-17 13:26:10.307  1894  3883 I AuthZen : Fetching signing key...
,03-17 13:26:10.337  1021  3141 D TimaService: TIMA: in getTimaVersion
,03-17 13:26:10.337  1021  1377 D TimaService: TIMA3: KeyStore3_init
,03-17 13:26:10.337  1021  1377 D TimaService: TIMA: in getTimaVersion
03-17 13:26:10.337  1021  1377 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
03-17 13:26:10.337  1021  1377 I TLC_TZ_KEYSTORE: : creating new keystore context...
,03-17 13:26:10.337  1021  1377 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-17 13:26:10.337  1021  1377 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
03-17 13:26:10.337  1021  1377 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
03-17 13:26:10.337  1021  1377 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,03-17 13:26:10.337  1021  1377 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
03-17 13:26:10.337  1021  1377 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-17 13:26:10.337  1021  1377 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-17 13:26:10.337  1021  1377 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
,03-17 13:26:10.337  1021  1377 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
03-17 13:26:10.337  1021  1377 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 13:26:10.347  2645  2645 D FactoryTestApp: [DummyFtClient$onDestroy](2645) Destroy DummyFtClient service
,03-17 13:26:10.357  2645  2645 D FactoryTestApp: [Support$Values.getString](2645) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 13:26:10.357  2645  2645 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2645) mConnectionMode = gsm
03-17 13:26:10.357  2645  2645 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2645) RUNNING_FTCLIENT : false
03-17 13:26:10.357  2645  2645 D FactoryTestApp: [DummyFtClient$onDestroy](2645) kill process
,03-17 13:26:10.367  2645  2645 I Process : Sending signal. PID: 2645 SIG: 9
,03-17 13:26:10.367  1021  1377 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 13:26:10.377  1021  1377 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
,03-17 13:26:10.377  1021  1377 I TLC_TZ_KEYSTORE: : ctx = 0xb8bedaa0, comm = 0xb8b37340, sendmsg = 0xa144e000, recvmsg = 0xa144e440
,03-17 13:26:10.377  1021  1377 I TZ_init: : TZ_init: sending initialization request...
,03-17 13:26:10.377  1894  3883 I AuthZen : Signing key fetched successfully!
,03-17 13:26:10.377  1021  1377 E TZ_init: : TZ_init Process: Secure memory is not initialized!
,03-17 13:26:10.377  1894  3859 I EventLogService: Aggregate from 1458215042353 (log), 1458215042353 (data)
,03-17 13:26:10.377  1021  1045 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,03-17 13:26:10.387  1021  1377 E TZ_init: : trustlet initialization failed
03-17 13:26:10.387  1021  1377 I TZ_init: : TZ_init_START...
,03-17 13:26:10.387  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 13:26:10.387  1021  1377 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-17 13:26:10.387  1021  1377 I TZ_init: : TZ_init: successful initialization
03-17 13:26:10.387  1021  1377 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 13:26:10.387  1021  1377 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-17 13:26:10.387  1021  1377 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-17 13:26:10.407  3912  3912 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:10.407  1894  3883 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 13:26:10.417  1894  3883 I AuthZen : Starting Enrollment...
,03-17 13:26:10.427  3860  3860 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-17 13:26:10.437  3228  3324 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:10.497  1021  3141 I ActivityManager: Process com.sec.factory (pid 2645)(adj 0) has died(35,1117)
,03-17 13:26:10.497  3484  3484 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 13:26:10.587  3438  3858 W jxcore-log: Initializing JXcore engine
03-17 13:26:10.587  3438  3858 W jxcore-log: JXcore engine is ready
,03-17 13:26:10.617  3484  3484 I ReactiveServiceManager: Supported : 1
,03-17 13:26:10.627  1021  1305 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 13:26:10.627  1021  1305 D QSEECOMAPI: : App is not loaded in QSEE
03-17 13:26:10.627  1021  1306 I ActivityManager: Killing 2097:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,03-17 13:26:10.647  1021  1305 D QSEECOMAPI: : Loaded image: APP id = 10
,03-17 13:26:10.657  1021  1305 D QSEECOMAPI: : QSEECom_dealloc_memory 
,03-17 13:26:10.657  1021  1305 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-17 13:26:10.657  1021  1305 E terrier : handleString: Failed to handle string(-4)
03-17 13:26:10.657  1021  1305 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-17 13:26:10.677  1888  1888 E audit   : type=1400 msg=audit(1458217570.677:205): avc:  denied  { ioctl } for  pid=3858 comm="Thread-474" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-17 13:26:10.677  1888  1888 E audit   :  SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:10.677  1888  1888 E audit   : type=1300 msg=audit(1458217570.677:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9adae8f8 items=0 ppid=309 ppcomm=main pid=3858 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-474" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 13:26:10.677  1888  1888 E audit   : type=1320 msg=audit(1458217570.677:205): 
,03-17 13:26:10.677  3484  3484 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
,03-17 13:26:10.677  3484  3484 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 13:26:10.687  3438  3858 W jxcore-log: Starting JXcore engine
,03-17 13:26:10.697  3484  3484 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 13:26:10.697  3484  3484 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:26:10.697  3484  3484 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:26:10.697  3484  3484 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 13:26:10.797  1744  1744 I art     : Explicit concurrent mark sweep GC freed 12847(796KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 10MB/17MB, paused 1.135ms total 86.035ms
,03-17 13:26:10.797  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.797  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.797  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.797  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.817  3937  3937 E Zygote  : MountEmulatedStorage()
,03-17 13:26:10.817  3937  3937 I libpersona: KNOX_SDCARD checking this for 10145
03-17 13:26:10.817  3937  3937 E Zygote  : v2
03-17 13:26:10.817  3937  3937 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:10.817  3937  3937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:10.827  3937  3937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:10.827  3937  3937 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.827  1021  1732 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3937 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 13:26:10.837  1894  3883 D AuthZen : getting auth token. Attempt 0
,03-17 13:26:10.837  3438  3858 W jxcore-log: Platform android
03-17 13:26:10.837  3438  3858 W jxcore-log: 
03-17 13:26:10.837  3438  3858 W jxcore-log: Process ARCH arm
03-17 13:26:10.837  3438  3858 W jxcore-log: 
,03-17 13:26:10.847  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.847  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.847  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.847  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.857  1021  1732 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3946 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,03-17 13:26:10.857  1021  1732 I ActivityManager: Killing 3043:com.google.android.configupdater/u0a86 (adj 15): empty #31
,03-17 13:26:10.857  3946  3946 E Zygote  : MountEmulatedStorage()
03-17 13:26:10.857  3946  3946 I libpersona: KNOX_SDCARD checking this for 10031
03-17 13:26:10.857  3946  3946 E Zygote  : v2
03-17 13:26:10.857  3946  3946 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:10.857  3946  3946 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:10.867  3946  3946 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:10.867  3946  3946 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:10.867  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 13:26:10.867  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:10.867  1021  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:10.867  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:10.897  3783  3783 I dex2oat : dex2oat took 1.989s (threads: 4)
,03-17 13:26:10.907  1894  3713 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
03-17 13:26:10.907  1894  3713 D DexOptUtils: Set odex to world readable.
,03-17 13:26:10.917  1894  3713 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
,03-17 13:26:10.917  1894  3713 D FileApkUtils: Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc,
,03-17 13:26:10.927  3228  3324 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 13:26:10.947  3946  3946 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.957  3946  3946 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.957  1894  3713 D GmsModuleFndr: Beginning GMS chimera module scan
,03-17 13:26:10.957  3937  3937 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.957  3937  3937 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.957  1894  3713 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
03-17 13:26:10.957  1894  3713 D ChimeraCfgMgr: Beginning module configuration check
,03-17 13:26:10.967  1894  3713 D ChimeraCfgMgr: Module APKs unchanged, check complete
,03-17 13:26:10.967  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-17 13:26:10.967  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:10.967  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:10.967  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 13:26:10.967  3749  3834 I AMMetaDataParserService: Resource data:2131165186
,03-17 13:26:10.977  3821  3821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,03-17 13:26:10.977  3749  3834 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:10.987  3749  3834 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:10.987  3749  3834 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 13:26:10.987  3749  3834 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:10.987  3749  3834 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-17 13:26:10.987  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:10.987  1021  1732 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:10.997  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.997  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:10.997  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:10.997  3749  3834 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-17 13:26:10.997  1894  3879 I SystemUpdateService: cancelUpdate (empty URL)
03-17 13:26:10.997  1894  3879 I SystemUpdateService: active receiver: disabled
,03-17 13:26:11.007  1021  3141 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.007  1021  3141 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.007  1021  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:11.017  1021  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-17 13:26:11.017  3749  3834 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-17 13:26:11.047  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.047  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.047  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.047  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.047  3749  3834 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,03-17 13:26:11.057  3946  3946 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 13:26:11.057  3972  3972 E Zygote  : MountEmulatedStorage()
,03-17 13:26:11.057  3972  3972 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:11.057  3972  3972 E Zygote  : v2
03-17 13:26:11.057  3972  3972 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:11.057  1021  1391 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3972 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:11.067  3972  3972 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:11.067  3972  3972 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:11.067  1690  1807 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,03-17 13:26:11.067  1690  1807 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:26:11.067  3972  3972 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.067  1690  1807 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:26:11.067  1690  1807 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:26:11.077  1690  1807 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 13:26:11.077  3937  3937 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:11.077  3937  3937 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:11.077  3937  3937 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:11.077  3937  3937 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:11.077  3937  3937 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 13:26:11.077  3749  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.,SelectBookmarkFolderActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
,03-17 13:26:11.077  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
03-17 13:26:11.077  3228  3324 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 13:26:11.087  1021  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.097  3228  3324 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 13:26:11.097  3228  3324 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 13:26:11.107  1021  3138 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1196 (0x0)
,03-17 13:26:11.107  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.107  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:11.107  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:11.117  3972  3972 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.117  3972  3972 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.137  3228  3324 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 13:26:11.147  3228  3324 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 13:26:11.147  3438  3858 I jxcore-log: JXcore Cordova bridge is ready!
03-17 13:26:11.147  3438  3858 I jxcore-log: 
03-17 13:26:11.147  3228  3324 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 13:26:11.147  3438  3858 W jxcore-log: JXcore engine is started
,03-17 13:26:11.147  3438  3697 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 13:26:11.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-17 13:26:11.157  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:11.157  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:11.157  3749  3834 I AMMetaDataParserService: Resource data:2131034113
,03-17 13:26:11.167  3749  3834 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:11.167  3749  3834 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:11.167  3749  3834 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:11.167  3749  3834 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 13:26:11.167  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:11.167  1021  1045 W libprocessgroup: failed to open /acct/uid_10012/pid_2097/cgroup.procs: No such file or directory
,03-17 13:26:11.167  1021  1045 W libprocessgroup: failed to open /acct/uid_10086/pid_3043/cgroup.procs: No such file or directory
,03-17 13:26:11.167  3438  3858 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 13:26:11.167  3438  3858 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 13:26:11.177  3438  3438 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-17 13:26:11.187  1021  1377 D FocusedStackFrame: Set to : 0
,03-17 13:26:11.187  1021  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 13:26:11.187  1021  1377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-17 13:26:11.197  1021  1377 D InputDispatcher: Focused application set to: xxxx
,03-17 13:26:11.197  1021  1377 D InputDispatcher: Focus left window: 3438
,03-17 13:26:11.207  3972  3972 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 13:26:11.207  1021  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:11.207  1021  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:11.207   258  1106 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (169 us)
,03-17 13:26:11.217  3972  3972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:11.237  1021  1498 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:11.237  3438  3697 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 57ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 13:26:11.247  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.247  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.247  1021  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:11.247  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 13:26:11.247  1021  1732 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:11.247  1021  1732 W ActivityManager: mDVFSHelper.acquire()
,03-17 13:26:11.257  1021  1732 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:11.257  1021  1732 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 13:26:11.257  1021  1732 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 13:26:11.257  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 13:26:11.257  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:11.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:11.257  3972  3972 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 13:26:11.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:11.257  3972  3972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
03-17 13:26:11.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:11.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:11.267  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:11.277  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.277  1021  1498 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:11.277  3749  3834 I GFX construct_block_size_descriptor_2d second part: took 3.169634ms for 0*0 texture 0
,03-17 13:26:11.277  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.277  1021  1306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:11.277  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 13:26:11.277  1501  1501 D Launcher: onRestart, Launcher: 821365854
,03-17 13:26:11.287  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.287  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.287  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.287  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.287  3749  3834 I GFX generate_partition_tables: took 7.390836ms for 0*0 texture 0
,03-17 13:26:11.287  3749  3834 I GFX raster: took 12.216667ms for 96*96 texture 0,
03-17 13:26:11.287  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8671e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8678968 counterpartCT=4 counterpartW=96 counterparth=96,
,03-17 13:26:11.297  3749  3834 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 13:26:11.297  3994  3994 E Zygote  : MountEmulatedStorage()
,03-17 13:26:11.307  3994  3994 E Zygote  : v2
,03-17 13:26:11.307  3994  3994 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:11.307  3994  3994 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.307  3994  3994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:11.317  1021  1497 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3994 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:11.317  1021  1496 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:11.317  3994  3994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:11.317  3994  3994 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.317  1501  1501 D Launcher: onStart, Launcher: 821365854
03-17 13:26:11.317  1501  1501 D Launcher.HomeView: onStart
03-17 13:26:11.317  1501  1501 D Launcher: onResume, Launcher: 821365854
,03-17 13:26:11.317  1021  3141 D SettingsProvider: name = kids_home_mode
03-17 13:26:11.317  1021  3141 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:11.317  1021  3141 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:11.317  1021  3141 D SettingsProvider: selectionArgs: false
03-17 13:26:11.317  1021  3141 D SettingsProvider: selectionArgs: 10007
03-17 13:26:11.317  1021  3141 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:11.317  1021  3141 D SettingsProvider: ret = -1
,03-17 13:26:11.317  1501  1501 D Launcher.HomeView: onResume
,03-17 13:26:11.327  1021  1034 D RCPManagerService: exchangeData() failure , invalid userId
03-17 13:26:11.327  1894  1894 D SystemUpdateService: onDestroy
,03-17 13:26:11.327  1021  1021 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 13:26:11.327  1021  1021 D SensorService: [SO] activate (ident=0xb8755570, enabled=0)
,03-17 13:26:11.327  1021  1021 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 13:26:11.337  3972  3972 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-17 13:26:11.337  3972  3972 I F_PHONE : default registerAction()
03-17 13:26:11.337  3972  3972 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 13:26:11.337  1021  1021 D SensorManager: unregisterListener ::   
03-17 13:26:11.337  1021  1021 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
03-17 13:26:11.337  1021  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:11.347  1894  3883 E AuthZen : Error getting auth token
03-17 13:26:11.347  1894  3883 E AuthZen : com.google.android.gms.auth.ad: BadAuthentication
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:318)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:11.347  1894  3883 E AuthZen : Failed to do enrollment for account: thalitester@gmail.com
03-17 13:26:11.347  1894  3883 E AuthZen : com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:11.347  1894  3883 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 13:26:11.347  1021  1021 D SensorService: [SO] changed settle time [0]
03-17 13:26:11.347  1021  1021 D SensorService: [SO] setDelay [200000000]
03-17 13:26:11.347  1021  1021 D SensorService: [SO] activate (ident=0xb8755570, enabled=1)
03-17 13:26:11.347  1021  1021 D SensorService: [SO] AR_init
03-17 13:26:11.347  1021  1021 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 13:26:11.347  1501  1501 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 13:26:11.347  1021  1021 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-17 13:26:11.357  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.357  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:11.357  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:11.357  1744  3930 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-17 13:26:11.357  3994  3994 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:11.357  1501  1501 D MenuAppsGridFragment: onResume
,03-17 13:26:11.357  3994  3994 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.357  1021  1133 D ActivityManager: handle home activity for 0
03-17 13:26:11.357  1021  1133 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 13:26:11.357  1021  1021 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 13:26:11.357  1021  1133 D KnoxTimeoutHandler: post home show event for user 0
03-17 13:26:11.357  1021  1133 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 13:26:11.357  1021  1021 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 13:26:11.357  1021  1133 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 13:26:11.357  1021  1021 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 13:26:11.357  1021  1133 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 13:26:11.357  1021  1021 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 13:26:11.357   258   258 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-17 13:26:11.367  1021  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:26:11.367  1021  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:26:11.367  1021  1496 D InputDispatcher: Focus entered window: 1501
,03-17 13:26:11.367  1021  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:11.367  1021  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 13:26:11.367  1501  1501 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 13:26:11.387  1501  1501 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 13:26:11.387  1021  1034 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 13:26:11.387  1021  4014 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:11.387  1196  1196 I StatusBar: Icon Only
,03-17 13:26:11.387  1196  1196 D PanelView: There is/are notification(s) 
,03-17 13:26:11.387  3438  3438 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 13:26:11.387  3994  3994 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 13:26:11.397  1809  1809 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 13:26:11.407  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 13:26:11.417  3994  3994 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-17 13:26:11.417  3994  3994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:11.417  1021  3138 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.417  1021  3138 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.417  1021  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:11.417  1021  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-17 13:26:11.447  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.447  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.447  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.447  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.447  1501  1501 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@21f2d84d time:42409
,03-17 13:26:11.457  1475  1475 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 13:26:11.457  1475  1475 D BluetoothBDTestService: onCreate()
03-17 13:26:11.457  1475  1475 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-17 13:26:11.457  1475  1475 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-17 13:26:11.457  1475  1475 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-17 13:26:11.457  4018  4018 E Zygote  : MountEmulatedStorage()
03-17 13:26:11.457  4018  4018 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:11.457  4018  4018 E Zygote  : v2
03-17 13:26:11.457  4018  4018 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.467  4018  4018 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:11.467  4018  4018 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:11.467  4018  4018 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.467  1021  1052 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:11.477  1021  1377 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4018 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:11.477  1021  1391 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:11.487  1021  3138 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:11.487  1021  1517 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.497  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.497  1021  1517 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:11.497  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-17 13:26:11.497  4018  4018 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.507  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.507  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.507  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.507  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.507  4018  4018 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.527  4037  4037 E Zygote  : MountEmulatedStorage()
03-17 13:26:11.527  4037  4037 I libpersona: KNOX_SDCARD checking this for 10072
03-17 13:26:11.527  4037  4037 E Zygote  : v2
03-17 13:26:11.527  4037  4037 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.527  1021  1306 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4037 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,03-17 13:26:11.547  1021  1043 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 13:26:11.547  1021  1052 I ActivityManager: Displayed Component not be shown by security: +294ms
,03-17 13:26:11.557  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.557  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.557  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.557  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.557  1894  3883 D a       : Opening database auth.proximity.permit_store...
,03-17 13:26:11.567  4018  4018 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:11.577  4049  4049 E Zygote  : MountEmulatedStorage(),
03-17 13:26:11.577  4049  4049 I libpersona: KNOX_SDCARD checking this for 10146
03-17 13:26:11.577  4049  4049 E Zygote  : v2
03-17 13:26:11.577  4049  4049 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.577  1021  1732 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4049 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 13:26:11.577  1021  1732 I ActivityManager: Killing 1902:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-17 13:26:11.587  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.597  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.597  1021  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:11.597  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 13:26:11.627  1021  3140 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 13:26:11.637  4037  4037 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 13:26:11.637  4037  4037 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:11.637  1021  1377 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:11.637  4037  4037 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.637  1894  3883 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files,
03-17 13:26:11.637  1894  3883 D AuthZenTransactionCache: Clearing transaction cache
03-17 13:26:11.647  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.647  1021  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:11.647  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:11.647  4049  4049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 13:26:11.647  4049  4049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:11.657  4049  4049 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.657  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:11.657  3749  3834 I GFX raster: took 0.846875ms for 96*96 texture 0
03-17 13:26:11.657  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8671e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8680ad0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:11.677  4018  4018 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 13:26:11.677  4018  4018 I KnoxUsageLogPro: premStatus:2
,03-17 13:26:11.677  4018  4018 I KnoxUsageLogPro: isEulaShown : false
03-17 13:26:11.677  4018  4018 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 13:26:11.677  4018  4065 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458217571697
,03-17 13:26:11.687  1021  1033 I ActivityManager: Killing 3150:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-17 13:26:11.687  4049  4049 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.687  4049  4049 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.687  3749  3834 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 13:26:11.687  1021  3140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:11.697  4037  4037 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.697  4037  4037 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.697  1021  1045 W libprocessgroup: failed to open /acct/uid_10004/pid_1902/cgroup.procs: No such file or directory
,03-17 13:26:11.707  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.707  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:11.707  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:11.727  1021  1517 I ActivityManager: Killing 3198:com.sec.factory.camera/1000 (adj 15): empty #31
,03-17 13:26:11.727  4049  4049 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:11.737  3946  3946 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,03-17 13:26:11.747  1021  1043 D SensorService: [SO] currT = 42701177000, prevT = 42251100000, diff = 450077000, [0.172 0.421 10.247]
,03-17 13:26:11.747  1021  1043 D SensorService: [SO] 0.172 0.421 10.247
,03-17 13:26:11.747  1021  1043 D SensorService: [SO] [100 -> 255]
,03-17 13:26:11.747  1021  1046 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:11.747  1021  1046 W ActivityManager: mDVFSHelper.release()
,03-17 13:26:11.747  1021  1046 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:11.767  4037  4037 D BadgeProvider: onCreate
,03-17 13:26:11.767  4037  4037 D BadgeProvider: DatabaseHelper
,03-17 13:26:11.787  4037  4076 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 13:26:11.787  1021  1045 W libprocessgroup: failed to open /acct/uid_10094/pid_3150/cgroup.procs: No such file or directory
,03-17 13:26:11.787  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3198/cgroup.procs: No such file or directory
,03-17 13:26:11.787  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.797  1021  1305 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 13:26:11.797  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.797  1021  1517 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.807  4037  4076 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 13:26:11.807  4037  4076 D BadgeProvider: sendNotify, [notify] : null
03-17 13:26:11.807  4037  4076 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 13:26:11.807  4037  4076 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 13:26:11.807  4037  4076 D BadgeProvider: update, [UpdateCount] : 1
03-17 13:26:11.807  1501  1501 D Launcher.Model: reloadBadges entered.
,03-17 13:26:11.847  1021  1306 I ActivityManager: Killing 3228:com.policydm/1000 (adj 15): empty #31
,03-17 13:26:11.887  1021  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.887  1021  1497 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 13:26:11.887  1021  3138 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.887  3946  3946 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,03-17 13:26:11.887  1021  3140 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.887  1021  1391 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-17 13:26:11.887  3937  4043 I Process : Sending signal. PID: 3937 SIG: 9
,03-17 13:26:11.907  1021  1033 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:11.917  1021  1517 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.917  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.917  1021  1517 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:11.917  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange,
,03-17 13:26:11.927  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3228/cgroup.procs: No such file or directory
,03-17 13:26:11.927  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.927  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.927  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.927  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.937  4018  4065 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 42639
,03-17 13:26:11.947  4083  4083 E Zygote  : MountEmulatedStorage(),
03-17 13:26:11.947  4083  4083 E Zygote  : v2
03-17 13:26:11.947  4083  4083 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 13:26:11.947  4083  4083 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.957  1021  1391 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4083 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:11.957  4083  4083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:11.957  4083  4083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:11.957  4083  4083 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.967  1021  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2aca99c0 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:42923
,03-17 13:26:11.967   258  3721 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
03-17 13:26:11.967   258  1106 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 13:26:11.967  1021  1046 I ActivityManager: Killing 3239:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,03-17 13:26:11.977   255   255 E lowmemorykiller: Error writing /proc/3937/oom_score_adj; errno=22
03-17 13:26:11.977  1021  1517 I ActivityManager: Killing 3264:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,03-17 13:26:11.997  1021  1497 I ActivityManager: Process com.android.email (pid 3937)(adj 13) has died(46,1092)
,03-17 13:26:11.997  4083  4083 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.997  4083  4083 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.007  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.007  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.007  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.007  1021  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.007  1021  1034 W SEAMService:  hashset_to_int_array returning null
,03-17 13:26:12.017  4101  4101 E Zygote  : MountEmulatedStorage(),
03-17 13:26:12.017  4101  4101 E Zygote  : v2
03-17 13:26:12.017  4101  4101 I libpersona: KNOX_SDCARD checking this for 10145
,03-17 13:26:12.017  4101  4101 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:12.027  1021  3138 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4101 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
03-17 13:26:12.027  4101  4101 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:12.027  4101  4101 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:12.027  4101  4101 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:12.027  1021  1498 W SEAMService:  hashset_to_int_array returning null
,03-17 13:26:12.037  3821  3821 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id)
,03-17 13:26:12.037  3821  3821 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
,03-17 13:26:12.057  1021  1021 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:12.057  1021  1498 W SEAMService:  hashset_to_int_array returning null
,03-17 13:26:12.067  1021  1045 W libprocessgroup: failed to open /acct/uid_10003/pid_3239/cgroup.procs: No such file or directory
,03-17 13:26:12.067  4101  4101 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.067  1021  1045 W libprocessgroup: failed to open /acct/uid_10100/pid_3264/cgroup.procs: No such file or directory
03-17 13:26:12.067  4101  4101 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.077  3438  3438 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1e419bed that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:12.077  3438  3438 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1e419bed that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:12.077  3438  3438 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:12.077  1021  1034 I ActivityManager: Killing 3280:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,03-17 13:26:12.087  3438  3438 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2ac1ba04 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:12.087  3438  3438 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2ac1ba04 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:12.087  3438  3438 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:12.087  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.097  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.097  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.097  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.107  4101  4101 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
03-17 13:26:12.107  4101  4101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:12.107  4101  4101 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:12.107  4101  4101 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:12.107  4101  4101 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 13:26:12.107  4122  4122 E Zygote  : MountEmulatedStorage()
03-17 13:26:12.107  4122  4122 E Zygote  : v2
03-17 13:26:12.107  4122  4122 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:12.107  4122  4122 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:12.107  4122  4122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:12.107  1021  1305 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4122 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:12.107  1021  1305 I ActivityManager: Killing 3299:com.samsung.helphub/1000 (adj 15): empty #31
,03-17 13:26:12.117  4122  4122 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:12.117  4122  4122 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:12.137  4122  4122 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.137  4122  4122 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.147  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.147  3749  3834 I GFX construct_block_size_descriptor_2d second part: took 2.682448ms for 0*0 texture 0
,03-17 13:26:12.157  3749  3834 I GFX generate_partition_tables: took 7.837708ms for 0*0 texture 0
,03-17 13:26:12.157  3749  3834 I GFX raster: took 11.578958ms for 96*96 texture 0
03-17 13:26:12.157  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867d3d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867d498 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.167  3946  3946 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 13:26:12.167  3946  3946 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 13:26:12.177  3912  4137 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,03-17 13:26:12.177  3912  4137 I Babel_SMS: MmsConfig.loadMmsSettings
,03-17 13:26:12.177  3912  4137 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,03-17 13:26:12.177  3946  3946 D DialogFlow: initQueue()
,03-17 13:26:12.177  3912  4137 I Babel_SMS: MmsConfig.loadFromDatabase
,03-17 13:26:12.187  3749  3834 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 13:26:12.197  1021  1045 W libprocessgroup: failed to open /acct/uid_10060/pid_3280/cgroup.procs: No such file or directory
03-17 13:26:12.197  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3299/cgroup.procs: No such file or directory
,03-17 13:26:12.197  4122  4122 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 13:26:12.197  4122  4122 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 13:26:12.197  4122  4122 D SecurityLogAgent: StateMachine : Current State = 1
03-17 13:26:12.197  4122  4122 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-17 13:26:12.197  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.197  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.197  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.197  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.217  4141  4141 E Zygote  : MountEmulatedStorage()
03-17 13:26:12.217  4141  4141 E Zygote  : v2
03-17 13:26:12.217  4141  4141 I libpersona: KNOX_SDCARD checking this for 10152
03-17 13:26:12.217  4141  4141 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:12.217  4141  4141 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:12.217  4141  4141 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:12.217  4141  4141 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:12.227  1021  3140 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4141 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
03-17 13:26:12.227  1021  3140 I ActivityManager: Killing 3346:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,03-17 13:26:12.237  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.237  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.237  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.237  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.237  4141  4141 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:12.237  4141  4141 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.247   309   309 I art     : Explicit concurrent mark sweep GC freed 8775(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 658us total 24.550ms
,03-17 13:26:12.257  3912  4137 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-17 13:26:12.257  3912  4137 I Babel_SMS: MmsConfig.loadFromResources
03-17 13:26:12.257  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:12.257  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:12.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:12.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:12.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:12.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:12.257  3912  4137 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 13:26:12.257  3912  4137 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,03-17 13:26:12.267  1021  3141 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:12.267   289   289 E SMD     : DCD OFF,
03-17 13:26:12.267   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 19.728ms
,03-17 13:26:12.287  3484  3494 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
03-17 13:26:12.287   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 19.698ms
,03-17 13:26:12.307  4156  4156 E Zygote  : MountEmulatedStorage()
03-17 13:26:12.307  4156  4156 I libpersona: KNOX_SDCARD checking this for 10032
03-17 13:26:12.307  4156  4156 E Zygote  : v2
03-17 13:26:12.307  4156  4156 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:12.307  4156  4156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:12.317  4156  4156 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:12.317  4156  4156 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:12.317  1021  3140 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4156 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
03-17 13:26:12.317  1021  3140 I ActivityManager: Killing 3378:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-17 13:26:12.327  1690  1690 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,03-17 13:26:12.357  4156  4156 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.357  4156  4156 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.357  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.357  3749  3834 I GFX raster: took 0.612187ms for 96*96 texture 0
03-17 13:26:12.357  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8681e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8681f58 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.367  3749  3834 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 13:26:12.377  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.377  3749  3834 I GFX raster: took 0.805990ms for 96*96 texture 0
03-17 13:26:12.377  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867d600 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867d928 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.387  3749  3834 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 13:26:12.407  1744  3930 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-17 13:26:12.407  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-17 13:26:12.417  3912  3924 W art     : Suspending all threads took: 7.704ms
,03-17 13:26:12.417   284   284 W QCamera2Factory: getCameraInfo: E, camera_id = 0
03-17 13:26:12.417   284   284 W QCamera2Factory: getCameraInfo: X
,03-17 13:26:12.417   284  1016 W QCamera2Factory: getCameraInfo: E, camera_id = 1
03-17 13:26:12.417   284  1016 W QCamera2Factory: getCameraInfo: X
,03-17 13:26:12.427  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.427  3749  3834 I GFX raster: took 0.650469ms for 96*96 texture 0
,03-17 13:26:12.427  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867cb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867cbe0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.437  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 13:26:12.447  1021  1498 I art     : Explicit concurrent mark sweep GC freed 32683(2020KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 30MB/45MB, paused 2.764ms total 171.847ms
,03-17 13:26:12.447  1021  1047 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 13:26:12.447  1021  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.457  1021  1497 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.457  1021  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.457  1021  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:12.457  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.457  3749  3834 I GFX raster: took 0.763802ms for 96*96 texture 0
03-17 13:26:12.457  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867d928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867dbe0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.457  1021  3140 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:12.467  1021  1047 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 13:26:12.477  3749  3834 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 13:26:12.477  1744  3930 I GCoreUlr: Unbound from all location providers
,03-17 13:26:12.487  1021  1045 W libprocessgroup: failed to open /acct/uid_10062/pid_3346/cgroup.procs: No such file or directory
,03-17 13:26:12.487  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3378/cgroup.procs: No such file or directory
,03-17 13:26:12.487  4141  4141 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-17 13:26:12.507  1021  3140 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:12.507  1021  1498 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:12.527  1744  1744 I GCoreUlr: DispatchingService.onDestroy()
,03-17 13:26:12.537  1744  1744 I GCoreUlr: Unbound from all location providers
,03-17 13:26:12.547  3912  3912 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 13:26:12.547  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.557  3749  3834 I GFX raster: took 0.635209ms for 96*96 texture 0
03-17 13:26:12.557  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867f4f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867f7e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.557  1021  1517 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.557  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.557  1021  1517 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:12.557  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-17 13:26:12.557  3749  3834 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 13:26:12.567  3912  3912 I Babel_Crash: startup - clean
,03-17 13:26:12.567  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.567  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.567  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.567  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.577  1021  2829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:26:12.587  4182  4182 E Zygote  : MountEmulatedStorage(),
03-17 13:26:12.587  4182  4182 E Zygote  : v2
03-17 13:26:12.587  4182  4182 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 13:26:12.587  4182  4182 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:12.587  4182  4182 I libpersona: KNOX_SDCARD not a persona,
,03-17 13:26:12.587  4182  4182 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:12.587  4182  4182 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 13:26:12.597  1021  1391 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4182 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 13:26:12.597  3912  4179 I Babel   : deleted: false for 0
,03-17 13:26:12.597  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity,
03-17 13:26:12.597  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:12.597  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:12.597  3749  3834 I AMMetaDataParserService: Resource data:2131034113
,03-17 13:26:12.597  1021  2792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 ,
,03-17 13:26:12.607  3860  3860 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar },
03-17 13:26:12.607  3749  3834 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main,
03-17 13:26:12.607  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml,
,03-17 13:26:12.607  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:12.607  3749  3834 I GFX raster: took 0.814115ms for 96*96 texture 0
03-17 13:26:12.607  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8671e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb867cc78 counterpartCT=4 counterpartW=96 counterparth=96
03-17 13:26:12.607  1021  1391 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
03-17 13:26:12.607  1021  1391 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.607  1021  1391 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:12.607  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 13:26:12.617  1021  3139 I ActivityManager: Killing 3390:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-17 13:26:12.617  3749  3834 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 13:26:12.627  4182  4182 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.627  4182  4182 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.637  1021  1305 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:12.647  1021  1306 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:12.647  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.647  1021  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.647  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,03-17 13:26:12.647  4037  4076 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 13:26:12.657  1021  1133 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:12.657  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.657  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.657  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.657  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.677  4200  4200 E Zygote  : MountEmulatedStorage()
,03-17 13:26:12.677  4200  4200 I libpersona: KNOX_SDCARD checking this for 10033
03-17 13:26:12.677  4200  4200 E Zygote  : v2
03-17 13:26:12.677  4200  4200 I libpersona: KNOX_SDCARD not a persona,
,03-17 13:26:12.677  4200  4200 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:12.677  1021  1377 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4200 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
03-17 13:26:12.677  1021  1377 I ActivityManager: Killing 3411:com.fmm.dm/1000 (adj 15): empty #31
,03-17 13:26:12.677  4200  4200 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:12.687  1021  1732 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
03-17 13:26:12.687  4200  4200 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 13:26:12.687  4037  4076 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 13:26:12.687  1501  1501 D Launcher.Model: reloadBadges entered.
03-17 13:26:12.687  4037  4076 D BadgeProvider: sendNotify, [notify] : null
03-17 13:26:12.687  4037  4076 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 13:26:12.687  4037  4076 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 13:26:12.687  4037  4076 D BadgeProvider: update, [UpdateCount] : 1
03-17 13:26:12.687  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:12.687  4049  4094 I Process : Sending signal. PID: 4049 SIG: 9
,03-17 13:26:12.697  3749  3834 I GFX raster: took 0.844948ms for 96*96 texture 0
03-17 13:26:12.697  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8671e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb867bff0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.697  3749  3834 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 13:26:12.707  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.707  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.707  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.707  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.717  4200  4200 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.717  4200  4200 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.727  4215  4215 E Zygote  : MountEmulatedStorage()
03-17 13:26:12.727  4215  4215 E Zygote  : v2
03-17 13:26:12.727  4215  4215 I libpersona: KNOX_SDCARD checking this for 1101
03-17 13:26:12.727  4215  4215 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:12.727  1021  1305 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4215 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,03-17 13:26:12.727  4215  4215 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:12.727  1021  1305 I ActivityManager: Killing 3470:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-17 13:26:12.737  1021  1305 I ActivityManager: Killing 3512:com.sec.android.app.mt/1000 (adj 15): empty #31,
,03-17 13:26:12.737  4215  4215 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:12.737  4215  4215 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 13:26:12.777  4215  4215 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.777  4215  4215 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.777  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.777  3749  3834 I GFX raster: took 0.597292ms for 96*96 texture 0
03-17 13:26:12.777  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867d3d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867b778 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.787  1021  1517 I ActivityManager: Process com.android.exchange (pid 4049)(adj 15) has died(52,1098)
,03-17 13:26:12.797  3749  3834 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 13:26:12.807  4215  4215 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-17 13:26:12.817  1021  2792 D SSRM:n  : SIOP:: AP = 410
,03-17 13:26:12.837  4215  4215 V SmartcardService: main Received broadcast
03-17 13:26:12.837  4215  4215 V SmartcardService: Starting smartcard service after boot completed
03-17 13:26:12.837  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.837  1021  3139 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.837  3749  3834 I GFX raster: took 0.697135ms for 96*96 texture 0
,03-17 13:26:12.837  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8681e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8681f58 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.837  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.837  1021  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:12.837  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3390/cgroup.procs: No such file or directory
03-17 13:26:12.837  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3411/cgroup.procs: No such file or directory
,03-17 13:26:12.847  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-17 13:26:12.847  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3512/cgroup.procs: No such file or directory
03-17 13:26:12.847  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3470/cgroup.procs: No such file or directory
,03-17 13:26:12.857  1021  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.857  3749  3834 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 13:26:12.857  1021  1497 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.857  1021  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:12.857  1021  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 13:26:12.867  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.867  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.867  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.867  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.877  4230  4230 E Zygote  : MountEmulatedStorage(),
03-17 13:26:12.877  4230  4230 E Zygote  : v2,
,03-17 13:26:12.877  4230  4230 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:12.877  4230  4230 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:12.877  4230  4230 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:12.887  4230  4230 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:12.887  4230  4230 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:12.887  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.887  3749  3834 I GFX raster: took 0.855000ms for 96*96 texture 0
03-17 13:26:12.887  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867d600 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8681f58 counterpartCT=4 counterpartW=96 counterparth=96,
,03-17 13:26:12.887  1021  3141 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=4230 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 13:26:12.907  3749  3834 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 13:26:12.917  4230  4230 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.927  4230  4230 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.927  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.927  3749  3834 I GFX raster: took 0.641042ms for 96*96 texture 0
03-17 13:26:12.927  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867cb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8681f58 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.937  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 13:26:12.937  4200  4200 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:12.937  4200  4200 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:12.937  4200  4200 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:12.937  3912  3912 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 13:26:12.947  3912  3912 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 13:26:12.947  3912  3912 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 13:26:12.957  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.957  3749  3834 I GFX raster: took 0.675781ms for 96*96 texture 0
03-17 13:26:12.957  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867d928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8681f58 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.967  3912  3912 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 13:26:12.967  3912  3912 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 13:26:12.967  4230  4230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:12.967  3749  3834 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
03-17 13:26:12.967  1021  3141 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
03-17 13:26:12.967  1021  3141 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.967  1021  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:12.967  1021  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
03-17 13:26:12.967  4200  4200 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:12.967  4200  4200 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:12.967  4200  4200 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:12.977  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.977  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.977  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.977  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.977  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.977  3912  3912 W AudioCapabilities: Unsupported mime audio/x-ms-wma
03-17 13:26:12.977  3749  3834 I GFX raster: took 0.559583ms for 96*96 texture 0
03-17 13:26:12.977  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867f4f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8681f58 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.987  3912  3912 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 13:26:12.997  4248  4248 E Zygote  : MountEmulatedStorage()
03-17 13:26:12.997  4248  4248 E Zygote  : v2,
03-17 13:26:12.997  4248  4248 I libpersona: KNOX_SDCARD checking this for 10157
03-17 13:26:12.997  4248  4248 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:12.997  4248  4248 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:12.997  4248  4248 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:12.997  4248  4248 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:12.997  1021  1391 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4248 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,03-17 13:26:13.007  3749  3834 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 13:26:13.007  3912  3912 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 13:26:13.017  3912  3912 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 13:26:13.017  4200  4200 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 13:26:13.017  4200  4200 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 13:26:13.017  4200  4200 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:13.017  4248  4248 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:13.027  4248  4248 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:13.027  3749 , 3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: Resource data:2131034112
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-17 13:26:13.027  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
03-17 13:26:13.027  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:13.027  3749  3834 I GFX raster: took 1.217605ms for 96*96 texture 0
03-17 13:26:13.027  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8681e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8681f58 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.037  3749  3834 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-17 13:26:13.057  1021  3141 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.057  1021  3141 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-17 13:26:13.057  4248  4248 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:13.057  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.057  3912  3912 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 13:26:13.057  3912  3912 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 13:26:13.057  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.067  1021  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.067  3749  3834 I GFX raster: took 1.594062ms for 96*96 texture 0
03-17 13:26:13.067  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8681e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867c988 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.077  3912  3912 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 13:26:13.077  3912  3912 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 13:26:13.077  3912  3912 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 13:26:13.077  3749  3834 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-17 13:26:13.077  3912  3912 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 13:26:13.087  3912  3912 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 13:26:13.087  3912  3912 W VideoCapabilities: Unsupported mime video/mp43
,03-17 13:26:13.087  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.087  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.087  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.087  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.097  3912  3912 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 13:26:13.107  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.107  3749  3834 I GFX raster: took 0.641614ms for 96*96 texture 0
03-17 13:26:13.107  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867d600 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86413b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.107  4263  4263 E Zygote  : MountEmulatedStorage()
,03-17 13:26:13.107  4263  4263 E Zygote  : v2
03-17 13:26:13.107  4263  4263 I libpersona: KNOX_SDCARD checking this for 10159
03-17 13:26:13.107  4263  4263 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:13.107  4263  4263 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:13.107  1021  1496 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4263 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:13.107  1021  1496 I ActivityManager: Killing 3453:com.wssnps/1000 (adj 15): empty #31
,03-17 13:26:13.117  3912  3912 W VideoCapabilities: Unsupported mime video/mp4v-esdp,
,03-17 13:26:13.117  3749  3834 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-17 13:26:13.117  4263  4263 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:13.117  4263  4263 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,03-17 13:26:13.127  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.127  3749  3834 I GFX raster: took 0.682552ms for 96*96 texture 0
,03-17 13:26:13.127  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb863eb78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8660648 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.137  4263  4263 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:13.137  4263  4263 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.137  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-17 13:26:13.157  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3453/cgroup.procs: No such file or directory
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelection,Activity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
,03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
,03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: Resource data:2131034113
03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
,03-17 13:26:13.157  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
03-17 13:26:13.157  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:13.157  3749  3834 I GFX raster: took 0.814687ms for 96*96 texture 0
03-17 13:26:13.157  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839fad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb863d840 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.167  3749  3834 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-17 13:26:13.167  4263  4263 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
,03-17 13:26:13.167  3912  3912 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 13:26:13.177  1021  3141 I ActivityManager: Killing 3534:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,03-17 13:26:13.187  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.187  3749  3834 I GFX raster: took 0.808594ms for 96*96 texture 0
03-17 13:26:13.187  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839fad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb865f7b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.197  3749  3834 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 13:26:13.207  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.217  3749  3834 I GFX raster: took 0.839480ms for 96*96 texture 0
03-17 13:26:13.217  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86413b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86583e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.217  3912  3912 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 13:26:13.217  3912  3912 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 13:26:13.217  3749  3834 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 13:26:13.227  3912  3912 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 13:26:13.227  3912  3912 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 13:26:13.237  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.237  3749  3834 I GFX raster: took 0.598594ms for 96*96 texture 0
03-17 13:26:13.237  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8681e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8660648 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.237  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3534/cgroup.procs: No such file or directory
,03-17 13:26:13.247  3749  3834 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 13:26:13.247  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.247  3749  3834 I GFX raster: took 0.826875ms for 96*96 texture 0
,03-17 13:26:13.247  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb863d840 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb865f7b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.257  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:13.257  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:13.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:13.257  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:13.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:13.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:13.267  3749  3834 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 13:26:13.267  3912  3912 I vclib   : onServiceConnected
,03-17 13:26:13.277  3912  3912 W Babel   : Attempted to change video mute state without an active call.
,03-17 13:26:13.277  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.277  3749  3834 I GFX raster: took 0.629687ms for 96*96 texture 0
03-17 13:26:13.277  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb863eb78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86583e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.287  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.287  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.287  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.287  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.287  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 13:26:13.297  4288  4288 E Zygote  : MountEmulatedStorage()
03-17 13:26:13.297  4288  4288 E Zygote  : v2
03-17 13:26:13.297  4288  4288 I libpersona: KNOX_SDCARD checking this for 10035
03-17 13:26:13.297  4288  4288 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:13.297  4288  4288 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:13.307  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-17 13:26:13.307  1021  1377 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4288 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:13.307  3749  3834 I GFX raster: took 0.701198ms for 96*96 texture 0
03-17 13:26:13.307  1021  1377 I ActivityManager: Killing 3551:com.fmm.ds/1000 (adj 15): empty #31
03-17 13:26:13.307  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8660648 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb865f7b0 counterpartCT=4 counterpartW=96 counterparth=96
03-17 13:26:13.307  4288  4288 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:13.307  4288  4288 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.307  3749  3834 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 13:26:13.327  1021  3139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:13.327  4288  4288 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:13.327  4288  4288 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.327  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.327  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:13.327  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.347  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.347  3749  3834 I GFX raster: took 0.680365ms for 96*96 texture 0
03-17 13:26:13.347  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867f4f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86583e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.347  3749  3834 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-17 13:26:13.357  3749  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:13.357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-17 13:26:13.,357  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-17 13:26:13.367  4200  4200 I Process : Sending signal. PID: 4200 SIG: 9
,03-17 13:26:13.367  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,03-17 13:26:13.367  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-17 13:26:13.367  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
,03-17 13:26:13.367  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-17 13:26:13.367  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-17 13:26:13.367  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-17 13:26:13.367  3946  4115 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
,03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:13.377  3749  3834 I AMMetaDataParserService: Resource data:2131165203
,03-17 13:26:13.377  3749  3834 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:13.377  3749  3834 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:13.377  3749  3834 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:13.377  3749  3834 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:13.377  3749  3834 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:13.377  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3551/cgroup.procs: No such file or directory
,03-17 13:26:13.407  3749  3834 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
,03-17 13:26:13.407  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:13.407  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.407  3749  3834 I GFX construct_block_size_descriptor_2d second part: took 2.550989ms for 0*0 texture 0
,03-17 13:26:13.417  4288  4305 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-17 13:26:13.417  4288  4305 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-17 13:26:13.417  4288  4288 E SPPClientService: [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
03-17 13:26:13.417  4288  4288 E SPPClientService: [SystemStateMoniter] Current Time : 44377
,03-17 13:26:13.417  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-17 13:26:13.427  3749  3834 I GFX generate_partition_tables: took 10.281617ms for 0*0 texture 0
,03-17 13:26:13.427  3749  3834 I GFX raster: took 13.681148ms for 96*96 texture 0
03-17 13:26:13.427  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865d2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb865d3f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.427  1021  1497 I ActivityManager: Process com.sec.android.app.sns3 (pid 4200)(adj 0) has died(40,1106),
,03-17 13:26:13.427  3749  3834 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
03-17 13:26:13.427  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.427  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.427  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.427  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.437  4288  4305 D SPPClientService: PushLog.txt file is not deleted.
,03-17 13:26:13.437  4288  4305 D SPPClientService: PushLog.txt file is not deleted.
03-17 13:26:13.437  4288  4305 D SPPClientService: ============PushLog. stop!
,03-17 13:26:13.447  4307  4307 E Zygote  : MountEmulatedStorage()
,03-17 13:26:13.447  4307  4307 E Zygote  : v2
03-17 13:26:13.447  4307  4307 I libpersona: KNOX_SDCARD checking this for 10034
03-17 13:26:13.447  4307  4307 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:13.447  4307  4307 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 13:26:13.447  1021  1046 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4307 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
03-17 13:26:13.447  4307  4307 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:13.447  4307  4307 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.457  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.457  3749  3834 I GFX raster: took 0.843282ms for 96*96 texture 0
03-17 13:26:13.457  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86550e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8655190 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.467  3749  3834 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 13:26:13.467  4307  4307 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:13.467  4307  4307 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.477  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.477  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.477  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.477  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.477  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.477  3749  3834 I GFX raster: took 1.016823ms for 96*96 texture 0,
03-17 13:26:13.477  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86550e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb864a850 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.487  3749  3834 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 13:26:13.497  4322  4322 E Zygote  : MountEmulatedStorage(),
03-17 13:26:13.497  4322  4322 E Zygote  : v2
03-17 13:26:13.497  4322  4322 I libpersona: KNOX_SDCARD checking this for 10166
03-17 13:26:13.497  4322  4322 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:13.497  4322  4322 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:13.497  1021  3141 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4322 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:13.497  1021  3141 I ActivityManager: Killing 3327:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,03-17 13:26:13.497  4322  4322 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:13.497  4322  4322 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.517  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.517  3749  3834 I GFX raster: took 0.764792ms for 96*96 texture 0
,03-17 13:26:13.517  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86550e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb864bb58 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.517  4322  4322 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:13.517  4322  4322 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.527  3749  3834 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 13:26:13.547  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.547  3749  3834 I GFX raster: took 0.724167ms for 96*96 texture 0
,03-17 13:26:13.547  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb864cfe8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb864d090 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.547  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.547  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.557  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.557  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.557  3749  3834 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 13:26:13.567  4338  4338 E Zygote  : MountEmulatedStorage()
,03-17 13:26:13.567  4338  4338 E Zygote  : v2
,03-17 13:26:13.567  4338  4338 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 13:26:13.567  4338  4338 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:13.567  4338  4338 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:13.567  1021  1391 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:13.567  4338  4338 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:13.577  4338  4338 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:13.577  1021  1391 I ActivityManager: Killing 3614:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,03-17 13:26:13.597  4338  4338 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:13.597  4338  4338 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.597   309   309 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 30.981ms
,03-17 13:26:13.617   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 19.044ms
,03-17 13:26:13.637   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 18.713ms,
,03-17 13:26:13.647  1021  1045 W libprocessgroup: failed to open /acct/uid_10009/pid_3327/cgroup.procs: No such file or directory
03-17 13:26:13.647  1021  1045 W libprocessgroup: failed to open /acct/uid_10125/pid_3614/cgroup.procs: No such file or directory
,03-17 13:26:13.657  4338  4338 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 13:26:13.677  4156  4176 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 13:26:13.677  4156  4176 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:13.677  4156  4176 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:13.707  4156  4176 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:13.717  4338  4338 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 13:26:13.717  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.717  3749  3834 I GFX raster: took 0.689635ms for 96*96 texture 0
03-17 13:26:13.717  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb864cfe8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867c1c8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.727  3749  3834 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 13:26:13.727  4338  4338 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 13:26:13.727  4338  4353 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 13:26:13.737  4338  4353 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 13:26:13.747  4338  4338 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 13:26:13.747  4338  4338 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-17 13:26:13.747  4338  4338 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 13:26:13.747  4338  4338 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-17 13:26:13.747  4338  4353 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-17 13:26:13.747  4338  4338 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,03-17 13:26:13.747  4338  4338 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 13:26:13.757  4338  4338 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 13:26:13.757  4338  4338 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-17 13:26:13.757  4338  4338 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 13:26:13.757  4338  4338 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 13:26:13.767  4338  4338 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 13:26:13.777  4338  4338 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-17 13:26:13.787  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.787  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.787  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.787  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.797  4361  4361 E Zygote  : MountEmulatedStorage(),
03-17 13:26:13.797  4361  4361 E Zygote  : v2
,03-17 13:26:13.807  1021  1497 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4361 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:13.807  1021  1497 I ActivityManager: Killing 3629:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
03-17 13:26:13.807  4322  4357 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 13:26:13.807  4322  4357 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-17 13:26:13.807  4361  4361 I libpersona: KNOX_SDCARD checking this for 10041
,03-17 13:26:13.807  4361  4361 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:13.817  4361  4361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:13.817  4361  4361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:13.827  4361  4361 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.877  4361  4361 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:13.877  4361  4361 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:13.877  1690  1690 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
03-17 13:26:13.877  4338  4353 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-17 13:26:13.877  4338  4353 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:13.887  4338  4353 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
03-17 13:26:13.887  4338  4353 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 13:26:13.897  4338  4353 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 13:26:13.907  4322  4357 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-17 13:26:13.917  3749  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-17 13:26:13.917  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-17 13:26:13.927  4338  4353 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 13:26:13.927  1021  1045 W libprocessgroup: failed to open /acct/uid_10069/pid_3629/cgroup.procs: No such file or directory
,03-17 13:26:13.937  4338  4353 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 13:26:13.947  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-17 13:26:13.947  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-17 13:26:13.947  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-17 13:26:13.947  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-17 13:26:13.947  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-17 13:26:13.947  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.947  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 13:26:13.947  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 13:26:13.947  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:13.947  3749  3834 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:13.947  4338  4353 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 13:26:13.947  4338  4353 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 13:26:13.947  4338  4354 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 13:26:13.947  4338  4353 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 13:26:13.957  4338  4354 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:13.957  4338  4353 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
,03-17 13:26:13.967  4338  4353 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/13:26:13
,03-17 13:26:13.967  4338  4353 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
03-17 13:26:13.967  3749  3834 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 13:26:13.967  3749  3834 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:13.967  3749  3834 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:13.967  3749  3834 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:13.967  3749  3834 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 13:26:13.967  3749  3834 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:13.967  3749  3834 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:13.967  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:13.967  4338  4353 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 13:26:13.967  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.967  3749  3834 I GFX raster: took 0.697135ms for 96*96 texture 0
03-17 13:26:13.967  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8676a38 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.967  4338  4354 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 13:26:13.967  4338  4354 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 13:26:13.977  3749  3834 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:13.977  4338  4354 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 13:26:13.977  4338  4354 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 13:26:13.987  4338  4353 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
03-17 13:26:13.987  4338  4354 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 13:26:13.987  4338  4354 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-17 13:26:13.987  4338  4354 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 13:26:13.987  4338  4354 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 13:26:14.007  4322  4357 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 13:26:14.007  4322  4357 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d9b3f59: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 13:26:14.007  4322  4357 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 13:26:14.017  4338  4354 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 13:26:14.017  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.027  3749  3834 I GFX construct_block_size_descriptor_2d second part: took 2.544427ms for 0*0 texture 0,
,03-17 13:26:14.037  3749  3834 I GFX generate_partition_tables: took 8.803803ms for 0*0 texture 0
,03-17 13:26:14.037  3749  3834 I GFX raster: took 12.368333ms for 96*96 texture 0
03-17 13:26:14.037  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c6e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b8c788 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.037  4361  4361 I SA      : [SSP] onCreated
,03-17 13:26:14.047  3749  3834 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:14.057  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.057  3749  3834 I GFX raster: took 0.668698ms for 96*96 texture 0
03-17 13:26:14.057  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8674378 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.067  4338  4354 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
03-17 13:26:14.067  3749  3834 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:14.117  4338  4353 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 13:26:14.117  4338  4353 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 13:26:14.117  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.127  3749  3834 I GFX raster: took 0.771564ms for 96*96 texture 0
,03-17 13:26:14.127  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866a720 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb866a7c8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.127  3749  3834 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:14.147  4361  4361 I SA      : [TPM] There is no property file
,03-17 13:26:14.147  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.147  3749  3834 I GFX raster: took 0.625990ms for 96*96 texture 0
03-17 13:26:14.147  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86750f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8675198 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.147  4361  4361 I SA      : [SCU] isHaveSA() - false
,03-17 13:26:14.147  4361  4361 I SA      : [TPM] getModelProperty : null
,03-17 13:26:14.147  4361  4361 I SA      : [TPM] getCSCProperty : null
,03-17 13:26:14.157  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:14.157  4361  4361 I SA      : [DM] FLOATING AMOLED FEATURE: true
,03-17 13:26:14.157  4361  4361 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-17 13:26:14.157  4361  4361 I SA      : [DM] TFT FEATURE: false
,03-17 13:26:14.177  4361  4361 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,03-17 13:26:14.177  4361  4361 I SA      : [DM] init START
,03-17 13:26:14.177  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.187  4361  4361 I SA      : [DM] This device is not a Vodafone
,03-17 13:26:14.187  3749  3834 I GFX raster: took 1.104429ms for 96*96 texture 0
03-17 13:26:14.187  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86753c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8675470 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.187  3749  3834 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:14.197  4361  4361 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
03-17 13:26:14.197  4361  4361 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
03-17 13:26:14.197  4361  4361 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,03-17 13:26:14.197  4361  4361 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-17 13:26:14.197  4361  4361 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-17 13:26:14.197  4361  4361 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,03-17 13:26:14.197  4361  4361 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-17 13:26:14.207  4361  4361 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
03-17 13:26:14.207  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-17 13:26:14.207  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-17 13:26:14.207  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.207  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:14.207  3749  3834 I AMMetaDataParserService: Resource data:2131099648
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
03-17 13:26:14.207  3749  3834 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:14.207  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
03-17 13:26:14.207  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
03-17 13:26:14.207  4361  4361 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,03-17 13:26:14.217  4361  4361 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
03-17 13:26:14.217  3749  3834 I GFX raster: took 0.710156ms for 96*96 texture 0
03-17 13:26:14.217  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867f4e8 counterpartCT=4 counterpartW=96 counterparth=96
03-17 13:26:14.217  4361  4361 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,03-17 13:26:14.217  4361  4361 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,03-17 13:26:14.217  4361  4361 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-17 13:26:14.217  4361  4361 I SA      : [SCU] isHaveSA() - false
03-17 13:26:14.217  4361  4361 I SA      : support phone number id : false
03-17 13:26:14.217  4361  4361 I SA      : [DM] Supports Ref Jpn : true
,03-17 13:26:14.217  4361  4361 I SA      : [DM] init END
,03-17 13:26:14.227  4361  4361 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
03-17 13:26:14.227  4361  4361 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-17 13:26:14.227  1021  3139 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,03-17 13:26:14.227  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.227  1021  3139 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 13:26:14.227  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-17 13:26:14.227  3749  3834 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:14.237  4361  4361 I SA      : [OR] onReceive END
,03-17 13:26:14.247  4338  4354 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 13:26:14.257  4361  4361 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 13:26:14.257  4361  4361 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-17 13:26:14.257  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.257  3749  3834 I GFX raster: took 0.654375ms for 96*96 texture 0
03-17 13:26:14.257  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c6e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb86685f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.257  4361  4361 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
,03-17 13:26:14.267  4361  4361 I SA      : [LBE] REF_JPN : true
,03-17 13:26:14.267  4361  4361 I SA      : [BDC] create
,03-17 13:26:14.267  3749  3834 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:14.287  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.287  3749  3834 I GFX raster: took 0.797448ms for 96*96 texture 0
03-17 13:26:14.287  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8674628 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.297  3749  3834 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:14.297  4338  4354 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0],
,03-17 13:26:14.317  4338  4354 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 13:26:14.357  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.357  3749  3834 I GFX raster: took 0.644844ms for 96*96 texture 0
03-17 13:26:14.357  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866a720 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.357  3749  3834 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:14.367  4322  4334 W art     : Suspending all threads took: 13.388ms
,03-17 13:26:14.387  4361  4361 I SA      : [DBMV2] getEmailID
,03-17 13:26:14.387  4361  4361 I SA      : [DBMV2] getDataV02ForItems
03-17 13:26:14.387  4361  4361 I SA      : [SSP] query invoked
,03-17 13:26:14.387  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.387  3749  3834 I GFX raster: took 0.683646ms for 96*96 texture 0
03-17 13:26:14.387  4361  4361 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-17 13:26:14.387  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86750f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.397  4361  4361 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-17 13:26:14.397  4361  4361 I SA      : [BDC] destroy
,03-17 13:26:14.397  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:14.397  1021  1133 I ActivityManager: Killing 3649:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,03-17 13:26:14.417  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.417  3749  3834 I GFX raster: took 0.724375ms for 96*96 texture 0
03-17 13:26:14.417  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86753c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.417  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-17 13:26:14.427  3749  3834 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:14.447  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
,03-17 13:26:14.447  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-17 13:26:14.447  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
,03-17 13:26:14.447  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-17 13:26:14.447  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.447  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
,03-17 13:26:14.447  3749  3834 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:14.447  3749  3834 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-17 13:26:14.447  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:14.447  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.447  3749  3834 I GFX raster: took 0.733541ms for 96*96 texture 0
,03-17 13:26:14.447  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.457  3749  3834 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523,
,03-17 13:26:14.477  1021  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:14.487  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.487  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.487  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.487  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.487  3749  3834 I GFX raster: took 0.628177ms for 96*96 texture 0
03-17 13:26:14.487  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c6e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.487  3749  3834 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:14.497  4322  4322 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 13:26:14.507  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.507  3749  3834 I GFX raster: took 0.643595ms for 96*96 texture 0
,03-17 13:26:14.507  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.507  1021  1045 W libprocessgroup: failed to open /acct/uid_10014/pid_3649/cgroup.procs: No such file or directory
,03-17 13:26:14.517  3749  3834 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:14.527  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.527  3749  3834 I GFX raster: took 0.658698ms for 96*96 texture 0
,03-17 13:26:14.527  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866a720 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.537  4390  4390 I dex2oat : ----------------------------------------------------
,03-17 13:26:14.537  4390  4390 I dex2oat : <SS>: S T A R T I N G . . .
03-17 13:26:14.537  4390  4390 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 13:26:14.537  4390  4390 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2055868273.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-2055868273.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 13:26:14.537  3749  3834 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:14.547  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.547  3749  3834 I GFX raster: took 0.661824ms for 96*96 texture 0
,03-17 13:26:14.547  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86750f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.557  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:14.567  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.567  3749  3834 I GFX raster: took 0.717864ms for 96*96 texture 0
03-17 13:26:14.567  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86753c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.567   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 13:26:14.567   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:14.567  4322  4322 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 13:26:14.567  3749  3834 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:14.577  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-17 13:26:14.577  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.577  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:14.577  3749  3834 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:14.577  3749  3834 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:14.577  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:14.577  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.577  3749  3834 I GFX raster: took 0.828855ms for 96*96 texture 0,
03-17 13:26:14.577  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.587  3749  3834 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:14.607  4390  4390 I dex2oat : dex2oat took 69.906ms (threads: 4)
,03-17 13:26:14.607  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.607  3749  3834 I GFX raster: took 0.723906ms for 96*96 texture 0
,03-17 13:26:14.617  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c6e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.617  3749  3834 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:14.627  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.627  3749  3834 I GFX raster: took 0.681460ms for 96*96 texture 0
,03-17 13:26:14.627  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.637  3749  3834 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:14.667  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.667  3749  3834 I GFX raster: took 0.655365ms for 96*96 texture 0
03-17 13:26:14.667  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866a720 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb866b618 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.667  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.667  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.667  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.667  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:14.667  1021  1305 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:14.667  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.667  1021  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.667  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.667  3749  3834 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:14.677  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.677  3749  3834 I GFX raster: took 0.717863ms for 96*96 texture 0
,03-17 13:26:14.677  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86750f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.687  4322  4334 W art     : Suspending all threads took: 6.908ms
,03-17 13:26:14.687  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:14.697  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.707  3749  3834 I GFX raster: took 0.773906ms for 96*96 texture 0
03-17 13:26:14.707  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86753c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.707  3749  3834 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:14.717  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-17 13:26:14.717  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.717  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:14.717  3749  3834 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:14.717  3749  3834 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-17 13:26:14.717  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:14.717  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.727  3749  3834 I GFX raster: took 0.845936ms for 96*96 texture 0
,03-17 13:26:14.727  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.737  3749  3834 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:14.807  1021  1104 V AlarmManager: waitForAlarm result :4
,03-17 13:26:14.807  1021  1104 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0,
,03-17 13:26:14.827  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.827  3749  3834 I GFX raster: took 0.841094ms for 96*96 texture 0
,03-17 13:26:14.827  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c6e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.847  3749  3834 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:14.857  1021  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:26:14.867  1021  1498 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
03-17 13:26:14.867  1021  1498 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,03-17 13:26:14.867  1021  1021 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:26:14.867  1021  1021 I MotionRecognitionService: Plugged
,03-17 13:26:14.867  1021  1021 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:26:14.877  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:26:14.877  1435  1435 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:26:14.877  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:26:14.877  1435  1435 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:26:14.877  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:14.877  3749  3834 I GFX raster: took 0.619843ms for 96*96 texture 0
03-17 13:26:14.877  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.877  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:26:14.877  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:26:14.877  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:26:14.887  3749  3834 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-17 13:26:14.887  2692  2692 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:26:14.887  2692  2778 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:26:14.907  1894  4416 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 95 ms
,03-17 13:26:14.917  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.927  3749  3834 I GFX raster: took 0.755677ms for 96*96 texture 0
,03-17 13:26:14.927  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866a720 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.937  3749  3834 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:14.947   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/,
,03-17 13:26:14.947  4322  4322 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache,
03-17 13:26:14.947   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:14.947   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/,
03-17 13:26:14.947   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:14.947  4322  4322 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 13:26:14.947   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 13:26:14.947   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:14.957  4322  4322 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 13:26:14.957  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.957  3749  3834 I GFX raster: took 0.645469ms for 96*96 texture 0
,03-17 13:26:14.957  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86750f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.967  1021  1732 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:14.967  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.967  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.967  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.967  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
03-17 13:26:14.967  4322  4322 W InstanceID/Rpc: Found 10012
,03-17 13:26:15.017   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 13:26:15.017  4322  4322 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
03-17 13:26:15.017   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:15.017  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.017  3749  3834 I GFX raster: took 0.808854ms for 96*96 texture 0
,03-17 13:26:15.017  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86753c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.027  3749  3834 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:15.037  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,03-17 13:26:15.037  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:15.037  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:15.037  3749  3834 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:15.037  3749  3834 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-17 13:26:15.037  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:15.037  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.037  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.037  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.037  1021  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.037  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:15.047  3749  3834 I GFX raster: took 0.758749ms for 96*96 texture 0
03-17 13:26:15.047  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.047  3749  3834 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:15.067  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.067  3749  3834 I GFX raster: took 0.687292ms for 96*96 texture 0
03-17 13:26:15.067  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c6e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.077  3749  3834 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:15.087  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.087  3749  3834 I GFX raster: took 0.714010ms for 96*96 texture 0
03-17 13:26:15.087  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b8c788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.087  3749  3834 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:15.097  1021  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.097  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.097  1021  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:15.097  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:15.107  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.107  3749  3834 I GFX raster: took 0.629687ms for 96*96 texture 0
03-17 13:26:15.107  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb866a720 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.117  3749  3834 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:15.117  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.117  3749  3834 I GFX raster: took 0.805625ms for 96*96 texture 0
03-17 13:26:15.117  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86750f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.127  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:15.137  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.137  3749  3834 I GFX raster: took 0.728489ms for 96*96 texture 0
03-17 13:26:15.137  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86753c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8674728 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.147  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.147  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.147  1021  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.147  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:15.147  1021  1517 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.147  3749  3834 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
03-17 13:26:15.147  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.147  1021  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.147  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:15.157  1021  1046 I ActivityManager: Waited long enough for: ServiceRecord{1fa390e0 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-17 13:26:15.157  1021  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android,.mms.ui.PushMessageDialog
03-17 13:26:15.157  3749  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity,
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity,
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable,
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList,
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable,
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages,
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity,
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity,
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-17 13:26:15.177  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
,03-17 13:26:15.177  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
,03-17 13:26:15.177  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-17 13:26:15.177  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-17 13:26:15.157  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
03-17 13:26:15.167  1021  1391 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.167  1021  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.167  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:15.187  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-17 13:26:15.187  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.187  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:15.187  3749  3834 I AMMetaDataParserService: Resource data:2131165197
,03-17 13:26:15.197  4449  4449 E Zygote  : MountEmulatedStorage()
03-17 13:26:15.197  4449  4449 I libpersona: KNOX_SDCARD checking this for 10101
03-17 13:26:15.197  4449  4449 E Zygote  : v2
03-17 13:26:15.197  4449  4449 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:15.197  4449  4449 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:15.197  3749  3834 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:15.197  3749  3834 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 13:26:15.197  3749  3834 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:15.197  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
03-17 13:26:15.197  3749  3834 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:15.197  4449  4449 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:15.197  3749  3834 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:15.197  3749  3834 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 13:26:15.197  3749  3834 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 13:26:15.197  3749  3834 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 13:26:15.197  3749  3834 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:15.207  4449  4449 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:15.207  1021  1033 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4449 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:15.207  4322  4444 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
03-17 13:26:15.207  4322  4444 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
03-17 13:26:15.207  3749  3834 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
03-17 13:26:15.207  4322  4444 I System.out: Thread-718(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 13:26:15.217  4322  4444 I System.out: Thread-718(ApacheHTTPLog):isSBSettingEnabled false
03-17 13:26:15.217  4322  4444 I System.out: Thread-718(ApacheHTTPLog):isShipBuild true
03-17 13:26:15.217  4322  4444 I System.out: Thread-718(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 13:26:15.217  4322  4444 I System.out: Thread-718(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 13:26:15.217   279  1003 D EnterpriseController: uids 10166
03-17 13:26:15.217   279  1003 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 13:26:15.217   279  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10166
,03-17 13:26:15.227  1021  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
03-17 13:26:15.227  1021  1497 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.227  1021  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.227  1021  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:15.227  4449  4449 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:15.227  4449  4449 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:15.227  3749  3834 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 13:26:15.247  1021  1377 I ActivityManager: Killing 3213:com.google.android.gms:car/u0a12 (adj 15): empty #31
,03-17 13:26:15.257  3749  3834 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 13:26:15.267  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:15.267  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:15.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:15.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:15.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:15.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:15.267   289   289 E SMD     : DCD OFF
,03-17 13:26:15.297  1021  1498 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,03-17 13:26:15.307  1021  1045 W libprocessgroup: failed to open /acct/uid_10012/pid_3213/cgroup.procs: No such file or directory
,03-17 13:26:15.327  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 13:26:15.337  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-17 13:26:15.337  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.337  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:15.337  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:15.337  3749  3834 I AMMetaDataParserService: Resource data:2131165197
,03-17 13:26:15.337  3749  3834 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-17 13:26:15.337  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:15.347  3749  3834 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 13:26:15.377  3749  3834 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 13:26:15.397  3749  3834 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 13:26:15.427  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-17 13:26:15.437  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 13:26:15.447  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
,03-17 13:26:15.447  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
,03-17 13:26:15.447  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:15.447  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
,03-17 13:26:15.447  3749  3834 I AMMetaDataParserService: Resource data:2131165197
,03-17 13:26:15.447  3749  3834 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-17 13:26:15.447  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:15.457  3749  3834 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 13:26:15.467  3749  3834 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 13:26:15.477  3749  3834 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 13:26:15.497  3749  3834 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-17 13:26:15.507  3749  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:15.507  3749  3834 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-17 13:26:15.507  3749  3834 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:15.507  3749  3834 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 13:26:15.507  3749  3834 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 13:26:15.507  3749  3834 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-17 13:26:15.507  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:15.517  1021  1377 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:15.517  1021  1377 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:15.517  3749  3834 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-17 13:26:15.527  3749  3834 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-17 13:26:15.557  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,03-17 13:26:15.557  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-17 13:26:15.557  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,03-17 13:26:15.557  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,03-17 13:26:15.557  3749  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 13:26:15.617  4449  4470 I Gmail   : getAccountsCursor
,03-17 13:26:15.617  1021  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.627  4322  4444 I System.out: Thread-718 calls detatch()
,03-17 13:26:15.627  1690  1690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:15.637  4449  4449 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 13:26:15.637  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-17 13:26:15.637  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.637  3749  3834 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:15.637  3749  3834 I AMMetaDataParserService: Resource data:2131165220
,03-17 13:26:15.647  3749  3834 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 13:26:15.647  3749  3834 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:15.647  3749  3834 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:15.647  3749  3834 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:15.647  3749  3834 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:15.647  3749  3834 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 13:26:15.647  3749  3834 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-17 13:26:15.647  3749  3834 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:15.647  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.647  3749  3834 I GFX raster: took 0.689271ms for 96*96 texture 0
03-17 13:26:15.647  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d91198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d90f60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.657  1021  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.657  1021  1391 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 13:26:15.657  3749  3834 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-17 13:26:15.667  3749  3834 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.667  3749  3834 I GFX raster: took 0.778281ms for 96*96 texture 0
03-17 13:26:15.667  3749  3834 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d91040 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da4450 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.677  4449  4476 I Gmail   : Observing account changes for notifications
,03-17 13:26:15.677  1021  1377 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:15.677  1021  1377 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:15.677  3749  3834 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-17 13:26:15.677  1021  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.677  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.687  1021  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.687  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 13:26:15.687  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.,settings.wifi.WifiSecSetupActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  1021  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-17 13:26:15.697  1021  1498 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
,03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-17 13:26:15.687  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 13:26:15.697  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.717  1021  1497 I ActivityManager: Killing 3694:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activit,ycom.android.settings.applications.StorageUse
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.727  1021  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
,03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataP,arserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Choose,LockPassword
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-17 13:26:15.737  1021  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-17 13:26:15.697  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.757  1021  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.757  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.757  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.757  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.757  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-17 13:26:15.767  4487  4487 I libpersona: KNOX_SDCARD checking this for 10092
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-17 13:26:15.767  4487  4487 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.777  1021  1377 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=4487 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.777  1021  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.777  1021  1498 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-17 13:26:15.777  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-17 13:26:15.707  3749  3834 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-17 13:26:15.727  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.727  1021  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.727  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-17 13:26:15.727  4449  4480 E Gmail   : Error finding the version of the Email provider.....
03-17 13:26:15.727  4449  4480 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 13:26:15.727  4449  4480 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 13:26:15.727  4449  4480 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
03-17 13:26:15.727  4449  4480 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
03-17 13:26:15.727  4449  4480 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 13:26:15.727  4449  4480 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.727  4449  4480 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.727  4449  4480 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 13:26:15.727  4449  4480 W EmailMigration: We do not support migrating this version of the Email provider.
03-17 13:26:15.737  4449  4482 I Gmail   : getAccountsCursor
03-17 13:26:15.747  1690  1690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 13:26:,15.757  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.757  1021  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.757  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-17 13:26:15.767  4487  4487 E Zygote  : MountEmulatedStorage()
03-17 13:26:15.767  4487  4487 E Zygote  : v2
03-17 13:26:15.777  4487  4487 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:15.777  4487  4487 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:15.777  4487  4487 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 13:26:15.787  1690  1690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 13:26:15.807  4487  4487 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:15.807  4487  4487 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:15.827  4449  4483 E SQLiteLog: (283) recovered 76 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
03-17 13:26:15.837  1021  1045 W libprocessgroup: failed to open /acct/uid_10131/pid_3694/cgroup.procs: No such file or directory
,03-17 13:26:15.907  4449  4483 E File    : fail readDirectory() errno=2
,03-17 13:26:15.917  4449  4497 I Gmail   : notifyAccountChanged
,03-17 13:26:15.917  4449  4497 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 13:26:15.927  4449  4497 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 13:26:15.937  4449  4497 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 13:26:15.937  4449  4497 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 13:26:15.947  1021  1033 I art     : Explicit concurrent mark sweep GC freed 37607(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 30MB/45MB, paused 2.560ms total 154.751ms
,03-17 13:26:15.947  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.957  1690  1690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:15.957  1021  3141 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:15.957  1021  3141 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:15.957  4449  4506 I Gmail   : getAccountsCursor
,03-17 13:26:15.967  1021  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.967  1690  1690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:15.967  4449  4449 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@d1da96c that was originally bound here
03-17 13:26:15.967  4449  4449 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@d1da96c that was originally bound here
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at com.android.emailcommon.service.ak.a(SourceFile:181)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at com.android.emailcommon.service.ak.e(SourceFile:224)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:177)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:198)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:142)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.967  4449  4449 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:15.967  1021  1377 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@a79fd5c
,03-17 13:26:15.977  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 13:26:15.977  4449  4483 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,03-17 13:26:15.987  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.987  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.987  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.987  4449  4483 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,03-17 13:26:15.987  1021  3139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:15.997  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.997  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:15.997  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.037  1021  1055 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-17 13:26:16.037  1021  1055 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-17 13:26:16.037  1021  1055 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:16.037  1021  1055 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 13:26:16.047  1021  1176 D lights  : lcd : 25 +,
,03-17 13:26:16.057  1021  1055 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-17 13:26:16.057  1021  1055 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:16.057  1021  1176 D lights  : lcd : 25 -
,03-17 13:26:16.057  1021  1176 D lights  : lcd : 19 +
,03-17 13:26:16.067  1021  3138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:16.077  1021  3138 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.077  1021  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:16.077  1021  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.077  4449  4483 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,03-17 13:26:16.077  1021  1176 D lights  : lcd : 19 -
,03-17 13:26:16.077  1021  1055 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 13:26:16.077  1021  1055 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:16.087  1021  1498 I ActivityManager: Killing 3182:com.android.vending/u0a28 (adj 15): empty #31
,03-17 13:26:16.137  4449  4470 I Gmail   : getAccountsCursor
,03-17 13:26:16.137  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 13:26:16.137  1690  1690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:16.197  1021  1045 W libprocessgroup: failed to open /acct/uid_10028/pid_3182/cgroup.procs: No such file or directory
,03-17 13:26:16.197  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-17 13:26:16.197  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.197  1021  1732 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 13:26:16.197  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android,
03-17 13:26:16.207  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.207  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.207  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.207  1021  1732 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.217  4508  4508 E Zygote  : MountEmulatedStorage(),
,03-17 13:26:16.217  4508  4508 E Zygote  : v2
03-17 13:26:16.217  1021  1732 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=4508 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:16.217  4508  4508 I libpersona: KNOX_SDCARD checking this for 10092
03-17 13:26:16.217  4508  4508 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:16.227  4508  4508 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:16.227  4508  4508 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:16.227  4508  4508 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.257  4508  4508 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.257  4508  4508 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.267  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 13:26:16.267  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-17 13:26:16.267  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:16.277  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:16.277  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:16.277  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:16.297  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.297  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.297  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.297  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.317  4487  4487 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 13:26:16.317  4525  4525 E Zygote  : MountEmulatedStorage()
,03-17 13:26:16.317  4525  4525 E Zygote  : v2
03-17 13:26:16.317  4525  4525 I libpersona: KNOX_SDCARD checking this for 10012
03-17 13:26:16.317  4525  4525 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:16.317  4525  4525 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 13:26:16.317  1021  1046 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=4525 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-17 13:26:16.327  4525  4525 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:16.327  4525  4525 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.337  4487  4487 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 13:26:16.347  4525  4525 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.347  4525  4525 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.367  4525  4525 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 13:26:16.367  4525  4525 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 13:26:16.387  4487  4487 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_9807ade0d39f04306c7e28de04204d1f53ae2228_armv7a
,03-17 13:26:16.397  4525  4525 I MultiDex: VM with version 2.1.0 has multidex support
03-17 13:26:16.397  4525  4525 I MultiDex: install
03-17 13:26:16.397  4525  4525 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 13:26:16.397  4487  4487 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 13:26:16.397  1021  1497 I ActivityManager: Killing 3675:com.google.android.partnersetup/u0a15 (adj 15): empty #31
03-17 13:26:16.397  4487  4487 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_b492ffd532b8b6365d97439f842c164c3c90fd4e_armv7a
,03-17 13:26:16.407  4487  4487 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_e16babc055b114839529ea959e1ce06f2a593b63_armv7a
,03-17 13:26:16.417  4525  4525 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 13:26:16.427  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-17 13:26:16.467  4525  4525 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 13:26:16.467  4525  4525 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b705307: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 13:26:16.467  4525  4525 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 13:26:16.477  1021  1496 I ActivityManager: Killing 3781:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,03-17 13:26:16.517  4487  4487 I libDropboxSync.so: Setting global terminate handler.
,03-17 13:26:16.547  4487  4487 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_aa417f8c60b792b71fc3cef90fc4bb8ddba4ea56_armv7a
,03-17 13:26:16.557  1021  1045 W libprocessgroup: failed to open /acct/uid_10015/pid_3675/cgroup.procs: No such file or directory
,03-17 13:26:16.557  1021  1045 W libprocessgroup: failed to open /acct/uid_10022/pid_3781/cgroup.procs: No such file or directory
,03-17 13:26:16.597  4487  4487 I com.dropbox.sync.android.L: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 13:26:16.607  4487  4487 I com.dropbox.sync.android.L: Removing unclaimed file/directory in cache: "local-dbapp_noauth"
,03-17 13:26:16.627  4487  4487 I com.dropbox.sync.android.bf: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/3.0.2 DropboxSync/3.1+dev (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-17 13:26:16.637  4487  4487 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:16.637  4487  4487 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:16.647  4487  4487 I com.dropbox.sync.android.aS: Created NativeDbappNoAuthClientProvider
,03-17 13:26:16.647  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.sync.android.DbxSyncService; callingUser = 0; userId(target) = 0
,03-17 13:26:16.657  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.657  1021  1498 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 13:26:16.657  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 13:26:16.707  4487  4547 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,03-17 13:26:16.707  4487  4547 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 13:26:16.707  4487  4547 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 13:26:16.707  4487  4547 I System.out: (HTTPLog)-Thread-687-540886814: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 13:26:16.707  4487  4547 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 13:26:16.707   279  1003 D EnterpriseController: uids 10092
03-17 13:26:16.707   279  1003 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 13:26:16.707   279  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 13:26:16.797  4487  4547 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 13:26:16.807  4487  4487 I com.dropbox.sync.android.DbxSyncService: DbxSyncService starting.
,03-17 13:26:16.807  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.807  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.807  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.817  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.827  4559  4559 E Zygote  : MountEmulatedStorage()
03-17 13:26:16.827  4559  4559 E Zygote  : v2
,03-17 13:26:16.827  4559  4559 I libpersona: KNOX_SDCARD checking this for 10057
03-17 13:26:16.827  4559  4559 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:16.827  4559  4559 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:16.827  4559  4559 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:16.827  1021  1496 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4559 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-17 13:26:16.827  4559  4559 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.837  1021  1305 I ActivityManager: Killing 3749:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-17 13:26:16.847  4559  4559 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.847  4559  4559 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.947  1021  1061 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-17 13:26:16.947  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3749/cgroup.procs: No such file or directory
,03-17 13:26:17.027  4487  4547 I com.dropbox.sync.android.aF: Created new socket: SSL socket over Socket[address=api.dropbox.com/108.160.172.205,port=443,localPort=53820]
,03-17 13:26:17.077  1021  1306 D LocationManagerService: getProviders()=[passive]
,03-17 13:26:17.117  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.117  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.117  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.117  1021  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.137  4338  4353 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO,
,03-17 13:26:17.137  4581  4581 E Zygote  : MountEmulatedStorage()
,03-17 13:26:17.137  4581  4581 I libpersona: KNOX_SDCARD checking this for 10015
03-17 13:26:17.137  4581  4581 E Zygote  : v2,
03-17 13:26:17.137  4581  4581 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:17.137  4581  4581 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:17.147  4581  4581 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:17.147  4581  4581 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.147  1021  1133 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4581 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-17 13:26:17.167  4581  4581 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.167  4581  4581 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.167  4338  4353 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 13:26:17.167  1021  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.177  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.177  1021  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.177  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 13:26:17.177  4338  4353 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 13:26:17.177  4338  4353 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 13:26:17.177  4338  4353 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 13:26:17.177  4338  4353 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 13:26:17.187  4338  4353 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 13:26:17.187  4338  4353 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 13:26:17.247  1021  1498 I splitIntent: Queue : backgroundsplit_2 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 13:26:17.247  1021  1046 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.247  1021  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.247  1021  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 13:26:17.257  1021  1517 I ActivityManager: Killing 3805:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-17 13:26:17.257  1021  1305 I ActivityManager: Killing 3759:com.android.calendar/u0a135 (adj 15): empty #31
,03-17 13:26:17.277  1021  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
03-17 13:26:17.277  1475  4611 D SIP     : [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,03-17 13:26:17.277  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.277  1021  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.277  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:17.277  1475  4611 E File    : fail readDirectory() errno=2
,03-17 13:26:17.287  2607  2607 I Hs20UtilService: Starting #3
,03-17 13:26:17.287  2607  2622 I Hs20UtilService: Message received 5011
,03-17 13:26:17.287  1021  1138 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 13:26:17.287  1021  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:17.287  1021  1138 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 13:26:17.287  1021  1138 E WifiNative-wlan0: invaild command id : 215
,03-17 13:26:17.287  1021  1496 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:17.287  1021  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.287  1021  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.297  4122  4122 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 13:26:17.297  4122  4122 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 13:26:17.297  4122  4122 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 13:26:17.297  4122  4122 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 13:26:17.307  1349  1349 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,03-17 13:26:17.307  1349  1349 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 13:26:17.307  1349  1349 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 13:26:17.307  1021  3140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:17.307  1349  1349 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 13:26:17.307  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.307  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:17.307  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.307  1349  1349 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,03-17 13:26:17.307  1349  1349 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:17.327  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.327  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.327  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.327  1021  1377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.347  4613  4613 E Zygote  : MountEmulatedStorage()
03-17 13:26:17.347  4613  4613 I libpersona: KNOX_SDCARD checking this for 10068
03-17 13:26:17.347  4613  4613 E Zygote  : v2
03-17 13:26:17.347  4613  4613 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:17.347  4613  4613 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 13:26:17.347  1021  1377 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4613 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 13:26:17.357  4613  4613 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 13:26:17.357  4613  4613 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.387  4613  4613 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.387  4613  4613 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.407  4613  4613 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 13:26:17.417  4613  4613 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-17 13:26:17.427  4613  4613 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,03-17 13:26:17.437  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-17 13:26:17.457  1021  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 13:26:17.457  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.457  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.457  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.457  4613  4613 D FileShare-Client: Outbound.stopDelayTimer - 
,03-17 13:26:17.457  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.457  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.457  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.457  1021  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.477  4631  4631 E Zygote  : MountEmulatedStorage(),
03-17 13:26:17.477  4631  4631 I libpersona: KNOX_SDCARD checking this for 10069
03-17 13:26:17.477  4631  4631 E Zygote  : v2
03-17 13:26:17.477  4631  4631 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:17.477  4631  4631 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:17.477  1021  1305 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4631 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:17.477  4631  4631 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:17.477  1021  1305 I ActivityManager: Killing 3484:com.sec.pcw.device/1000 (adj 15): empty #31
,03-17 13:26:17.477  4631  4631 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.487  1021  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:17.487  1021  1497 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.487  1021  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:17.487  1021  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.507  1690  2781 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,03-17 13:26:17.507  1690  2781 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-17 13:26:17.507  1690  2781 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-17 13:26:17.507  1690  2781 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:26:17.507  1690  2781 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:17.517  1021  3138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.517  1021  3138 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.517  1021  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.517  1021  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.527  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3805/cgroup.procs: No such file or directory
03-17 13:26:17.527  1021  1045 W libprocessgroup: failed to open /acct/uid_10135/pid_3759/cgroup.procs: No such file or directory
,03-17 13:26:17.527  4631  4631 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.527  4631  4631 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.557  4631  4631 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-17 13:26:17.567  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.567  1021  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.567  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.567  1021  1133 I ActivityManager: Killing 3887:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 13:26:17.567  1690  2781 I art     : Explicit concurrent mark sweep GC freed 9588(536KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 1.021ms total 43.551ms
,03-17 13:26:17.567  1021  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.567  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.567  1021  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.567  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.577  1021  3139 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-17 13:26:17.577  1021  3139 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-17 13:26:17.577  1021  3139 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-17 13:26:17.577  1021  3139 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 13:26:17.577  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.577  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.577  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.577  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.577  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.577  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.577  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3484/cgroup.procs: No such file or directory
,03-17 13:26:17.587  1690  1690 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 13:26:17.587  1690  4647 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 13:26:17.587  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.587  1021  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-17 13:26:17.587  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.597  1021  3141 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.597  1021  3141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.597  1021  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.597  1894  1894 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 13:26:17.597  1021  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.597  1021  2829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-17 13:26:17.597  1021  1497 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
03-17 13:26:17.597  1021  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 13:26:17.597  1021  1391 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.597  1021  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.597  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.607  1021  1021 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:26:17.607  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.607  1021  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.607  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.607  1196  1196 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 13:26:17.607  4559  4603 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at com.google.android.gms.auth.b.c(Unknown Source),
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: ,	at java.lang.Thread.run(Thread.java:818)
03-17 13:26:17.607  4559  4603 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,03-17 13:26:17.607  1196  1196 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:17.617  4559  4600 E VelvetNetworkClient: Failed to get auth token,
,03-17 13:26:17.617  1196  1196 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:17.617  1196  1196 I PhoneStatusBar: Icon Only
03-17 13:26:17.617  1196  1196 I StatusBar: Icon Only
03-17 13:26:17.617  1196  1196 D PanelView: There is/are notification(s) 
03-17 13:26:17.617  1196  1196 D PanelView: kidsfalse mQsExpansionEnabled:true
03-17 13:26:17.617  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.617  1021  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.617  1196  1196 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:17.617  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:17.617  1196  1196 I PhoneStatusBar: Icon Only
03-17 13:26:17.617  1196  1196 I StatusBar: Icon Only
,03-17 13:26:17.617  1196  1196 D PanelView: There is/are notification(s) 
03-17 13:26:17.617  1196  1196 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:26:17.617  1021  1391 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.627  1021  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.627  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.627  1021  3140 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:17.627  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,03-17 13:26:17.627  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.627  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.627  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.627  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.637  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.637  1021  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.637  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.637  1021  3140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:17.647  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.647  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.647  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.647  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.647  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.647  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.647  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.667  4650  4650 E Zygote  : MountEmulatedStorage()
03-17 13:26:17.667  1021  3140 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4650 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
03-17 13:26:17.667  4650  4650 E Zygote  : v2
03-17 13:26:17.667  4650  4650 I libpersona: KNOX_SDCARD checking this for 10012
03-17 13:26:17.667  4650  4650 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:17.667  1021  1517 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:17.667  4650  4650 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:17.667  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.667  1021  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.667  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.677  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.677  1021  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.677  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.677  4650  4650 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:17.677  4650  4650 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.677  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 13:26:17.677  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.677  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.677  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.687  1894  4656 D LocationInitializer: Restart initialization of location,
,03-17 13:26:17.687  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
03-17 13:26:17.687  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.687  1021  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.687  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.687  1196  1196 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-17 13:26:17.687  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.697  1021  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.697  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.697  1021  1034 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:17.697  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.697  1021  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.697  4650  4650 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:17.697  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 13:26:17.697  1021  1045 W libprocessgroup: failed to open /acct/uid_10139/pid_3887/cgroup.procs: No such file or directory
,03-17 13:26:17.697  4650  4650 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.707  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.707  1021  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.707  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.707  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.707  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.707  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.717  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.717  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:17.717  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.717  4650  4650 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 13:26:17.727  4650  4650 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 13:26:17.727  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.727  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.727  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.727  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.727  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.727  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.737  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.737  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.737  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.737  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.737  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.737  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.737  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.737  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.737  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.737  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.737  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.737  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.747  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.747  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.747  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.747  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.747  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.747  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.747  1021  1021 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:17.747  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.747  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.757  1021  1021 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:17.757  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.757  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.757  4650  4650 I MultiDex: VM with version 2.1.0 has multidex support,
03-17 13:26:17.757  4650  4650 I MultiDex: install
03-17 13:26:17.757  4650  4650 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 13:26:17.757  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.757  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.757  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.757  1021  1021 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.757  1021  1021 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.757  1021  1021 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.777  4650  4650 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 13:26:17.827  4650  4650 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 13:26:17.827  4650  4650 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b705307: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 13:26:17.827  4650  4650 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 13:26:17.837  1021  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.837  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.837  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.837  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.837  1021  1133 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 13:26:17.837  1021  1133 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
,03-17 13:26:17.837  1021  1133 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-17 13:26:17.837  1021  1133 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 13:26:17.847  1690  1690 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 13:26:17.847  1690  4668 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 13:26:17.857  1894  1894 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 13:26:17.857  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.857  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.857  1021  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.857  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.877  1021  1732 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:17.887  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.887  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.887  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.897  1021  3138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 13:26:17.897  1021  3138 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.897  1021  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.897  1021  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.897  1894  4669 D LocationInitializer: Restart initialization of location
,03-17 13:26:17.897  1021  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.907  1021  1496 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.907  1021  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:17.907  1021  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.917  4650  4650 D WearableService: callingUid 10012, callindPid: 4650
,03-17 13:26:17.917  1021  3138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:17.917  1021  3138 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.917  1021  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.917  1021  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:17.927  2607  2607 I Hs20UtilService: Starting #4
,03-17 13:26:17.927  1349  1349 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 13:26:17.927  2607  2622 I Hs20UtilService: Message received 5007
,03-17 13:26:17.927  1349  1349 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 13:26:17.937  1349  1349 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 13:26:17.937  1349  1349 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 13:26:17.937  1349  1349 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 13:26:17.937  1349  1349 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:17.947  1021  1305 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:17.947  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.947  1021  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.947  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:17.957  2607  2607 I Hs20UtilService: Starting #5
,03-17 13:26:17.957  2607  2622 I Hs20UtilService: Message received 5007
,03-17 13:26:17.957  1744  4648 E MDM     : [187] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 13:26:17.967  1349  1349 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 13:26:17.967  1349  1349 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:17.967  1744  4672 E MDM     : [188] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 13:26:17.977  1021  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:17.977  1021  1133 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:17.977  1021  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.977  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:17.987  2607  2607 I Hs20UtilService: Starting #6
,03-17 13:26:17.987  1349  1349 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 13:26:17.987  1349  1349 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
03-17 13:26:17.987  2607  2622 I Hs20UtilService: Message received 5007
,03-17 13:26:17.987  1349  1349 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 13:26:17.987  1349  1349 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-17 13:26:17.987  1349  1349 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 13:26:17.987  1349  1349 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:17.997  1021  1377 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:17.997  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.997  1021  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.997  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:17.997  1349  1349 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 13:26:17.997  2607  2607 I Hs20UtilService: Starting #7
,03-17 13:26:18.007  1349  1349 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:18.007  1021  1732 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-17 13:26:18.007  2607  2622 I Hs20UtilService: Message received 5007
,03-17 13:26:18.017  1021  1133 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-17 13:26:18.017  1021  1133 D SecContentProvider2: mCursor = null
,03-17 13:26:18.017  1021  1305 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 13:26:18.017  1021  1305 D SecContentProvider2: mCursor = null
,03-17 13:26:18.017  1021  1496 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-17 13:26:18.017  1021  1496 D SecContentProvider2: mCursor = null
,03-17 13:26:18.017  1021  3139 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-17 13:26:18.017  1021  3139 D SecContentProvider2: mCursor = null
,03-17 13:26:18.027  1021  1517 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-17 13:26:18.027  1021  1517 D SecContentProvider2: mCursor = null
,03-17 13:26:18.027  1021  3138 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-17 13:26:18.027  1021  3138 D SecContentProvider2: mCursor = null
,03-17 13:26:18.037  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.037  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.037  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.037  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.047   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-17 13:26:18.047  4673  4673 E Zygote  : MountEmulatedStorage()
03-17 13:26:18.047  4673  4673 E Zygote  : v2
03-17 13:26:18.047  4673  4673 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:18.047  4673  4673 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:18.047  4673  4673 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:18.057  4673  4673 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 13:26:18.057  1021  3141 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4673 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:18.057  4673  4673 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:18.057  1021  1498 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1021
03-17 13:26:18.057  1021  1055 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-17 13:26:18.057  1021  1055 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:18.057  1021  1055 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 13:26:18.067  1196  1196 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 13:26:18.077  1021  1176 D lights  : lcd : 32 +
03-17 13:26:18.077  1021  1055 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-17 13:26:18.077  1021  1055 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:18.077  4673  4673 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:18.077  4673  4673 D ActivityThread: Added TimaKeyStore provider,
,03-17 13:26:18.087   309   309 I art     : Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 774us total 30.296ms
,03-17 13:26:18.097  1021  1176 D lights  : lcd : 32 -
03-17 13:26:18.097  1021  1055 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-17 13:26:18.097  1021  1055 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:18.097   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 16.979ms,
,03-17 13:26:18.107  4673  4673 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 13:26:18.107  4673  4673 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-17 13:26:18.107  4673  4673 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 13:26:18.117   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 17.832ms
,03-17 13:26:18.117  4673  4673 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 13:26:18.117  4673  4673 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:26:18.117  4673  4673 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:26:18.117  4673  4673 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:18.127  1021  3139 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
,03-17 13:26:18.127  1021  3139 I splitIntent: base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
03-17 13:26:18.127  1021  3139 I splitIntent: other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
,03-17 13:26:18.127  1021  3139 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,03-17 13:26:18.127  1021  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.127  1021  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.127  1021  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.127  1021  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.137  4690  4690 E Zygote  : MountEmulatedStorage()
,03-17 13:26:18.137  4690  4690 E Zygote  : v2,
03-17 13:26:18.137  4690  4690 I libpersona: KNOX_SDCARD checking this for 10111
,03-17 13:26:18.137  4690  4690 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:18.137  1021  3139 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4690 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:18.147  4690  4690 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:18.147  1021  3139 I ActivityManager: Killing 3821:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,03-17 13:26:18.147  4690  4690 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:18.147  4690  4690 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:18.167  4690  4690 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:18.167  4690  4690 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:18.247  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3821/cgroup.procs: No such file or directory
,03-17 13:26:18.277   289   289 E SMD     : DCD OFF
,03-17 13:26:18.387  4690  4690 I MusicStore: Database version: 120
,03-17 13:26:18.437  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-17 13:26:18.467  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 13:26:18.477  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.477  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:18.477  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:18.517   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 13:26:18.517   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:18.517  4690  4690 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 13:26:18.547  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,03-17 13:26:18.547  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.547  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.547  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:18.597   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 13:26:18.597   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:18.597  4690  4690 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 13:26:18.597   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 13:26:18.597   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:18.597  4690  4690 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 13:26:18.627  4690  4690 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 13:26:18.637  4690  4690 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 13:26:18.637  1021  1145 D SettingsProvider: name = audio_safe_volume_state
,03-17 13:26:18.637  1021  1341 E Watchdog: !@Sync 1
,03-17 13:26:18.657  4690  4690 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 13:26:18.707  4690  4690 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 13:26:18.707  4690  4690 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ad5128a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 13:26:18.707  4690  4690 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 13:26:18.707  4690  4690 D AndroidMusic: GMSCore installation verified
,03-17 13:26:18.717  4690  4690 I ConfigStore: Config Database version: 1
,03-17 13:26:18.717  1021  1046 I ActivityManager: Waited long enough for: ServiceRecord{1fb09e0f u0 com.samsung.android.providers.context/.ContextService}
,03-17 13:26:18.797  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.797  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.797  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.797  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:18.817  1021  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-17 13:26:18.817  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.817  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.817  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:18.847  1021  1391 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:18.847  1021  1377 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:18.857  1021  1034 I AudioService: getStreamVolume 3 index 0
,03-17 13:26:18.857  4690  4690 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-17 13:26:18.857  4690  4690 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-17 13:26:18.867  4690  4690 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 13:26:18.887  1021  1046 I ActivityManager: Waited long enough for: ServiceRecord{f87c459 u0 com.android.settings/.wifi.WifiCredService}
,03-17 13:26:18.897  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 13:26:18.897  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.897  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.897  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
,03-17 13:26:18.897  1021  1517 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0,
,03-17 13:26:18.897  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.897  1021  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:18.897  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
03-17 13:26:18.897  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.897  1021  3140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
03-17 13:26:18.897  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-17 13:26:18.897  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:18.907  1021  3139 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:18.907  4690  4690 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 13:26:18.917  1021  1021 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.917  1021  1021 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.917  1021  1021 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.917  1021  1021 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.937  4716  4716 E Zygote  : MountEmulatedStorage(),
03-17 13:26:18.937  1021  1021 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4716 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:18.937  4716  4716 E Zygote  : v2
03-17 13:26:18.937  4716  4716 I libpersona: KNOX_SDCARD checking this for 10002
03-17 13:26:18.937  4716  4716 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:18.937  4716  4716 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:18.937  4716  4716 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 13:26:18.937  4716  4716 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:18.957  4716  4716 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:18.957  4690  4690 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
03-17 13:26:18.957  4716  4716 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:18.967  1021  1034 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:18.967  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.967  1021  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.967  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.967  1021  1517 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.967  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.967  1021  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.967  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.967  4690  4690 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-17 13:26:18.977  1021  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 13:26:18.977  1021  1391 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.977  1021  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.977  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:18.997  1021  1377 I ActivityManager: Killing 3994:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-17 13:26:19.047  1021  1391 I ActivityManager: Killing 4018:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-17 13:26:19.047  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.047  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.047  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.047  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.067  4735  4735 E Zygote  : MountEmulatedStorage()
,03-17 13:26:19.067  4735  4735 E Zygote  : v2
03-17 13:26:19.067  4735  4735 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:19.067  4735  4735 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:19.067  4735  4735 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 13:26:19.067  1021  1306 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4735 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:19.067  4735  4735 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:19.067  4735  4735 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.087  4735  4735 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.087  4735  4735 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.117  4735  4735 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 13:26:19.217  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_3994/cgroup.procs: No such file or directory
,03-17 13:26:19.217  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_4018/cgroup.procs: No such file or directory
,03-17 13:26:19.217  4735  4735 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 13:26:19.227  4735  4735 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 13:26:19.227  4735  4735 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:19.227  4735  4735 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 13:26:19.227  4735  4735 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-17 13:26:19.227  4735  4735 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 13:26:19.247  1021  1104 V AlarmManager: waitForAlarm result :4
,03-17 13:26:19.277  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:19.277  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:19.277  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:19.277  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:19.287  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:19.287  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:19.287  4338  4346 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:19.287  4338  4346 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:19.287  4338  4346 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 13:26:19.287  4338  4347 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:19.297  4338  4347 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:19.297  4338  4347 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 13:26:19.307  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.307  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.307  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.307  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.317  1021  1497 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4752 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 13:26:19.327  4752  4752 E Zygote  : MountEmulatedStorage()
,03-17 13:26:19.327  4752  4752 I libpersona: KNOX_SDCARD checking this for 10009
03-17 13:26:19.327  4752  4752 E Zygote  : v2
03-17 13:26:19.327  4752  4752 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:19.327  4752  4752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:19.327  4752  4752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:19.327  4752  4752 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.347  4752  4752 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.347  4752  4752 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.397  1021  3141 I ActivityManager: Killing 3438:com.test.thalitest/u0a174 (adj 15): empty #31
,03-17 13:26:19.407  4752  4752 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 13:26:19.417  4752  4752 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 13:26:19.417  1021  1391 I ActivityManager: Killing 4083:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 13:26:19.427  3728  3728 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 13:26:19 GMT+01:00 2016
,03-17 13:26:19.427  1021  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 13:26:19.427  1021  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.427  1021  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:19.427  1021  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 13:26:19.427  3728  3728 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 13:26:19.427  3728  3728 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 13:26:19.437  3728  3728 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 13:26:19.437  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,03-17 13:26:19.437  3728  3728 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 13:26:19.437  3728  4769 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 13:26:19.437  3728  4769 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-17 13:26:19.447  3728  4769 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-17 13:26:19.447  3728  4769 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,03-17 13:26:19.447  4338  4338 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:19.447  3728  4769 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,03-17 13:26:19.457  4361  4361 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ],
03-17 13:26:19.457  4361  4361 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,03-17 13:26:19.457  4361  4361 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==,
03-17 13:26:19.457  4338  4770 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 13:26:19.457  4338  4770 I DBG_POLICYDM: [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
03-17 13:26:19.457  4361  4361 I SA      : [SLFUCHKMGR] constructor called
,03-17 13:26:19.457  4338  4770 E DBG_POLICYDM: [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,03-17 13:26:19.467  4361  4361 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-17 13:26:19.467  4361  4361 I SA      : [OR] == isSIMCardReady false ==
,03-17 13:26:19.467  3728  4769 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-17 13:26:19.467  3728  4769 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,03-17 13:26:19.467  3728  3728 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 13:26:19.467  4361  4361 I SA      : [SCU] == networkStateCheck == true
,03-17 13:26:19.477  4338  4770 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 13:26:19.477  4361  4361 I SA      : [DM] getCountryCodeFromCSC : PL
03-17 13:26:19.477  4361  4361 I SA      : isChinaCountryCode : false
03-17 13:26:19.477  4361  4361 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-17 13:26:19.477  4361  4361 I SA      : [OR] == networkStateCheck true ==
,03-17 13:26:19.477  4361  4361 I SA      : [OR] GetMyCountryZoneTask
,03-17 13:26:19.477  4361  4361 I SA      : [OR] onReceive END
,03-17 13:26:19.477  1243  1243 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:19.487  1021  3138 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-17 13:26:19.487  1021  3138 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.487  1021  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:19.487  1021  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 13:26:19.487  4338  4770 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 13:26:19.487  4338  4770 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 13:26:19.487  4338  4770 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 13:26:19.497  4361  4772 I SA      : [SRS] prepareGetMyCountryZone
,03-17 13:26:19.497  1622  1622 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 13:26:19.497  4338  4770 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 13:26:19.497  4338  4770 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 13:26:19.497  4338  4770 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 13:26:19.497  4338  4770 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 13:26:19.497  4338  4770 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-17 13:26:19.497  4338  4770 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-17 13:26:19.507  1313  1324 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,03-17 13:26:19.507  4338  4770 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,03-17 13:26:19.507  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_4083/cgroup.procs: No such file or directory
03-17 13:26:19.507  1021  1045 W libprocessgroup: failed to open /acct/uid_10174/pid_3438/cgroup.procs: No such file or directory,
03-17 13:26:19.517  4361  4772 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-17 13:26:19.517  4361  4772 I SA      : [SSP] query invoked
,03-17 13:26:19.517  1622  1622 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-17 13:26:19.517  1622  1622 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-17 13:26:19.517  1622  1622 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,03-17 13:26:19.517  1622  1622 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-17 13:26:19.517  4338  4770 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:19.527  4338  4770 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,03-17 13:26:19.657  1021  1391 I art     : Explicit concurrent mark sweep GC freed 28895(1720KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 30MB/45MB, paused 2.354ms total 140.606ms
,03-17 13:26:19.657  1021  1306 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 13:26:19.657  1021  1306 D SecContentProvider2: mCursor = null
,03-17 13:26:19.657  4361  4772 I SA      : [TPMU] GetMccFromDB : null
,03-17 13:26:19.657  4361  4772 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-17 13:26:19.657  1622  1622 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 13:26:19.657  4361  4772 I SA      : [TPM] isNoProxy(default) : true
,03-17 13:26:19.667  1622  1622 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 13:26:19.667  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.667  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.667  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.667  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.677  4361  4772 E File    : fail readDirectory() errno=2
,03-17 13:26:19.687  4775  4775 E Zygote  : MountEmulatedStorage()
03-17 13:26:19.687  4775  4775 E Zygote  : v2
03-17 13:26:19.687  4775  4775 I libpersona: KNOX_SDCARD checking this for 10125
03-17 13:26:19.687  4775  4775 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:19.687  4775  4775 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:19.687  1021  3141 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4775 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 13:26:19.687  4775  4775 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:19.687  4775  4775 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.707  4775  4775 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.707  4775  4775 D ActivityThread: Added TimaKeyStore provider,
,03-17 13:26:19.717  4775  4775 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:19.717  4775  4775 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 13:26:19.717  4775  4775 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 13:26:19.747  4775  4775 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:19.747  4775  4775 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-17 13:26:19.747  4775  4775 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 13:26:19.757  1021  1305 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:19.757  1021  1033 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:19.767  4122  4122 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 13:26:19.767  4122  4122 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 13:26:19.767  4122  4122 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 13:26:19.767  4122  4122 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 13:26:19.777  1021  1498 I ActivityManager: Killing 3946:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-17 13:26:19.797  1021  3140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 13:26:19.797  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.797  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:19.797  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.837  1021  1061 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,03-17 13:26:19.857  1021  1108 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 13:26:19.867  3574  3574 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,03-17 13:26:19.887  1894  4793 I iu.SyncManager: SYNC; picasa accounts,
,03-17 13:26:19.927  1460  1460 D RegisteredComponentCache: Collect Tech packages for Knox
,03-17 13:26:19.937  1460  1460 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:19.947  1460  1460 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:19.947  1460  1460 D RegisteredServicesCache: empty dynamic service
,03-17 13:26:19.947  1894  1894 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-17 13:26:19.947  1894  1894 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-17 13:26:19.967  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:19.977  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,03-17 13:26:19.977  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.977  1021  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.977  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.977  1894  4793 I iu.UploadsManager: num queued entries: 0
,03-17 13:26:19.977  1894  4793 I iu.UploadsManager: num updated entries: 0
,03-17 13:26:19.977  1894  4793 I iu.SyncManager: NEXT; no task
,03-17 13:26:19.987  1021  3140 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 13:26:19.987  1021  3140 D SecContentProvider2: mCursor = null
,03-17 13:26:19.987  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:19.997  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:19.997  1021  1021 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,03-17 13:26:19.997  1021  1021 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-17 13:26:19.997  1021  1021 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 13:26:19.997  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:19.997  1021  1021 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 13:26:19.997  1021  1021 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,03-17 13:26:20.007  1894  1894 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-17 13:26:20.007  1894  1894 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-17 13:26:20.027  1021  1021 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 13:26:20.027  1021  1021 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2c51291e
,03-17 13:26:20.027  1021  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,03-17 13:26:20.027  1021  1391 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:20.027  1021  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:20.027  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
03-17 13:26:20.027  1501  1501 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 13:26:20.037  1501  1501 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 13:26:20.037  4288  4288 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:20.037  4288  4288 E SPPClientService: [SystemStateMoniter] Current Time : 50997
,03-17 13:26:20.047  4288  4288 E SPPClientService: [SystemStateMoniter] No Connect : false
,03-17 13:26:20.047  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,03-17 13:26:20.047  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:20.047  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:20.047  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:20.047  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.047  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.047  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.047  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.067  3912  4797 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager,
03-17 13:26:20.067  3912  4797 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 13:26:20.067  3912  4797 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 13:26:20.067  3912  4797 I System.out: (HTTPLog)-Thread-566-581503465: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 13:26:20.067  3912  4797 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 13:26:20.067  4799  4799 E Zygote  : MountEmulatedStorage()
03-17 13:26:20.067  4799  4799 E Zygote  : v2
03-17 13:26:20.067  4799  4799 I libpersona: KNOX_SDCARD checking this for 10113
03-17 13:26:20.067  4799  4799 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:20.067  4799  4799 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:20.077  4799  4799 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:20.077   279  1003 D EnterpriseController: uids 10104
03-17 13:26:20.077   279  1003 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 13:26:20.077   279  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10104
,03-17 13:26:20.077  1021  1496 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4799 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:20.077  4799  4799 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:20.087  1021  1045 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
,03-17 13:26:20.087  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:20.097  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:20.097  4799  4799 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.097  4799  4799 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:20.097  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:20.097  1021  1045 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:20.097  1021  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:20.097  1021  1045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:20.097  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:20.117  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:20.117  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:20.117  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:26:20.117  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 13:26:20.117  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:20.127  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:26:20.127  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 13:26:20.127  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:26:20.127  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 13:26:20.127  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 13:26:20.137  1021  1045 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-17 13:26:20.137  1021  1045 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-17 13:26:20.147  1021  1045 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-17 13:26:20.147  1021  1045 W libprocessgroup: failed to open /acct/uid_10031/pid_3946/cgroup.procs: No such file or directory
,03-17 13:26:20.147  1021  1045 D LocationProviderProxy: applying state to connected service
,03-17 13:26:20.287  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:20.287  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:20.287  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:20.287  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:20.287  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:20.287  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:20.397   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 13:26:20.397   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.397  4799  4818 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 13:26:20.397   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 13:26:20.397   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.397  4799  4818 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 13:26:20.407  4361  4772 I SA      : [RC New] Execute method=[GET] start
,03-17 13:26:20.417   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 13:26:20.417   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.427  4799  4819 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 13:26:20.427   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 13:26:20.427   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.427  4799  4799 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-17 13:26:20.427  4799  4799 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 13:26:20.427  4799  4799 I GAv4    :   adb logcat -s GAv4
,03-17 13:26:20.427  4799  4819 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 13:26:20.437  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 13 sec
,03-17 13:26:20.447  4361  4772 I SA      : [RC New] Security=[true]
,03-17 13:26:20.447  4361  4772 I System.out: Thread-675(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 13:26:20.447  4361  4772 I System.out: Thread-675(ApacheHTTPLog):isSBSettingEnabled false
,03-17 13:26:20.447  4361  4772 I System.out: Thread-675(ApacheHTTPLog):isShipBuild true
03-17 13:26:20.447  4361  4772 I System.out: Thread-675(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 13:26:20.447  4361  4772 I System.out: Thread-675(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 13:26:20.447   279  1003 D EnterpriseController: uids 10041
03-17 13:26:20.447   279  1003 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 13:26:20.447   279  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,03-17 13:26:20.457  4799  4799 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 13:26:20.467  4799  4799 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-17 13:26:20.477  4799  4822 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-17 13:26:20.627  1021  3138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-17 13:26:20.637  1021  3138 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:20.637  1021  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:20.637  1021  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 13:26:20.657  4449  4474 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 13:26:20.697  1021  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:20.697  1021  1496 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:20.697  1021  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:20.697  1021  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-17 13:26:20.707  4799  4799 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-17 13:26:20.727  4799  4799 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1679-1681)
03-17 13:26:20.727  4799  4799 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:20.737  4799  4799 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {132f57a0}
,03-17 13:26:20.737  4799  4799 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:20.737  4799  4799 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 13:26:20.747  4799  4799 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 13:26:20.747  4799  4799 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:20.747  4799  4799 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 13:26:20.767  4799  4799 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 13:26:20.767  4799  4799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 13:26:20.767  4799  4799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 13:26:20.767  4799  4799 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 13:26:20.767  4799  4799 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:26:20.767  4799  4799 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:26:20.767  4799  4799 I Adreno-EGL: Local Branch: 
03-17 13:26:20.767  4799  4799 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:26:20.767  4799  4799 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:26:20.767  4799  4799 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 13:26:20.837  4799  4852 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-17 13:26:20.847  3912  4797 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 13:26:20.857  4799  4799 I NSApplication: Starting up...
,03-17 13:26:20.867  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.867  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.867  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.867  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.887  4857  4857 E Zygote  : MountEmulatedStorage(),
03-17 13:26:20.887  4857  4857 E Zygote  : v2
,03-17 13:26:20.887  1021  1306 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4857 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:20.887  4857  4857 I libpersona: KNOX_SDCARD checking this for 10081
03-17 13:26:20.887  4857  4857 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:20.887  4857  4857 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:20.887  4857  4857 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:20.887  4857  4857 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-17 13:26:20.907  4857  4857 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.907  4857  4857 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.977  3912  4797 I Babel   : connection state changed from UNKNOWN to CONNECTED
,03-17 13:26:20.987  1021  3139 I ActivityManager: Killing 4141:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31,
,03-17 13:26:21.107  1021  1045 W libprocessgroup: failed to open /acct/uid_10152/pid_4141/cgroup.procs: No such file or directory
,03-17 13:26:21.147  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.147  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 13:26:21.147  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.147  1021  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.157  4875  4875 E Zygote  : MountEmulatedStorage()
03-17 13:26:21.157  1021  3140 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4875 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-17 13:26:21.157  4875  4875 E Zygote  : v2
03-17 13:26:21.157  4875  4875 I libpersona: KNOX_SDCARD checking this for 10120
03-17 13:26:21.157  4875  4875 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:21.157  4875  4875 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:21.157  1021  3140 I ActivityManager: Killing 4182:com.sec.modem.settings/1000 (adj 15): empty #31
,03-17 13:26:21.167  4875  4875 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:21.167  4875  4875 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:21.187  4875  4875 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:21.187  4875  4875 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:21.207  4875  4875 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:21.237  4361  4772 I SA      : [RC New] [v2liruge] api execute + 793
,03-17 13:26:21.237  4361  4772 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-17 13:26:21.237  4361  4772 I System.out: AsyncTask #1 calls detatch()
,03-17 13:26:21.277  1021  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_4182/cgroup.procs: No such file or directory
,03-17 13:26:21.277   289   289 E SMD     : DCD OFF
,03-17 13:26:21.287  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 13:26:21.287  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:21.287  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:21.287  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:21.287  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:21.287  1196  1196 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:21.317  4361  4772 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-17 13:26:21.317  4361  4772 I SA      : [OCP] update openData : PL
,03-17 13:26:21.327  4361  4772 I SA      : [TPMU] getNetworkMcc : 
,03-17 13:26:21.327  4361  4772 I SA      : [SCU] saveMccToPreferece Start
,03-17 13:26:21.327  4361  4772 I SA      : [SCU] RegionMCC : 260
,03-17 13:26:21.327  4361  4772 I SA      : [SSP] query invoked
,03-17 13:26:21.327  4361  4772 I SA      : [TPMU] GetMccFromDB : null
,03-17 13:26:21.327  4361  4772 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-17 13:26:21.327  4361  4772 I SA      : [SCU] saveMccToPreferece End
,03-17 13:26:21.337  4361  4772 I SA      : [RC New] executeRequest [v2liruge] end. 931
03-17 13:26:21.337  4361  4772 I SA      : [RC New] Execute end
,03-17 13:26:21.337  4361  4361 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-17 13:26:21.337  4361  4361 I SA      : [OR] GetMyCountryZoneTask Success
,03-17 13:26:21.447  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 14 sec
,03-17 13:26:21.547  1021  3139 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1021) eventTime = 52501
,03-17 13:26:21.547  1021  3139 D PowerManagerService: [s] UserActivityState : 2 -> 1
,03-17 13:26:21.547  1021  3139 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1021 (0x0)
,03-17 13:26:21.547  1021  3139 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1021, ws=WorkSource{10054}) (elapsedTime=3487)
,03-17 13:26:21.637  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.637  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.637  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.637  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.647  4895  4895 E Zygote  : MountEmulatedStorage()
,03-17 13:26:21.647  4895  4895 E Zygote  : v2
03-17 13:26:21.647  4895  4895 I libpersona: KNOX_SDCARD checking this for 10010
03-17 13:26:21.647  4895  4895 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:21.657  4895  4895 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 13:26:21.657  1021  3141 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4895 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 13:26:21.657  4895  4895 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:21.657  4895  4895 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 13:26:21.667  1021  3141 I ActivityManager: Killing 4037:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-17 13:26:21.687  4895  4895 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:21.687  4895  4895 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:21.777  1021  1045 W libprocessgroup: failed to open /acct/uid_10072/pid_4037/cgroup.procs: No such file or directory
,03-17 13:26:21.847  4895  4895 D WaitQueueForNetworkActivate: notifyNetworkActivated,
,03-17 13:26:21.907  4487  4556 I System.out: Thread-695(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 13:26:21.907  4487  4556 I System.out: Thread-695(ApacheHTTPLog):isSBSettingEnabled false
03-17 13:26:21.907  4487  4556 I System.out: Thread-695(ApacheHTTPLog):isShipBuild true
03-17 13:26:21.907  4487  4556 I System.out: Thread-695(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 13:26:21.907  4487  4556 I System.out: Thread-695(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 13:26:21.917   279  1003 D EnterpriseController: uids 10092
03-17 13:26:21.917   279  1003 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 13:26:21.917   279  1003 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 13:26:21.967  4895  4895 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-17 13:26:21.967  1021  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:21.967  1021  1497 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-17 13:26:22.077   258  3721 I SurfaceFlinger: id=13 Removed Uoast (8/8)
,03-17 13:26:22.077   258  1106 I SurfaceFlinger: id=13 Removed Uoast (-2/8)
,03-17 13:26:22.097  1021  3140 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-17 13:26:22.097  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.097  1021  3140 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 13:26:22.097  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-17 13:26:22.107  4895  4895 D hcjo    : AutoUpdateManager:IDLE:execute
,03-17 13:26:22.107  1021  1021 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,03-17 13:26:22.107  1021  1021 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-17 13:26:22.107  4895  4895 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
03-17 13:26:22.107  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.107  4895  4895 D InitializeManagerStateMachine: exit::IDLE
03-17 13:26:22.107  4895  4895 D InitializeManagerStateMachine: entry::NETWORK_CHECK
03-17 13:26:22.117  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.117  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.117  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.117  4895  4895 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
,03-17 13:26:22.117  4895  4895 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-17 13:26:22.117  4895  4895 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-17 13:26:22.117  4895  4895 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-17 13:26:22.117  4895  4895 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-17 13:26:22.117  4895  4895 D InitializeManagerStateMachine: entry::SUCCESS
,03-17 13:26:22.117  4895  4895 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-17 13:26:22.127  4919  4919 E Zygote  : MountEmulatedStorage()
03-17 13:26:22.127  4919  4919 E Zygote  : v2
03-17 13:26:22.127  4919  4919 I libpersona: KNOX_SDCARD checking this for 10062
03-17 13:26:22.127  4919  4919 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:22.127  4919  4919 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:22.127  4919  4919 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 13:26:22.127  1021  1046 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4919 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:22.127  4919  4919 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 13:26:22.127  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.127  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.127  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.127  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.147  4930  4930 E Zygote  : MountEmulatedStorage()
03-17 13:26:22.147  4930  4930 E Zygote  : v2
03-17 13:26:22.147  4930  4930 I libpersona: KNOX_SDCARD checking this for 10135
03-17 13:26:22.147  4930  4930 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:22.147  1021  1046 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4930 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-17 13:26:22.147  4930  4930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:22.147  4895  4895 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-17 13:26:22.157  4930  4930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:22.157  4752  4752 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 13:26:22.157  1313  1313 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
03-17 13:26:22.157  4930  4930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:22.157  1313  1313 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 13:26:22.157  1313  1313 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:22.167  4895  4895 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
03-17 13:26:22.167  4895  4895 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
03-17 13:26:22.167  4919  4919 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.167  4919  4919 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.167  1313  1313 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:22.167   309   309 I art     : Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 24.286ms
,03-17 13:26:22.167  1313  1313 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-17 13:26:22.167  4895  4895 D InitializeManagerStateMachine: exit::SUCCESS
03-17 13:26:22.167  4895  4895 D InitializeManagerStateMachine: entry::IDLE
,03-17 13:26:22.177  4752  4752 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-17 13:26:22.187  4930  4930 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:22.187  4930  4930 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:22.187  1313  1313 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,03-17 13:26:22.187  1313  1313 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 13:26:22.187  1313  1313 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 13:26:22.187  1313  1313 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 13:26:22.187  1313  1313 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 13:26:22.187  1313  1313 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 13:26:22.187  1313  1313 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 13:26:22.187   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.436ms
,03-17 13:26:22.187  1313  1313 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 13:26:22.197  3728  3728 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Mar 17 13:26:22 GMT+01:00 2016
03-17 13:26:22.197  1021  1033 I ActivityManager: Killing 4215:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 13:26:22.207  1313  1313 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 13:26:22.207  1313  1313 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 13:26:22.207  1313  1313 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 13:26:22.207  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 13:26:22.207  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.207  1021  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.207  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
03-17 13:26:22.207  1313  1313 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 13:26:22.207   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 18.613ms
,03-17 13:26:22.207  3728  3728 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 13:26:22.217  1313  1313 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 13:26:22.217  4361  4361 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-17 13:26:22.217  3728  3728 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 13:26:22.217  4930  4930 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:22.217  4930  4930 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:22.217  4930  4930 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:22.227  3728  3728 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 13:26:22.227  1313  1313 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,03-17 13:26:22.227  1313  1313 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 13:26:22.227  3728  3728 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 13:26:22.237  3728  4951 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-17 13:26:22.237  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 13:26:22.237  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.237  1021  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:22.237  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:22.237  3728  4951 I KLMS-2.5.183: : KLMSIntentService(): TIME_CHANGED
,03-17 13:26:22.247  3728  4951 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().START : Thu Mar 17 13:26:22 GMT+01:00 2016
03-17 13:26:22.247  4919  4919 I ExternalOEMControlProvider: onCreate
,03-17 13:26:22.257  3728  4951 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().END
,03-17 13:26:22.257  1622  1622 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-17 13:26:22.257  1622  1622 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 13:26:22.257  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.257  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.257  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.257  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.287  4954  4954 E Zygote  : MountEmulatedStorage()
,03-17 13:26:22.287  4954  4954 E Zygote  : v2
03-17 13:26:22.287  4954  4954 I libpersona: KNOX_SDCARD checking this for 10046
03-17 13:26:22.287  4954  4954 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:22.287  4954  4954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 13:26:22.287  1021  1496 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4954 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,03-17 13:26:22.287  4954  4954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 13:26:22.287  1021  1496 I ActivityManager: Killing 4248:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-17 13:26:22.287  4954  4954 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.297  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.297  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 13:26:22.297  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.297  1021  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 13:26:22.307  4954  4954 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.307  4954  4954 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.317  4969  4969 E Zygote  : MountEmulatedStorage()
03-17 13:26:22.317  4969  4969 E Zygote  : v2
03-17 13:26:22.317  4969  4969 I libpersona: KNOX_SDCARD checking this for 10085
03-17 13:26:22.317  4969  4969 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:22.317  4969  4969 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 13:26:22.317  1021  1496 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4969 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:22.317  3728  3728 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 13:26:22.327  4969  4969 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:22.327  4969  4969 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.327  4919  4952 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-17 13:26:22.347  4954  4954 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-17 13:26:22.347  4954  4954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:22.347  4954  4954 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 13:26:22.347  4954  4954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:22.347  4954  4954 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 13:26:22.347  4954  4954 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:22.357  4969  4969 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.357  4969  4969 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.377  1021  1377 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 13:26:22.377  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.377  1021  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:22.377  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 13:26:22.377  1313  1324 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:22.377  1021  1045 W libprocessgroup: failed to open /acct/uid_1101/pid_4215/cgroup.procs: No such file or directory
03-17 13:26:22.377  1021  1045 W libprocessgroup: failed to open /acct/uid_10157/pid_4248/cgroup.procs: No such file or directory
,03-17 13:26:22.397  1021  1306 W ActivityManager: userId = 0, bbcId = -10000,
,03-17 13:26:22.397  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
03-17 13:26:22.397  1021  1306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.397  4969  4969 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:22.397  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-17 13:26:22.397  4969  4969 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:22.397  4969  4969 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:22.397  4969  4969 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 13:26:22.397  4969  4969 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:22.397  4969  4969 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 13:26:22.407  4122  4122 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
03-17 13:26:22.407  4122  4122 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-17 13:26:22.407  4122  4122 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 13:26:22.417  1021  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 13:26:22.417  1021  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.417  1021  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:22.417  1021  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:22.427  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.427  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.427  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.427  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.437  4991  4991 E Zygote  : MountEmulatedStorage()
03-17 13:26:22.437  4991  4991 E Zygote  : v2
03-17 13:26:22.437  4991  4991 I libpersona: KNOX_SDCARD checking this for 10157
03-17 13:26:22.437  4991  4991 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:22.437  4991  4991 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:22.447  4991  4991 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:22.447  1021  1033 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4991 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-17 13:26:22.447  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 15 sec
03-17 13:26:22.447  4991  4991 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 13:26:22.467  4991  4991 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:22.467  4991  4991 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.497  4991  4991 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:22.497  1021  1498 D SettingsProvider: name = next_alarm_formatted
,03-17 13:26:22.497  1021  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:22.497  1021  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 13:26:22.497  1021  1498 D SettingsProvider: selectionArgs: false
,03-17 13:26:22.497  1021  1498 D SettingsProvider: selectionArgs: 10085
03-17 13:26:22.497  1021  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:22.497  1021  1498 D SettingsProvider: ret = -1
,03-17 13:26:22.507  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.507  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.507  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.507  1021  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.517  5007  5007 E Zygote  : MountEmulatedStorage()
,03-17 13:26:22.517  1021  3141 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:22.517  5007  5007 E Zygote  : v2
03-17 13:26:22.517  5007  5007 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:22.517  5007  5007 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:22.527  5007  5007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:22.517  1021  3141 I ActivityManager: Killing 4322:com.google.android.youtube/u0a166 (adj 15): empty #31
,03-17 13:26:22.527  1021  3139 I ActivityManager: Killing 4449:com.google.android.gm/u0a101 (adj 15): empty #31
,03-17 13:26:22.527  5007  5007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:22.527  5007  5007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:22.527  4954  4954 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-17 13:26:22.557  5007  5007 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:22.557  5007  5007 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.607  5007  5007 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458217582618
03-17 13:26:22.607  5007  5007 D         : TimeServiceNative: User Time to be set is 1458217582618
03-17 13:26:22.607  5007  5007 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-17 13:26:22.607  5007  5007 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-17 13:26:22.607  5007  5007 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458217582618
,03-17 13:26:22.607  1021  2829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:22.607   326   557 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-17 13:26:22.607  5007  5007 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-17 13:26:22.607   326  5022 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458217582618
03-17 13:26:22.607   326  5022 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458217582618, operation = 0
03-17 13:26:22.607   326  5022 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/8/70 3:39:58
,03-17 13:26:22.607   326  5022 D QC-time-services: Daemon:Value read from RTC seconds = 21613198000
03-17 13:26:22.607   326  5022 D QC-time-services: Daemon:new time 1458217582618 
03-17 13:26:22.607   326  5022 D QC-time-services: Daemon: delta 1436604384618 genoff 1436604384618 
03-17 13:26:22.607   326  5022 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436604384618 to memory
03-17 13:26:22.607   326  5022 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-17 13:26:22.607   326  5022 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 13:26:22.617  4969  4969 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 117.336ms
,03-17 13:26:22.627   326  5022 D QC-time-services: Updating the TOD offset,
03-17 13:26:22.627   326  5022 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436604384618 to memory
03-17 13:26:22.627   326  5022 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 13:26:22.627   326  5022 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation ,
,03-17 13:26:22.637   326  5022 E QC-time-services: Daemon:Update to modem bit set,
03-17 13:26:22.637   326  5022 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-17 13:26:22.637   326  5022 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120639584618
03-17 13:26:22.637  5007  5007 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-17 13:26:22.637  1021  1045 W libprocessgroup: failed to open /acct/uid_10101/pid_4449/cgroup.procs: No such file or directory
03-17 13:26:22.637  1021  1045 W libprocessgroup: failed to open /acct/uid_10166/pid_4322/cgroup.procs: No such file or directory
,03-17 13:26:22.637   326   549 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-17 13:26:22.637   326   557 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-17 13:26:22.637  1021  1305 I ActivityManager: Killing 4508:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,03-17 13:26:22.657  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.657  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.657  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.657  1021  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.667  5023  5023 E Zygote  : MountEmulatedStorage(),
03-17 13:26:22.667  5023  5023 I libpersona: KNOX_SDCARD checking this for 10094
03-17 13:26:22.667  5023  5023 E Zygote  : v2
03-17 13:26:22.667  1021  1391 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5023 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
03-17 13:26:22.667  5023  5023 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 13:26:22.667  5023  5023 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:22.667  1021  1391 I ActivityManager: Killing 4525:com.google.android.gms:car/u0a12 (adj 15): empty #31
,03-17 13:26:22.677  4954  4954 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 115.111ms,
,03-17 13:26:22.677  5023  5023 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:22.687  5023  5023 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.697  5023  5023 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.697  5023  5023 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.727  5023  5023 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-17 13:26:22.727  5023  5023 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 13:26:22.727  5023  5023 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 13:26:22.727  1021  1391 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 13:26:22.727  1021  1391 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.727  1021  1391 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.727  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 13:26:22.727  5023  5023 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-17 13:26:22.737  1021  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.737  1021  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.737  5023  5023 D elm:15183: ElmAgentService : onCreate()
03-17 13:26:22.737  1021  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.737  1021  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.737  5023  5039 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-17 13:26:22.737  5023  5039 D elm:15183: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,03-17 13:26:22.737  5023  5023 D elm:15183: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,03-17 13:26:22.737  5023  5023 D elm:15183: ModuleBase.ModifySetAlarm()
03-17 13:26:22.737  5023  5023 D elm:15183: MDMBridge.getInstance()
03-17 13:26:22.737  5023  5023 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 13:26:22.747  1021  1043 D SensorService: [SO] 0.192 0.402 10.190
,03-17 13:26:22.757  4954  5043 D Mms/ArtClassLoader: init before art
,03-17 13:26:22.757  5042  5042 E Zygote  : MountEmulatedStorage(),
03-17 13:26:22.757  5042  5042 E Zygote  : v2
03-17 13:26:22.757  5042  5042 I libpersona: KNOX_SDCARD checking this for 10134
03-17 13:26:22.757  5042  5042 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:22.767  5042  5042 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 13:26:22.767  4954  4954 D Mms/TelephonyPermission: start operation mode monitor
,03-17 13:26:22.767  1021  1517 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5042 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,03-17 13:26:22.767  5042  5042 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:22.767  1021  1498 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,03-17 13:26:22.767  1021  1045 W libprocessgroup: failed to open /acct/uid_10012/pid_4525/cgroup.procs: No such file or directory
03-17 13:26:22.767  5023  5023 D elm:15183: ElmAgentService : onDestroy().
,03-17 13:26:22.767  5042  5042 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.767  1021  1045 W libprocessgroup: failed to open /acct/uid_10092/pid_4508/cgroup.procs: No such file or directory
,03-17 13:26:22.777  1021  3138 I ActivityManager: Killing 4487:com.dropbox.android/u0a92 (adj 15): empty #31
,03-17 13:26:22.777  1021  1046 I ActivityManager: Waited long enough for: ServiceRecord{298b9eef u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
03-17 13:26:22.777  4954  4954 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:22.787  4954  4954 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-17 13:26:22.787  4954  4954 D Mms/TelephonyPermission: isDefault true
,03-17 13:26:22.787  4954  4954 D Mms/MmsApp: onCreate() com.android.mms
,03-17 13:26:22.797  5042  5042 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.797  5042  5042 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.807  5042  5042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:22.807  5042  5042 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-17 13:26:22.827  4954  4954 D Mms/MmsApp: [start]    initCountryIso consume time = 294.586041
,03-17 13:26:22.827  1021  1391 D CountryDetector: The first listener is added
,03-17 13:26:22.827  4954  4954 D Mms/MmsApp: [end]    initCountryIso consume time = 8.377188
,03-17 13:26:22.837  4954  4954 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.806406
,03-17 13:26:22.837  1021  1306 I ActivityManager: Killing 4581:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 13:26:22.847  4954  4954 D Mms/MmsConfig: before partial update
,03-17 13:26:22.847  1021  2792 D SSRM:n  : SIOP:: AP = 410
,03-17 13:26:22.857   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:26:22.857  4954  4954 D Mms/MmsConfig: Load Resize quality : 80
,03-17 13:26:22.867  4954  4954 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-17 13:26:22.867  4954  4954 D EasySignUpManager_1.0.1: isAuth is false
,03-17 13:26:22.867  4954  4954 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-17 13:26:22.877  1475  2989 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4954
,03-17 13:26:22.877  1475  2989 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.090 ms
,03-17 13:26:22.887  4954  4954 D EasySignUpManager_1.0.1: isAuth is false
,03-17 13:26:22.887  4954  4954 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-17 13:26:22.887  4954  4954 E CscParser: mps_code.dat does not exist
,03-17 13:26:22.887  4954  4954 E CscParser: customer_path =/system/csc/customer.xml
,03-17 13:26:22.887  4954  4954 E CscParser: fileName + /system/csc/customer.xml
,03-17 13:26:22.897  4954  4954 E CscParser: mps_code.dat does not exist
,03-17 13:26:22.897  4954  4954 E CscParser: customer_path =/system/csc/customer.xml
03-17 13:26:22.897  4954  4954 E CscParser: fileName + /system/csc/customer.xml
,03-17 13:26:22.907  4954  4954 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-17 13:26:22.907  4954  4954 D Mms/MmsConfig:  enable multiwindow = true
,03-17 13:26:22.917  4954  4954 E Mms/MessageUtils: setCountryDetector : update country detector info 
,03-17 13:26:22.917  4954  4954 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-17 13:26:22.927  4954  4954 D Mms/MmsConfig: [end]    init() consume time = 92.814583
,03-17 13:26:22.927  4954  4954 D Mms/Contact: [start]    init() consume time = 2.189792
,03-17 13:26:22.937  1475  1495 D TP/MmsSmsProvider: query,matched:13, calling pid = 4954
,03-17 13:26:22.937  1475  1495 D TP/MmsSmsProvider: match 13:Elapsed time : 2.484 ms
,03-17 13:26:22.937  4954  4954 D Mms/Contact: [end]    init consume time = 13.263333
,03-17 13:26:22.947  4954  5063 D Mms/DraftCache: [start]    rebuildCache consume time = 7.954792
,03-17 13:26:22.947  1475  1483 D TP/MmsSmsProvider: query,matched:12, calling pid = 4954
,03-17 13:26:22.957  1475  1483 D TP/MmsSmsProvider: match 12:Elapsed time : 2.044 ms
,03-17 13:26:22.957  4954  5063 D Mms/DraftCache: [end]    rebuildCache consume time = 7.764531
,03-17 13:26:22.957  4954  4954 D Mms/MethodReflector: getSubId is called
,03-17 13:26:22.957  4954  4954 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 13:26:22.957  4954  4954 D Mms/MethodReflector: getTelephonyProperty is called
,03-17 13:26:22.957  4954  4954 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 13:26:22.957  4954  4954 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
,03-17 13:26:22.957  4954  4954 D Mms/DownloadManager: auto download without roaming -> true
03-17 13:26:22.957  4954  4954 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,03-17 13:26:22.957  4954  4954 D Mms/MethodReflector: getSubId is called
,03-17 13:26:22.967  4954  4954 D Mms/MethodReflector: getDefaultSmsSubId is called
,03-17 13:26:22.967  4954  4954 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-17 13:26:22.967  4954  4954 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
,03-17 13:26:22.967  4954  4954 D Mms/MethodReflector: getTelephonyProperty is called
,03-17 13:26:22.967  4954  4954 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-17 13:26:22.967  4954  4954 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
,03-17 13:26:22.967  4954  4954 D Mms/DownloadManager: auto download without roaming -> true
03-17 13:26:22.967  4954  4954 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-17 13:26:22.967  4954  4954 D Mms/DownloadManager: auto download during roaming secondary -> false
03-17 13:26:22.967  4954  4954 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 13:26:22.977  1021  1305 I ActivityManager: Killing 4559:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,03-17 13:26:22.987  1021  1104 V AlarmManager: waitForAlarm result :8
,03-17 13:26:22.987  1021  1104 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:22.997  4954  4954 D ComposerPerformance: 1458217583013 ms / [DONE] Composer constructor
,03-17 13:26:22.997  4954  5064 D Mms/Conversation: [start]    init() consume time = 43.707292
,03-17 13:26:23.007  1475  1723 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-17 13:26:23.007  4954  4954 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-17 13:26:23.007  1021  1045 W libprocessgroup: failed to open /acct/uid_10092/pid_4487/cgroup.procs: No such file or directory
,03-17 13:26:23.007  1021  1045 W libprocessgroup: failed to open /acct/uid_10015/pid_4581/cgroup.procs: No such file or directory
03-17 13:26:23.007  4954  4954 I Mms/ReservationManager: ReservationManager()
,03-17 13:26:23.007  4954  4954 I Mms/ReservationManager: resetAfterConnected()
,03-17 13:26:23.007  1475  1483 D TP/MmsSmsProvider: query,matched:7, calling pid = 4954
,03-17 13:26:23.007  1475  1723 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 13:26:23.007  1475  1723 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-17 13:26:23.017  1475  1723 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 13:26:23.017  1475  1723 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:23.017  1475  1723 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:23.017  1475  1723 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:23.017  1475  1723 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:23.017  1475  1723 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:23.017  1475  1723 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 13:26:23.027  1475  1483 D TP/MmsSmsProvider: match 7:Elapsed time : 14.592 ms
,03-17 13:26:23.027  1475  1723 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-17 13:26:23.027  1475  1723 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 13:26:23.027  4954  5064 D Mms/Conversation: [end]    init consume time = 27.190104
,03-17 13:26:23.027  4954  4954 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 13:26:23.037  4954  5043 D Mms/ArtClassLoader: init [DONE] art
,03-17 13:26:23.037  4954  5064 D Mms/MessagingNotification: [start]    init() consume time = 7.668958
,03-17 13:26:23.037  4954  4954 D Mms/MmsApp: [end]    onCreate() consume time = 3.577136
,03-17 13:26:23.037  4954  5064 D Mms/MessagingNotification: [end]    init consume time = 0.968906
,03-17 13:26:23.037  1021  1377 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,03-17 13:26:23.037  4954  4954 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-17 13:26:23.037  4954  4954 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-17 13:26:23.047  1021  1377 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.047  1021  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:23.047  1021  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 13:26:23.047  1021  1377 I ActivityManager: Killing 4613:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-17 13:26:23.047  4954  5066 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 5.184479
03-17 13:26:23.047  1475  2989 D TP/MmsSmsProvider: query,matched:400, calling pid = 4954
03-17 13:26:23.047  1475  1495 D TP/MmsSmsProvider: query,matched:0, calling pid = 4954
03-17 13:26:23.047  1475  1495 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-17 13:26:23.047  1475  1495 D TP/MmsSmsProvider: match 0:Elapsed time : 2.080 ms
,03-17 13:26:23.057  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,03-17 13:26:23.057  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.057  1021  1306 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 13:26:23.057  4954  4954 D Mms/MethodReflector: getSubId is called
03-17 13:26:23.057  4954  4954 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
03-17 13:26:23.057  4954  5067 D Mms/Synchronizer: [start]    doSync consume time = 9.80125
,03-17 13:26:23.057  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-17 13:26:23.057  4954  5066 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 4.244948
,03-17 13:26:23.057  4954  4954 D Mms/MethodReflector: getTelephonyProperty is called
,03-17 13:26:23.057  4954  4954 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 13:26:23.057  4954  4954 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 13:26:23.057  4954  4954 D Mms/DownloadManager: auto download without roaming -> true
,03-17 13:26:23.057  4954  4954 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-17 13:26:23.057  4954  4954 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 13:26:23.067  1475  2989 D TP/MmsSmsProvider: update, matched:300, calling pid = 4954
,03-17 13:26:23.067  1475  2989 V TP/MmsSmsProvider: syncDBData start
,03-17 13:26:23.067  1475  2989 V TP/MmsSmsProvider: syncDBData sms end
,03-17 13:26:23.067  1475  2989 V TP/MmsSmsProvider: syncDBData mms end
,03-17 13:26:23.067  1475  2989 V TP/MmsSmsProvider: syncDBData end
,03-17 13:26:23.067  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:23.067  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:23.067  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:23.067  1021  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:23.077  5070  5070 E Zygote  : MountEmulatedStorage()
,03-17 13:26:23.077  5070  5070 I libpersona: KNOX_SDCARD checking this for 10072
03-17 13:26:23.077  5070  5070 E Zygote  : v2
03-17 13:26:23.077  5070  5070 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:23.087  5070  5070 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:23.087  5070  5070 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:23.087  5070  5070 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 13:26:23.087  1021  1497 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5070 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,03-17 13:26:23.087  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,03-17 13:26:23.087  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.087  1021  1306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:23.087  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 13:26:23.097  4954  5067 D Mms/Synchronizer: [end]    doSync consume time = 35.813333
03-17 13:26:23.097  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.097  1021  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.097  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.097  1021  1045 W libprocessgroup: failed to open /acct/uid_10057/pid_4559/cgroup.procs: No such file or directory
,03-17 13:26:23.097  1021  1045 W libprocessgroup: failed to open /acct/uid_10068/pid_4613/cgroup.procs: No such file or directory
,03-17 13:26:23.107  1021  3141 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 13:26:23.107  1021  3141 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.107  1021  3141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.107  1021  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.107  1021  1498 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-17 13:26:23.107  1021  1498 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-17 13:26:23.107  1021  1498 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-17 13:26:23.107  1021  1498 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 13:26:23.107  1690  5086 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 13:26:23.107  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.107  1021  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.107  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.117  5070  5070 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:23.117  5070  5070 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:23.117  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.117  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.117  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.117  1690  1690 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 13:26:23.127  4673  4673 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,03-17 13:26:23.137  4673  5089 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 13:26:23.137  1021  1305 I ActivityManager: Killing 4631:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-17 13:26:23.137  1021  1133 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.137  1021  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.137  1021  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.147  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.147  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.147  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.147  1894  1894 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 13:26:23.147  1021  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
03-17 13:26:23.147  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.147  1021  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.147  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.157  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.157  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.157  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.157  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.157  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:23.157  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.167  1021  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.167  4673  5089 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 13:26:23.167  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.167  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.167  4673  5089 I ReactiveServiceManager: Supported : 1
03-17 13:26:23.167  1021  1498 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 13:26:23.167  1021  1498 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 13:26:23.167  5070  5070 D BadgeProvider: onCreate
03-17 13:26:23.167  5070  5070 D BadgeProvider: DatabaseHelper
,03-17 13:26:23.177  1021  1305 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.177  1021  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.177  1021  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.177  1021  1732 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:23.177  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.177  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.177  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.187  4650  4650 D WearableService: callingUid 10012, callindPid: 4650
,03-17 13:26:23.187  1021  1498 D QSEECOMAPI: : Loaded image: APP id = 11
,03-17 13:26:23.187  1021  1496 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.187  1021  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:23.187  1021  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.197  1021  1498 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 13:26:23.197  1021  1498 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,03-17 13:26:23.197  1021  1498 E terrier : handleString: Failed to handle string(-4)
03-17 13:26:23.197  1021  1498 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-17 13:26:23.197  4673  5089 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 13:26:23.197  4673  5089 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 13:26:23.207  1744  5091 E MDM     : [189] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 13:26:23.207  4673  5089 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 13:26:23.207  4673  5089 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:26:23.207  4673  5089 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:26:23.207  4673  5089 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 13:26:23.207  1021  1496 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.207  1021  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.207  1021  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.207  1021  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:23.217  1021  1045 W libprocessgroup: failed to open /acct/uid_10069/pid_4631/cgroup.procs: No such file or directory
,03-17 13:26:23.217  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.217  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.217  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.217  4954  5064 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-17 13:26:23.217  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.227  1021  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:23.227  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.227  1475  1723 D TP/SmsProvider: query,matched:26, calling pid = 4954
,03-17 13:26:23.227  1475  1723 D TP/SmsProvider: match 26:Elapsed time : 1.613 ms
,03-17 13:26:23.227  1021  3140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 13:26:23.237  1021  3140 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.237  1021  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.237  1021  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.237  1894  5092 D LocationInitializer: Restart initialization of location
,03-17 13:26:23.237  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.237  1021  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.237  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.237  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 13:26:23.237  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.237  1021  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.237  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.247  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.247  1021  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.247  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.257  1475  1495 D TP/MmsSmsProvider: query,matched:6, calling pid = 4954
,03-17 13:26:23.257  1021  1732 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:23.267  1475  1495 D TP/MmsSmsProvider: match 6:Elapsed time : 3.714 ms
,03-17 13:26:23.267  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.267  1021  1732 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.267  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.277  1021  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.277  1021  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:23.277  1021  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,03-17 13:26:23.297  1021  1391 I art     : Explicit concurrent mark sweep GC freed 35192(1947KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 30MB/46MB, paused 2.788ms total 168.181ms
,03-17 13:26:23.317  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:23.317  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:23.317  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:23.317  1021  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:23.327  5095  5095 E Zygote  : MountEmulatedStorage()
03-17 13:26:23.327  5095  5095 E Zygote  : v2
,03-17 13:26:23.327  5095  5095 I libpersona: KNOX_SDCARD checking this for 10025
03-17 13:26:23.327  5095  5095 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:23.327  5095  5095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:23.337  5095  5095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 13:26:23.337  5095  5095 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:23.337  1021  1306 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5095 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,03-17 13:26:23.347  1021  3141 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.347  1021  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:23.347  1021  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-17 13:26:23.357  5095  5095 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:23.357  5095  5095 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:23.357  4954  4954 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-17 13:26:23.367  1021  1021 I ValidateNoPeople: mEvictionCount: 0
,03-17 13:26:23.367  1021  3138 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.367  1021  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 13:26:23.367  1021  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
03-17 13:26:23.367  4954  4954 D Mms/Contact: performUpdate:widgetCount=0
,03-17 13:26:23.367  4954  5111 D Mms/ContactsCache: [start]    invalidate() consume time = 270.481979
,03-17 13:26:23.367  4954  5111 D Mms/ContactsCache: [end]    invalidate() consume time = 0.252761
,03-17 13:26:23.377  5095  5095 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 13:26:23.407  1021  3139 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:23.407  1021  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,03-17 13:26:23.407  1021  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.407  1744  1744 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-17 13:26:23.407  1021  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:23.417  1021  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.417  1021  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.417  1021  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.417  1021  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:23.417  1021  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:23.417  1021  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:23.417  1021  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:23.427  5112  5112 E Zygote  : MountEmulatedStorage(),
03-17 13:26:23.427  5112  5112 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:23.427  5112  5112 E Zygote  : v2
03-17 13:26:23.427  5112  5112 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:23.427  5112  5112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 13:26:23.427  1021  1498 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5112 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:23.427  5112  5112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 13:26:23.427  1021  1391 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:23.437  5112  5112 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:23.437  1021  1391 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.437  1021  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:23.437  1021  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:23.447  3082  3145 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 16 sec
,03-17 13:26:23.457  5095  5095 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-17 13:26:23.457  5112  5112 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:23.457  5112  5112 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:23.487  4954  5064 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-17 13:26:23.487  5112  5112 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-17 13:26:23.487  1021  1497 D SecContentProvider2: uri = 14 selection = getSealedState
,03-17 13:26:23.487  1021  1497 D SecContentProvider2: mCursor = null
,03-17 13:26:23.487  1021  1377 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-17 13:26:23.487  1021  1377 D SecContentProvider2: mCursor = null
,03-17 13:26:23.487  5112  5112 V MTPRx   : sealedState: false
03-17 13:26:23.497  5112  5112 V MTPRx   : sealedUsbMassStorageState: false
03-17 13:26:23.497  5112  5112 E MTPRx   : check value of boot_completed is1
03-17 13:26:23.497  5112  5112 E MTPRx   : check booting is completed_sys.boot_completed
,03-17 13:26:23.497  5112  5112 E MTPRx   : Sd-Card path/storage/extSdCard
,03-17 13:26:23.497  5112  5112 E MTPRx   : Status for mount/Unmount :removed
03-17 13:26:23.497  5112  5112 E MTPRx   : SDcard is not available
,03-17 13:26:23.497  5112  5112 W MTPRx   : value of connected istrue
03-17 13:26:23.497  5112  5112 W MTPRx   : value of configured istrue
03-17 13:26:23.497  5112  5112 W MTPRx   : value of mtpEnabled istrue
03-17 13:26:23.497  5112  5112 W MTPRx   : value of ptpEnabled isfalse
,03-17 13:26:23.497  5112  5112 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-17 13:26:23.497  5112  5112 E MTPRx   : mFirstTime: false
,03-17 13:26:23.507  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-17 13:26:23.507  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369,
,03-17 13:26:23.507  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-17 13:26:23.507  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-17 13:26:23.507  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-17 13:26:23.507  5112  5112 D         : MTP: reading debug level property
,03-17 13:26:23.507  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-17 13:26:23.507  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-17 13:26:23.507  5112  5112 E MTPJNIInterface: Getting CryptionKey from JAVA
03-17 13:26:23.507  5112  5112 E MTPRx   : currentUserId is 0
,03-17 13:26:23.507  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-17 13:26:23.517  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-17 13:26:23.517  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-17 13:26:23.517  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-17 13:26:23.517  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-17 13:26:23.517  5112  5112 E MTPRx   : Start observing USB_STATE_MATCH 
,03-17 13:26:23.517  5095  5095 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-17 13:26:23.517  5112  5112 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-17 13:26:23.517  5112  5112 E MTPRx   : is_Privatemode is NOT 1
,03-17 13:26:23.527  1021  1391 D SettingsProvider: name = boot_time_connected
,03-17 13:26:23.527  5112  5112 E MTPRx   : Sending NORMAL_BOOT to stack,
03-17 13:26:23.527  5112  5112 E MTPJNIInterface: noti = 17
03-17 13:26:23.527  1021  1498 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:23.527  1021  1305 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-17 13:26:23.527  5112  5112 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-17 13:26:23.527  1021  1732 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 13:26:23.527  1021  1732 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:23.527  1021  1732 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:23.527  1021  1732 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 13:26:23.537  1021  1033 D SettingsProvider: name = mtp_running_status
,03-17 13:26:23.537  1196  1196 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:23.537  1021  1377 D SettingsProvider: name = mtp_usb_conditions_met
03-17 13:26:23.537  5112  5112 E MTPRx   : else part ... so first time!!!
03-17 13:26:23.537  5112  5112 E MTPPlaObsrvr: inside setContext()
03-17 13:26:23.537  5112  5112 E MTPPlaObsrvr:  inside createplafiles
,03-17 13:26:23.547  5112  5112 E MTPPlaObsrvr: playlist count is0
,03-17 13:26:23.547  5112  5112 E MTPPlaObsrvr:  inside try branch createplafiles
,03-17 13:26:23.547  5112  5112 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-17 13:26:23.547  5112  5112 E MTPPlaObsrvr: Inside registerContentObserver
,03-17 13:26:23.547  5112  5112 E MtpAdbObserver: inside setContext(),
03-17 13:26:23.557  5112  5112 E MtpAdbObserver: Inside registerContentObserver
03-17 13:26:23.557  5112  5112 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-17 13:26:23.557  1021  3141 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 13:26:23.557  1021  3141 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.557  1021  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:23.557  1021  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 13:26:23.557  1021  3138 D SettingsProvider: name = mtp_running_status
,03-17 13:26:23.557  1021  1497 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:23.557  5112  5130 V MtpMediaDBManager: inside deleteAllDB
,03-17 13:26:23.557  5112  5112 E MtpService: onCreate.
,03-17 13:26:23.557  5112  5112 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-17 13:26:23.567  1021  1306 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-17 13:26:23.567  1021  1306 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:23.567  1021  1306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:23.567  1021  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 13:26:23.567  5112  5112 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-17 13:26:23.567  5112  5112 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-17 13:26:23.577  1243  1243 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 13:26:23.577  5112  5112 W MTPRx   : calling native method
03-17 13:26:23.577  5112  5112 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-17 13:26:23.577  1021  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:23.577  1021  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:23.577  1021  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:23.577  1021  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:23.587  5132  5132 E Zygote  : MountEmulatedStorage()
03-17 13:26:23.587  5132  5132 E Zygote  : v2
03-17 13:26:23.587  5132  5132 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:23.587  5132  5132 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:23.587  5132  5132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 13:26:23.597  5112  5130 V MtpMediaDBManager: inside Thread updateDB,
03-17 13:26:23.597  1021  1517 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5132 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:23.597  5132  5132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 13:26:23.597  5112  5112 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
03-17 13:26:23.597  5112  5112 E MTPJNIInterface: noti = 10
,03-17 13:26:23.597  5112  5112 E MtpService: onStartCommand.
03-17 13:26:23.597  5112  5112 W MTPRx   : calling native method
03-17 13:26:23.597  5112  5112 E MTPRx   : Checking the driver time out
03-17 13:26:23.597  5112  5112 E MTPJNIInterface: noti = 2
03-17 13:26:23.597  5112  5112 D         : deleting sockets before message queue initialization
03-17 13:26:23.597  5132  5132 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:23.607  5112  5131 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-17 13:26:23.607  5112  5112 D         : event handler thread is created, so set the flag
03-17 13:26:23.607  5112  5112 E MTPRx   : called native method
03-17 13:26:23.607  5112  5112 E MTPJNIInterface: setting Media scanner status0
03-17 13:26:23.607  5112  5112 E MTPJNIInterface: After setting Media scanner status0
03-17 13:26:23.607  5112  5112 E MtpService: onStartCommand.
,03-17 13:26:23.607  5112  5131 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-17 13:26:23.607  5112  5130 E MtpMediaDBManager: count : 27
,03-17 13:26:23.607  5112  5112 W MTPRx   : notification from stack 1
,03-17 13:26:23.607  5112  5141 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-17 13:26:23.607  5112  5141 E MTPJNIInterface: Getting media scanner status0
,03-17 13:26:23.617  5112  5141 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A5)
,03-17 13:26:23.627  5112  5130 W MtpMediaDBManager: sending db update complete noti to stack
03-17 13:26:23.627  5112  5130 E MTPJNIInterface: noti = 29
,03-17 13:26:23.627  5132  5132 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:23.627  5132  5132 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:23.637  5112  5141 E MTPJNIInterface: Status for mount/Unmount :removed
,03-17 13:26:23.637  5112  5141 E MTPJNIInterface: SDcard is not available
,03-17 13:26:23.677  5112  5141 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-17 13:26:23.677  5112  5141 E MTPJNIInterface: Status for mount/Unmount :removed
,03-17 13:26:23.687  5112  5141 E MTPJNIInterface: SDcard is not available
03-17 13:26:23.687  5112  5141 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:23.687  5112  5141 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 13:26:23.687  5112  5141 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:23.687  5112  5141 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 13:26:23.687  5112  5141 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:23.687  5112  5141 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 13:26:23.687  5112  5141 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:23.687  5112  5141 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-17 13:26:23.687  5112  5112 W MTPRx   : notification from stack 2
,03-17 13:26:23.687  5112  5148 D         : [mtp_init_device] Library open with 32 bits.
,03-17 13:26:23.687  5112  5148 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-17 13:26:23.687  5112  5148 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-17 13:26:23.687  5112  5148 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-17 13:26:23.687  5112  5148 E         :  [sua_support_present:1287] returning false 
,03-17 13:26:23.687  5112  5148 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-17 13:26:23.687  5132  5132 D TMNetworkReceiver: TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
03-17 13:26:23.687  5132  5132 D TMNetworkReceiver: TMNetworkReceiver.onReceive() Enter
,03-17 13:26:23.687  5132  5132 D TMNetworkReceiver: MirrorLink feauture level: using UEvent
,03-17 13:26:23.697  1021  3139 I ActivityManager: Killing 4673:com.sec.pcw.device/1000 (adj 15): empty #31

```
