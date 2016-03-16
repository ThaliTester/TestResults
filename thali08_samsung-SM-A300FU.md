#### Test 63012666c2ddc84_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-16 06:28:52.884  1020  1044 I CrashAnrDetector: onPackageAdded : com.test.thalitest
--------- beginning of system
03-16 06:28:52.884  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2997/cgroup.procs: No such file or directory
03-16 06:28:52.904  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:52.904  1020  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:52.904  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
03-16 06:28:52.904  1996  1996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
03-16 06:28:52.914  1996  1996 D SecUISvc: Service started flags 0 startId 1
03-16 06:28:52.924  1996  3878 D SecUISvc: Thread created.
03-16 06:28:52.934  1020  1033 D SettingsProvider: name = media_player_mode
03-16 06:28:52.934  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:52.934  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:52.934  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 06:28:52.944  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:52.954  1020  1032 D SettingsProvider: name = mtp_usb_conditions_met
03-16 06:28:52.964  1020  1141 D SettingsProvider: name = mtp_running_status
03-16 06:28:52.974  1020  1302 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:52.974  1020  1302 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:52.974  1020  1302 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
03-16 06:28:52.974  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:52.984  2099  3882 D FileApkUtils: Optimizing (staging complete)
03-16 06:28:52.984  2099  3882 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
03-16 06:28:52.984  2099  3882 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-16 06:28:52.994  3842  3842 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
03-16 06:28:52.994  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:52.994  2099  3882 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
03-16 06:28:52.994  3842  3842 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-16 06:28:52.994  3842  3842 D UserAnalysis: Create SecureDbHelper
03-16 06:28:52.994  1020  1559 D SettingsProvider: name = media_mount_count
03-16 06:28:53.004  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:53.024  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:53.024  3842  3842 D IntelligenceServiceApplication: onCreate()
03-16 06:28:53.024  3842  3842 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
03-16 06:28:53.024  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:53.024  1020  1302 D SettingsProvider: name = mtp_sync_alive
03-16 06:28:53.024  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:53.024  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:53.024  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:53.044  3888  3888 E Zygote  : MountEmulatedStorage()
03-16 06:28:53.044  3888  3888 E Zygote  : v2
03-16 06:28:53.044  3888  3888 I libpersona: KNOX_SDCARD checking this for 10056
03-16 06:28:53.044  3888  3888 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:53.044  3888  3888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:53.044  3888  3888 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:53.044  3888  3888 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:28:53.044  1020  1303 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3888 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-16 06:28:53.054  1020  1558 D SettingsProvider: name = sdcard_launch
03-16 06:28:53.054  1020  1044 W libprocessgroup: failed to open /acct/uid_10077/pid_2649/cgroup.procs: No such file or directory
03-16 06:28:53.054  1020  1044 W libprocessgroup: failed to open /acct/uid_10039/pid_2492/cgroup.procs: No such file or directory
03-16 06:28:53.054  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:53.054  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3118/cgroup.procs: No such file or directory
03-16 06:28:53.064  1020  1044 W libprocessgroup: failed to open /acct/uid_10141/pid_2626/cgroup.procs: No such file or directory
03-16 06:28:53.064  1020  1044 W libprocessgroup: failed to open /acct/uid_10097/pid_3143/cgroup.procs: No such file or directory
03-16 06:28:53.064  1020  1503 D SettingsProvider: name = boot_time_connected
03-16 06:28:53.064  3842  3842 D IntelligenceServiceApplication: no applications having user consent for prediction
03-16 06:28:53.064  1020  1044 W libprocessgroup: failed to open /acct/uid_1101/pid_3174/cgroup.procs: No such file or directory
03-16 06:28:53.064  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:53.074  1020  1303 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:53.074   309   309 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 675us total 31.276ms
03-16 06:28:53.074  1020  1303 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:53.074  1020  1303 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 06:28:53.084  3842  3842 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-16 06:28:53.084  1020  1557 D SettingsProvider: name = mtp_open_session
03-16 06:28:53.094   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 691us total 18.445ms
03-16 06:28:53.104  3888  3888 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:53.104  3888  3888 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:53.114   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 17.977ms
03-16 06:28:53.144  3444  3523 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
03-16 06:28:53.164  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:53.164  3616  3616 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 06:28:53.164  3616  3616 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 06:28:53.164  3616  3616 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 06:28:53.164  3616  3616 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-16 06:28:53.164  3616  3616 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-16 06:28:53.164  3616  3616 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
03-16 06:28:53.164  3842  3842 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-16 06:28:53.164  3842  3842 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
03-16 06:28:53.184  1020  1404 D NtpTrustedTime: requestTime Success from server:north-america.pool.ntp.org mCachedNtpTime : 1458106133699 mCachedNtpElapsedRealtime : 43050 mCachedNtpCertainty : 100
03-16 06:28:53.184  1020  1404 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 06:28:53.184  1020  1404 D AlarmManagerService: Setting time of day to sec=1458106133
03-16 06:28:53.184  1020  1404 D AlarmManagerService: Trying to open a file
03-16 06:28:53.194  1020  1404 D AlarmManagerService: File Open Success
03-16 06:28:53.194  1020  1404 D AlarmManagerService: File Close Success
03-16 06:28:53.194  1020  1404 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
03-16 06:28:53.699  1020  1404 W AlarmManagerService: Unable to set rtc to 1458106133: Invalid argument
03-16 06:28:53.699  1020  1098 V AlarmManager: waitForAlarm result :65536
03-16 06:28:53.699  1020  1098 V AlarmManager: No more alarm at this time.nowELAPSED=43070 batch.start=48437
03-16 06:28:53.699  1020  1020 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
03-16 06:28:53.699  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
03-16 06:28:53.699  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
03-16 06:28:53.708  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
03-16 06:28:53.708  1020  1020 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
03-16 06:28:53.718  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
03-16 06:28:53.718  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-16 06:28:53.718  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
03-16 06:28:53.728  1758  1758 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_SET
03-16 06:28:53.728  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
03-16 06:28:53.728  2099  3906 I Icing   : Storage manager: low false usage 2.10MB avail 9.95GB capacity 11.63GB
03-16 06:28:53.728  1020  1020 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-16 06:28:53.728  1020  1302 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-16 06:28:53.728  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-16 06:28:53.728  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-16 06:28:53.738  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-16 06:28:53.738  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
03-16 06:28:53.738  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:53.738  1020  1805 D SettingsProvider: name = lockscreen_zoom_panning_effect
03-16 06:28:53.738  1020  1805 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 06:28:53.738  1020  1805 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 06:28:53.738  1020  1805 D SettingsProvider: selectionArgs: false
03-16 06:28:53.738  1020  1805 D SettingsProvider: selectionArgs: 10049
03-16 06:28:53.738  1020  1805 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 06:28:53.738  1020  1805 D SettingsProvider: ret = -1
03-16 06:28:53.738  1020  1020 I DrmEventService:  no response from SecureClock 
03-16 06:28:53.748  1020  1805 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
03-16 06:28:53.748  3574  3704 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
03-16 06:28:53.748  1176  1176 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
03-16 06:28:53.758  1176  1176 D KeyguardEffectViewController: isPreloadedWallpaper=true
03-16 06:28:53.758  1176  1176 I GeometricMosaic_Keyguard: update
03-16 06:28:53.768  3574  3704 I LibraryLoader: Loading: webviewchromium
03-16 06:28:53.768  1176  1176 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
03-16 06:28:53.818  3574  3704 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 3142-3197)
03-16 06:28:53.818  3574  3704 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 06:28:53.828  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
03-16 06:28:53.838  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
03-16 06:28:53.838  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
03-16 06:28:53.838  3574  3704 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 06:28:53.838  1758  1758 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-16 06:28:53.838  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
03-16 06:28:53.838  1758  1758 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-16 06:28:53.838  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
03-16 06:28:53.838  3888  3888 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
03-16 06:28:53.838  1758  1758 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 06 28
03-16 06:28:53.888  1176  1206 I art     : Background partial concurrent mark sweep GC freed 24101(1031KB) AllocSpace objects, 6(136KB) LOS objects, 40% free, 18MB/30MB, paused 1.984ms total 110.762ms
03-16 06:28:53.918  1176  1176 I KeyguardEffectViewUtil: set current wallpaper info
03-16 06:28:53.928  1020  1033 D SettingsProvider: name = keyguard_current_wallpaper_type
03-16 06:28:53.928  1020  1033 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 06:28:53.928  1020  1033 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 06:28:53.928  1020  1033 D SettingsProvider: selectionArgs: false
03-16 06:28:53.928  1020  1033 D SettingsProvider: selectionArgs: 10049
03-16 06:28:53.928  1020  1033 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 06:28:53.928  1020  1033 D SettingsProvider: ret = -1
03-16 06:28:53.938  1020  1033 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
03-16 06:28:53.938  1020  1303 D SettingsProvider: name = keyguard_current_wallpaper_file_path
03-16 06:28:53.938  1020  1303 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 06:28:53.938  1020  1303 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 06:28:53.938  1020  1303 D SettingsProvider: selectionArgs: false
03-16 06:28:53.938  1020  1303 D SettingsProvider: selectionArgs: 10049
03-16 06:28:53.938  1020  1303 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 06:28:53.938  1020  1303 D SettingsProvider: ret = -1
03-16 06:28:53.948  1020  1303 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
03-16 06:28:53.948  1020  1560 D SettingsProvider: name = keyguard_current_wallpaper_res_id
03-16 06:28:53.948  1020  1560 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 06:28:53.948  1020  1560 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 06:28:53.948  1020  1560 D SettingsProvider: selectionArgs: false
03-16 06:28:53.948  1020  1560 D SettingsProvider: selectionArgs: 10049
03-16 06:28:53.948  1020  1560 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 06:28:53.948  1020  1560 D SettingsProvider: ret = -1
03-16 06:28:53.948   292   292 E SMD     : DCD OFF
03-16 06:28:53.968  3503  3809 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
03-16 06:28:53.968  3503  3809 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
03-16 06:28:53.968  3503  3809 I System.out: Thread-531(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-16 06:28:53.968  3503  3809 I System.out: Thread-531(ApacheHTTPLog):isSBSettingEnabled false
03-16 06:28:53.968  3503  3809 I System.out: Thread-531(ApacheHTTPLog):isShipBuild true
03-16 06:28:53.968  3503  3809 I System.out: Thread-531(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-16 06:28:53.968  3503  3809 I System.out: Thread-531(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-16 06:28:53.988   279  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 06:28:53.988   279  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10161
03-16 06:28:53.988  1020  1560 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
03-16 06:28:54.048   279  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 06:28:54.048   279  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10052
03-16 06:28:54.058  3895  3895 D AndroidRuntime: 
03-16 06:28:54.058  3895  3895 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 06:28:54.058  3895  3895 D AndroidRuntime: CheckJNI is OFF
03-16 06:28:54.058  3895  3895 D AndroidRuntime: readGMSProperty: start
03-16 06:28:54.058  3895  3895 D AndroidRuntime: readGMSProperty: already setted!!
03-16 06:28:54.058  3895  3895 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 06:28:54.058  3895  3895 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 06:28:54.058  3895  3895 D AndroidRuntime: readGMSProperty: end
03-16 06:28:54.058  3895  3895 D AndroidRuntime: addProductProperty: start
03-16 06:28:54.068  1176  1531 D TEST    : run!!!
03-16 06:28:54.078  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:54.078  3616  3616 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
03-16 06:28:54.088  1176  1531 I GeometricMosaic_Renderer: setBackgroundBitmap
03-16 06:28:54.098  1020  1559 I ActivityManager: Killing 3226:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
03-16 06:28:54.108  3574  3704 I qtaguid : Tagging socket 42 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.108  1324  3428 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
03-16 06:28:54.108  1020  1509 I ActivityManager: Killing 3241:flipboard.app/u0a96 (adj 15): empty #31
03-16 06:28:54.108  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.108  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.108  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.108  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.118  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:54.118  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:54.128  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:54.128  3616  3616 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
03-16 06:28:54.128  3931  3931 E Zygote  : MountEmulatedStorage()
03-16 06:28:54.128  3931  3931 E Zygote  : v2
03-16 06:28:54.128  3931  3931 I libpersona: KNOX_SDCARD checking this for 10058
03-16 06:28:54.128  3931  3931 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:54.138  3931  3931 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:54.138  3931  3931 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:54.138  3931  3931 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:28:54.148  1020  1509 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3931 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 06:28:54.148  1020  1509 I ActivityManager: Killing 3258:com.sec.usbsettings/1000 (adj 15): empty #31
03-16 06:28:54.158  1176  1176 D KeyguardEffectViewController: isPreloadedWallpaper=true
03-16 06:28:54.158  3616  3616 I ReactiveServiceManager: Supported : 1
03-16 06:28:54.158  1020  1557 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-16 06:28:54.158  1020  1557 D QSEECOMAPI: : App is not loaded in QSEE
03-16 06:28:54.158  1324  3428 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
03-16 06:28:54.168  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.168  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.168  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
03-16 06:28:54.178  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 06:28:54.178  1020  1557 D QSEECOMAPI: : Loaded image: APP id = 10
03-16 06:28:54.178  1324  3428 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
03-16 06:28:54.178  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 06:28:54.178  1020  1033 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-16 06:28:54.178  1020  1558 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-16 06:28:54.188  1020  1557 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-16 06:28:54.188  1020  1557 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
03-16 06:28:54.188  1020  1557 E terrier : handleString: Failed to handle string(-4)
03-16 06:28:54.188  1020  1557 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-16 06:28:54.188  3616  3616 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-16 06:28:54.188  3616  3616 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-16 06:28:54.188  3931  3931 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:54.188  3616  3616 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 06:28:54.188  3616  3616 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 06:28:54.188  3616  3616 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 06:28:54.188  3616  3616 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
03-16 06:28:54.188  3931  3931 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:54.198  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.198  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.198  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.198  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.208  3957  3957 E Zygote  : MountEmulatedStorage()
03-16 06:28:54.208  3957  3957 E Zygote  : v2
03-16 06:28:54.208  3957  3957 I libpersona: KNOX_SDCARD checking this for 10028
03-16 06:28:54.208  3957  3957 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:54.208  3957  3957 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:54.208  3957  3957 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:54.208  3957  3957 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 06:28:54.218  1020  1033 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3957 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-16 06:28:54.238  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3258/cgroup.procs: No such file or directory
03-16 06:28:54.238  1020  1044 W libprocessgroup: failed to open /acct/uid_10096/pid_3241/cgroup.procs: No such file or directory
03-16 06:28:54.238  1020  1044 W libprocessgroup: failed to open /acct/uid_10153/pid_3226/cgroup.procs: No such file or directory
03-16 06:28:54.248  3957  3957 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:54.248  3957  3957 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:54.248  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.248  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.248  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.248  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.248  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.248  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.248  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.248  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.248  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.248  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.248  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.248  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.248  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.248  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.248  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.248  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.248  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.248  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.248  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.248  3798  3948 I Gmail   : getAccountsCursor
03-16 06:28:54.248  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.258  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.258  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.258  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.258  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.258  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.258  3574  3704 I qtaguid : Untagging socket 46
03-16 06:28:54.258  3798  3956 I Gmail   : Observing account changes for notifications
03-16 06:28:54.258  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 06:28:54.308  3798  3798 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-16 06:28:54.348  1020  1303 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.348  1020  1303 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.348  1020  1303 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-16 06:28:54.368  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.368  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.368  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
03-16 06:28:54.378  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.378  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.378  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 06:28:54.398  3574  3704 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3574, getuid(): 10052
03-16 06:28:54.398  3574  3743 I ContactAccountLoggerTas: canRun() : Opted Out
03-16 06:28:54.418  3931  3931 I ExternalOEMControlProvider: onCreate
03-16 06:28:54.418  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.418  1020  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.418  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-16 06:28:54.418  3574  3704 W GAV2    : Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-16 06:28:54.418  1020  1303 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-16 06:28:54.428  3503  3809 I System.out: Thread-531 calls detatch()
03-16 06:28:54.428  3574  3704 W GAV2    : Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
03-16 06:28:54.428  3574  3743 I ContactAccountLoggerTas: canRun() : Opted Out
03-16 06:28:54.428  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.428  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.428  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.428  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.438  3982  3982 E Zygote  : MountEmulatedStorage()
03-16 06:28:54.438  3982  3982 E Zygote  : v2
03-16 06:28:54.438  3982  3982 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:28:54.438  3982  3982 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:54.448  1020  1559 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 06:28:54.448  3982  3982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:54.448  1020  1559 I ActivityManager: Killing 2382:com.android.mms/u0a41 (adj 15): empty #31
03-16 06:28:54.448  3982  3982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:54.448  3982  3982 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:28:54.458  1020  1511 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-16 06:28:54.458  1020  1511 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 06:28:54.458  1020  1511 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 06:28:54.458  1020  1511 D SettingsProvider: selectionArgs: false
03-16 06:28:54.458  1020  1511 D SettingsProvider: selectionArgs: 10058
03-16 06:28:54.458  1020  1511 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 06:28:54.458  1020  1511 D SettingsProvider: ret = -1
03-16 06:28:54.478  3982  3982 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:54.478  3982  3982 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:54.508  3982  3982 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 06:28:54.528  3982  3982 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-16 06:28:54.528  3982  3982 I ServiceMode: setReferenceIsDumpState : 0
03-16 06:28:54.538  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.538  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.538  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.538  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.538  1020  1558 D CountryDetector: No listener is left
03-16 06:28:54.548  2985  3051 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
03-16 06:28:54.568  4000  4000 E Zygote  : MountEmulatedStorage()
03-16 06:28:54.568  4000  4000 E Zygote  : v2
03-16 06:28:54.568  4000  4000 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:28:54.568  4000  4000 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:54.568  1020  1557 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=4000 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 06:28:54.568  1020  1557 I ActivityManager: Killing 3276:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
03-16 06:28:54.568  4000  4000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:54.578  1020  1558 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.578  1020  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.578  1020  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 06:28:54.578  4000  4000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:54.578  4000  4000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:28:54.588  1020  1511 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
03-16 06:28:54.588  1020  1560 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-16 06:28:54.588  1020  1560 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 06:28:54.588  1020  1560 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 06:28:54.588  1020  1560 D SettingsProvider: selectionArgs: false
03-16 06:28:54.588  1020  1560 D SettingsProvider: selectionArgs: 10058
03-16 06:28:54.588  1020  1560 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 06:28:54.588  1020  1560 D SettingsProvider: ret = -1
03-16 06:28:54.598  1020  1560 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
03-16 06:28:54.598  3574  3704 I ContactLabelSupplier: get() : OptedIn = false
03-16 06:28:54.608  4000  4000 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:54.608  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:54.608  4000  4000 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:54.628  3798  4011 E Gmail   : Error finding the version of the Email provider.....
03-16 06:28:54.628  3798  4011 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-16 06:28:54.628  3798  4011 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-16 06:28:54.628  3798  4011 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-16 06:28:54.628  3798  4011 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-16 06:28:54.628  3798  4011 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 06:28:54.628  3798  4011 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 06:28:54.628  3798  4011 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-16 06:28:54.628  3798  4011 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 06:28:54.628  3798  4011 W EmailMigration: We do not support migrating this version of the Email provider.
03-16 06:28:54.638  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:28:54.638  1020  1511 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.638  1020  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.638  1020  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-16 06:28:54.638  1020  1044 W libprocessgroup: failed to open /acct/uid_10041/pid_2382/cgroup.procs: No such file or directory
03-16 06:28:54.638  1020  1044 W libprocessgroup: failed to open /acct/uid_10043/pid_3276/cgroup.procs: No such file or directory
03-16 06:28:54.648  3444  3523 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
03-16 06:28:54.648  3798  3916 I Gmail   : getAccountsCursor
03-16 06:28:54.648  1822  2234 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-16 06:28:54.648  1822  2234 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-16 06:28:54.648  1822  2234 I System.out: (HTTPLog)-Static: isShipBuild true
03-16 06:28:54.648  1822  2234 I System.out: (HTTPLog)-Thread-189-273854478: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-16 06:28:54.648  1822  2234 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-16 06:28:54.658   279  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 06:28:54.658   279  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
03-16 06:28:54.658  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 06:28:54.668  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.668  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.668  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-16 06:28:54.668  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 06:28:54.778  4000  4000 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
03-16 06:28:54.778  3957  3957 I System.out: Inside onCreate() of WakeupTriggerProvide
03-16 06:28:54.778  3957  3957 I System.out: Inside WakeupProvider
03-16 06:28:54.778  4000  4000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
03-16 06:28:54.828  1020  1511 I art     : Explicit concurrent mark sweep GC freed 24060(1230KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 4.461ms total 149.917ms
03-16 06:28:54.828  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.828  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.828  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
03-16 06:28:54.838  1822  2234 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
03-16 06:28:54.838  1822  2234 I qtaguid : Tagging socket 75 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1822, getuid(): 10011
03-16 06:28:54.848  3895  3895 E AffinityControl: AffinityControl: registerfunction enter
03-16 06:28:54.848  3798  4017 E SQLiteLog: (283) recovered 50 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
03-16 06:28:54.858  1020  1557 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.858  1020  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:54.858  1020  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
03-16 06:28:54.858  1020  1805 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-16 06:28:54.868  4000  4000 D NPS_WSSNPS: [] Service onCreate!!
03-16 06:28:54.868  1020  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.868  1020  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.868  1020  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.868  1020  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.878  3895  3895 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 06:28:54.878  4025  4025 E Zygote  : MountEmulatedStorage()
03-16 06:28:54.878  4025  4025 E Zygote  : v2
03-16 06:28:54.878  4025  4025 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:28:54.878  4025  4025 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:54.878  4025  4025 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:54.888  4025  4025 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:54.888  4025  4025 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:28:54.888  1020  1558 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=4025 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 06:28:54.898  2099  2099 W InstanceID/Rpc: Found 10011
03-16 06:28:54.898  1020  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.898  1020  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.898  1020  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.898  1020  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:54.908  1822  2234 I qtaguid : Tagging socket 80 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1822, getuid(): 10011
03-16 06:28:54.908  4025  4025 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:54.908  4025  4025 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:54.918  4044  4044 E Zygote  : MountEmulatedStorage()
03-16 06:28:54.918  4044  4044 I libpersona: KNOX_SDCARD checking this for 10102
03-16 06:28:54.918  4044  4044 E Zygote  : v2
03-16 06:28:54.918  4044  4044 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:54.918  1020  1558 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4044 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-16 06:28:54.918  4044  4044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:54.918  4044  4044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:54.918  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.918  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.918  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
03-16 06:28:54.918  4044  4044 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 06:28:54.928  1020  1033 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-16 06:28:54.938  4000  4053 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
03-16 06:28:54.938  3798  3798 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@360610f3 that was originally bound here
03-16 06:28:54.938  3798  3798 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@360610f3 that was originally bound here
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 06:28:54.938  3798  3798 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 06:28:54.938  1020  1503 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@2edf2bb6
03-16 06:28:54.948  4000  4000 D NPS_WSSNPS: [50.150321] smlDBHelper
03-16 06:28:54.948  4044  4044 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:54.948  4044  4044 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:54.958  1651  4030 I GoogleHttpClient: GMS http client unavailable, use old client
03-16 06:28:54.958  1020  1303 E PersonaManagerService: inState():  stateMachine is null !!
03-16 06:28:54.958  1020  1303 I PersonaManagerService: PersonaId don't exist
03-16 06:28:54.958  1020  1303 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-16 06:28:54.958  1020  1557 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:54.958  1020  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:54.958  1020  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
03-16 06:28:54.968  4044  4044 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 06:28:54.988  4000  4000 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
03-16 06:28:55.048  3957  3957 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
03-16 06:28:55.048  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:55.048  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.048  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 06:28:55.078  4000  4064 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
03-16 06:28:55.078  4000  4064 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
03-16 06:28:55.078  4000  4064 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
03-16 06:28:55.128  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:55.128  1020  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:55.128  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
03-16 06:28:55.138  4000  4000 D NPS_WSSNPS: [50.150321] Service onDestroy
03-16 06:28:55.138  1020  1303 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 06:28:55.138  1020  3997 D SettingsProvider: name = access_control_enabled
03-16 06:28:55.218  4000  4000 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
03-16 06:28:55.218  4000  4000 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
03-16 06:28:55.218  4000  4000 I NPS_WSSNPS: [50.150321] smlBREmailDelete
03-16 06:28:55.218  4000  4000 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-16 06:28:55.218  4000  4000 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-16 06:28:55.218  4000  4000 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
03-16 06:28:55.218  4000  4000 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
03-16 06:28:55.218  4000  4000 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
03-16 06:28:55.218  4000  4000 I NPS_WSSNPS: [50.150321] cpuBooster release : false
03-16 06:28:55.238  1020  1303 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-16 06:28:55.238  1020  1303 W ActivityManager: mDVFSHelper.acquire()
03-16 06:28:55.258  1020  1303 D FocusedStackFrame: Set to : 0
03-16 06:28:55.258  3798  4017 E File    : fail readDirectory() errno=2
03-16 06:28:55.268  1020  1303 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 06:28:55.268  1020  1303 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 06:28:55.268  3798  4022 I Gmail   : notifyAccountChanged
03-16 06:28:55.268  1020  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 06:28:55.268  1020  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-16 06:28:55.268  1020  1303 D InputDispatcher: Focused application set to: xxxx
03-16 06:28:55.268  1020  1303 D InputDispatcher: Focus left window: 1492
03-16 06:28:55.268  3895  3895 D AndroidRuntime: Shutting down VM
03-16 06:28:55.278  3798  4022 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-16 06:28:55.278  1492  1492 D Launcher.HomeView: onPause
03-16 06:28:55.278  1492  1492 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-16 06:28:55.278  1020  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.278  1020  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.278  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 06:28:55.278  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 06:28:55.278  1020  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.278  1020  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.288  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 06:28:55.288  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 06:28:55.288   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
03-16 06:28:55.288  3798  4022 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-16 06:28:55.298  4069  4069 E Zygote  : MountEmulatedStorage()
03-16 06:28:55.298  4069  4069 E Zygote  : v2
03-16 06:28:55.298  4069  4069 I libpersona: KNOX_SDCARD checking this for 10065
03-16 06:28:55.298  4069  4069 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:55.298  4069  4069 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:55.298  4069  4069 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:55.298  3798  4022 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-16 06:28:55.298  3798  4022 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-16 06:28:55.298  4069  4069 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:28:55.298  1020  1560 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4069 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 06:28:55.308  1020  1560 I ActivityManager: Killing 3160:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
03-16 06:28:55.308  4000  4000 D NPS_WSSNPS: [50.150321] dsServerSocket close
03-16 06:28:55.318  1020  1805 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:55.318  1020  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.318  1020  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 06:28:55.318  1020  3997 I ActivityManager: Waited long enough for: ServiceRecord{2c35a771 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
03-16 06:28:55.318  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:55.318  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.318  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 06:28:55.328  2962  2962 D FactoryTestApp: [DummyFtClient$onDestroy](2962) Destroy DummyFtClient service
03-16 06:28:55.328  1020  1509 I ActivityManager: Killing 1614:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
03-16 06:28:55.338  2962  2962 D FactoryTestApp: [Support$Values.getString](2962) id=MODEL_COMMUNICATION_MODE, value=gsm
03-16 06:28:55.338  2962  2962 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2962) mConnectionMode = gsm
03-16 06:28:55.338  2962  2962 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2962) RUNNING_FTCLIENT : false
03-16 06:28:55.338  2962  2962 D FactoryTestApp: [DummyFtClient$onDestroy](2962) kill process
03-16 06:28:55.338  2962  2962 I Process : Sending signal. PID: 2962 SIG: 9
03-16 06:28:55.338  4069  4069 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:55.338  4069  4069 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:55.348  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.348  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.348  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.348  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.348  3957  3957 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
03-16 06:28:55.358  4085  4085 E Zygote  : MountEmulatedStorage()
03-16 06:28:55.358  4085  4085 I libpersona: KNOX_SDCARD checking this for 10167
03-16 06:28:55.358  4085  4085 E Zygote  : v2
03-16 06:28:55.358  4085  4085 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:55.368  4085  4085 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:55.368  4085  4085 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:55.368  4085  4085 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 06:28:55.368  1020  1557 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4085 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 06:28:55.378  4085  4085 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:55.378  4085  4085 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:55.388  1020  1302 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:55.388  1020  1302 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.388  1020  1302 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 06:28:55.398  1020  1141 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 06:28:55.398  1020  1141 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 06:28:55.398  1020  1141 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 06:28:55.408  1492  1492 V ActivityThread: updateVisibility : ActivityRecord{111d14e5 token=android.os.BinderProxy@4986ab6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-16 06:28:55.408  1492  1492 D Launcher.HomeView: onStop
03-16 06:28:55.408  1492  1492 V ActivityThread: updateVisibility : ActivityRecord{111d14e5 token=android.os.BinderProxy@4986ab6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-16 06:28:55.418  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 06:28:55.428  1020  1141 D PersonaManager: isKioskContainerExistOnDevice
03-16 06:28:55.438  1020  1044 W libprocessgroup: failed to open /acct/uid_10068/pid_1614/cgroup.procs: No such file or directory
03-16 06:28:55.448  1020  1044 W libprocessgroup: failed to open /acct/uid_10081/pid_3160/cgroup.procs: No such file or directory
03-16 06:28:55.458  1492  1492 D Launcher: onTrimMemory. Level: 20
03-16 06:28:55.478  3895  3895 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-16 06:28:55.488  1020  1557 I ActivityManager: Process com.sec.factory (pid 2962)(adj 0) has died(33,643)
03-16 06:28:55.498  2099  2117 W art     : Suspending all threads took: 50.614ms
03-16 06:28:55.498  1020  1560 I ActivityManager: Killing 3359:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-16 06:28:55.508  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-16 06:28:55.508  1020  1020 D SensorService: [SO] activate (ident=0xb8aa9e00, enabled=0)
,03-16 06:28:55.508  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-16 06:28:55.518  1020  1020 D SensorManager: unregisterListener ::   
,03-16 06:28:55.518  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-16 06:28:55.528  1020  1020 D SensorService: [SO] changed settle time [1]
03-16 06:28:55.528  1020  1020 D SensorService: [SO] setDelay [66000000]
03-16 06:28:55.528  1020  1020 D SensorService: [SO] activate (ident=0xb8bbcd58, enabled=1)
03-16 06:28:55.528  1020  1020 D SensorService: [SO] AR_init
03-16 06:28:55.528  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-16 06:28:55.528  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-16 06:28:55.558  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:55.558  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.558  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:55.568  4069  4069 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-16 06:28:55.578  3574  3743 I ContactAccountLoggerTas: canRun() : Opted Out
,03-16 06:28:55.588  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:55.588  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.588  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:55.598  1020  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-16 06:28:55.628  3957  3957 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-16 06:28:55.628  3957  3957 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-16 06:28:55.628  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3359/cgroup.procs: No such file or directory
,03-16 06:28:55.648  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:28:55.658  3444  3523 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-16 06:28:55.658  3798  3915 I Gmail   : getAccountsCursor
,03-16 06:28:55.668  1020  1042 D SensorService: [SO] -0.460 0.192 9.902
,03-16 06:28:55.668  1020  1042 D SensorService: [SO] [100 -> 255]
,03-16 06:28:55.668  3957  3957 D DialogFlow: initQueue()
,03-16 06:28:55.668  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:28:55.688  4085  4085 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-16 06:28:55.698  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:55.698  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.698  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:55.708  3798  3950 I Gmail   : getAccountsCursor
,03-16 06:28:55.708  4085  4085 I LibraryLoader: Loading: webviewchromium
,03-16 06:28:55.718  2099  4065 D GCM     : COMPAT: Multi user not supported
03-16 06:28:55.718  4085  4085 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 5082-5090)
03-16 06:28:55.718  4085  4085 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 06:28:55.718  1020  1509 I ActivityManager: Killing 2741:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,03-16 06:28:55.728  1020  3997 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:55.728  1020  3997 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.728  1020  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:55.728  1020  1557 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:55.728  1020  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.728  1020  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:55.728  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:28:55.728  4044  4115 I Babel   : MmsConfig: mnc/mcc: 0/0
03-16 06:28:55.728  4044  4115 I Babel   : MmsConfig.loadMmsSettings
,03-16 06:28:55.738  4044  4115 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-16 06:28:55.738  4044  4115 I Babel   : MmsConfig.loadFromDatabase
,03-16 06:28:55.738  1822  4119 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-16 06:28:55.738  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.738  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.738  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:55.738  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:55.738  4085  4085 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3168e07f}
,03-16 06:28:55.748  4085  4085 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 06:28:55.748  4085  4085 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
03-16 06:28:55.748  2099  3906 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 06:28:55.758  4121  4121 E Zygote  : MountEmulatedStorage()
,03-16 06:28:55.758  4121  4121 E Zygote  : v2
03-16 06:28:55.758  4121  4121 I libpersona: KNOX_SDCARD checking this for 10030
03-16 06:28:55.758  4121  4121 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:55.758  4121  4121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:55.758  4121  4121 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:55.758  4121  4121 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-16 06:28:55.768  1020  1032 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4121 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-16 06:28:55.778  1020  1558 W ActivityManager: userId = 0, bbcId = -10000,
03-16 06:28:55.778  1020  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.778  1020  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:55.788  4044  4115 E Babel   : canonicalizeMccMnc: invalid mccmnc 
03-16 06:28:55.788  4044  4115 I Babel   : MmsConfig.loadFromResources
,03-16 06:28:55.788  4044  4115 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
03-16 06:28:55.788  4044  4115 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-16 06:28:55.788  4085  4085 I BrowserStartupController: Initializing chromium process, renderers=0
,03-16 06:28:55.788  4085  4085 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 06:28:55.788  4121  4121 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:55.788  4121  4121 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:55.798  1020  1511 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:55.798  1020  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.798  1020  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:55.808  1020  1303 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:55.808  1020  1303 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.808  1020  1303 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:55.808  1020  1557 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:55.808  1020  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.808  1020  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:55.848  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:55.848  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:55.848  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:55.848  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
03-16 06:28:55.858  4044  4044 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 06:28:55.858  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:28:55.868   258   451 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-16 06:28:55.868   258   441 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-16 06:28:55.878  2099  4142 I CheckinService: Disabling old GoogleServicesFramework version
,03-16 06:28:55.928  4044  4059 W art     : Suspending all threads took: 67.432ms
,03-16 06:28:55.938  4085  4085 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-16 06:28:55.938  4085  4085 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,03-16 06:28:55.948  2099  2116 W art     : Suspending all threads took: 25.874ms
,03-16 06:28:55.948  4085  4085 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,03-16 06:28:55.958  1020  1044 W libprocessgroup: failed to open /acct/uid_10117/pid_2741/cgroup.procs: No such file or directory
,03-16 06:28:55.978  4044  4114 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 06:28:55.988  4085  4085 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 06:28:55.988  4085  4085 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 06:28:55.988  4085  4085 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 06:28:55.988  4085  4085 I Adreno-EGL: Local Branch: 
03-16 06:28:55.988  4085  4085 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 06:28:55.988  4085  4085 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 06:28:55.988  4085  4085 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 06:28:55.998  4121  4121 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 06:28:55.998  4121  4121 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 06:28:55.998  4121  4121 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 06:28:55.998  4044  4114 W AudioCapabilities: Unsupported mime audio/evrc
,03-16 06:28:56.008  4044  4114 W AudioCapabilities: Unsupported mime audio/qcelp
,03-16 06:28:56.008  4044  4114 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-16 06:28:56.008  4044  4114 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-16 06:28:56.018  4044  4114 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-16 06:28:56.028  4044  4114 W AudioCapabilities: Unsupported mime audio/x-ima
,03-16 06:28:56.028  4044  4114 W AudioCapabilities: Unsupported mime audio/qcelp
,03-16 06:28:56.028  4044  4114 W AudioCapabilities: Unsupported mime audio/evrc
,03-16 06:28:56.038  1020  1557 I ActivityManager: Killing 3435:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,03-16 06:28:56.048  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-16 06:28:56.048  1020  1020 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-16 06:28:56.058  2099  2113 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-16 06:28:56.058  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.058  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.058  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.058  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:56.058  2099  2099 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-16 06:28:56.068  2099  4065 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}],
,03-16 06:28:56.068  2099  2099 D BootCompletedReceiver: Got an BootCompleted event.
,03-16 06:28:56.078  4161  4161 E Zygote  : MountEmulatedStorage()
03-16 06:28:56.078  4161  4161 E Zygote  : v2
03-16 06:28:56.078  4161  4161 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:28:56.078  4161  4161 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:56.078  4044  4059 W art     : Suspending all threads took: 5.137ms
,03-16 06:28:56.078  4161  4161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:56.078  4161  4161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:56.078  4161  4161 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:28:56.088  1020  1020 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4161 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 06:28:56.088  4121  4121 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 06:28:56.088  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:56.098  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.098  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:56.098  4121  4121 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 06:28:56.098  4121  4121 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 06:28:56.098  1822  1822 I GCoreUlr: DispatchingService.onCreate()
,03-16 06:28:56.108  2099  2099 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-16 06:28:56.118  2099  4143 I CheckinService: Checking schedule, now: 1458106136133 next: 1458299986961
03-16 06:28:56.118  2099  4143 I CheckinService: active receiver: disabled
,03-16 06:28:56.128  2099  2099 D SystemUpdateService: onCreate
,03-16 06:28:56.138  1020  3997 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:56.138  1020  3997 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.138  1020  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 06:28:56.138  1020  1044 W libprocessgroup: failed to open /acct/uid_10146/pid_3435/cgroup.procs: No such file or directory
,03-16 06:28:56.138  4161  4161 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-16 06:28:56.138  4161  4161 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:56.158  4044  4114 W VideoCapabilities: Unsupported mime video/wvc1
,03-16 06:28:56.158  4044  4044 V Babel   : babel boot account: SMS
03-16 06:28:56.158  4044  4044 V Babel   : babel boot account: thalitester@gmail.com
,03-16 06:28:56.168  4044  4114 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-16 06:28:56.168  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:56.168  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.168  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.168  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:56.178  4121  4121 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-16 06:28:56.178  4121  4121 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 06:28:56.188  1020  1303 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4180 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-16 06:28:56.188  1020  1303 I ActivityManager: Killing 3384:com.sec.dsm.system/1000 (adj 15): empty #31,
,03-16 06:28:56.198  4180  4180 E Zygote  : MountEmulatedStorage(),
,03-16 06:28:56.198  2099  2099 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
03-16 06:28:56.208  4180  4180 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:28:56.208  4180  4180 E Zygote  : v2
03-16 06:28:56.208  4180  4180 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:56.208  4180  4180 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:56.208  4180  4180 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 06:28:56.208  4180  4180 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:28:56.218   309   309 I art     : Explicit concurrent mark sweep GC freed 8733(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 31.027ms
,03-16 06:28:56.238   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.675ms
03-16 06:28:56.238  2099  4187 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-16 06:28:56.248   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 563us total 16.327ms
,03-16 06:28:56.258  4180  4180 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:56.258  4180  4180 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:56.298  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 06:28:56.298  4044  4114 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-16 06:28:56.308  4044  4114 W VideoCapabilities: Unsupported mime video/wvc1
,03-16 06:28:56.308  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3384/cgroup.procs: No such file or directory
,03-16 06:28:56.318  2099  4187 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-16 06:28:56.328  4044  4114 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-16 06:28:56.328  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 06:28:56.328  4044  4114 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-16 06:28:56.338  4044  4114 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-16 06:28:56.338  1020  3997 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:56.338  1020  3997 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.338  1020  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 06:28:56.338  4044  4114 W VideoCapabilities: Unsupported mime video/mp43
,03-16 06:28:56.348  2099  4186 I SystemUpdateService: cancelUpdate (empty URL)
03-16 06:28:56.348  2099  4186 I SystemUpdateService: active receiver: disabled
,03-16 06:28:56.348  4044  4114 W VideoCapabilities: Unsupported mime video/sorenson
,03-16 06:28:56.368  4044  4114 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-16 06:28:56.398  4085  4151 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-16 06:28:56.398  4044  4114 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 06:28:56.418  4085  4085 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-16 06:28:56.458  1020  1560 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:56.458  1020  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.458  1020  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:56.468  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:56.468  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.468  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:56.488  4085  4085 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 06:28:56.488  2099  4187 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 06:28:56.498  1020  1559 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 06:28:56.498  1020  1559 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 06:28:56.498  1020  1559 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 06:28:56.508  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 06:28:56.508  1020  1020 I MotionRecognitionService: Plugged
,03-16 06:28:56.508  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 06:28:56.518  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 06:28:56.518  1176  1176 D PowerUI : Cable  true --> true mBootCompleted : true
03-16 06:28:56.518  1176  1176 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,03-16 06:28:56.518  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 06:28:56.518  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 06:28:56.528  4161  4161 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-16 06:28:56.528  1822  4203 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED,
,03-16 06:28:56.528  2985  2985 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 06:28:56.538  2985  3063 D HeadsetStateMachine: Disconnected process message: 10
,03-16 06:28:56.538  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 06:28:56.538  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 06:28:56.538  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 06:28:56.538  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 06:28:56.538  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 06:28:56.538  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 06:28:56.548  1020  3997 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:56.548  1020  3997 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:56.548  1020  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-16 06:28:56.558  1020  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.558  1020  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.558  1020  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.558  1020  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:56.568  4208  4208 E Zygote  : MountEmulatedStorage(),
03-16 06:28:56.578  4208  4208 E Zygote  : v2
,03-16 06:28:56.578  1020  1302 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4208 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 06:28:56.578  3488  3594 I System.out: Thread-478(ApacheHTTPLog):isSBSettingEnabled false
03-16 06:28:56.578  3488  3594 I System.out: Thread-478(ApacheHTTPLog):isShipBuild true
03-16 06:28:56.578  3488  3594 I System.out: Thread-478(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-16 06:28:56.578  3488  3594 I System.out: Thread-478(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
03-16 06:28:56.578  4208  4208 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:28:56.578  4208  4208 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:56.578   279  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 06:28:56.578   279  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10088
03-16 06:28:56.578  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:56.578  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.578  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
03-16 06:28:56.578  4085  4085 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 06:28:56.578  4208  4208 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:56.588  4208  4208 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:56.588  4208  4208 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:28:56.588  1020  1503 I ActivityManager: Killing 3467:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-16 06:28:56.588  4085  4085 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 06:28:56.588  4085  4085 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-16 06:28:56.588  2099  2099 D SystemUpdateService: onDestroy
,03-16 06:28:56.598  4085  4085 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-16 06:28:56.608  1020  1805 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:56.608  1020  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.608  1020  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:56.628  4208  4208 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:56.628  4208  4208 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:56.638  4085  4085 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 06:28:56.638  4085  4085 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 06:28:56.638  1651  1675 I art     : Explicit concurrent mark sweep GC freed 4341(186KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 916us total 31.801ms
,03-16 06:28:56.648  3488  4206 D GCMRegistrar: resetting backoff for com.dropbox.android
,03-16 06:28:56.648  3488  4206 V GCMRegistrar: Registering app com.dropbox.android of senders 735665981150
,03-16 06:28:56.658  1651  1668 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-16 06:28:56.658  1020  1303 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:56.658  1020  1303 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.658  1020  1303 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
,03-16 06:28:56.668  4208  4208 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-16 06:28:56.668  3444  3523 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-16 06:28:56.688  2099  4187 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-16 06:28:56.688  3616  3625 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-16 06:28:56.768  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.768  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.768  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.768  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:56.778  4238  4238 E Zygote  : MountEmulatedStorage(),
03-16 06:28:56.778  4238  4238 E Zygote  : v2
03-16 06:28:56.778  4238  4238 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:28:56.778  4238  4238 I libpersona: KNOX_SDCARD not a persona,
03-16 06:28:56.778  4238  4238 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 06:28:56.778  4238  4238 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 06:28:56.778  4238  4238 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:28:56.778  4208  4208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 ,
,03-16 06:28:56.788  1020  1511 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4238 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 06:28:56.798  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:56.798  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.798  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 06:28:56.798  4238  4238 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:56.798  4238  4238 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:56.808  1020  1558 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:56.808  1020  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:56.808  1020  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-16 06:28:56.818  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3467/cgroup.procs: No such file or directory
,03-16 06:28:56.818  1822  2125 W GCoreFlp: No location to return for getLastLocation()
03-16 06:28:56.818  1822  2132 W FusedLocationProvider: location=null
,03-16 06:28:56.838  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.838  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:56.838  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:56.838  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:56.848  4085  4256 D OpenGLRenderer: Render dirty regions requested: true
,03-16 06:28:56.858  4257  4257 E Zygote  : MountEmulatedStorage()
,03-16 06:28:56.858  4257  4257 E Zygote  : v2
03-16 06:28:56.858  4257  4257 I libpersona: KNOX_SDCARD checking this for 1000
,03-16 06:28:56.858  4257  4257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:56.858  4257  4257 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:56.858  1020  1511 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4257 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 06:28:56.868  4257  4257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:56.868  4257  4257 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-16 06:28:56.868  1020  1560 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 06:28:56.868  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 06:28:56.868  1020  1560 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 06:28:56.868  1020  1560 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 06:28:56.868  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-16 06:28:56.868  4085  4085 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 06:28:56.868  4085  4085 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-16 06:28:56.878   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,03-16 06:28:56.888  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:56.888  1020  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.888  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:56.888  1822  2125 W GCoreFlp: No location to return for getLastLocation()
,03-16 06:28:56.888  1822  1833 W FusedLocationProvider: location=null
,03-16 06:28:56.898  4257  4257 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:56.898  4257  4257 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:56.898  1020  1032 D InputDispatcher: Focus entered window: 4085
,03-16 06:28:56.908  2099  4187 I AuthZen : Fetching signing key...
03-16 06:28:56.908  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 06:28:56.908  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 06:28:56.908  4085  4085 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 06:28:56.908  4085  4256 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 06:28:56.918  4085  4256 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-16 06:28:56.918  4085  4256 D OpenGLRenderer: Enabling debug mode 0
,03-16 06:28:56.918  1020  1557 I ActivityManager: Killing 3403:com.google.android.configupdater/u0a82 (adj 15): empty #31
,03-16 06:28:56.938  4208  4208 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-16 06:28:56.938  4208  4208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-16 06:28:56.938  1020  1303 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:56.938  1020  1303 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:56.938  1020  1303 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-16 06:28:56.948  1822  1822 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-16 06:28:56.948   292   292 E SMD     : DCD OFF
,03-16 06:28:56.948  4257  4257 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 06:28:56.958  1822  4279 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,03-16 06:28:56.958  4238  4238 E KnoxSetupWizardClient: isShipMode : 1
03-16 06:28:56.958  4238  4238 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-16 06:28:56.968  1020  1557 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:56.968  1020  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:56.968  1020  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:56.968  4257  4257 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-16 06:28:56.968  4257  4257 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-16 06:28:56.978  4208  4208 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
,03-16 06:28:56.978  4208  4208 I F_PHONE : default registerAction()
03-16 06:28:56.978  4208  4208 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-16 06:28:56.978  1020  1558 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:56.978  1020  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 06:28:56.978  1020  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-16 06:28:56.998  1461  1461 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 06:28:56.998  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:28:56.998  1461  1461 D BluetoothBDTestService: onCreate()
,03-16 06:28:56.998  1461  1461 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-16 06:28:56.998  1461  1461 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-16 06:28:57.008  1461  1461 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-16 06:28:57.008  1822  4279 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-16 06:28:57.008   279  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 06:28:57.008   279  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-16 06:28:57.008  2099  4187 I AuthZen : Signing key fetched successfully!
,03-16 06:28:57.018  1822  4279 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-16 06:28:57.038  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{14c8f919 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,03-16 06:28:57.038  2099  4187 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 06:28:57.058  1020  1044 W libprocessgroup: failed to open /acct/uid_10082/pid_3403/cgroup.procs: No such file or directory
,03-16 06:28:57.078  4238  4281 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-16 06:28:57.098  4238  4281 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-16 06:28:57.098  4238  4281 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-16 06:28:57.098  4238  4281 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-16 06:28:57.098  4238  4281 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-16 06:28:57.098  4238  4281 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-16 06:28:57.098  4238  4281 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-16 06:28:57.118  1822  4203 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-16 06:28:57.168  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,03-16 06:28:57.168  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 06:28:57.178  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-16 06:28:57.178  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-16 06:28:57.178  4161  4214 I AMMetaDataParserService: Resource data:2131165186
03-16 06:28:57.178  1020  1032 I art     : Explicit concurrent mark sweep GC freed 37167(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 22MB/34MB, paused 3.078ms total 199.168ms
,03-16 06:28:57.178  1020  1805 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 06:28:57.198  4161  4214 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 06:28:57.198  4161  4214 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 06:28:57.198  4161  4214 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-16 06:28:57.198  3957  4104 I System.out: INFO:Resource not found:/Common.properties Using default values
03-16 06:28:57.198  4161  4214 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 06:28:57.198  4161  4214 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-16 06:28:57.198  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:28:57.198  1176  1176 I StatusBar: Icon Only
03-16 06:28:57.198  1176  1176 D PanelView: There is/are notification(s) 
,03-16 06:28:57.208  1020  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 06:28:57.208  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.208  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.208  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.208  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:57.208  4161  4214 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-16 06:28:57.208  1020  4299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 06:28:57.218  4300  4300 E Zygote  : MountEmulatedStorage()
,03-16 06:28:57.218  4300  4300 E Zygote  : v2
03-16 06:28:57.218  4300  4300 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:28:57.218  4300  4300 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:57.218  4300  4300 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:57.228  4300  4300 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:57.228  4238  4238 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
03-16 06:28:57.228  1020  1557 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4300 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 06:28:57.228  4300  4300 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:28:57.228  4085  4085 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@31104d5a time:46607
,03-16 06:28:57.238  4121  4121 I Process : Sending signal. PID: 4121 SIG: 9
,03-16 06:28:57.248  1020  1050 I ActivityManager: Displayed Component not be shown by security: +1s903ms
,03-16 06:28:57.248  1020  1050 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-16 06:28:57.248  1020  1050 W ActivityManager: mDVFSHelper.release()
03-16 06:28:57.248  1020  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2e33f89 u0 com.test.thalitest/.MainActivity t11} time:46628
,03-16 06:28:57.248  1020  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-16 06:28:57.258  4238  4238 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-16 06:28:57.258  4238  4238 D ShortcutReceiver:  KnoxContainerVersion 2.3.0
03-16 06:28:57.258  4238  4238 D ShortcutReceiver:  shortcut migration not required 
,03-16 06:28:57.258  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.258  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.258  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.258  1020  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:57.278  4320  4320 E Zygote  : MountEmulatedStorage(),
03-16 06:28:57.278  4320  4320 E Zygote  : v2
03-16 06:28:57.278  4320  4320 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:28:57.278  4320  4320 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:57.278  4320  4320 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 06:28:57.278  4300  4300 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:57.278  4300  4300 D ActivityThread: Added TimaKeyStore provider
03-16 06:28:57.278  1020  1557 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4320 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 06:28:57.288  4320  4320 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:57.288  4320  4320 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:28:57.298  4161  4214 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-16 06:28:57.328  1020  1511 I ActivityManager: Process com.sec.android.app.sns3 (pid 4121)(adj 0) has died(24,652)
,03-16 06:28:57.328  4320  4320 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:57.328  4320  4320 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:57.338  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 06:28:57.338  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.338  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.338  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:57.348  4338  4338 E Zygote  : MountEmulatedStorage()
,03-16 06:28:57.348  4338  4338 E Zygote  : v2
03-16 06:28:57.348  4338  4338 I libpersona: KNOX_SDCARD checking this for 10031
03-16 06:28:57.348  4338  4338 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:57.348  4300  4300 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 06:28:57.348  4338  4338 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:57.358  4161  4214 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,03-16 06:28:57.358  4338  4338 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:57.358  4338  4338 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:28:57.358  1020  1045 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4338 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,03-16 06:28:57.368  1822  4203 I GCoreUlr: Unbound from all location providers
,03-16 06:28:57.368  1822  4203 I GCoreUlr: Place inference reporting - stopped
,03-16 06:28:57.368  2099  4187 D a       : Opening database auth.proximity.permit_store...
,03-16 06:28:57.398  4338  4338 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:57.398  4338  4338 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataP,arserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-16 06:28:57.408  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
03-16 06:28:57.418  1020  1560 I ActivityManager: Killing 3488:com.dropbox.android/u0a88 (adj 15): empty #31
03-16 06:28:57.428  1822  1822 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
03-16 06:28:57.438  2099  4187 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
03-16 06:28:57.438  2099  4187 D AuthZenTransactionCache: Clearing transaction cache
,03-16 06:28:57.448  1879  1879 I SamsungIME: getCurrentCandidateView
,03-16 06:28:57.458  1822  1822 I GCoreUlr: DispatchingService.onDestroy()
,03-16 06:28:57.458  1822  1822 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-16 06:28:57.458  1822  1822 I GCoreUlr: Unbound from all location providers
03-16 06:28:57.458  1822  1822 I GCoreUlr: Place inference reporting - stopped
,03-16 06:28:57.478  4161  4214 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-16 06:28:57.488  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:57.488  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:57.488  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:57.488   258  1100 I SurfaceFlinger: id=11 Removed uhalitest (7/8)
,03-16 06:28:57.488   258   441 I SurfaceFlinger: id=11 Removed uhalitest (-2/8)
,03-16 06:28:57.498  4320  4320 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-16 06:28:57.498  1020  1033 D PersonaManagerService: getPersonasForUser(): returning null!
,03-16 06:28:57.498  4300  4300 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-16 06:28:57.518  4300  4360 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458106137536
,03-16 06:28:57.538  4300  4300 I KnoxUsageLogPro: premStatus:2
,03-16 06:28:57.548  4300  4300 I KnoxUsageLogPro: isEulaShown : false
03-16 06:28:57.548  4300  4300 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-16 06:28:57.548  1020  1557 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:57.548  1020  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:57.548  1020  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:57.548  1020  1044 W libprocessgroup: failed to open /acct/uid_10088/pid_3488/cgroup.procs: No such file or directory
,03-16 06:28:57.548  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,03-16 06:28:57.558  4320  4320 I StatusChecker: onReceive : net.mt.init : DONE
,03-16 06:28:57.558  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:57.568  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.568  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.568  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.568  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-16 06:28:57.568  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:28:57.568  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:28:57.568  4161  4214 I AMMetaDataParserService: Resource data:2131034113
,03-16 06:28:57.568  4161  4214 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
03-16 06:28:57.568  4161  4214 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 06:28:57.568  4161  4214 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 06:28:57.578  4161  4214 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
,03-16 06:28:57.578  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
03-16 06:28:57.578  4365  4365 E Zygote  : MountEmulatedStorage()
03-16 06:28:57.578  4365  4365 E Zygote  : v2
03-16 06:28:57.578  4365  4365 I libpersona: KNOX_SDCARD checking this for 10026
03-16 06:28:57.578  4365  4365 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:57.578  4365  4365 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:57.588  4365  4365 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:57.588  4365  4365 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 06:28:57.588  1020  1511 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4365 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 06:28:57.588  4300  4360 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 46899
,03-16 06:28:57.608  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.608  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.608  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.608  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:57.608  1879  1879 D SamsungIME: Dismiss ExpandCandiate
,03-16 06:28:57.618  2714  2714 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,03-16 06:28:57.618  4365  4365 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:57.618  4380  4380 E Zygote  : MountEmulatedStorage()
03-16 06:28:57.618  4365  4365 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:57.618  4380  4380 E Zygote  : v2
03-16 06:28:57.618  4380  4380 I libpersona: KNOX_SDCARD checking this for 10113
03-16 06:28:57.618  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 06:28:57.618  4380  4380 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:57.618  4380  4380 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:57.628  1020  1511 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4380 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,03-16 06:28:57.628  1020  1511 I ActivityManager: Killing 2846:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-16 06:28:57.628  4380  4380 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:57.628  4380  4380 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:28:57.628  4161  4214 I GFX construct_block_size_descriptor_2d second part: took 3.348070ms for 0*0 texture 0
,03-16 06:28:57.638  4085  4085 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 06:28:57.648  2714  2714 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-16 06:28:57.648  4161  4214 I GFX generate_partition_tables: took 12.091719ms for 0*0 texture 0
,03-16 06:28:57.648  4161  4214 I GFX raster: took 16.708175ms for 96*96 texture 0
03-16 06:28:57.648  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.648  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86e29b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86e08a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:28:57.648  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.648  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.648  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:57.658  4380  4380 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:57.658  4380  4380 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:57.668  4392  4392 E Zygote  : MountEmulatedStorage(),
03-16 06:28:57.668  4392  4392 I libpersona: KNOX_SDCARD checking this for 10032
03-16 06:28:57.668  4392  4392 E Zygote  : v2
03-16 06:28:57.668  4392  4392 I libpersona: KNOX_SDCARD not a persona,
03-16 06:28:57.668  4392  4392 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:57.668  4392  4392 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 06:28:57.668  4392  4392 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,03-16 06:28:57.668  1020  1303 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4392 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 06:28:57.678  1020  1303 I ActivityManager: Killing 3525:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,03-16 06:28:57.678  3444  3523 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
03-16 06:28:57.678  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
03-16 06:28:57.678  4161  4214 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 06:28:57.698  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-16 06:28:57.698  4161  4214 I GFX raster: took 0.889115ms for 96*96 texture 0
03-16 06:28:57.698  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86e29b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8727e28 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:28:57.708  4392  4392 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:57.708  4392  4392 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:57.758  4380  4380 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-16 06:28:57.778  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2846/cgroup.procs: No such file or directory
,03-16 06:28:57.778  1020  1044 W libprocessgroup: failed to open /acct/uid_10088/pid_3525/cgroup.procs: No such file or directory
,03-16 06:28:57.808  4392  4411 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-16 06:28:57.808  4392  4411 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-16 06:28:57.808  4380  4380 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-16 06:28:57.808  1020  1560 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:57.808  1020  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:57.808  1020  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-16 06:28:57.808  4392  4392 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-16 06:28:57.808  4380  4380 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-16 06:28:57.818  1020  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.818  1020  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.818  1020  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.818  1020  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:57.828  4161  4214 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 06:28:57.828  4413  4413 E Zygote  : MountEmulatedStorage()
,03-16 06:28:57.828  4413  4413 E Zygote  : v2
03-16 06:28:57.828  4413  4413 I libpersona: KNOX_SDCARD checking this for 10121
03-16 06:28:57.828  4413  4413 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:57.828  4413  4413 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:57.828  1020  3997 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4413 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-16 06:28:57.838  4413  4413 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:57.838  4413  4413 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:28:57.858  4413  4413 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:57.858  4413  4413 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:57.878  4413  4413 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 06:28:57.878  4413  4413 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 06:28:57.878  4413  4413 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 06:28:57.888  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 06:28:57.918  4413  4413 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-16 06:28:57.918  1020  1302 D SettingsProvider: name = scon_is_running
03-16 06:28:57.918  1020  1302 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 06:28:57.918  1020  1302 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 06:28:57.918  1020  1302 D SettingsProvider: selectionArgs: false
03-16 06:28:57.918  1020  1302 D SettingsProvider: selectionArgs: 10121
03-16 06:28:57.918  1020  1302 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 06:28:57.918  1020  1302 D SettingsProvider: ret = -1
,03-16 06:28:57.928  1020  1302 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-16 06:28:57.928  4413  4413 D QuickConnect: Utils.setQCRunningSetting - set : 0
,03-16 06:28:57.928  4413  4413 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-16 06:28:57.928  4413  4413 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-16 06:28:57.928  1020  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 06:28:57.928  1020  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 06:28:57.928  1020  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.928  1020  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:57.938  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
,03-16 06:28:57.948  4429  4429 E Zygote  : MountEmulatedStorage(),
03-16 06:28:57.948  4429  4429 E Zygote  : v2
03-16 06:28:57.948  4429  4429 I libpersona: KNOX_SDCARD checking this for 10127
03-16 06:28:57.948  4429  4429 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:57.948  4429  4429 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:57.948  1020  1560 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4429 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a,
03-16 06:28:57.948  1020  1560 I ActivityManager: Killing 3547:com.fmm.dm/1000 (adj 15): empty #31
,03-16 06:28:57.948  4429  4429 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:57.958  4429  4429 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:28:57.968  4429  4429 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:57.968  4429  4429 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:57.978   309   309 I art     : Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 718us total 24.988ms
,03-16 06:28:57.988  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:57.988  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.988  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:57.988  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:57.998  4429  4429 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 06:28:57.998  4429  4429 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 06:28:57.998  4429  4429 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 06:28:57.998  4429  4429 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 06:28:57.998   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.720ms
,03-16 06:28:58.008   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 563us total 16.350ms
,03-16 06:28:58.028  4444  4444 E Zygote  : MountEmulatedStorage()
,03-16 06:28:58.028  4444  4444 E Zygote  : v2
03-16 06:28:58.028  4444  4444 I libpersona: KNOX_SDCARD checking this for 10036
03-16 06:28:58.028  4444  4444 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:58.028  4444  4444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 06:28:58.028  1020  1559 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4444 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-16 06:28:58.028  1020  1559 I ActivityManager: Killing 3637:com.fmm.ds/1000 (adj 15): empty #31
,03-16 06:28:58.028  4444  4444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:58.028  4444  4444 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-16 06:28:58.048  4444  4444 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:58.048  4444  4444 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:58.068  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3547/cgroup.procs: No such file or directory
,03-16 06:28:58.068  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3637/cgroup.procs: No such file or directory
,03-16 06:28:58.078  4392  4411 D SPPClientService: PushLog.txt file is not deleted.
,03-16 06:28:58.078  4392  4411 D SPPClientService: PushLog.txt file is not deleted.
,03-16 06:28:58.078  4392  4411 D SPPClientService: ============PushLog. stop!
,03-16 06:28:58.118  1879  1879 I SamsungIME: KeybaordView init() : load resources
,03-16 06:28:58.138  4444  4444 I SA      : [SSP] onCreated
,03-16 06:28:58.178  1020  3071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-16 06:28:58.268  1020  3071 D SSRM:n  : SIOP:: AP = 410
,03-16 06:28:58.278  1020  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 06:28:58.318  4444  4444 I SA      : [TPM] There is no property file
,03-16 06:28:58.318  4444  4444 I SA      : [SCU] isHaveSA() - false,
03-16 06:28:58.318  4444  4444 I SA      : [TPM] getModelProperty : null
03-16 06:28:58.318  4444  4444 I SA      : [TPM] getCSCProperty : null
03-16 06:28:58.318  4444  4444 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-16 06:28:58.318  4444  4444 I SA      : [DM] PRODUCT AMOLED FEATURE: false,
03-16 06:28:58.318  4444  4444 I SA      : [DM] TFT FEATURE: false
,03-16 06:28:58.328  4444  4444 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,03-16 06:28:58.338  4444  4444 I SA      : [DM] init START
,03-16 06:28:58.338  4444  4444 I SA      : [DM] This device is not a Vodafone
,03-16 06:28:58.338  4444  4444 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-16 06:28:58.338  4444  4444 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,03-16 06:28:58.338  4444  4444 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,03-16 06:28:58.338  4444  4444 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-16 06:28:58.348  4444  4444 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-16 06:28:58.348  4444  4444 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,03-16 06:28:58.348  4444  4444 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-16 06:28:58.348  4444  4444 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-16 06:28:58.348  4444  4444 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,03-16 06:28:58.348  4444  4444 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-16 06:28:58.348  4444  4444 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-16 06:28:58.358  4444  4444 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,03-16 06:28:58.358  4444  4444 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,03-16 06:28:58.358  4444  4444 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-16 06:28:58.358  4444  4444 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,03-16 06:28:58.358  4444  4444 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
03-16 06:28:58.358  4444  4444 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-16 06:28:58.358  4444  4444 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,03-16 06:28:58.358  4444  4444 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-16 06:28:58.358  4444  4444 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-16 06:28:58.358  4444  4444 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,03-16 06:28:58.368  4444  4444 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,03-16 06:28:58.368  4444  4444 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
03-16 06:28:58.368  4444  4444 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,03-16 06:28:58.368  4444  4444 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,03-16 06:28:58.368  4444  4444 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-16 06:28:58.378  4444  4444 I SA      : [SCU] isHaveSA() - false
03-16 06:28:58.378  4444  4444 I SA      : support phone number id : false
03-16 06:28:58.378  4444  4444 I SA      : [DM] Supports Ref Jpn : true
,03-16 06:28:58.378  4444  4444 I SA      : [DM] init END
,03-16 06:28:58.378  4444  4444 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-16 06:28:58.378  4444  4444 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-16 06:28:58.388  1020  1805 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:58.388  1020  1805 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-16 06:28:58.388  1020  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-16 06:28:58.388  4444  4444 I SA      : [OR] onReceive END
,03-16 06:28:58.388  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:58.388  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:58.388  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:58.388  1020  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:58.398  1879  1879 I SamsungIME: getCurrentKeyboard
03-16 06:28:58.398  1879  1879 I SamsungIME: getTextKeyboard
,03-16 06:28:58.408  1020  1559 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4467 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 06:28:58.408  4467  4467 E Zygote  : MountEmulatedStorage()
,03-16 06:28:58.408  4467  4467 E Zygote  : v2
03-16 06:28:58.408  4467  4467 I libpersona: KNOX_SDCARD checking this for 10037
03-16 06:28:58.408  4467  4467 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:58.418  4467  4467 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:58.428  4467  4467 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:58.428  4467  4467 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 06:28:58.438  4467  4467 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:58.438  4467  4467 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:58.448  4444  4444 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-16 06:28:58.448  4444  4444 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-16 06:28:58.458  4444  4444 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
,03-16 06:28:58.458  4444  4444 I SA      : [LBE] REF_JPN : true
03-16 06:28:58.458  4444  4444 I SA      : [BDC] create
,03-16 06:28:58.458  2099  3906 I Icing   : Internal init done: storage state 0
,03-16 06:28:58.468  2099  3906 I Icing   : Post-init done
,03-16 06:28:58.488  4467  4467 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 06:28:58.498  4429  4429 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-16 06:28:58.508  4365  4365 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 06:28:58.538  4429  4429 D ManifestProvider: onCreate()
,03-16 06:28:58.538  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:58.548  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:28:58.548  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:58.558  4429  4429 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-16 06:28:58.578  4085  4318 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-16 06:28:58.578  4085  4318 I chromium: 
,03-16 06:28:58.578  4444  4444 I SA      : [DBMV2] getEmailID
,03-16 06:28:58.588  4444  4444 I SA      : [DBMV2] getDataV02ForItems
,03-16 06:28:58.588  4444  4444 I SA      : [SSP] query invoked
,03-16 06:28:58.598  4444  4444 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-16 06:28:58.608  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:58.608  4161  4214 I GFX construct_block_size_descriptor_2d second part: took 2.346354ms for 0*0 texture 0
,03-16 06:28:58.608  4444  4444 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-16 06:28:58.618  4444  4444 I SA      : [BDC] destroy
,03-16 06:28:58.618  1020  1503 I ActivityManager: Killing 3597:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,03-16 06:28:58.628  4161  4214 I GFX generate_partition_tables: took 7.788178ms for 0*0 texture 0
,03-16 06:28:58.628  4161  4214 I GFX raster: took 11.067969ms for 96*96 texture 0
03-16 06:28:58.628  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8727350 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb870aad8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:28:58.638  4161  4214 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 06:28:58.648  4429  4429 W System.err: java.lang.NoSuchMethodException: isEnabled []
,03-16 06:28:58.658  4429  4429 W System.err: 	at java.lang.Class.getMethod(Class.java:665)
03-16 06:28:58.658  4429  4429 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
03-16 06:28:58.658  4429  4429 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
03-16 06:28:58.658  4429  4429 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
03-16 06:28:58.658  4429  4429 W System.err: 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
03-16 06:28:58.658  4429  4429 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
03-16 06:28:58.658  4429  4429 W System.err: 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
03-16 06:28:58.658  4429  4429 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-16 06:28:58.658  4429  4429 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-16 06:28:58.658  4429  4429 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-16 06:28:58.658  4429  4429 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 06:28:58.658  4429  4429 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-16 06:28:58.658  4429  4429 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 06:28:58.658  4429  4429 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 06:28:58.658  4429  4429 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 06:28:58.658  4429  4429 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 06:28:58.658  4429  4429 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-16 06:28:58.658  4429  4429 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@3ab5059b
,03-16 06:28:58.658  4429  4429 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
,03-16 06:28:58.668  4429  4429 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-16 06:28:58.668  1020  1044 W libprocessgroup: failed to open /acct/uid_10090/pid_3597/cgroup.procs: No such file or directory
,03-16 06:28:58.678  4467  4467 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-16 06:28:58.678  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:58.678  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:58.678  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:58.678  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:58.678  3444  3523 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-16 06:28:58.678  4085  4493 D jxcore_app_log: JniHelper::setJavaVM(0xb836b448), pthread_self() = -1196761216
,03-16 06:28:58.698  4497  4497 E Zygote  : MountEmulatedStorage()
03-16 06:28:58.698  4497  4497 E Zygote  : v2
03-16 06:28:58.698  4497  4497 I libpersona: KNOX_SDCARD checking this for 10131
03-16 06:28:58.698  4497  4497 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:58.698  4085  4493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 06:28:58.698  4085  4493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 06:28:58.698  4085  4493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 06:28:58.698  4085  4493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 06:28:58.698  4085  4493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 06:28:58.698  4085  4493 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34affbf1 added. We now have 1 listener(s)
03-16 06:28:58.698  4497  4497 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:58.698  1879  1879 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-16 06:28:58.698  1020  1032 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4497 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-16 06:28:58.698  4497  4497 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:58.698  4497  4497 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:28:58.708  1020  1032 I ActivityManager: Killing 3681:com.sec.factory.camera/1000 (adj 15): empty #31
,03-16 06:28:58.708  4085  4493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-16 06:28:58.718  4085  4493 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-16 06:28:58.718  4085  4493 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-16 06:28:58.718  4085  4493 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 06:28:58.718  4085  4493 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 06:28:58.718  1020  3997 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:58.718  1020  3997 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:58.718  1020  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 06:28:58.728  4085  4493 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29234544 added. We now have 1 listener(s)
,03-16 06:28:58.728  4085  4493 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 06:28:58.748  4497  4497 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:58.748  4497  4497 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:58.748  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:58.748  4085  4493 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-16 06:28:58.748  4161  4214 I GFX raster: took 0.752343ms for 96*96 texture 0
03-16 06:28:58.748  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8727e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb870aad8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:28:58.758  4161  4214 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 06:28:58.758  4085  4493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-16 06:28:58.758  4085  4493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-16 06:28:58.758  4085  4493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-16 06:28:58.758  4085  4493 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-16 06:28:58.768  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:58.768  4161  4214 I GFX raster: took 0.993021ms for 96*96 texture 0
03-16 06:28:58.768  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb870aad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83bf338 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:28:58.778  4161  4214 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 06:28:58.788  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:58.788  1020  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:28:58.788  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:58.798  4085  4493 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 06:28:58.798  4085  4493 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-16 06:28:58.818  4497  4497 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 06:28:58.818  4497  4497 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 06:28:58.818  4497  4497 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 06:28:58.818  4085  4493 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 06:28:58.818  4085  4493 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 06:28:58.818  4085  4493 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 06:28:58.818  4085  4493 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 06:28:58.818  4085  4493 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 06:28:58.818  4085  4493 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 06:28:58.818  4085  4493 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 06:28:58.818  4085  4493 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 06:28:58.818  4085  4493 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 06:28:58.818  4085  4493 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 06:28:58.818  4085  4085 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-16 06:28:58.818  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3681/cgroup.procs: No such file or directory
,03-16 06:28:58.818  4085  4085 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 06:28:58.848  4085  4085 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 06:28:58.888  1020  1042 D SensorService: [SO] -0.460 0.211 9.883
,03-16 06:28:58.888  4365  4365 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 06:28:58.908  4365  4365 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 06:28:58.908  4365  4365 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 06:28:59.048  4365  4519 D Volley  : [658] DiskBasedCache.clear: Cache cleared.
03-16 06:28:59.048  4365  4487 D Volley  : [651] DiskBasedCache.clear: Cache cleared.
,03-16 06:28:59.058  1020  1557 I ActivityManager: Killing 3719:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,03-16 06:28:59.058  1020  1557 I ActivityManager: Killing 2901:com.sec.android.fotaclient/u0a8 (adj 15): empty #32
,03-16 06:28:59.058  1020  1098 V AlarmManager: waitForAlarm result :8
,03-16 06:28:59.068  1837  1851 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 06:28:59.078  1020  1302 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:59.078  1020  1302 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.078  1020  1302 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-16 06:28:59.078  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.088  1020  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:59.088  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 06:28:59.088  4365  4365 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-16 06:28:59.088  4365  4365 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 06:28:59.098  4365  4534 D Ads     : Skipping gmscore version check
,03-16 06:28:59.108  4365  4365 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 06:28:59.108  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.108  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.118  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-16 06:28:59.128  1020  1511 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.128  1020  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:59.128  1020  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 06:28:59.128  1020  1044 W libprocessgroup: failed to open /acct/uid_10095/pid_3719/cgroup.procs: No such file or directory
,03-16 06:28:59.138  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:59.138  4161  4214 I GFX raster: took 0.632864ms for 96*96 texture 0
03-16 06:28:59.138  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb870c460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb870c528 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:28:59.138  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 06:28:59.148  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:59.148  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:59.148  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:59.148  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:59.158  4540  4540 E Zygote  : MountEmulatedStorage()
03-16 06:28:59.158  4540  4540 E Zygote  : v2
03-16 06:28:59.158  4540  4540 I libpersona: KNOX_SDCARD checking this for 10135
,03-16 06:28:59.158  4540  4540 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:59.168  4540  4540 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:59.168  4540  4540 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 06:28:59.168  4540  4540 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:28:59.168  1020  1141 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4540 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
03-16 06:28:59.168  1020  1044 W libprocessgroup: failed to open /acct/uid_10008/pid_2901/cgroup.procs: No such file or directory
,03-16 06:28:59.178  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:59.178  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 06:28:59.178  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 06:28:59.178  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 06:28:59.188  4161  4214 I GFX raster: took 0.736770ms for 96*96 texture 0
03-16 06:28:59.188  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb871c440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb871c498 counterpartCT=4 counterpartW=96 counterparth=96
03-16 06:28:59.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 06:28:59.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 06:28:59.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 06:28:59.188  4365  4365 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
03-16 06:28:59.188  1020  1511 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:59.188  1020  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.188  1020  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-16 06:28:59.208  4161  4214 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 06:28:59.218  4540  4540 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:59.218  4540  4540 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:59.248  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:59.248  4161  4214 I GFX raster: took 0.522239ms for 96*96 texture 0
03-16 06:28:59.248  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb870be30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb870bed8 counterpartCT=4 counterpartW=96 counterparth=96
03-16 06:28:59.248  4540  4540 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-16 06:28:59.248  4540  4540 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 06:28:59.248  4540  4540 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 06:28:59.248  4540  4540 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-16 06:28:59.248  4540  4540 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 06:28:59.248  4161  4214 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 06:28:59.278  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-16 06:28:59.278  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:28:59.278  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:28:59.278  4161  4214 I AMMetaDataParserService: Resource data:2131034113
,03-16 06:28:59.278  1020  1805 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:59.278  1020  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.278  1020  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 06:28:59.288  4467  4467 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-16 06:28:59.288  4161  4214 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-16 06:28:59.288  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:28:59.288  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:59.288  4161  4214 I GFX raster: took 0.819999ms for 96*96 texture 0
03-16 06:28:59.288  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86e29b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86b3e40 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:28:59.298  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.298  1020  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.298  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:59.318  4161  4214 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533,
,03-16 06:28:59.328  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 06:28:59.328  1020  1098 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:59.338  1020  1098 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:59.338  1020  1098 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:59.338  1020  1098 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:59.338  3798  3972 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 06:28:59.358  4561  4561 E Zygote  : MountEmulatedStorage()
03-16 06:28:59.358  4561  4561 E Zygote  : v2
03-16 06:28:59.358  4561  4561 I libpersona: KNOX_SDCARD checking this for 10117
03-16 06:28:59.358  4561  4561 I libpersona: KNOX_SDCARD not a persona
03-16 06:28:59.358  4561  4561 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:28:59.358  4561  4561 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:28:59.358  4561  4561 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 06:28:59.368  1020  1098 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService: pid=4561 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,03-16 06:28:59.368  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.368  1020  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.368  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:59.378  4561  4561 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:28:59.378  4561  4561 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:59.408  1020  1805 I ActivityManager: Killing 1534:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-16 06:28:59.418  4561  4561 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 06:28:59.418  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.428  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.428  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-16 06:28:59.438  1020  3997 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.438  1020  3997 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:59.448  1020  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 06:28:59.448  3574  3978 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 06:28:59.478  1020  1044 W libprocessgroup: failed to open /acct/uid_10003/pid_1534/cgroup.procs: No such file or directory
,03-16 06:28:59.498  1020  1511 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.498  1020  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:28:59.498  1020  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 06:28:59.538  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 06:28:59.548  1020  1319 E Watchdog: !@Sync 1
,03-16 06:28:59.548  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:59.548  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:59.548  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:28:59.548  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:28:59.558  4583  4583 E Zygote  : MountEmulatedStorage(),
03-16 06:28:59.558  4583  4583 E Zygote  : v2
03-16 06:28:59.558  4583  4583 I libpersona: KNOX_SDCARD checking this for 10141
03-16 06:28:59.558  4583  4583 I libpersona: KNOX_SDCARD not a persona
,03-16 06:28:59.568  4583  4583 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:28:59.568  1020  1140 D SettingsProvider: name = audio_safe_volume_state
03-16 06:28:59.568  1020  1503 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4583 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
03-16 06:28:59.568  4583  4583 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:28:59.568  4583  4583 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:28:59.578  1020  1557 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:59.578  1020  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.578  1020  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:59.578  1020  1805 I ActivityManager: Killing 3707:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,03-16 06:28:59.588  1020  3997 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:28:59.588  1020  3997 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.588  1020  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:59.598  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:59.598  4161  4214 I GFX raster: took 0.813646ms for 96*96 texture 0
03-16 06:28:59.598  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86e29b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86b3e40 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:28:59.618  4583  4583 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:28:59.628  4583  4583 D ActivityThread: Added TimaKeyStore provider
,03-16 06:28:59.628  4161  4214 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 06:28:59.638  4583  4583 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 06:28:59.648  4583  4583 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 06:28:59.648  4583  4583 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 06:28:59.648  4583  4583 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 06:28:59.678  3444  3523 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-16 06:28:59.718  1020  1044 W libprocessgroup: failed to open /acct/uid_10013/pid_3707/cgroup.procs: No such file or directory
,03-16 06:28:59.778  4085  4100 I art     : Background sticky concurrent mark sweep GC freed 7573(1041KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 15MB/15MB, paused 11.238ms total 34.547ms,
,03-16 06:28:59.798  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:59.798  4161  4214 I GFX raster: took 0.747395ms for 96*96 texture 0
03-16 06:28:59.798  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8727350 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8745158 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:28:59.798  1020  1503 I art     : Explicit concurrent mark sweep GC freed 27783(1427KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 22MB/33MB, paused 2.613ms total 163.460ms
,03-16 06:28:59.808  4161  4214 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 06:28:59.818  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.818  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.818  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:59.828  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.828  1020  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.828  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:28:59.838  2099  4582 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 287 ms
,03-16 06:28:59.928  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:59.928  4161  4214 I GFX raster: took 0.632970ms for 96*96 texture 0
,03-16 06:28:59.928  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8727e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8745e60 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:28:59.938  4161  4214 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 06:28:59.948  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:28:59.948  4161  4214 I GFX raster: took 0.815157ms for 96*96 texture 0
03-16 06:28:59.948  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb870aad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8746b00 counterpartCT=4 counterpartW=96 counterparth=96
03-16 06:28:59.948   292   292 E SMD     : DCD OFF
,03-16 06:28:59.958  4161  4214 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 06:28:59.988  1020  1098 V AlarmManager: waitForAlarm result :8
,03-16 06:28:59.988  1020  1558 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:28:59.988  1020  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:28:59.988  1020  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-16 06:28:59.998  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-16 06:28:59.998  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 06:29:00.008  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 06:29:00.008  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 06:29:00.018  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 06:29:00.018  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-16 06:29:00.018  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 06:29:00.038  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:00.038  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:00.048  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:00.058  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 06:29:00.058  1020  1557 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:00.058  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-16 06:29:00.058  1020  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:00.058  1020  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:00.068  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 06:29:00.078  1020  1560 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:00.088  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 06:29:00.088  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:00.088  1020  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:00.088  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:00.098  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 06:29:00.118  1758  1758 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
03-16 06:29:00.118  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-16 06:29:00.118  1020  1557 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:00.118  1020  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:00.118  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-16 06:29:00.118  1020  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:00.118  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-16 06:29:00.118  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-16 06:29:00.118  1758  1758 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,03-16 06:29:00.118  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,03-16 06:29:00.118  1758  1758 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,03-16 06:29:00.128  1758  1758 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,03-16 06:29:00.128  1758  1758 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 06 29
,03-16 06:29:00.138  1020  1558 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:00.148  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.148  4161  4214 I GFX raster: took 0.884634ms for 96*96 texture 0
03-16 06:29:00.148  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb870c460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86b3e40 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.158  1020  1805 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:00.158  1020  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:00.158  1020  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:00.158  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:00.158  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:00.158  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:00.158  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 06:29:00.168  4085  4524 W jxcore-log: Initializing JXcore engine
,03-16 06:29:00.168  4085  4524 W jxcore-log: JXcore engine is ready
,03-16 06:29:00.178  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:00.178  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:00.178  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:00.178  1020  1511 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:00.178  1020  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:00.178  1020  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:00.188  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 06:29:00.188  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 06:29:00.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 06:29:00.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 06:29:00.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 06:29:00.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 06:29:00.188  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:00.198  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:00.198  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:00.268  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.268  4161  4214 I GFX raster: took 0.694010ms for 96*96 texture 0
03-16 06:29:00.268  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb871c440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8745158 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.278  4161  4214 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 06:29:00.288  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.288  4161  4214 I GFX raster: took 0.524375ms for 96*96 texture 0
03-16 06:29:00.288  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb870be30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8745e60 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.298  4161  4214 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 06:29:00.308  1020  1303 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:00.328  3574  3840 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 7184 ms] updated apps [took 7184 ms] 
,03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 06:29:00.338  4161 , 4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: Resource data:2131034112
03-16 06:29:00.338  1020  1509 D RCPManagerService: exchangeData() failure , invalid userId
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-16 06:29:00.338  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
03-16 06:29:00.338  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 06:29:00.348  4161  4214 I GFX raster: took 0.724531ms for 96*96 texture 0
03-16 06:29:00.348  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8727e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86fd788 counterpartCT=4 counterpartW=96 counterparth=96
03-16 06:29:00.348  4161  4214 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-16 06:29:00.378  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.388  4161  4214 I GFX raster: took 0.679115ms for 96*96 texture 0
03-16 06:29:00.388  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8727e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86fd788 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.418  4161  4214 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-16 06:29:00.438  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.438  4161  4214 I GFX raster: took 0.641302ms for 96*96 texture 0
03-16 06:29:00.438  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86fd788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86b3e40 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.458  4467  4467 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 06:29:00.458  4161  4214 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-16 06:29:00.458  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:00.458  1020  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:00.458  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 06:29:00.468  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.478  4161  4214 I GFX raster: took 1.162135ms for 96*96 texture 0
,03-16 06:29:00.478  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb84706e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8746a48 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.488  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
03-16 06:29:00.488  1931  1931 E audit   : type=1400 msg=audit(1458106140.488:205): avc:  denied  { ioctl } for  pid=4524 comm="Thread-617" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 06:29:00.488  1931  1931 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-16 06:29:00.488  1931  1931 E audit   : type=1300 msg=audit(1458106140.488:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9358f8f8 items=0 ppid=309 ppcomm=main pid=4524 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-617" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-16 06:29:00.488  1931  1931 E audit   : type=1320 msg=audit(1458106140.488:205): 
,03-16 06:29:00.498  1020  1558 I ActivityManager: Killing 3769:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.em,ergency.InteractionEmergencyMessageActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:00.498  4161  4214 I AMMetaDataParserService: Resource data:2131034113
03-16 06:29:00.508  4467  4467 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 06:29:00.508  4161  4214 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-16 06:29:00.508  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
03-16 06:29:00.508  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 06:29:00.508  4161  4214 I GFX raster: took 0.809219ms for 96*96 texture 0
03-16 06:29:00.508  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8727e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8727350 counterpartCT=4 counterpartW=96 counterparth=96
03-16 06:29:00.528  4161  4214 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-16 06:29:00.528  4085  4524 W jxcore-log: Starting JXcore engine
,03-16 06:29:00.548  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.548  4161  4214 I GFX raster: took 0.827604ms for 96*96 texture 0
03-16 06:29:00.548  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8727e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8477bd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.548  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:00.548  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:00.558  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:00.558  4161  4214 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
03-16 06:29:00.558  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:00.568  4623  4623 E Zygote  : MountEmulatedStorage()
03-16 06:29:00.568  4623  4623 I libpersona: KNOX_SDCARD checking this for 10068
03-16 06:29:00.568  4623  4623 E Zygote  : v2
03-16 06:29:00.568  4623  4623 I libpersona: KNOX_SDCARD not a persona
,03-16 06:29:00.568  4623  4623 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:29:00.578  4623  4623 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:29:00.578  4623  4623 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-16 06:29:00.578  1020  1509 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4623 uid=10068 gids={50068, 9997} abi=armeabi-v7a
03-16 06:29:00.578  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.578  4161  4214 I GFX raster: took 0.623906ms for 96*96 texture 0
03-16 06:29:00.578  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb87466a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb870aad8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.588  4161  4214 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
03-16 06:29:00.598  1020  1044 W libprocessgroup: failed to open /acct/uid_10098/pid_3769/cgroup.procs: No such file or directory
,03-16 06:29:00.598  1020  1559 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:00.608  4623  4623 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:29:00.608  4623  4623 D ActivityThread: Added TimaKeyStore provider
,03-16 06:29:00.618  1020  1559 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:00.628  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.628  4161  4214 I GFX raster: took 0.595365ms for 96*96 texture 0
03-16 06:29:00.628  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8727350 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8477bd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.628  1020  1303 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:00.628  1020  1303 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:00.628  1020  1303 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-16 06:29:00.638  4161  4214 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 06:29:00.648  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.648  4161  4214 I GFX raster: took 0.815000ms for 96*96 texture 0
03-16 06:29:00.648  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb870aad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8477bd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.658  4161  4214 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 06:29:00.678  4623  4623 D BadgeProvider: onCreate
03-16 06:29:00.678  4623  4623 D BadgeProvider: DatabaseHelper
,03-16 06:29:00.678  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:00.678  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:00.678  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:00.678  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:00.688  4645  4645 E Zygote  : MountEmulatedStorage()
,03-16 06:29:00.688  4645  4645 E Zygote  : v2
03-16 06:29:00.688  4645  4645 I libpersona: KNOX_SDCARD checking this for 10142
03-16 06:29:00.688  4645  4645 I libpersona: KNOX_SDCARD not a persona
03-16 06:29:00.688  4645  4645 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:29:00.698  4645  4645 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:29:00.698  1020  1511 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4645 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-16 06:29:00.698  4645  4645 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:29:00.698  1020  1511 I ActivityManager: Killing 3661:com.google.android.partnersetup/u0a14 (adj 15): empty #31
03-16 06:29:00.698  1020  1511 I ActivityManager: Killing 3824:com.android.managedprovisioning/u0a20 (adj 15): empty #32
,03-16 06:29:00.698  3444  3523 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-16 06:29:00.708  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 06:29:00.708  4161  4214 I GFX raster: took 0.699688ms for 96*96 texture 0
03-16 06:29:00.708  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb84706e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8477bd8 counterpartCT=4 counterpartW=96 counterparth=96
03-16 06:29:00.708  4085  4524 W jxcore-log: Platform android
03-16 06:29:00.708  4085  4524 W jxcore-log: 
03-16 06:29:00.708  4085  4524 W jxcore-log: Process ARCH arm
03-16 06:29:00.708  4085  4524 W jxcore-log: 
,03-16 06:29:00.718  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 06:29:00.728  4645  4645 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:29:00.728  4645  4645 D ActivityThread: Added TimaKeyStore provider
,03-16 06:29:00.738  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:00.738  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:00.738  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-16 06:29:00.738  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.748  4161  4214 I GFX raster: took 0.790573ms for 96*96 texture 0
03-16 06:29:00.748  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8477bd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86e29b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.748  4623  4637 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-16 06:29:00.758  4161  4214 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 06:29:00.778  1492  1492 D Launcher.Model: reloadBadges entered.
,03-16 06:29:00.778  4623  4637 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-16 06:29:00.778  4623  4637 D BadgeProvider: sendNotify, [notify] : null
03-16 06:29:00.778  4623  4637 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-16 06:29:00.778  4623  4637 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 06:29:00.778  4623  4637 D BadgeProvider: update, [UpdateCount] : 1
,03-16 06:29:00.788  4645  4645 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 06:29:00.798  1020  1044 W libprocessgroup: failed to open /acct/uid_10014/pid_3661/cgroup.procs: No such file or directory
03-16 06:29:00.798  1020  1044 W libprocessgroup: failed to open /acct/uid_10020/pid_3824/cgroup.procs: No such file or directory
,03-16 06:29:00.818  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 06:29:00.818  4161  4214 I GFX raster: took 0.531093ms for 96*96 texture 0
03-16 06:29:00.818  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86da4d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86e29b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 06:29:00.828  4161  4214 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 06:29:00.848  1020  1303 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-16 06:29:00.858  1020  1503 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-16 06:29:00.858  1020  1805 W ActivityManager: getTasks: caller 10141 does not hold GET_TASKS; limiting output
,03-16 06:29:00.858  4583  4641 I Process : Sending signal. PID: 4583 SIG: 9
,03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-16 06:29:00.868  4161  4214 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-16 06:29:00.868  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.Ac,countSecurity
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:00.878  4161  4214 I AMMetaDataParserService: Resource data:2131165203
03-16 06:29:00.888  1020  1503 D RCPManagerService: exchangeData() failure , invalid userId
03-16 06:29:00.888  4161  4214 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-16 06:29:00.888  4161  4214 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 06:29:00.888  4161  4214 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 06:29:00.888  4161  4214 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-16 06:29:00.888  4161  4214 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-16 06:29:00.888  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
03-16 06:29:00.888  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
03-16 06:29:00.898  1020  1558 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:00.898  1020  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:00.898  1020  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
03-16 06:29:00.898  4161  4214 I GFX construct_block_size_descriptor_2d second part: took 4.326197ms for 0*0 texture 0
03-16 06:29:00.908  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:00.908  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:00.908  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:00.908  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:00.918  4161  4214 I GFX generate_partition_tables: took 17.617189ms for 0*0 texture 0
03-16 06:29:00.918  4161  4214 I GFX raster: took 22.774585ms for 80*80 texture 0
03-16 06:29:00.918  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8722460 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb8723120 counterpartCT=4 counterpartW=80 counterparth=80
03-16 06:29:00.918  4663  4663 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:29:00.918  4663  4663 E Zygote  : MountEmulatedStorage()
03-16 06:29:00.918  4663  4663 I libpersona: KNOX_SDCARD not a persona
03-16 06:29:00.918  4663  4663 E Zygote  : v2
03-16 06:29:00.918  4663  4663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:29:00.918  1020  1033 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4663 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 06:29:00.928  4161  4214 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
03-16 06:29:00.928  4663  4663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:29:00.928  4663  4663 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:29:00.928  1020  1559 I ActivityManager: Killing 3842:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,03-16 06:29:00.938  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 06:29:00.938  4161  4214 I GFX construct_block_size_descriptor_2d second part: took 2.556250ms for 0*0 texture 0
,03-16 06:29:00.948  4161  4214 I GFX generate_partition_tables: took 5.529791ms for 0*0 texture 0
,03-16 06:29:00.948  4161  4214 I GFX raster: took 9.188697ms for 80*80 texture 0
03-16 06:29:00.948  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a98410 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8a984b8 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 06:29:00.948  1020  1032 I ActivityManager: Process com.android.email (pid 4583)(adj 9) has died(31,588)
,03-16 06:29:00.958  4161  4214 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-16 06:29:00.968  1020  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:00.968  1020  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:00.968  1020  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:00.968  1020  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:00.968  4663  4663 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:29:00.968  4663  4663 D ActivityThread: Added TimaKeyStore provider
,03-16 06:29:00.978  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 06:29:00.978  4161  4214 I GFX raster: took 0.850677ms for 80*80 texture 0
03-16 06:29:00.978  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a98410 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb87227c0 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 06:29:00.978  4679  4679 E Zygote  : MountEmulatedStorage(),
03-16 06:29:00.978  4679  4679 I libpersona: KNOX_SDCARD checking this for 10141
03-16 06:29:00.978  4679  4679 E Zygote  : v2
03-16 06:29:00.978  4679  4679 I libpersona: KNOX_SDCARD not a persona
03-16 06:29:00.978  4679  4679 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:29:00.988  4679  4679 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 06:29:00.988  4679  4679 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:29:00.988  1020  1805 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4679 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-16 06:29:00.988  4161  4214 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-16 06:29:01.008  4679  4679 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:29:01.008  4679  4679 D ActivityThread: Added TimaKeyStore provider
,03-16 06:29:01.038  4679  4679 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 06:29:01.038  4679  4679 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 06:29:01.038  4679  4679 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 06:29:01.038  4679  4679 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 06:29:01.048  1020  1044 W libprocessgroup: failed to open /acct/uid_10055/pid_3842/cgroup.procs: No such file or directory
,03-16 06:29:01.048  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:01.048  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:01.048  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:01.048  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:01.058  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80,
03-16 06:29:01.058  4161  4214 I GFX raster: took 0.689010ms for 80*80 texture 0
03-16 06:29:01.058  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a98410 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8a984b8 counterpartCT=4 counterpartW=80 counterparth=80
03-16 06:29:01.058  4161  4214 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575,
,03-16 06:29:01.068  4695  4695 E Zygote  : MountEmulatedStorage(),
03-16 06:29:01.068  4695  4695 E Zygote  : v2
03-16 06:29:01.068  4695  4695 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:29:01.068  4695  4695 I libpersona: KNOX_SDCARD not a persona,
03-16 06:29:01.068  4695  4695 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:29:01.068  4695  4695 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 06:29:01.068  4695  4695 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:29:01.078  1020  1503 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4695 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-16 06:29:01.088  1020  1503 I ActivityManager: Killing 3860:com.samsung.android.MtpApplication/1000 (adj 15): empty #31,
,03-16 06:29:01.088  4695  4695 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-16 06:29:01.088  4695  4695 D ActivityThread: Added TimaKeyStore provider
,03-16 06:29:01.108   309   309 I art     : Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 685us total 32.145ms
,03-16 06:29:01.118  1020  1141 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:01.128   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 17.311ms
,03-16 06:29:01.128  1020  1560 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:01.138   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 17.219ms
,03-16 06:29:01.168  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3860/cgroup.procs: No such file or directory
,03-16 06:29:01.168  1020  1302 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:01.168  1020  1557 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:01.178  4695  4695 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-16 06:29:01.178  4695  4695 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-16 06:29:01.178  4695  4695 D SecurityLogAgent: StateMachine : Current State = 1
03-16 06:29:01.178  4695  4695 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-16 06:29:01.178  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:01.178  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:01.178  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:01.178  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:01.188  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 06:29:01.188  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 06:29:01.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 06:29:01.198  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
03-16 06:29:01.198  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 06:29:01.198  4716  4716 I libpersona: KNOX_SDCARD checking this for 10148
03-16 06:29:01.198  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 06:29:01.198  4716  4716 I libpersona: KNOX_SDCARD not a persona,
03-16 06:29:01.198  4716  4716 E Zygote  : MountEmulatedStorage()
03-16 06:29:01.198  4716  4716 E Zygote  : v2
03-16 06:29:01.198  4716  4716 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:29:01.198  4716  4716 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 06:29:01.198  4716  4716 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:29:01.208  1020  1032 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4716 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a,
,03-16 06:29:01.218  1020  1032 I ActivityManager: Killing 3888:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,03-16 06:29:01.228  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 06:29:01.228  4161  4214 I GFX raster: took 1.188179ms for 80*80 texture 0
03-16 06:29:01.228  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86fd750 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8371520 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 06:29:01.238  4161  4214 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-16 06:29:01.258  4716  4716 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:29:01.258  4716  4716 D ActivityThread: Added TimaKeyStore provider
,03-16 06:29:01.278  4161  4214 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 06:29:01.278  4161  4214 I GFX raster: took 0.636979ms for 80*80 texture 0
03-16 06:29:01.278  4161  4214 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86fd750 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8722460 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 06:29:01.278  4085  4524 I jxcore-log: JXcore Cordova bridge is ready!
03-16 06:29:01.278  4085  4524 I jxcore-log: 
03-16 06:29:01.278  4085  4524 W jxcore-log: JXcore engine is started
,03-16 06:29:01.288  4161  4214 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-16 06:29:01.288  4085  4493 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 06:29:01.288  4085  4085 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 06:29:01.308  4623  4631 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-16 06:29:01.308  1020  1302 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-16 06:29:01.318  4161  4214 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-16 06:29:01.318  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-16 06:29:01.348  1020  1044 W libprocessgroup: failed to open /acct/uid_10056/pid_3888/cgroup.procs: No such file or directory
,03-16 06:29:01.348  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:01.348  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:01.348  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-16 06:29:01.358  1020  1557 W ActivityManager: getTasks: caller 10142 does not hold GET_TASKS; limiting output
,03-16 06:29:01.368  4645  4669 I Process : Sending signal. PID: 4645 SIG: 9
,03-16 06:29:01.378  4716  4716 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-16 06:29:01.388  1020  1560 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.388  1020  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.388  1020  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-16 06:29:01.388  1020  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:01.388  1020  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:01.388  1020  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:01.388  1020  3997 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:01.398  1020  1503 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 06:29:01.408  4737  4737 E Zygote  : MountEmulatedStorage()
03-16 06:29:01.408  4737  4737 E Zygote  : v2
03-16 06:29:01.408  4737  4737 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:29:01.408  4737  4737 I libpersona: KNOX_SDCARD not a persona
,03-16 06:29:01.408  4737  4737 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:29:01.408  4737  4737 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:29:01.408  4737  4737 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-16 06:29:01.408  1020  3997 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4737 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 06:29:01.428  1492  1492 D Launcher.Model: reloadBadges entered.
,03-16 06:29:01.428  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-16 06:29:01.428  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-16 06:29:01.428  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-16 06:29:01.428  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-16 06:29:01.428  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-16 06:29:01.428  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:01.428  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-16 06:29:01.428  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 06:29:01.428  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:01.428  4161  4214 I AMMetaDataParserService: Resource data:2131099648
,03-16 06:29:01.438  4623  4631 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,03-16 06:29:01.438  4623  4631 D BadgeProvider: sendNotify, [notify] : null
03-16 06:29:01.438  4623  4631 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-16 06:29:01.438  4623  4631 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 06:29:01.438  4623  4631 D BadgeProvider: update, [UpdateCount] : 1
,03-16 06:29:01.438  4161  4214 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-16 06:29:01.438  4161  4214 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 06:29:01.438  4161  4214 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 06:29:01.438  4161  4214 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 06:29:01.438  4161  4214 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 06:29:01.448  1020  1141 I ActivityManager: Process com.android.exchange (pid 4645)(adj 11) has died(25,581)
,03-16 06:29:01.448  4737  4737 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:29:01.448  4161  4214 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-16 06:29:01.448  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:01.448  4737  4737 D ActivityThread: Added TimaKeyStore provider
,03-16 06:29:01.468  4161  4214 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 06:29:01.478  4161  4214 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 06:29:01.508  4161  4214 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 06:29:01.518  1020  1141 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-16 06:29:01.518  1020  1141 I ActivityManager: Killing 3616:com.sec.pcw.device/1000 (adj 15): empty #31
,03-16 06:29:01.528  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:01.528  1020  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.528  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.528  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.528  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 06:29:01.528  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.538  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.538  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.538  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.538  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:01.538  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.538  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.538  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.548  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.548  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.548  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.548  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.548  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.548  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.548  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.548  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.558  4161  4214 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 06:29:01.558  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.558  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.558  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.558  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.558  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.558  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.568  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.568  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.568  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.568  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 06:29:01.568  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.568  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.568  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.578  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.578  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.578  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.578  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.578  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.578  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.588  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.588  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.588  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.588  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.588  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.588  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 06:29:01.588  4161  4214 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 06:29:01.598  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:01.598  1020  1020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:01.598  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.598  1020  1805 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-16 06:29:01.598  1020  1805 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-16 06:29:01.598  1020  1805 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-16 06:29:01.598  1020  1805 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-16 06:29:01.598  1020  1805 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:01.598  1020  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:01.598  1020  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.608  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.608  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.608  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.618  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.618  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.618  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.628  1020  1559 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.628  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-16 06:29:01.628  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-16 06:29:01.628  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:01.628  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:01.628  4161  4214 I AMMetaDataParserService: Resource data:2131099648
,03-16 06:29:01.628  1020  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.628  4161  4214 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 06:29:01.628  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:01.628  1020  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.628  4161  4214 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 06:29:01.638  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.638  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.638  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.648  4161  4214 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 06:29:01.658  1822  1822 D WearableService: callingUid 10011, callindPid: 1822
,03-16 06:29:01.658  1020  1805 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.658  1020  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.658  1020  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.668  1822  4753 E MDM     : [243] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 06:29:01.668  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.678  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.678  4161  4214 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 06:29:01.678  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.678  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.678  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.678  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.688  4161  4214 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 06:29:01.688  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.688  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.688  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.698  1822  1822 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 06:29:01.698  1020  1302 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.698  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 06:29:01.698  1020  1302 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.698  1020  1302 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.698  2099  4754 D LocationInitializer: Restart initialization of location
,03-16 06:29:01.698  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:01.698  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:01.698  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.708  1020  3997 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.708  1020  3997 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.708  1020  3997 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.718  1020  1303 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.718  1020  1303 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.718  1020  1303 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.718  4161  4214 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 06:29:01.728  3444  3523 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-16 06:29:01.728  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.728  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.728  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.728  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-16 06:29:01.728  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-16 06:29:01.728  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-16 06:29:01.728  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-16 06:29:01.728  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:01.728  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:01.728  4161  4214 I AMMetaDataParserService: Resource data:2131099648
,03-16 06:29:01.728  4161  4214 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 06:29:01.728  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:01.738  1822  1822 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:29:01.738  4161  4214 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 06:29:01.738  1020  1557 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.738  1020  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.748  1020  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.758  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:01.758  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:01.758  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.768  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.768  1020  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 06:29:01.768  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:01.768  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:01.768  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 06:29:01.768  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-16 06:29:01.778  1822  2125 W GCoreFlp: No location to return for getLastLocation()
,03-16 06:29:01.778  1822  4755 W FusedLocationProvider: location=null,
,03-16 06:29:01.798  4161  4214 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 06:29:01.818  1020  1805 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:01.818  1020  1805 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:01.818  1020  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-16 06:29:01.818  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:01.818  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:01.818  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:01.818  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:01.828  4161  4214 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 06:29:01.838  4161  4214 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 06:29:01.848  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 06:29:01.858  4161  4214 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 06:29:01.878  4760  4760 E Zygote  : MountEmulatedStorage(),
,03-16 06:29:01.878  4760  4760 E Zygote  : v2
,03-16 06:29:01.878  4760  4760 I libpersona: KNOX_SDCARD checking this for 10041
03-16 06:29:01.878  4760  4760 I libpersona: KNOX_SDCARD not a persona
,03-16 06:29:01.878  4760  4760 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 06:29:01.888  4760  4760 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 06:29:01.888  4760  4760 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 06:29:01.888  1020  1509 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.widget.MmsWidgetProvider: pid=4760 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,03-16 06:29:01.898  1020  1557 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-16 06:29:01.898  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-16 06:29:01.898  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:01.898  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:01.898  4161  4214 I AMMetaDataParserService: Resource data:2131099648
,03-16 06:29:01.898  4161  4214 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 06:29:01.898  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:01.908  4161  4214 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 06:29:01.918  4161  4214 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 06:29:01.928  4760  4760 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:29:01.928  4760  4760 D ActivityThread: Added TimaKeyStore provider
,03-16 06:29:01.948  4760  4760 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-16 06:29:01.948  4760  4760 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 06:29:01.948  4760  4760 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 06:29:01.948  4161  4214 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 06:29:01.948  4760  4760 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 06:29:01.948  4760  4760 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 06:29:01.958  4161  4214 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 06:29:01.968  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 06:29:02.008  4161  4214 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 06:29:02.028  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-16 06:29:02.028  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.028  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:02.028  4161  4214 I AMMetaDataParserService: Resource data:2131099648
,03-16 06:29:02.038  4161  4214 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 06:29:02.038  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:02.038  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3616/cgroup.procs: No such file or directory
,03-16 06:29:02.038  4161  4214 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 06:29:02.048  4161  4214 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 06:29:02.058  4161  4214 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 06:29:02.078  4161  4214 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 06:29:02.088  1020  1020 I ValidateNoPeople: mEvictionCount: 0
,03-16 06:29:02.128  4760  4760 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-16 06:29:02.188  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 06:29:02.198  4161  4214 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 06:29:02.208  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,03-16 06:29:02.208  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.208  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
,03-16 06:29:02.208  4161  4214 I AMMetaDataParserService: Resource data:2131099648
,03-16 06:29:02.208  4161  4214 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-16 06:29:02.208  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:02.218  4161  4214 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 06:29:02.228  4161  4214 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 06:29:02.238  4161  4214 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 06:29:02.258  4161  4214 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 06:29:02.268  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 06:29:02.278  4760  4760 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 138.190ms,
,03-16 06:29:02.278  4161  4214 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
,03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-16 06:29:02.298  4161  4214 W ContextImpl: Calling a method in the system process without a qualified use,r: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-16 06:29:02.298  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
03-16 06:29:02.328  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-16 06:29:02.328  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.328  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:02.328  4161  4214 I AMMetaDataParserService: Resource data:2131165197
03-16 06:29:02.328  4161  4214 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 06:29:02.328  4161  4214 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 06:29:02.328  4161  4214 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 06:29:02.328  4161  4214 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 06:29:02.328  4161  4214 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 06:29:02.328  4161  4214 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 06:29:02.328  4161  4214 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-16 06:29:02.338  4161  4214 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-16 06:29:02.338  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:02.358  4161  4214 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
03-16 06:29:02.378  4161  4214 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 06:29:02.388  4760  4760 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 113.660ms
,03-16 06:29:02.398  4760  4760 D Mms/TelephonyPermission: start operation mode monitor
,03-16 06:29:02.398  4161  4214 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 06:29:02.398  4760  4777 D Mms/ArtClassLoader: init before art
,03-16 06:29:02.408  4760  4760 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 06:29:02.428  4760  4760 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-16 06:29:02.428  4760  4760 D Mms/TelephonyPermission: isDefault true
,03-16 06:29:02.428  4760  4760 D Mms/MmsApp: onCreate() com.android.mms
,03-16 06:29:02.428  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 06:29:02.438  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,03-16 06:29:02.438  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 06:29:02.438  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-16 06:29:02.438  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:02.438  4161  4214 I AMMetaDataParserService: Resource data:2131165197
,03-16 06:29:02.438  4161  4214 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-16 06:29:02.438  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:02.458  4161  4214 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 06:29:02.468  4760  4760 D Mms/MmsApp: [start]    initCountryIso consume time = 340.684896
,03-16 06:29:02.468  1020  1557 D CountryDetector: The first listener is added
,03-16 06:29:02.478  4760  4760 D Mms/MmsApp: [end]    initCountryIso consume time = 8.91125
03-16 06:29:02.478  4760  4760 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.100208
,03-16 06:29:02.478  4161  4214 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 06:29:02.498  4161  4214 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 06:29:02.498  4760  4760 D Mms/MmsConfig: before partial update
,03-16 06:29:02.508  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 06:29:02.508  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-16 06:29:02.508  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-16 06:29:02.508  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.508  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:02.508  4161  4214 I AMMetaDataParserService: Resource data:2131165197
,03-16 06:29:02.518  4161  4214 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-16 06:29:02.518  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:02.518  4760  4760 D Mms/MmsConfig: Load Resize quality : 80
,03-16 06:29:02.528  4760  4760 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-16 06:29:02.528  4760  4760 D EasySignUpManager_1.0.1: isAuth is false
,03-16 06:29:02.528  4760  4760 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-16 06:29:02.528  4161  4214 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 06:29:02.538  1461  1754 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4760,
,03-16 06:29:02.538  1461  1754 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.315 ms
,03-16 06:29:02.538  4161  4214 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 06:29:02.548  4760  4760 D EasySignUpManager_1.0.1: isAuth is false
,03-16 06:29:02.548  4760  4760 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-16 06:29:02.548  4760  4760 E CscParser: mps_code.dat does not exist
,03-16 06:29:02.548  4760  4760 E CscParser: customer_path =/system/csc/customer.xml
,03-16 06:29:02.558  4760  4760 E CscParser: fileName + /system/csc/customer.xml
,03-16 06:29:02.558  4760  4760 E CscParser: mps_code.dat does not exist
,03-16 06:29:02.558  4760  4760 E CscParser: customer_path =/system/csc/customer.xml
03-16 06:29:02.558  4760  4760 E CscParser: fileName + /system/csc/customer.xml
,03-16 06:29:02.568  4161  4214 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 06:29:02.568  4760  4760 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-16 06:29:02.578  4760  4760 D Mms/MmsConfig:  enable multiwindow = false
,03-16 06:29:02.578  4760  4760 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-16 06:29:02.578  4760  4760 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-16 06:29:02.588  4760  4760 D Mms/MmsConfig: [end]    init() consume time = 114.456823
,03-16 06:29:02.588  4760  4760 D Mms/Contact: [start]    init() consume time = 1.38349
,03-16 06:29:02.598  1461  1477 D TP/MmsSmsProvider: query,matched:13, calling pid = 4760
,03-16 06:29:02.598  4161  4214 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 06:29:02.598  1461  1477 D TP/MmsSmsProvider: match 13:Elapsed time : 1.690 ms
,03-16 06:29:02.598  4760  4760 D Mms/Contact: [end]    init consume time = 13.704948
,03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-16 06:29:02.608  4161  4214 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-16 06:29:02.608  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
03-16 06:29:02.608  4760  4784 D Mms/DraftCache: [start]    rebuildCache consume time = 7.240937
,03-16 06:29:02.618  1461  1754 D TP/MmsSmsProvider: query,matched:12, calling pid = 4760
,03-16 06:29:02.618  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-16 06:29:02.618  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.618  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-16 06:29:02.618  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-16 06:29:02.618  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-16 06:29:02.618  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 06:29:02.618  4161  4214 I AMMetaDataParserService: Resource data:2131099648
,03-16 06:29:02.618  1461  1754 D TP/MmsSmsProvider: match 12:Elapsed time : 1.986 ms
,03-16 06:29:02.618  4161  4214 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-16 06:29:02.618  4161  4214 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 06:29:02.618  4161  4214 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 06:29:02.618  4161  4214 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-16 06:29:02.618  4161  4214 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 06:29:02.618  4161  4214 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-16 06:29:02.618  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:02.628  4760  4760 D Mms/MethodReflector: getSubId is called
,03-16 06:29:02.628  4760  4784 D Mms/DraftCache: [end]    rebuildCache consume time = 14.589583
,03-16 06:29:02.628  4760  4760 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-16 06:29:02.628  4760  4760 D Mms/MethodReflector: getTelephonyProperty is called
,03-16 06:29:02.628  4760  4760 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-16 06:29:02.628  4760  4760 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
,03-16 06:29:02.628  4760  4760 D Mms/DownloadManager: auto download without roaming -> true
03-16 06:29:02.628  4760  4760 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,03-16 06:29:02.628  4760  4760 D Mms/MethodReflector: getSubId is called
,03-16 06:29:02.628  4760  4760 D Mms/MethodReflector: getDefaultSmsSubId is called
,03-16 06:29:02.628  4760  4760 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-16 06:29:02.628  4760  4760 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
,03-16 06:29:02.628  4760  4760 D Mms/MethodReflector: getTelephonyProperty is called
03-16 06:29:02.628  4760  4760 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-16 06:29:02.628  4760  4760 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
,03-16 06:29:02.638  4760  4760 D Mms/DownloadManager: auto download without roaming -> true
03-16 06:29:02.638  4760  4760 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-16 06:29:02.638  4760  4760 D Mms/DownloadManager: auto download during roaming secondary -> false
03-16 06:29:02.638  4760  4760 D Mms/DownloadManager: mAutoDownload ------> true
,03-16 06:29:02.648  4161  4214 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-16 06:29:02.668  4760  4760 D ComposerPerformance: 1458106142681 ms / [DONE] Composer constructor
,03-16 06:29:02.678  4161  4214 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
03-16 06:29:02.678  4760  4760 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-16 06:29:02.678  4760  4760 I Mms/ReservationManager: ReservationManager()
,03-16 06:29:02.688  4760  4760 I Mms/ReservationManager: resetAfterConnected()
,03-16 06:29:02.688  1461  1477 D TP/MmsSmsProvider: query,matched:7, calling pid = 4760
,03-16 06:29:02.688  4760  4785 D Mms/Conversation: [start]    init() consume time = 61.268334
,03-16 06:29:02.688  1461  1477 D TP/MmsSmsProvider: match 7:Elapsed time : 2.207 ms
,03-16 06:29:02.688  4760  4760 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-16 06:29:02.698  1461  1754 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-16 06:29:02.698  4760  4760 D Mms/MmsApp: [end]    onCreate() consume time = 15.996406
,03-16 06:29:02.708  1461  1754 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-16 06:29:02.708  1461  1754 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-16 06:29:02.708  1461  1754 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-16 06:29:02.708  1461  1754 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 06:29:02.708  1461  1754 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 06:29:02.708  1461  1754 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-16 06:29:02.708  1461  1754 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 06:29:02.708  1461  1754 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 06:29:02.708  1461  1754 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-16 06:29:02.718  1461  1754 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,03-16 06:29:02.718  1461  1754 D TP/MmsSmsProvider: need read changed broadcast:false
,03-16 06:29:02.718  4760  4785 D Mms/Conversation: [end]    init consume time = 17.815104
,03-16 06:29:02.718  4760  4760 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-16 06:29:02.718  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:02.718  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 06:29:02.718  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 06:29:02.718  4760  4760 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-16 06:29:02.728  1020  1032 I ActivityManager: Killing 3931:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,03-16 06:29:02.728  4760  4785 D Mms/MessagingNotification: [start]    init() consume time = 4.449219
,03-16 06:29:02.728  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-16 06:29:02.728  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-16 06:29:02.728  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-16 06:29:02.728  4161  4214 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-16 06:29:02.728  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,03-16 06:29:02.728  3444  3523 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-16 06:29:02.738  4760  4760 D Mms/MethodReflector: getSubId is called
03-16 06:29:02.738  4760  4760 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-16 06:29:02.738  4760  4760 D Mms/MethodReflector: getTelephonyProperty is called
03-16 06:29:02.738  4760  4760 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-16 06:29:02.738  4760  4760 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-16 06:29:02.738  4760  4760 D Mms/DownloadManager: auto download without roaming -> true
03-16 06:29:02.738  4760  4760 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
03-16 06:29:02.738  4760  4760 D Mms/DownloadManager: mAutoDownload ------> true
,03-16 06:29:02.818  1020  1044 W libprocessgroup: failed to open /acct/uid_10058/pid_3931/cgroup.procs: No such file or directory
,03-16 06:29:02.828  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
,03-16 06:29:02.828  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.828  4161  4214 I AMMetaDataParserService: getResourcePackageName:assistant
,03-16 06:29:02.828  4161  4214 I AMMetaDataParserService: Resource data:2131165220
,03-16 06:29:02.838  4161  4214 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 06:29:02.838  4161  4214 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 06:29:02.838  4161  4214 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 06:29:02.838  4161  4214 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 06:29:02.838  4161  4214 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 06:29:02.838  4161  4214 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 06:29:02.848  4161  4214 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
,03-16 06:29:02.848  4161  4214 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 06:29:02.858  4161  4214 I AMMetaDataParserService: Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,03-16 06:29:02.858  4760  4777 D Mms/ArtClassLoader: init [DONE] art
,03-16 06:29:02.878  4161  4214 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
,03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
,03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-16 06:29:02.898  1020  1509 I art     : Explicit concurrent mark sweep GC freed 27627(1686KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.660ms total 175.474ms
,03-16 06:29:02.898  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.a,ndroid.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity,
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-16 06:29:02.918  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  1020  1303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
,03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resour,ce data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-16 06:29:02.928  4161,  4214 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-16 06:29:02.938  4786  4786 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.938  4786  4786 I libpersona: KNOX_SDCARD not a persona
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.948  1020  1303 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4786 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
,03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-16 06:29:02.908  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.,918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-16 06:29:02.918  4161  4214 I AMMetaDataParse,rService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Lo,op for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserServic,e: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-16 06:29:02.918  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-16 06:29:02.928  4161  4214 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-16 06:29:02.938  4786  4786 E Zygote  : MountEmulatedStorage()
03-16 06:29:02.938  4786  4786 E Zygote  : v2
03-16 06:29:02.938  4786  4786 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:29:02.948  4786  4786 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:29:02.948   292   292 E SMD     : DCD OFF
03-16 06:29:02.958  4786  4786 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:29:02.968  4760  4785 D Mms/MessagingNotification: [end]    init consume time = 243.13276
03-16 06:29:02.978  1461  1754 D TP/MmsSmsProvider: query,matched:0, calling pid = 4760
03-16 06:29:02.978  1461  1754 V TP/MmsSmsProvider: getSimpleConversations entered.
03-16 06:29:02.978  1461  1754 D TP/MmsSmsProvider: match 0:Elapsed time : 1.169 ms
03-16 06:29:02.978  4760  4797 D Mms/Synchronizer: [start]    doSync consume time = 15.122292
03-16 06:29:02.988  4760  4796 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.880573
03-16 06:29:02.988  1461  3998 D TP/MmsSmsProvider: update, matched:300, calling pid = 4760
03-16 06:29:03.038  1020  1032 I ActivityManager: Killing 3982:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
03-16 06:29:02.988  1461  3998 V TP/MmsSmsProvider: syncDBData start
03-16 06:29:02.988  1461  3998 V TP/MmsSmsProvider: syncDBData sms end
03-16 06:29:02.988  1461  3998 V TP/MmsSmsProvider: syncDBData mms end
03-16 06:29:02.988  1461  3998 V TP/MmsSmsProvider: syncDBData end
03-16 06:29:02.998  1461  1477 D TP/MmsSmsProvider: query,matched:400, calling pid = 4760
03-16 06:29:02.998  4760  4797 D Mms/Synchronizer: [end]    doSync consume time = 13.519219
03-16 06:29:02.998  4760  4796 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 5.582604
03-16 06:29:03.008  4786  4786 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 06:29:03.018  4786  4786 D ActivityThread: Added TimaKeyStore provider
03-16 06:29:03.018  4760  4785 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
03-16 06:29:03.038  1461  3998 D TP/SmsProvider: query,matched:26, calling pid = 4760
03-16 06:29:03.038  1461  3998 D TP/SmsProvider: match 26:Elapsed time : 8.840 ms
03-16 06:29:03.048  1461  1477 D TP/MmsSmsProvider: query,matched:6, calling pid = 4760
03-16 06:29:03.048  1461  1477 D TP/MmsSmsProvider: match 6:Elapsed time : 1.594 ms
03-16 06:29:03.078  4786  4786 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
03-16 06:29:03.078  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:03.078  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:03.078  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:03.078  1020  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:03.098  1020  1511 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4803 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,03-16 06:29:03.098  4803  4803 E Zygote  : MountEmulatedStorage()
03-16 06:29:03.098  1020  1302 D SecContentProvider2: uri = 14 selection = getSealedState
03-16 06:29:03.098  1020  1302 D SecContentProvider2: mCursor = null
,03-16 06:29:03.098  4803  4803 E Zygote  : v2
,03-16 06:29:03.098  4803  4803 I libpersona: KNOX_SDCARD checking this for 10023
03-16 06:29:03.098  4803  4803 I libpersona: KNOX_SDCARD not a persona
,03-16 06:29:03.098  4803  4803 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 06:29:03.098  1020  1303 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-16 06:29:03.098  1020  1303 D SecContentProvider2: mCursor = null
03-16 06:29:03.098  4786  4786 V MTPRx   : sealedState: false
03-16 06:29:03.098  4786  4786 V MTPRx   : sealedUsbMassStorageState: false
03-16 06:29:03.098  4786  4786 E MTPRx   : check value of boot_completed is1
03-16 06:29:03.098  4786  4786 E MTPRx   : check booting is completed_sys.boot_completed
,03-16 06:29:03.108  4786  4786 E MTPRx   : Sd-Card path/storage/extSdCard
,03-16 06:29:03.108  4786  4786 E MTPRx   : Status for mount/Unmount :removed
03-16 06:29:03.108  4786  4786 E MTPRx   : SDcard is not available
03-16 06:29:03.108  4803  4803 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 06:29:03.108  4803  4803 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 06:29:03.108  4786  4786 W MTPRx   : value of connected istrue
03-16 06:29:03.108  4786  4786 W MTPRx   : value of configured istrue
03-16 06:29:03.108  4786  4786 W MTPRx   : value of mtpEnabled istrue
03-16 06:29:03.108  4786  4786 W MTPRx   : value of ptpEnabled isfalse
03-16 06:29:03.108  4786  4786 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-16 06:29:03.108  4786  4786 E MTPRx   : mFirstTime: false
,03-16 06:29:03.128  4803  4803 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:29:03.128  4803  4803 D ActivityThread: Added TimaKeyStore provider
,03-16 06:29:03.138  1020  3997 I ActivityManager: Killing 3798:com.google.android.gm/u0a99 (adj 15): empty #31
,03-16 06:29:03.138  4786  4786 D         : MTP: reading debug level property
,03-16 06:29:03.138  4786  4786 E MTPJNIInterface: Getting CryptionKey from JAVA
03-16 06:29:03.138  4786  4786 E MTPRx   : currentUserId is 0
,03-16 06:29:03.148  4786  4786 E MTPRx   : Start observing USB_STATE_MATCH 
,03-16 06:29:03.148  4786  4786 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-16 06:29:03.148  4786  4786 E MTPRx   : is_Privatemode is NOT 1
,03-16 06:29:03.148  1020  1032 D SettingsProvider: name = boot_time_connected
,03-16 06:29:03.158  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3982/cgroup.procs: No such file or directory
,03-16 06:29:03.188  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 06:29:03.188  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 06:29:03.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 06:29:03.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 06:29:03.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 06:29:03.188  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 06:29:03.218  4803  4803 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-16 06:29:03.228  4786  4786 E MTPRx   : Sending NORMAL_BOOT to stack
03-16 06:29:03.228  4786  4786 E MTPJNIInterface: noti = 17
,03-16 06:29:03.228  1020  1033 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 06:29:03.228  1020  1302 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-16 06:29:03.228  4786  4786 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-16 06:29:03.238  1020  1560 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:03.238  1020  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:03.238  1020  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-16 06:29:03.238  1020  1805 D SettingsProvider: name = mtp_running_status
,03-16 06:29:03.248  1020  1509 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 06:29:03.248  4786  4786 E MTPRx   : else part ... so first time!!!
,03-16 06:29:03.248  4786  4786 E MTPPlaObsrvr: inside setContext()
,03-16 06:29:03.248  4786  4786 E MTPPlaObsrvr:  inside createplafiles
,03-16 06:29:03.258  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 06:29:03.258  4760  4785 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-16 06:29:03.258  4786  4786 E MTPPlaObsrvr: playlist count is0
03-16 06:29:03.258  4786  4786 E MTPPlaObsrvr:  inside try branch createplafiles
,03-16 06:29:03.268  4786  4786 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-16 06:29:03.268  4786  4786 E MTPPlaObsrvr: Inside registerContentObserver
,03-16 06:29:03.268  4786  4786 E MtpAdbObserver: inside setContext()
,03-16 06:29:03.268  4786  4786 E MtpAdbObserver: Inside registerContentObserver
03-16 06:29:03.268  4786  4786 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-16 06:29:03.268  1020  1044 W libprocessgroup: failed to open /acct/uid_10099/pid_3798/cgroup.procs: No such file or directory
,03-16 06:29:03.268  1020  1511 W ActivityManager: userId = 0, bbcId = -10000
,03-16 06:29:03.268  1020  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:03.268  1020  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-16 06:29:03.278  1020  1141 D SettingsProvider: name = mtp_running_status
,03-16 06:29:03.278  1020  1141 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 06:29:03.278  4786  4786 E MtpService: onCreate.
,03-16 06:29:03.278  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-16 06:29:03.278  1020  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 06:29:03.278  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-16 06:29:03.278  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-16 06:29:03.278  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-16 06:29:03.278  1020  1558 W ActivityManager: userId = 0, bbcId = -10000
03-16 06:29:03.278  1020  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 06:29:03.278  1020  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-16 06:29:03.278  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-16 06:29:03.278  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-16 06:29:03.288  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-16 06:29:03.288  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
03-16 06:29:03.288  4786  4820 V MtpMediaDBManager: inside deleteAllDB
,03-16 06:29:03.288  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-16 06:29:03.288  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-16 06:29:03.288  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-16 06:29:03.288  1231  1231 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-16 06:29:03.288  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-16 06:29:03.288  4803  4803 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-16 06:29:03.298  1020  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:03.298  1020  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:03.298  1020  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 06:29:03.298  1020  1302 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 06:29:03.298  4786  4786 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-16 06:29:03.308  4822  4822 E Zygote  : MountEmulatedStorage(),
03-16 06:29:03.308  4822  4822 I libpersona: KNOX_SDCARD checking this for 1000
03-16 06:29:03.308  4822  4822 E Zygote  : v2
03-16 06:29:03.308  4822  4822 I libpersona: KNOX_SDCARD not a persona
,03-16 06:29:03.308  1020  1302 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4822 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 06:29:03.318  4822  4822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 06:29:03.318  4786  4786 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
03-16 06:29:03.318  4786  4786 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
03-16 06:29:03.318  4822  4822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 06:29:03.318  4786  4786 E MtpService: onStartCommand.
03-16 06:29:03.318  4822  4822 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 06:29:03.318  4786  4821 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-16 06:29:03.318  4786  4786 W MTPRx   : calling native method
03-16 06:29:03.318  4786  4786 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-16 06:29:03.318  4786  4820 V MtpMediaDBManager: inside Thread updateDB
,03-16 06:29:03.328  4786  4786 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-16 06:29:03.328  4786  4786 E MTPJNIInterface: noti = 10
03-16 06:29:03.328  4786  4786 E MtpService: onStartCommand.
03-16 06:29:03.328  4786  4786 W MTPRx   : calling native method
03-16 06:29:03.328  4786  4786 E MTPRx   : Checking the driver time out
03-16 06:29:03.328  4786  4786 E MTPJNIInterface: noti = 2
03-16 06:29:03.328  4786  4786 D         : deleting sockets before message queue initialization
03-16 06:29:03.328  4786  4786 D         : event handler thread is created, so set the flag
03-16 06:29:03.328  4786  4786 E MTPRx   : called native method
03-16 06:29:03.328  4786  4786 E MTPJNIInterface: setting Media scanner status0
03-16 06:29:03.328  4786  4786 E MTPJNIInterface: After setting Media scanner status0
03-16 06:29:03.328  4786  4786 W MTPRx   : notification from stack 1
03-16 06:29:03.338  4786  4830 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-16 06:29:03.338  4786  4830 E MTPJNIInterface: Getting media scanner status0
,03-16 06:29:03.338  4786  4821 E MtpService: handleMessage. msg= { when=-8ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-16 06:29:03.338  4786  4820 E MtpMediaDBManager: count : 26
,03-16 06:29:03.338  4786  4830 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A3)
,03-16 06:29:03.348  4822  4822 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 06:29:03.348  4822  4822 D ActivityThread: Added TimaKeyStore provider
,03-16 06:29:03.358  4786  4820 W MtpMediaDBManager: sending db update complete noti to stack
03-16 06:29:03.358  4786  4820 E MTPJNIInterface: noti = 29
,03-16 06:29:03.358  4786  4830 E SQLiteLog: (5) database is locked
,03-16 06:29:03.378  4786  4830 E MTPJNIInterface: Status for mount/Unmount :removed
03-16 06:29:03.378  4786  4830 E MTPJNIInterface: SDcard is not available
,03-16 06:29:03.428  4786  4830 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-16 06:29:03.438  4786  4830 E MTPJNIInterface: Status for mount/Unmount :removed
03-16 06:29:03.438  4786  4830 E MTPJNIInterface: SDcard is not available
03-16 06:29:03.438  4786  4830 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 06:29:03.438  4786  4830 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-16 06:29:03.438  4786  4830 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 06:29:03.438  4786  4830 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-16 06:29:03.438  4786  4830 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 06:29:03.438  4786  4830 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-16 06:29:03.438  4786  4830 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 06:29:03.438  4786  4830 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-16 06:29:03.438  4786  4786 W MTPRx   : notification from stack 2
,03-16 06:29:03.438  4786  4838 D         : [mtp_init_device] Library open with 32 bits.
,03-16 06:29:03.438  4786  4838 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-16 06:29:03.438  4786  4838 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-16 06:29:03.438  4786  4838 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-16 06:29:03.438  4786  4838 E         :  [sua_support_present:1287] returning false 
,03-16 06:29:03.438  4786  4838 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-16 06:29:03.448  4822  4822 D TMNetworkReceiver: TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
03-16 06:29:03.448  4822  4822 D TMNetworkReceiver: TMNetworkReceiver.onReceive() Enter

```
