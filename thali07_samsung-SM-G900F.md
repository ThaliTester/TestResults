#### Test 575312438097721_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
D/TimaKeyStoreProvider( 7345): TimaSignature is unavailable
D/ActivityThread( 7345): Added TimaKeyStore provider
D/ResourcesManager( 7345): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client( 7345): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
--------- beginning of system
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7370): MountEmulatedStorage()
E/Zygote  ( 7370): v2
I/libpersona( 7370): KNOX_SDCARD checking this for 10019
I/libpersona( 7370): KNOX_SDCARD not a persona
I/ActivityManager(  885): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7370 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 7370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/art     (  315): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 536us total 19.889ms
E/SELinux ( 7370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 523us total 14.736ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 388us total 13.124ms
D/TimaKeyStoreProvider( 7370): TimaSignature is unavailable
D/ActivityThread( 7370): Added TimaKeyStore provider
D/ResourcesManager( 7370): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/KLMS-2.4.503: ( 7370): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.503: ( 7370): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1454429662029
I/KLMS-2.4.503: ( 7370): MainReciver(): TIME_CHANGED
I/KLMS-2.4.503: ( 7370): StateImplV2(): dateTimeChanged().START : Tue Feb 02 17:14:22 GMT+01:00 2016
I/KLMS-2.4.503: ( 7370): StateImplV2(): dateTimeChanged().END
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  885): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=7390 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6691:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
E/Zygote  ( 7390): MountEmulatedStorage()
E/Zygote  ( 7390): v2
I/libpersona( 7390): KNOX_SDCARD checking this for 10037
I/libpersona( 7390): KNOX_SDCARD not a persona
I/SELinux ( 7390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7390): TimaSignature is unavailable
D/ActivityThread( 7390): Added TimaKeyStore provider
W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_6691/cgroup.procs: No such file or directory
V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 7390): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/SO_AGENT( 7390): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
I/SA      ( 6748): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6591): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6591): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6591): [1] 5.onFinished: Scheduling replication attempt 1.
E/SMD     (  286): DCD ON
I/ActivityManager(  885): Killing 6707:com.sec.pcw.device/1000 (adj 15): bgCount ##41
I/ActivityManager(  885): Killing 6480:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7406): MountEmulatedStorage()
I/libpersona( 7406): KNOX_SDCARD checking this for 10067
E/Zygote  ( 7406): v2
I/libpersona( 7406): KNOX_SDCARD not a persona
I/ActivityManager(  885): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7406 uid=10067 gids={50067, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
I/SELinux ( 7406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7406): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  885): failed to open /acct/uid_1000/pid_6707/cgroup.procs: No such file or directory
W/libprocessgroup(  885): failed to open /acct/uid_10034/pid_6480/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7406): TimaSignature is unavailable
D/ActivityThread( 7406): Added TimaKeyStore provider
D/AndroidRuntime( 7388): 
D/AndroidRuntime( 7388): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7388): CheckJNI is OFF
D/AndroidRuntime( 7388): setted country_code = Germany
D/AndroidRuntime( 7388): setted countryiso_code = DE
D/AndroidRuntime( 7388): setted sales_code = DBT
D/AndroidRuntime( 7388): readGMSProperty: start
D/AndroidRuntime( 7388): readGMSProperty: already setted!!
D/AndroidRuntime( 7388): readGMSProperty: end
D/AndroidRuntime( 7388): addProductProperty: start
D/ResourcesManager( 7406): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7427): MountEmulatedStorage()
E/Zygote  ( 7427): v2
I/libpersona( 7427): KNOX_SDCARD checking this for 10071
I/libpersona( 7427): KNOX_SDCARD not a persona
I/SELinux ( 7427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  885): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7427 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
I/SELinux ( 7427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7427): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  885): Killing 6725:com.policydm/1000 (adj 15): bgCount ##41
I/ Time Manager ( 7406): Time Difference not stored. TIME_DIFFERENCE
D/TimaKeyStoreProvider( 7427): TimaSignature is unavailable
D/ActivityThread( 7427): Added TimaKeyStore provider
W/libprocessgroup(  885): failed to open /acct/uid_1000/pid_6725/cgroup.procs: No such file or directory
D/ResourcesManager( 7427): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
W/ResourcesManager( 7427): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7427): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7427): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/AffinityControl( 7388): AffinityControl: registerfunction enter
D/AndroidRuntime( 7388): Calling main entry com.android.commands.am.Am
D/comsamsunglog( 7427): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7427): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7427): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7427): [KK AccuPhone]>>> ==============================================================================================
E/PersonaManagerService(  885): inState():  stateMachine is null !!
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/comsamsunglog( 7427): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7427): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/ResourcesManager(  885): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/comsamsunglog( 7427): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7427): [KK AccuPhone]>>> ==============================================================================================
W/ActivityManager(  885): mDVFSHelper.acquire()
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7457): MountEmulatedStorage()
E/Zygote  ( 7457): v2
I/libpersona( 7457): KNOX_SDCARD checking this for 10200
I/libpersona( 7457): KNOX_SDCARD not a persona
I/SELinux ( 7457): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7457 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7457): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7457): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/AndroidRuntime( 7388): Shutting down VM
D/SettingsProvider(  885): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  885): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  885): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  885): selectionArgs: false
D/SettingsProvider(  885): selectionArgs: 10071
D/SecContentProvider(  885): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  885): ret = -1
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/TimaKeyStoreProvider( 7457): TimaSignature is unavailable
D/ActivityThread( 7457): Added TimaKeyStore provider
V/ActivityManager(  885): Display changed displayId=0
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/accuweather( 7427): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
D/accuweather( 7427): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/accuweather( 7427): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7427): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7427): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7427): [KK AccuPhone]>>> RM:136 [0:0]  V init 
I/SQLiteSecureOpenHelper( 3566): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3566): getDatabaseLocked(b,b,pwd)...
D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/ResourcesManager( 7457): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/accuweather( 7427): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/accuweather( 7427): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/accuweather( 7427): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
D/accuweather( 7427): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7472): MountEmulatedStorage()
E/Zygote  ( 7472): v2
I/libpersona( 7472): KNOX_SDCARD checking this for 10091
I/libpersona( 7472): KNOX_SDCARD not a persona
I/ActivityManager(  885): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7472 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 5361:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
I/SELinux ( 7472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7472): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  885): failed to open /acct/uid_10038/pid_5361/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7472): TimaSignature is unavailable
D/ActivityThread( 7472): Added TimaKeyStore provider
D/ResourcesManager( 7472): creating new AssetManager and set to /system/app/ClockPackage/ClockPackage.apk
W/ResourcesManager( 7472): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7472): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7472): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7472): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
I/WebViewFactory( 7457): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7457): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7457): Loading: webviewchromium
I/LibraryLoader( 7457): Time to load native libraries: 3 ms (timestamps 3973-3976)
I/LibraryLoader( 7457): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7457): Binding Chromium to main looper Looper (main, tid 1) {15c4fd88}
I/LibraryLoader( 7457): Expected native library version number "",actual native library version number ""
I/chromium( 7457): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7457): Initializing chromium process, renderers=0
W/art     ( 7457): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7457): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7457): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7457): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/ActivityManager(  885): Activity pause timeout for ActivityRecord{1ec1b3ec u0 com.test.thalitest/.MainActivity t18}
I/Adreno-EGL( 7457): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7457): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7457): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7457): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7457): Remote Branch: 
I/Adreno-EGL( 7457): Local Patches: 
I/Adreno-EGL( 7457): Reconstruct Branch: 
W/chromium( 7457): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/SettingsProvider(  885): name = next_alarm_formatted
D/SettingsProvider(  885): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  885): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  885): selectionArgs: false
D/SettingsProvider(  885): selectionArgs: 10091
D/SecContentProvider(  885): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  885): ret = -1
W/chromium( 7457): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
W/art     ( 7457): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7457): onDetachedFromWindow called when already detached. Ignoring
E/Zygote  ( 7514): MountEmulatedStorage()
E/Zygote  ( 7514): v2
I/libpersona( 7514): KNOX_SDCARD checking this for 10104
I/libpersona( 7514): KNOX_SDCARD not a persona
I/ActivityManager(  885): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7514 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  885): Killing 5937:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
I/SELinux ( 7514): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7514): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7514): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SystemWebViewEngine( 7457): CordovaWebView is running on device made by: samsung
D/TimaKeyStoreProvider( 7514): TimaSignature is unavailable
D/ActivityThread( 7514): Added TimaKeyStore provider
W/art     ( 7457): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7457): Attempt to remove local handle scope entry from IRT, ignoring
D/ResourcesManager( 7514): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/libprocessgroup(  885): failed to open /acct/uid_10042/pid_5937/cgroup.procs: No such file or directory
D/elm:14451( 7514): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
D/elm:14451( 7514): ELMEngine.ELMEngine( context ).
D/elm:14451( 7514): MDMBridge.setEnterpriseBridge()
D/elm:14451( 7514): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
D/elm:14451( 7514): ElmAgentService : onCreate()
D/elm:14451( 7514): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/elm:14451( 7514): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14451( 7514): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14451( 7514): ModuleBase.ModifySetAlarm()
D/elm:14451( 7514): MDMBridge.getInstance()
D/elm:14451( 7514): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 7536): MountEmulatedStorage()
E/Zygote  ( 7536): v2
I/libpersona( 7536): KNOX_SDCARD checking this for 10113
I/libpersona( 7536): KNOX_SDCARD not a persona
I/ActivityManager(  885): Start proc com.sec.android.GeoLookout for broadcast com.sec.android.GeoLookout/.widget.SafetyCareWidget: pid=7536 uid=10113 gids={50113, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 7536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/elm:14451( 7514): ElmAgentService : onDestroy().
I/ActivityManager(  885): Killing 6805:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
D/Activity( 7457): performCreate Call secproduct feature valuefalse
D/Activity( 7457): performCreate Call debug elastic valuetrue
I/SELinux ( 7536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7536): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/OpenGLRenderer( 7457): Render dirty regions requested: true
D/ActivityManager(  885): post active user change for 0
D/KnoxTimeoutHandler(  885): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  885): handleActiveUserChange for user 0
D/TimaKeyStoreProvider( 7536): TimaSignature is unavailable
D/ActivityThread( 7536): Added TimaKeyStore provider
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/StatusBarManagerService(  885): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/StatusBarManagerService(  885): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/ResourcesManager( 7536): creating new AssetManager and set to /system/app/GeoLookout/GeoLookout.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
I/OpenGLRenderer( 7457): Initialized EGL, version 1.4
W/libprocessgroup(  885): failed to open /acct/uid_10078/pid_6805/cgroup.procs: No such file or directory
I/OpenGLRenderer( 7457): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7457): Enabling debug mode 0
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/InputMethodManagerService(  885): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,W/ActivityManager(  885): mDVFSHelper.release()
I/Timeline(  885): Timeline: Activity_windows_visible id: ActivityRecord{1ec1b3ec u0 com.test.thalitest/.MainActivity t18} time:84622
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,W/IInputConnectionWrapper( 7457): showStatusIcon on inactive InputConnection
,I/Timeline( 7457): Timeline: Activity_idle id: android.os.BinderProxy@37440f1b time:84630
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,W/GeoLookout( 7536): H: zOXtzplbN+8pOR8lXMN+zuVFxvDlCo+Yzxg4ugbhd7A04DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
I/GeoLookout( 7536): H: zOXtzplbN+8pOR8lXMN+zq5rYKS75KQLo4xvOOBhIY6eGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
,D/SettingsProvider(  885): name = safetycare_geolookout_registering
,D/SettingsProvider(  885): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  885): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  885): selectionArgs: false
D/SettingsProvider(  885): selectionArgs: 10113
,D/SecContentProvider(  885): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  885): ret = -1
,D/GeoLookout( 7536): H: mmqeDLqBgrS1PY9ZxjAERmjpyYDSyckxRVEBLahXFCCjxEHkYkZuzwjV7ldL9/y2wUiG8ZXusFQQzoKG1FCUjw==
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDkvkgPm5dotWx3IPNd1bDZ3HtYRASO8LE3XMTl+CWy7mA0iuhqjXXzZB9tx1thU84s=
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1MpblPvMyD8bF5o9h5mVT9aba68PSLy9IpSfBXGHVgOg==
D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDkvkgPm5dotWx3IPNd1bDZ3HtYRASO8LE3XMTl+CWy7mA0iuhqjXXzZB9tx1thU84s=
D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
,D/JsMessageQueue( 7457): Set native->JS mode to OnlineEventsBridgeMode
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7568): MountEmulatedStorage()
E/Zygote  ( 7568): v2
I/libpersona( 7568): KNOX_SDCARD checking this for 1000
I/libpersona( 7568): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7568 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7568): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7568): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  885): Killing 6820:com.wsomacp/u0a25 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7568): TimaSignature is unavailable
,D/ActivityThread( 7568): Added TimaKeyStore provider
,D/ResourcesManager( 7568): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/libprocessgroup(  885): failed to open /acct/uid_10025/pid_6820/cgroup.procs: No such file or directory
,D/SSRM:m  (  885): SIOP:: AP = 370, PST = 431, CUR = 300
,D/SecurityLogAgent( 7568): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7568): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 7568): StateMachine : Current State = 1
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7586): MountEmulatedStorage()
I/libpersona( 7586): KNOX_SDCARD checking this for 10176
E/Zygote  ( 7586): v2
I/libpersona( 7586): KNOX_SDCARD not a persona
I/chromium( 7457): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7457): 
,D/jxcore_app_log( 7457): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358547584
,I/ActivityManager(  885): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7586 uid=10176 gids={50176, 9997} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6836:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/chromium( 7457): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/TimaKeyStoreProvider( 7586): TimaSignature is unavailable
,D/ActivityThread( 7586): Added TimaKeyStore provider
,D/ResourcesManager( 7586): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,W/ResourcesManager( 7586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7602): MountEmulatedStorage()
,E/Zygote  ( 7602): v2
I/libpersona( 7602): KNOX_SDCARD checking this for 1000
I/libpersona( 7602): KNOX_SDCARD not a persona
I/ActivityManager(  885): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7602 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6854:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  885): failed to open /acct/uid_10051/pid_6836/cgroup.procs: No such file or directory
,I/SELinux ( 7602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7602): TimaSignature is unavailable
,D/ActivityThread( 7602): Added TimaKeyStore provider
,D/ResourcesManager( 7602): creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,W/libprocessgroup(  885): failed to open /acct/uid_10058/pid_6854/cgroup.procs: No such file or directory
,D/TimeService( 7602): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454429665024
,D/        ( 7602): TimeServiceNative: User Time to be set is 1454429665024
D/QC-time-services( 7602): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 7602): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7602): Lib:time_genoff_operation: pargs->ts_val = 1454429665024
,D/QC-time-services(  326): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 7602): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  326): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454429665024
,D/QC-time-services(  326): Daemon:genoff_opr: Base = 2, val = 1454429665024, operation = 0
,D/QC-time-services(  326): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/10/70 3:49:16
,D/QC-time-services(  326): Daemon:Value read from RTC seconds = 13837756000
D/QC-time-services(  326): Daemon:new time 1454429665024 
D/QC-time-services(  326): Daemon: delta 1440591909024 genoff 1440591909024 
D/QC-time-services(  326): Daemon:genoff_persistent_update: Writing genoff = 1440591909024 to memory
D/QC-time-services(  326): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  326): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  326): Updating the TOD offset
D/QC-time-services(  326): Daemon:genoff_persistent_update: Writing genoff = 1440591909024 to memory
D/QC-time-services(  326): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  326): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services( 7602): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  326): Daemon:Update to modem bit set
D/QC-time-services(  326): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  326): Daemon: Base = 2, Value being sent to MODEM = 1124627109024
,I/ActivityManager(  885): Killing 6166:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,E/QC-time-services(  326): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  326): Daemon: Time-services: Waiting to acceptconnection
,D/daemonapp( 1325): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1325): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1325): [MSC_Daemon]>>> WDSM:41 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1325): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1325): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
,D/comsamsunglog( 1325): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1325): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1325): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1325): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1325): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1325): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1325): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1325): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,W/libprocessgroup(  885): failed to open /acct/uid_1000/pid_6166/cgroup.procs: No such file or directory
,D/comdaemonstockapp( 1325): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1325): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,E/SMD     (  286): DCD ON
,I/art     (  885): Explicit concurrent mark sweep GC freed 42428(2MB) AllocSpace objects, 12(192KB) LOS objects, 30% free, 36MB/52MB, paused 1.844ms total 132.378ms
,W/jxcore-log( 7457): Initializing JXcore engine
,W/jxcore-log( 7457): JXcore engine is ready
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/auditd  ( 2130): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  885): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  885): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,W/jxcore-log( 7457): Starting JXcore engine
D/SecurityLogAgent( 7568):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7568):  SeDenialReceiver : File path = null
,V/AlarmManager(  885): waitForAlarm result :4
,W/jxcore-log( 7457): Platform android
W/jxcore-log( 7457): 
,W/jxcore-log( 7457): Process ARCH arm
W/jxcore-log( 7457): 
,E/SQLiteLog( 7162): (284) automatic index on view_events(_id)
,D/CalendarAlarmManager( 7162): sys current time:1454429666838
,D/CalendarAlarmManager( 7162): reminder amount:0
,I/jxcore-log( 7457): JXcore Cordova bridge is ready!
I/jxcore-log( 7457): 
W/jxcore-log( 7457): JXcore engine is started
,I/jxcore-log( 7457): Toggling radios to true
I/jxcore-log( 7457): 
,D/BluetoothAdapter( 7457): enable()
,D/BluetoothAdapter( 7457): enable(): BT is already enabled..!
,D/WifiService(  885): New client listening to asynchronous messages
,I/WifiManager( 7457): packageName : com.test.thalitest
,D/SecContentProvider(  885): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  885): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  885): mCursor = null
,D/WifiService(  885): setWifiEnabled: true pid=7457, uid=10200
E/WifiService(  885): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  885): Permission Denial: getCurrentUser() from pid=7457, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  885): Failed getting userId using ActivityManagerNative
W/WifiService(  885): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7457, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  885): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  885): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  885): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  885): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  885): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  885): name = wifi_on
,I/WifiService(  885): disconnect: pid=7457, uid=10200
,I/jxcore-log( 7457): Radios toggled
I/jxcore-log( 7457): 
I/jxcore-log( 7457): My device name is: samsung-SM-G900F
I/jxcore-log( 7457): 
,I/wpa_supplicant( 1268): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1268): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1268): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1268): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  885): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1268): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1268): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1268): Disconnected - do not scan
I/wpa_supplicant( 1268): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  885): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
D/WifiP2pService(  885): InactiveState{ what=143375 }
D/WifiP2pService(  885): P2pEnabledState{ what=143375 }
D/CommandListener(  281): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1166): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 1677): Read error: ssl=0xaeb22200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1677): SSL shutdown failed: ssl=0xaeb22200: I/O error during system call, Broken pipe
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  885): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  885): updateNetworkInfo()
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService(  885): updateNetworkInfo()
D/ConnectivityService(  885): ignoring duplicate network state non-change
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=-10ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-10ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
,E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  885): evaluateTrafficStatsPolling
,I/CLocInfoService(  885): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1166): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth,
,D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1166): applyOpen
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
,D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
E/WifiStateMachine(  885): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1268): wlan0: Setting scan request: 0 sec 0 usec
D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/wpa_supplicant( 1268): P2P: Current p2p state = IDLE
D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/wpa_supplicant( 1268): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1268): First Scan Start
I/wpa_supplicant( 1268): Scan requested (ret=0) - scan timeout 30 seconds
,I/Hs20UtilService( 1299): Starting #6
E/WifiStateMachine(  885): ConnectModeState: Network connection lost 
,I/Hs20UtilService( 1299): Message received 5007
D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ what=143375 }
,D/WifiP2pService(  885): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1166): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  885): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  885): calling update connectivity
D/ConnectivityService(  885):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  885):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  885): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  885): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler( 1166): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Disconnected - quitting
D/EntConnectivity(  885): Not allowed due to - mEnabled false
,D/CommandListener(  281): Clearing all IP addresses on wlan0
,D/ConnectivityService(  885): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  885): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiStateMachine(  885): updateConfiguredNetworkExpiration - currTime: 1454429667679
,D/WifiStateMachine(  885): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/TelephonyNetworkFactory( 1477): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/CSLegacyTypeTracker(  885): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/CSLegacyTypeTracker(  885): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/WifiTrafficPoller(  885): evaluateTrafficStatsPolling
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  885): NetworkAgent: NetworkAgent channel lost
,I/CLocInfoService(  885): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1166): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,D/ConnectivityService(  885): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,I/Hs20UtilService( 1299): Starting #7
I/Hs20UtilService( 1299): Message received 5007
,D/SmartBondingService(  885): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  885): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  885): getSBEnabled() enabled =false
,D/SmartBondingService(  885): getSBEnabled() enabled =false
V/NetworkStats(  885): updateIfacesLocked()
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
D/SmartBondingService(  885): getSBEnabled() enabled =false
V/NetworkStats(  885): performPollLocked(flags=0x1)
,D/SmartBondingService(  885): getNetworkEnabled : wifi : true mobile : true
,E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
D/NetworkStatsFactory(  885): UpdateStatsForKnox
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  885): mCursor = null
,D/NtpTrustedTime(  885): currentTimeMillis() cache hit
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1166): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1166): updateDataNetType()
D/StatusBar.NetworkController( 1166): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  885): currentTimeMillis() cache hit
,D/NtpTrustedTime(  885): currentTimeMillis() cache hit
V/NetworkStats(  885): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
,E/ConnectivityService(  885): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1166): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1166): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1166): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1166): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
,D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,V/NetworkStats(  885): performPollLocked() took 18ms
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/NtpTrustedTime(  885): currentTimeMillis() cache hit
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
,D/SecContentProvider2(  885): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  885): mCursor = null
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  885): updateDataUsageMap
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2148): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/SmartBondingService(  885): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,D/SmartBondingService(  885): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  885): getSBEnabled() enabled =false
,D/SmartBondingService(  885): getSBEnabled() enabled =false
D/SmartBondingService(  885): getSBEnabled() enabled =false
,D/SmartBondingService(  885): getNetworkEnabled : wifi : true mobile : true
,I/CLocInfoService(  885): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  885): CLoinfo wifi false
,I/SystemBroadcastReceiver( 7180): [#DCM#] [DCM_Performance] onReceive completed in time  244 microsec. 
,E/Zygote  ( 7674): MountEmulatedStorage()
,E/Zygote  ( 7674): v2
I/libpersona( 7674): KNOX_SDCARD checking this for 1000
I/libpersona( 7674): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7674 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/SLocation(  885): No Active Data Connection
,I/SystemBroadcastReceiver( 7180): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7180): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7180): [#DCM#] setIsConnectedForExtractors 
,I/art     (  315): Explicit concurrent mark sweep GC freed 8755(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 842us total 21.556ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 7.898ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 9.873ms
,I/SELinux ( 7674): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7674): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7674): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5440): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7674): TimaSignature is unavailable
,D/ActivityThread( 7674): Added TimaKeyStore provider
,E/SMD     (  286): DCD ON
,D/ResourcesManager( 7674): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7674): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 7674): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7674): new DMDBOpenHelper instance
,I/DBG_DM  ( 3781): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3781): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_PushUtil( 7674): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7674): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7674): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7674): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7674): noConnectivity : true
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7700): MountEmulatedStorage()
,E/Zygote  ( 7700): v2
I/libpersona( 7700): KNOX_SDCARD checking this for 10002
I/libpersona( 7700): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7700 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6549:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,I/SELinux ( 7700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7700): TimaSignature is unavailable
,D/ActivityThread( 7700): Added TimaKeyStore provider
,D/ResourcesManager( 7700): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/libprocessgroup(  885): failed to open /acct/uid_10086/pid_6549/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 6873:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7717): MountEmulatedStorage()
E/Zygote  ( 7717): v2
,I/libpersona( 7717): KNOX_SDCARD checking this for 1000
I/libpersona( 7717): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7717 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7717): TimaSignature is unavailable
,D/ActivityThread( 7717): Added TimaKeyStore provider
,D/ResourcesManager( 7717): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  885): failed to open /acct/uid_10098/pid_6873/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7717): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7717): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7717): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/wpa_supplicant( 1268): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 1268): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1268): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1268): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  885): [1,454,429,668,715 ms] noteScanEnd no scan source
,I/DIAGMON_AGENT( 7717): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7717): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7717): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@31f56e18 sup_state=SCANNING debouncing=false
,I/CLocInfoService(  885): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  885): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  885): setDetailed state send new extra info0x
,D/SecContentProvider2(  885): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  885): mCursor = null
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7345): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7345): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7370): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7370): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454429668816
,I/KLMS-2.4.503: ( 7370): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7370): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7370): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  885): Killing 6921:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/SO_AGENT( 7390): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7736): MountEmulatedStorage()
I/libpersona( 7736): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7736): v2
I/libpersona( 7736): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7736 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/wpa_supplicant( 1268): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/wpa_supplicant( 1268): Associated with C0.AA.48
,I/SELinux ( 7736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7736): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2(  885): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  885): mCursor = null
,I/wpa_supplicant( 1268): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
D/SecContentProvider2(  885): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  885): mCursor = null
,D/TimaKeyStoreProvider( 7736): TimaSignature is unavailable
,D/ActivityThread( 7736): Added TimaKeyStore provider
,D/ResourcesManager( 7736): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,W/libprocessgroup(  885): failed to open /acct/uid_10033/pid_6921/cgroup.procs: No such file or directory
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1268): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1268): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,I/wpa_supplicant( 1268): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1268): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1268): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1268): Blacklist: Clear (temp) 
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  885): Network connection established
,E/Zygote  ( 7756): MountEmulatedStorage()
E/Zygote  ( 7756): v2
I/libpersona( 7756): KNOX_SDCARD checking this for 10038
I/libpersona( 7756): KNOX_SDCARD not a persona
,D/WifiNative-HAL(  885): callSECApiVoid - ID [50]
,E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/ActivityManager(  885): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7756 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6901:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,E/WifiStateMachine(  885): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  885): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  885): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  885): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  885): Got NetworkAgent Messenger
D/ConnectivityService(  885): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService(  885): updateNetworkInfo()
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  885): NetworkAgent connected
E/WifiStateMachine(  885): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  885): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  885): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  281): Setting iface cfg
E/WifiStateMachine(  885): Start Dhcp Watchdog 2
,D/SecContentProvider2(  885): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  885): mCursor = null
,I/SELinux ( 7756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1166): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1166): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/SELinux ( 7756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7756): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  885): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/TimaKeyStoreProvider( 7756): TimaSignature is unavailable
,D/ActivityThread( 7756): Added TimaKeyStore provider
,D/ResourcesManager( 7756): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,V/AlarmManager(  885): waitForAlarm result :4
,W/libprocessgroup(  885): failed to open /acct/uid_10099/pid_6901/cgroup.procs: No such file or directory
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7756): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7756): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7756): PushLog.txt file is not deleted.
D/SPPClientService( 7756): PushLog.txt file is not deleted.
,D/SPPClientService( 7756): ============PushLog. stop!
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend false
,E/SPPClientService( 7756): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SecContentProvider2(  885): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService(  885): InactiveState{ what=143375 }
D/WifiP2pService(  885): P2pEnabledState{ what=143375 }
,D/SecContentProvider2(  885): mCursor = null
,I/SA      ( 6748): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6748): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6748): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6748): [SLFUCHKMGR] constructor called
,I/SA      ( 6748): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6748): [OR] == isSIMCardReady false ==
,I/SA      ( 6748): [SCU] == networkStateCheck == false
I/SA      ( 6748): [OR] onReceive END
,E/SPPClientService( 7756): [[SystemStateMonitorService]] No Active Internet
,D/accuweather( 7427): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7427): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7781): MountEmulatedStorage()
I/libpersona( 7781): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7781): v2
I/libpersona( 7781): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7781 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  885): Killing 6963:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,E/SELinux ( 7781): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7781): TimaSignature is unavailable
,D/ActivityThread( 7781): Added TimaKeyStore provider
,D/ResourcesManager( 7781): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7781): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7781): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7781): premStatus:2
,I/KnoxUsageLogPro( 7781): isEulaShown : false
,I/KnoxUsageLogPro( 7781): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7796): MountEmulatedStorage()
,E/Zygote  ( 7796): v2
I/libpersona( 7796): KNOX_SDCARD checking this for 10086
I/libpersona( 7796): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7796 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6977:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/SELinux ( 7796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7796): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  885): failed to open /acct/uid_10020/pid_6963/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7796): TimaSignature is unavailable
,D/ActivityThread( 7796): Added TimaKeyStore provider
,D/ResourcesManager( 7796): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7796): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/dhcpcd  ( 7812): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7812): version 5.5.6 starting
,E/dhcpcd  ( 7812): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7812): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7812): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7812): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7812): bssid match
D/PushModule( 7796): [PushClientApplication] (main) PushClientApplication.onCreate()
I/PushModule( 7796): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7796): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,I/dhcpcd  ( 7812): wlan0: rebinding lease of 192.168.1.135
,W/libprocessgroup(  885): failed to open /acct/uid_10003/pid_6977/cgroup.procs: No such file or directory
,D/ChatON  ( 7796): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7796): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  885): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7796): [1][a] ChatONV isn't installed.
D/ChatON  ( 7796): [1][a] ChatONVPlugIn.isAvailable()
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,D/GeoLookout( 7536): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,E/Zygote  ( 7823): MountEmulatedStorage()
E/Zygote  ( 7823): v2
I/libpersona( 7823): KNOX_SDCARD checking this for 10088
I/libpersona( 7823): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7823 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6995:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/SELinux ( 7823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7823): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7823): TimaSignature is unavailable
,D/ActivityThread( 7823): Added TimaKeyStore provider
,D/ResourcesManager( 7823): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  885): failed to open /acct/uid_1000/pid_6995/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 7011:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,D/Headlines( 5573): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5573): getCountryCode(): countryCode = DE
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5573): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5573): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5573): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5573): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5573): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5573): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5573): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7843): MountEmulatedStorage()
I/libpersona( 7843): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7843): v2
I/libpersona( 7843): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7843 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7843): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7843): TimaSignature is unavailable
,D/ActivityThread( 7843): Added TimaKeyStore provider
,D/ResourcesManager( 7843): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  885): failed to open /acct/uid_10112/pid_7011/cgroup.procs: No such file or directory
,I/PowerManagerService(  885): [PWL] Off : 15s ago
,I/PowerManagerService(  885): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  885): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  885): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2405, ws=null) (elapsedTime=51840)
I/PowerManagerService(  885): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=885, ws=null) (elapsedTime=2021)
I/PowerManagerService(  885): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=885, ws=WorkSource{10012}) (elapsedTime=660)
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7843): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7843): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7843): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7843): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7843): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7843): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7843): Loading: webviewchromium
,I/LibraryLoader( 7843): Time to load native libraries: 4 ms (timestamps 306-310)
I/LibraryLoader( 7843): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7843): Binding Chromium to main looper Looper (main, tid 1) {2fa94606}
,I/LibraryLoader( 7843): Expected native library version number "",actual native library version number ""
,I/chromium( 7843): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7843): Initializing chromium process, renderers=0
,W/art     ( 7843): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7843): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7843): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7843): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7843): Requires BLUETOOTH permission
,I/Adreno-EGL( 7843): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7843): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7843): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7843): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7843): Remote Branch: 
I/Adreno-EGL( 7843): Local Patches: 
I/Adreno-EGL( 7843): Reconstruct Branch: 
,I/NSApplication( 7843): Starting up...
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7902): MountEmulatedStorage()
E/Zygote  ( 7902): v2
I/libpersona( 7902): KNOX_SDCARD checking this for 10138
I/libpersona( 7902): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7902 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7028:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,I/SELinux ( 7902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7902): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7902): TimaSignature is unavailable
,D/ActivityThread( 7902): Added TimaKeyStore provider
,D/ResourcesManager( 7902): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/libprocessgroup(  885): failed to open /acct/uid_10118/pid_7028/cgroup.procs: No such file or directory
,W/ResourcesManager( 7902): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7902): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7902): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7902): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7902): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7902): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7920): MountEmulatedStorage()
,E/Zygote  ( 7920): v2
I/libpersona( 7920): KNOX_SDCARD checking this for 10163
I/libpersona( 7920): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7920 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7044:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/SELinux ( 7920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7920): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7920): TimaSignature is unavailable
,D/ActivityThread( 7920): Added TimaKeyStore provider
,D/ResourcesManager( 7920): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7920): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7920): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7920): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7920): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  885): failed to open /acct/uid_1000/pid_7044/cgroup.procs: No such file or directory
,D/RCPManagerService(  885): exchangeData() failure , invalid userId
,D/RCPManagerService(  885): exchangeData() failure , invalid userId
,D/RCPManagerService(  885): exchangeData() failure , invalid userId
,D/RCPManagerService(  885): exchangeData() failure , invalid userId
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7943): MountEmulatedStorage()
I/libpersona( 7943): KNOX_SDCARD checking this for 10078
E/Zygote  ( 7943): v2
I/libpersona( 7943): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7943 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,I/art     (  315): Explicit concurrent mark sweep GC freed 8747(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 306us total 12.526ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 265us total 8.235ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 8.285ms
,I/SELinux ( 7943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7943): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7943): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  885): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7943): TimaSignature is unavailable
,D/ActivityThread( 7943): Added TimaKeyStore provider
,D/RCPManagerService(  885): exchangeData() failure , invalid userId
,I/ActivityManager(  885): Killing 7082:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7568): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7568): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7568): StateMachine : Current State = 1
,D/SecurityLogAgent( 7568): StateMachine : Changed Current State = 1
,I/ActivityManager(  885): Killing 6632:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,D/ResourcesManager( 7943): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/com.peel.receiver.ConnectivityActionReceiver( 3660): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
,D/com.peel.receiver.ConnectivityActionReceiver( 3660): NO active network... no services...
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): last run: 1454412206493 -- System.currentTimeMillis()-last_run: 17464028
D/com.peel.receiver.ConnectivityActionReceiver( 3660): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): ... skip last_72_check
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7812): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,E/Zygote  ( 7964): MountEmulatedStorage()
E/Zygote  ( 7964): v2
I/libpersona( 7964): KNOX_SDCARD checking this for 10178
I/libpersona( 7964): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7964 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/dhcpcd  ( 7812): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  885): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7964): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7943): onCreate
,D/BadgeProvider( 7943): DatabaseHelper
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/TimaKeyStoreProvider( 7964): TimaSignature is unavailable
,D/ActivityThread( 7964): Added TimaKeyStore provider
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/BadgeProvider( 7943): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,D/BadgeProvider( 7943): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7943): sendNotify, [notify] : null
D/BadgeProvider( 7943): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7943): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7943): update, [UpdateCount] : 1
,D/Launcher.Model( 1493): reloadBadges entered.
V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,D/ResourcesManager( 7964): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,I/ActivityManager(  885): Killing 7097:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
W/libprocessgroup(  885): failed to open /acct/uid_10166/pid_7082/cgroup.procs: No such file or directory
V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,W/libprocessgroup(  885): failed to open /acct/uid_10012/pid_6632/cgroup.procs: No such file or directory
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,I/iu.Environment( 2405): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2405): num queued entries: 0
,I/iu.UploadsManager( 2405): num updated entries: 0
,I/iu.SyncManager( 2405): NEXT; no task
,D/ChimeraCfgMgr( 2405): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,I/Hs20UtilService( 1299): Starting #8
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,I/Hs20UtilService( 1299): Message received 5007
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  885): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7920): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,W/libprocessgroup(  885): failed to open /acct/uid_10170/pid_7097/cgroup.procs: No such file or directory
,W/ActivityManager(  885): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ what=143375 }
D/WifiP2pService(  885): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  885): WifiStateMachine DHCP successful
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  885): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  885): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  885): Not connected state, yet.
D/StatusBar.NetworkController( 1166): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  885): VerifyingLinkState enter
,D/WifiStateMachine(  885): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  885): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  885): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  885): callSECApiInt - ID [210]
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  885): updateNetworkInfo()
,D/ConnectivityService(  885): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  885): Adding iface wlan0 to network 503
,I/CLocInfoService(  885): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  885): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  885): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  885): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  885): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  885): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1166): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  885): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  885): Now, connected state.
E/WifiStateMachine(  885): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  885): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,E/WifiStateMachine(  885): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  885): evaluateTrafficStatsPolling
,I/CLocInfoService(  885): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  885): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine(  885): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  885): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  885): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,D/StatusBar.NetworkController( 1166): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  885): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  885): mBoosterFLAG : 0
I/WifiTrafficPoller(  885): current booster mode : FullMode
D/WifiNative-HAL(  885): callSECApiVoid - ID [212]
,I/CLocInfoService(  885): External Intent Received android.net.wifi.STATE_CHANGE
,E/ConnectivityService(  885): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  885): updateSourceRoutes : add source routing for type : 1
I/WifiStateMachine(  885): REQUEST_POWER_SAVE_ON
,D/ConnectivityService(  885): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  281): QcRouteController
,D/StatusBar.NetworkController( 1166): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020492/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020492/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02012a/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
V/BitmapFactory( 1166): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_wifi_signal_3.png
,V/AlarmManager(  885): waitForAlarm result :4
D/StatusBar.NetworkController( 1166): applyOpen
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
I/Hs20UtilService( 1299): Starting #9
I/Hs20UtilService( 1299): Message received 5007
,V/        (  281): QcRouteController
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,V/        (  281): QcRouteController
,I/Hs20UtilService( 1299): Starting #10
,I/Hs20UtilService( 1299): Message received 5007
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
,V/        (  281): QcRouteController
,I/Hs20UtilService( 1299): Starting #11
,I/Hs20UtilService( 1299): Message received 5007
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,V/        (  281): QcRouteController
,I/WifiStateMachine(  885): callSECApi what=220
D/WifiStateMachine(  885): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  281): QcRouteController
,V/        (  281): QcRouteController
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4265, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  885): stay LED for fully charged
D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,V/        (  281): QcRouteController
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/ConnectivityService(  885): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  885): updateNetworkInfo()
D/ConnectivityService(  885): calling update connectivity
E/ConnectivityService(  885): updateNetworkInfo()
D/ConnectivityService(  885): ignoring duplicate network state non-change
D/ConnectivityService(  885): ignoring duplicate network state non-change
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  885): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  885): calling update connectivity
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  885):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Connected
D/ConnectivityService(  885):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  885):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
D/ConnectivityService(  885): currentScore = 0, newScore = 60
D/ConnectivityService(  885):    accepting network in place of null
D/ConnectivityService(  885): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1477): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  885): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/CSLegacyTypeTracker(  885): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PowerManagerService(  885): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=885
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/ConnectivityService(  885): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  885): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  885): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  885): calling update connectivity
D/ConnectivityService(  885):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  885):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/SmartBondingService(  885): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  885): getSBEnabled() enabled =false
D/SmartBondingService(  885): getSBEnabled() enabled =false
D/SmartBondingService(  885): getSBEnabled() enabled =false
D/ConnectivityService(  885): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  885): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  885):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  885):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1166): CM callback handler got msg 524290
D/ConnectivityService(  885): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  885): calling update connectivity
D/ConnectivityService(  885):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  885):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  885): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1166): CM callback handler got msg 524290
D/SmartBondingService(  885): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  885): updateIfacesLocked()
V/NetworkStats(  885): performPollLocked(flags=0x1)
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
V/NetworkStats(  885): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
D/NetworkStatsFactory(  885): UpdateStatsForKnox
D/ConnectivityService(  885): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/NetworkStats(  885): performPollLocked() took 7ms
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
D/NtpTrustedTime(  885): currentTimeMillis() cache hit
D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1166): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1166): updateDataNetType()
D/StatusBar.NetworkController( 1166): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1166): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1166): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1166): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1166): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020492/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020492/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02012a/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
D/StatusBar.NetworkController( 1166): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1166): applyOpen
D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1166): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1166): updateDataNetType()
D/StatusBar.NetworkController( 1166): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1166): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1166): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1166): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1166): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020492/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020492/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02012a/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/SmartBondingService(  885): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  885): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  885): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  885): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  885): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  885): getSBEnabled() enabled =false
,D/SmartBondingService(  885): getSBEnabled() enabled =false
,D/SmartBondingService(  885): getSBEnabled() enabled =false
,D/SmartBondingService(  885): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2148): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/CLocInfoService(  885): CLocinfo wifi true 
D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2198): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
W/ContextImpl( 2198): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7180): [#DCM#] [DCM_Performance] onReceive completed in time  184 microsec. 
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3781): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3781): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/SystemBroadcastReceiver( 7180): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7180): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7180): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7180): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,I/PCWCLIENTTRACE_PushUtil( 7674): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7674): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7674): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7674): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5440): type=WIFI subType= reason=null isConnected=true
,I/FrameworkService( 7180): [#DCM#] onCreate FrameworkService 
I/FrameworkService( 7180): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7180): [#DCM#] getSuccessState = true
I/FrameworkService( 7180): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7180): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  885): mCursor = null
,E/Zygote  ( 8039): MountEmulatedStorage()
I/libpersona( 8039): KNOX_SDCARD checking this for 10082
E/Zygote  ( 8039): v2
I/libpersona( 8039): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=8039 uid=10082 gids={50082, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8039): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SystemUtils( 7180): [#DCM#] LM: false,AM:631398400
,I/DCMThreadPoolExecutor( 7180): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7180): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@23b6bffc is submitted
,I/FrameworkService( 7180): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 74821 mirosec. 
,I/DIAGMON_AGENT( 7717): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7717): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/TimaKeyStoreProvider( 8039): TimaSignature is unavailable
,D/ActivityThread( 8039): Added TimaKeyStore provider
,D/ResourcesManager( 8039): creating new AssetManager and set to /system/app/Books/Books.apk
,V/AlarmManager(  885): waitForAlarm result :4
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7345): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7345): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7345): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7370): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7370): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454429671905
,I/KLMS-2.4.503: ( 7370): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7370): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7370): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7370): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7370): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7390): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/ReaderUtils( 8039): PortraitW 1080 LandscapeW 1920 SmallestSize 1005 LargestSize 1920 textZoom 3.3749998 isTablet false Memory 128
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7756): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6748): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6748): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6748): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6748): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6748): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6748): [SCU] == networkStateCheck == true
,I/SA      ( 6748): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6748): isChinaCountryCode : false
I/SA      ( 6748): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6748): [OR] == networkStateCheck true ==
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6748): [OR] GetMyCountryZoneTask
,I/SA      ( 6748): [OR] onReceive END
,W/GAV2    ( 8039): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6748): [SRS] prepareGetMyCountryZone
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,D/accuweather( 7427): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7427): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/jxcore-log( 7457): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7457): 
,I/KnoxUsageLogPro( 7781): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7781): premStatus:2
,I/SA      ( 6748): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/KnoxUsageLogPro( 7781): isEulaShown : false
I/KnoxUsageLogPro( 7781): KnoxUsageReceiver onReceive : not Processible, just return
I/SA      ( 6748): [SSP] query invoked
,D/ConnectivityService(  885): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Headlines( 5573): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5573): getCountryCode(): countryCode = DE
,I/BooksApp( 8039): Created application version: 3.3.11 (30311)
D/Headlines( 5573): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5573): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5573): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5573): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5573): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5573): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5573): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SA      ( 6748): [TPMU] GetMccFromDB : null
,I/SA      ( 6748): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6748): [TPM] isNoProxy(default) : true
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 6748): fail readDirectory() errno=2
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7902): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7902): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7902): PeriphStartReceiver.onReceive - no need to start
,I/art     (  885): Explicit concurrent mark sweep GC freed 71506(3MB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 36MB/52MB, paused 1.641ms total 104.761ms
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  885): exchangeData() failure , invalid userId
,D/RCPManagerService(  885): exchangeData() failure , invalid userId
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7568): KnoxConfiguration : Current State = 1
D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/SecurityLogAgent( 7568): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7568): StateMachine : Current State = 1
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7568): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 3660): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): last run: 1454412206493 -- System.currentTimeMillis()-last_run: 17465728
D/com.peel.receiver.ConnectivityActionReceiver( 3660): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 3660): ... skip last_72_check
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,I/BooksSync( 8039): Starting books sync, d
,D/ResourcesManager( 2405): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.Environment( 2405): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2405): num queued entries: 0
,I/iu.UploadsManager( 2405): num updated entries: 0
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/iu.SyncManager( 2405): NEXT; no task
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,D/ChimeraCfgMgr( 2405): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 5698): notifyNetworkActivated
,D/ChimeraCfgMgr( 2405): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/hcjo    ( 5698): AutoUpdateManager:IDLE:execute
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5698): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5698): exit::IDLE
D/InitializeManagerStateMachine( 5698): entry::NETWORK_CHECK
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 8084): MountEmulatedStorage()
E/Zygote  ( 8084): v2
I/libpersona( 8084): KNOX_SDCARD checking this for 10179
I/libpersona( 8084): KNOX_SDCARD not a persona
,D/InitializeManagerStateMachine( 5698): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5698): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5698): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5698): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5698): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5698): entry::SUCCESS
D/hcjo    ( 5698): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/ActivityManager(  885): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=8084 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,E/HttpOperation( 3292): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at dsf.a(PG:807)
E/HttpOperation( 3292): 	at fhk.a(PG:1126)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 8 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 10 more
,I/SELinux ( 8084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/hcjo    ( 5698): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5698): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
I/art     ( 1677): Explicit concurrent mark sweep GC freed 20147(1166KB) AllocSpace objects, 3(243KB) LOS objects, 40% free, 17MB/29MB, paused 503us total 37.456ms
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5698): exit::SUCCESS
,D/InitializeManagerStateMachine( 5698): entry::IDLE
,D/TimaKeyStoreProvider( 8084): TimaSignature is unavailable
,D/ActivityThread( 8084): Added TimaKeyStore provider
,D/ResourcesManager( 8084): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,W/ResourcesManager( 8084): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,W/Kids    ( 2405): [AccountUtils] Account not ready
W/Kids    ( 2405): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2405): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2405): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2405): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2405): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2405): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2405): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2405): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2405): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2405): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2405): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2405): 	at java.lang.Thread.run(Thread.java:818)
,D/UMC:Core( 8084): onCreate(): 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SQLiteLog( 8039): (284) automatic index on view_volumes(volume_id)
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/USER_AGENT( 8084): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3292): [getaccountstatus] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at ixd.a(PG:248)
E/HttpOperation( 3292): 	at ixd.b(PG:206)
E/HttpOperation( 3292): 	at ixd.a(PG:175)
E/HttpOperation( 3292): 	at fig.a(PG:78)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,E/EsSyncAdapterService( 3292): Sync failure
E/EsSyncAdapterService( 3292): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 3292): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 3292): 	at fig.a(PG:78)
E/EsSyncAdapterService( 3292): 	at lex.a(PG:85)
E/EsSyncAdapterService( 3292): 	at lex.b(PG:132)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 3292): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 3292): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 3292): 	at kff.u(PG:385)
E/EsSyncAdapterService( 3292): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 3292): 	... 10 more
E/EsSyncAdapterService( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 3292): 	at kft.a(PG:91)
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 3292): 	... 12 more
E/EsSyncAdapterService( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 3292): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 3292): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 3292): 	... 14 more
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/[SAMSUNG SMARCART NATIVE]( 8084): initialize...
D/[SAMSUNG SMARCART NATIVE]( 8084): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CSTORAGE( 8084): ================================================
I/CSTORAGE( 8084):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 8084): ================================================
I/TZ_CCM_C_GetFunctionList: ( 8084): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 8084): FINISHED: initialize rv:0
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,D/GCM     ( 1677): Connected
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/UMC:SecurityUtils( 8084): Loaded server certificates: 0
,D/UMC:SecurityUtils( 8084): Loaded server certificates: 0
D/UMC:SecurityUtils( 8084): timaVersion on the device: 3.0
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/UMC:CloudMDMSecurity( 8084): New Flow
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/TimaService(  885): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  885): TIMA: in getTimaVersion
,I/        (  885): CCM JNI: In ccm_register_for_default_cert
I/        (  885): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  885): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  885): pInitArgs 0x949e9814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  885): &ctx = 0x9fbb6c1c
I/TLC_TZ_CCM: (  885): creating new ccm context...
I/TLC_TZ_CCM: (  885): initializing ccm context...
I/TLC_TZ_CCM: (  885): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  885): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  885): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  885): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  885): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  885): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  885): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  885): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  885): Client_Server_Open was called
I/TZ: client_server_communication(  885): IClientServer::IClientServer()
I/TZ: client_server_communication(  885): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  885): IClientServer::~IClientServer()
,I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1075): OPENSWCONN
I/TZ_CCM_SERVER( 1075): creating new ccm context...
I/TZ_CCM_SERVER( 1075): initializing ccm context...
I/TZ_CCM_SERVER( 1075): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1075): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1075): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1075): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1075): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1075): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1075): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1075): QSEECom_get_handle sb_length = 0x9800
W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QSEECOMAPI: ( 1075): App is not loaded in QSEE
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 8039): null auth token
,D/QSEECOMAPI: ( 1075): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication( 1075): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  885): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  885): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  885): ctx = 0x8c033f10, comm = 0x965c7238, sendmsg = 0x8c156000, recvmsg = 0x8c15ac00
I/TZ_init: (  885): TZ_init: sending initialization request...
I/TZ: client_server_communication(  885): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  885): Calling Communicate()
,I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1075): COMM
,I/System.out( 8039): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 8039): (HTTPLog)-Static: isShipBuild true
I/TZ_init: (  885): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  885): Exercising TZ_DB_INIT in TLC
I/System.out( 8039): (HTTPLog)-Thread-1347-857542622: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/TZ: client_server_communication(  885): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  885): Calling Communicate()
,I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1075): COMM
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/TZ_COMMON: tlc_key_db_util: (  885): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  885): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  885): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  885): Calling Communicate()
I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1075): COMM
,I/TLC_TZ_CCM: register for default cert: (  885): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  885): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  885): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  885): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  885): Calling Communicate()
,I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1075): COMM
,I/TZ: client_server_communication(  885): Client_Server_Close was called
I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1075): CLOSESWCONN
D/QSEECOMAPI: ( 1075): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1075): QSEECom_shutdown_app, app_id = 3
,I/TZ: client_server_communication(  885): Client_Server_Close succeeded
,D/GCM     ( 1677): Message class com.google.f.a.a.p
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/UMC:CloudMDMSecurity( 8084): ccmRegisterForDefaultCertificate: 0
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/UMC:CloudMDMSecurity( 8084): TIMA service call for password change success!!
,D/UMC:AdminManager( 8084): init - start
,D/UMC:AdminManager( 8084): loadAdmins
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,D/UMC:AdminManager( 8084): startPolicyHandlers
,I/UMC:TestPolicyHandler( 8084): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 8084): init - end
,V/UMC:AlarmHandler( 8084): Enter loadList
,I/jxcore-log( 7457): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7457): 
,D/GSLBManager( 8084): migrateStoredUrlFromOldPref
,D/GSLBManager( 8084): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 8084): deactivateUMCAdminIfNotRequired : -1
,E/UMC:Utils( 8084): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 8084): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 8084): isContainer : 0
,W/LicenseLogService(  885): log() failed
,D/EnterpriseDeviceManagerService(  885): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 8084): No active admin owned by uid 10179
,D/UMC:UMCAdmin( 8084): isContainer : 0
,D/UMC:UMCAdmin( 8084): deactivateUMCAdmin - UMC App Admin deactivated
,V/UMC:AlarmHandler( 8084): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
,D/QuickStartReceiver( 8084): Msg Id : 2
,D/QuickStartReceiver( 8084): model : SM-G900F
D/QuickStartReceiver( 8084): id : 100
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 3292): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at dsf.a(PG:807)
E/HttpOperation( 3292): 	at fhk.a(PG:1126)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 8 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 10 more
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,I/jxcore-log( 7457): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7457): 
,I/jxcore-log( 7457): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 7457): 
,I/jxcore-log( 7457): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7457): 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 3292): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at ieo.a(PG:43)
E/HttpOperation( 3292): 	at iep.a(PG:93)
E/HttpOperation( 3292): 	at fhn.a(PG:59)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,E/ExperimentLoader( 3292): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): 	at kfv.a(PG:65)
E/ExperimentLoader( 3292): 	at kff.u(PG:385)
E/ExperimentLoader( 3292): 	at kfb.a(PG:29)
E/ExperimentLoader( 3292): 	at kff.l(PG:132)
E/ExperimentLoader( 3292): 	at ieo.a(PG:43)
E/ExperimentLoader( 3292): 	at iep.a(PG:93)
E/ExperimentLoader( 3292): 	at fhn.a(PG:59)
E/ExperimentLoader( 3292): 	at lex.a(PG:85)
E/ExperimentLoader( 3292): 	at lex.b(PG:132)
E/ExperimentLoader( 3292): 	at fhk.a(PG:1146)
E/ExperimentLoader( 3292): 	at fhk.a(PG:908)
E/ExperimentLoader( 3292): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 3292): 	at ihi.a(PG:22)
E/ExperimentLoader( 3292): 	at kft.a(PG:91)
E/ExperimentLoader( 3292): 	at kfv.a(PG:62)
E/ExperimentLoader( 3292): 	... 12 more
E/ExperimentLoader( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 3292): 	at gde.c(Unknown Source)
E/ExperimentLoader( 3292): 	at gde.b(Unknown Source)
E/ExperimentLoader( 3292): 	at ihi.a(PG:19)
E/ExperimentLoader( 3292): 	... 14 more
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,I/SA      ( 6748): [RC New] Execute method=[GET] start
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,I/SA      ( 6748): [RC New] Security=[true]
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
I/System.out( 6748): Thread-1095(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/System.out( 6748): Thread-1095(ApacheHTTPLog):isShipBuild true
,I/System.out( 6748): Thread-1095(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,E/HttpOperation( 3292): [getaccountstatus] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at ixd.a(PG:248)
E/HttpOperation( 3292): 	at ixd.b(PG:206)
E/HttpOperation( 3292): 	at ixd.a(PG:175)
E/HttpOperation( 3292): 	at fig.a(PG:78)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,E/EsSyncAdapterService( 3292): Sync failure
E/EsSyncAdapterService( 3292): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 3292): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 3292): 	at fig.a(PG:78)
E/EsSyncAdapterService( 3292): 	at lex.a(PG:85)
E/EsSyncAdapterService( 3292): 	at lex.b(PG:132)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 3292): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 3292): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 3292): 	at kff.u(PG:385)
E/EsSyncAdapterService( 3292): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 3292): 	... 10 more
E/EsSyncAdapterService( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 3292): 	at kft.a(PG:91)
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 3292): 	... 12 more
E/EsSyncAdapterService( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 3292): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 3292): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 3292): 	... 14 more
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 30769, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  885): mCursor = null
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=9156600049112855706&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  885): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  885): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  885): identical MTU - not setting
D/ConnectivityService(  885): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  885): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  281): QcRouteController
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  885): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  885): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  885): getSBEnabled() enabled =false
D/SmartBondingService(  885): getSBEnabled() enabled =false
,D/SmartBondingService(  885): getSBEnabled() enabled =false
,V/        (  281): QcRouteController
,W/NetworkManagementService(  885): route cmd failed: 
W/NetworkManagementService(  885): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  885): '
W/NetworkManagementService(  885): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  885): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  885): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  885): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  885): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  885): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  885): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  885): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  885): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  885): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  885): calling update connectivity
D/ConnectivityService(  885):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  885):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  885): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  885): calling update connectivity
D/ConnectivityService(  885):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  885):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  885): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1166): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1166): CM callback handler got msg 524295
,I/dhcpcd  ( 7812): wlan0: sending IPv6 Router Solicitation
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SA      ( 6748): [RC New] [v2liruge] api execute + 1199
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,I/SA      ( 6748): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
I/System.out( 6748): AsyncTask #1 calls detatch()
,I/SA      ( 6748): [ODM] saveOpenData( GEO_IP, PL )
,I/qtaguid ( 8039): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/SA      ( 6748): [OCP] update openData : PL
,I/WifiStateMachine(  885): REQUEST_POWER_SAVE_ON
,I/SA      ( 6748): [TPMU] getNetworkMcc : 
,I/SA      ( 6748): [SCU] saveMccToPreferece Start
,I/SA      ( 6748): [SCU] RegionMCC : 260
I/SA      ( 6748): [SSP] query invoked
,I/SA      ( 6748): [TPMU] GetMccFromDB : null
,I/SA      ( 6748): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6748): [SCU] saveMccToPreferece End
,I/SA      ( 6748): [RC New] executeRequest [v2liruge] end. 1291
I/SA      ( 6748): [RC New] Execute end
I/SA      ( 6748): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6748): [OR] GetMyCountryZoneTask Success
,E/SMD     (  286): DCD ON
,E/WifiStateMachine(  885): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=9156600049112855706&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/9)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/9)
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/PowerManagerService(  885): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 885) eventTime = 94889
,D/PowerManagerService(  885): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=885 (0x0)
D/PowerManagerService(  885): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=885, ws=WorkSource{10059}) (elapsedTime=3468)
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,D/SSRM:m  (  885): SIOP:: AP = 420, PST = 430, CUR = 300
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GAV4    ( 7843): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 8039): null auth token
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
W/ApiaryClient( 8039): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=9156600049112855706&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 8039): Soft error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=9156600049112855706&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 8039): Sync error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=9156600049112855706&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 8039): Finished books sync
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  885): Killing 6104:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63811, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  885): mCursor = null
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  885): failed to open /acct/uid_10114/pid_6104/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7674): mConnectivityHandler : connected
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7674): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7674): ================================================
,I/CSTORAGE( 7674):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7674): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7674): [GetString-S]
E/art     ( 7674): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 7674): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7674): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 7674): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7674): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 7674): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7674): [ensureRegistration] - No Samsung account
,I/GAV2    ( 8039): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  286): DCD ON
,I/dhcpcd  ( 7812): wlan0: sending IPv6 Router Solicitation
,I/jxcore-log( 7457): Test app app.js loaded
I/jxcore-log( 7457): 
,I/chromium( 7457): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7457): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7457): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7457): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7457): 	Bluetooth MAC address: B0:C5:59:3F:75:69, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7457): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7457): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7457): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7457): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7457): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7457): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@276753a0 added. We now have 1 listener(s)
,I/jxcore-log( 7457): BLE advertisement is supported
I/jxcore-log( 7457): 
,E/SMD     (  286): DCD ON
,I/dhcpcd  ( 7812): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7812): wlan0: no IPv6 Routers available
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  885): waitForAlarm result :4
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  885): stay LED for fully charged
,D/PreloadUpdateManagerStateMachine( 5698): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5698): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5698): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/hcjo    ( 5698): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5698): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/PreloadUpdateManagerStateMachine( 5698): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5698): entry::IDLE
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageManager(  885): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  885): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 1493): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  ( 8157): MountEmulatedStorage()
E/Zygote  ( 8157): v2
I/libpersona( 8157): KNOX_SDCARD checking this for 10034
I/libpersona( 8157): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8157 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 1493): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1493): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1493): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SELinux ( 8157): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8157): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8157): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 1493): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1493): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1493): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/RegisteredServicesCache( 1471): empty dynamic service
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 8157): TimaSignature is unavailable
,D/ActivityThread( 8157): Added TimaKeyStore provider
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  885): mCursor = null
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/Finsky  ( 6591): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6591): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6591): [1] 5.onFinished: Scheduling replication attempt 2.
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/FeatureConfig( 8157): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/art     (  885): Explicit concurrent mark sweep GC freed 47938(2MB) AllocSpace objects, 18(873KB) LOS objects, 30% free, 36MB/52MB, paused 8.242ms total 174.769ms
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/SMD     (  286): DCD ON
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  885): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/Watchdog(  885): !@Sync 3
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8157): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8157): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8157): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 8157): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8157): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8157): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8157): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk,
,W/ResourcesManager( 8157): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8157): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8157): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8157): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Killing 7220:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,I/UpdateIcingCorporaServi( 1578): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8191): MountEmulatedStorage()
E/Zygote  ( 8191): v2
I/libpersona( 8191): KNOX_SDCARD checking this for 10075
I/libpersona( 8191): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8191 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8191): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8191): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8191): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  885): failed to open /acct/uid_10044/pid_7220/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8191): TimaSignature is unavailable
,D/ActivityThread( 8191): Added TimaKeyStore provider
,D/ResourcesManager( 8191): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/UpdateIcingCorporaServi( 1578): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
,D/FileShare-Server( 8191): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8207): MountEmulatedStorage()
E/Zygote  ( 8207): v2
I/libpersona( 8207): KNOX_SDCARD checking this for 1000
I/libpersona( 8207): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8207 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 5036:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 8207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8207): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  885): failed to open /acct/uid_10012/pid_5036/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8207): TimaSignature is unavailable
,D/ActivityThread( 8207): Added TimaKeyStore provider
,D/ResourcesManager( 8207): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/ShortcutReceiver( 8207):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  885): Killing 4448:com.android.defcontainer/u0a5 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2405): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8235): MountEmulatedStorage()
,E/Zygote  ( 8235): v2
I/libpersona( 8235): KNOX_SDCARD checking this for 10012
I/libpersona( 8235): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=8235 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 8235): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8235): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8235): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_4448/cgroup.procs: No such file or directory
,I/PeopleContactsSync( 2405): CP2 sync disabled
,D/TimaKeyStoreProvider( 8235): TimaSignature is unavailable
,D/ActivityThread( 8235): Added TimaKeyStore provider
,D/ResourcesManager( 8235): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 8235): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8235): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8235): VM with version 2.1.0 has multidex support
I/MultiDex( 8235): install
,I/MultiDex( 8235): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8235): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 8235): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8235): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c07d4eb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8235): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1677): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/AlarmManager(  885): waitForAlarm result :4
,D/AuthorizationBluetoothService( 1677): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2405): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 8235): callingUid 10012, callindPid: 8235
,D/LocationInitializer( 2405): Restart initialization of location
,I/PowerManagerService(  885): [PWL] Off : 30s ago
I/PowerManagerService(  885): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  885): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  885): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=885, ws=WorkSource{10012}) (elapsedTime=109)
,E/MDM     ( 2211): [242] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/SSRM:m  (  885): SIOP:: AP = 400, PST = 427, CUR = 300
D/X       (  885): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,I/SystemBroadcastReceiver( 7180): [#DCM#] [DCM_Performance] onReceive completed in time  492 microsec. 
,I/SystemBroadcastReceiver( 7180): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7180): [#DCM#] onReceive action = EVENT_SIOP
D/ContentApp( 1216):  LEVEL : -1
,E/Zygote  ( 8264): MountEmulatedStorage()
E/Zygote  ( 8264): v2
I/libpersona( 8264): KNOX_SDCARD checking this for 10054
I/libpersona( 8264): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8264 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8264): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8264): TimaSignature is unavailable
,D/ActivityThread( 8264): Added TimaKeyStore provider
,D/ResourcesManager( 8264): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8264): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8264): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8264): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8264): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8264): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8264): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8264): core_num = 4
,W/linker  ( 8264): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8264): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8264): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 8264): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8264):  SIOP_LEVEL: -1
,I/ActivityManager(  885): Killing 6769:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/CountryDetector(  885): No listener is left
,W/libprocessgroup(  885): failed to open /acct/uid_10050/pid_6769/cgroup.procs: No such file or directory
,E/SMD     (  286): DCD ON
,I/ActivityManager(  885): Waited long enough for: ServiceRecord{21569f09 u0 com.samsung.dcm/.framework.FrameworkService}
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,I/ActivityManager(  885): Killing 7406:com.samsung.android.scloud.sync/u0a67 (adj 15): bgCount ##41
,W/libprocessgroup(  885): failed to open /acct/uid_10067/pid_7406/cgroup.procs: No such file or directory
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/FactoryTest( 6439): Not factory mode
,D/FactoryTest( 6439): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6439): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6439): still no open session command from host, so toast
,W/ContextImpl( 6439): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6439): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6439): Timeline: Activity_launch_request id:com.android.settings time:114121
,E/PersonaManagerService(  885): inState():  stateMachine is null !!
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  885): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,E/MTPRx   ( 6439): started activity for popup
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SQLiteSecureOpenHelper( 3566): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3566): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6439): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6439): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6439): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6439): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6439): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6439): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6439): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6439): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/InputMethodManagerService(  885): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  885): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@286cd2e6 attribute=null, token = android.os.BinderProxy@3b1c3e52
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6439): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6439): dev.kiessupport is : TRUE
,D/Activity( 6439): performCreate Call secproduct feature valuefalse
D/Activity( 6439): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,D/ActivityManager(  885): post active user change for 0
D/KnoxTimeoutHandler(  885): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  885): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,I/Timeline( 7457): Timeline: Activity_idle id: android.os.BinderProxy@37440f1b time:114737
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  885): SIOP:: AP = 350, PST = 419, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ActivityManager(  885): mDVFSHelper.release()
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  885): stay LED for fully charged
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  885): waitForAlarm result :4
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6591): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6591): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6591): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/PowerManagerService(  885): [PWL] Off : 50s ago
,D/SSRM:m  (  885): SIOP:: AP = 330, PST = 406, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 4
,D/SSRM:m  (  885): SIOP:: AP = 320, PST = 390, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  885): waitForAlarm result :4
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): stay LED for fully charged
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6591): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6591): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6591): [1] 5.onFinished: Scheduling replication attempt 4.
,D/SSRM:m  (  885): SIOP:: AP = 320, PST = 374, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  885): [PWL] Off : 75s ago
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  885): waitForAlarm result :4
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 8039): Starting books sync, d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 3292): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at dsf.a(PG:807)
E/HttpOperation( 3292): 	at fhk.a(PG:1126)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 8 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 10 more
W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 8039): null auth token
I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 3292): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at ieo.a(PG:43)
E/HttpOperation( 3292): 	at iep.a(PG:93)
E/HttpOperation( 3292): 	at fhn.a(PG:59)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
E/ExperimentLoader( 3292): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): 	at kfv.a(PG:65)
E/ExperimentLoader( 3292): 	at kff.u(PG:385)
E/ExperimentLoader( 3292): 	at kfb.a(PG:29)
E/ExperimentLoader( 3292): 	at kff.l(PG:132)
E/ExperimentLoader( 3292): 	at ieo.a(PG:43)
E/ExperimentLoader( 3292): 	at iep.a(PG:93)
E/ExperimentLoader( 3292): 	at fhn.a(PG:59)
E/ExperimentLoader( 3292): 	at lex.a(PG:85)
E/ExperimentLoader( 3292): 	at lex.b(PG:132)
E/ExperimentLoader( 3292): 	at fhk.a(PG:1146)
E/ExperimentLoader( 3292): 	at fhk.a(PG:908)
E/ExperimentLoader( 3292): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 3292): 	at ihi.a(PG:22)
E/ExperimentLoader( 3292): 	at kft.a(PG:91)
E/ExperimentLoader( 3292): 	at kfv.a(PG:62)
E/ExperimentLoader( 3292): 	... 12 more
E/ExperimentLoader( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 3292): 	at gde.c(Unknown Source)
E/ExperimentLoader( 3292): 	at gde.b(Unknown Source)
E/ExperimentLoader( 3292): 	at ihi.a(PG:19)
E/ExperimentLoader( 3292): 	... 14 more
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/qtaguid ( 8039): Untagging socket 34
W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
W/ApiaryClient( 8039): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4848001083183244103&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,I/art     ( 1677): Explicit concurrent mark sweep GC freed 39220(2MB) AllocSpace objects, 25(2025KB) LOS objects, 40% free, 17MB/29MB, paused 876us total 79.131ms
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 3292): [getaccountstatus] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at ixd.a(PG:248)
E/HttpOperation( 3292): 	at ixd.b(PG:206)
E/HttpOperation( 3292): 	at ixd.a(PG:175)
E/HttpOperation( 3292): 	at fig.a(PG:78)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/EsSyncAdapterService( 3292): Sync failure
E/EsSyncAdapterService( 3292): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 3292): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 3292): 	at fig.a(PG:78)
E/EsSyncAdapterService( 3292): 	at lex.a(PG:85)
E/EsSyncAdapterService( 3292): 	at lex.b(PG:132)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 3292): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 3292): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 3292): 	at kff.u(PG:385)
E/EsSyncAdapterService( 3292): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 3292): 	... 10 more
E/EsSyncAdapterService( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 3292): 	at kft.a(PG:91)
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 3292): 	... 12 more
E/EsSyncAdapterService( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 3292): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 3292): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 3292): 	... 14 more
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 125665, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  885): mCursor = null
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): stay LED for fully charged
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4848001083183244103&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 310, PST = 362, CUR = 300
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4848001083183244103&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 8039): Soft error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4848001083183244103&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 8039): Sync error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4848001083183244103&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 8039): Finished books sync
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127396, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  885): Explicit concurrent mark sweep GC freed 55021(2MB) AllocSpace objects, 25(790KB) LOS objects, 30% free, 36MB/52MB, paused 1.797ms total 135.487ms
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  885): mCursor = null
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 5
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/SSRM:m  (  885): SIOP:: AP = 310, PST = 353, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :4
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  885): stay LED for fully charged
D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1677): Vacuum at: now=1454429754478 tag=VacuumService
,I/GoogleURLConnFactory( 1677): Using platform SSLCertificateSocketFactory
,W/Uploader( 1677): No account for auth token provided
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1677): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1677): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1677): (HTTPLog)-Thread-198-868648223: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1677): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,I/qtaguid ( 1677): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6591): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6591): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6591): [1] 5.onFinished: Scheduling replication attempt 5.
,D/SSRM:m  (  885): SIOP:: AP = 300, PST = 343, CUR = 300
,E/SMD     (  286): DCD ON
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
,D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,E/Uploader( 1677): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1677): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1677): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1677): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/qtaguid ( 1677): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,W/Uploader( 1677): No account for auth token provided
,I/qtaguid ( 1677): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,W/Uploader( 1677): No account for auth token provided
,I/qtaguid ( 1677): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,W/Uploader( 1677):  no longer exists, so no auth token.
,I/qtaguid ( 1677): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  885): [PWL] Off : 105s ago
,V/AlarmManager(  885): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :4
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  885): SIOP:: AP = 300, PST = 336, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 6
,V/AlarmManager(  885): waitForAlarm result :4
,D/SSRM:m  (  885): SIOP:: AP = 300, PST = 324, CUR = 300
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6591): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6591): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6591): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  885): SIOP:: AP = 300, PST = 314, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  885): [PWL] Off : 140s ago
,D/SSRM:m  (  885): SIOP:: AP = 300, PST = 309, CUR = 300
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :4
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 8039): Starting books sync, d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1734826087871003405&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1734826087871003405&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  286): DCD ON
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1734826087871003405&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 8039): Soft error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1734826087871003405&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 8039): Sync error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1734826087871003405&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 8039): Finished books sync
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 217827, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  885): mCursor = null
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 3292): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at dsf.a(PG:807)
E/HttpOperation( 3292): 	at fhk.a(PG:1126)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 8 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 10 more
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 3292): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at ieo.a(PG:43)
E/HttpOperation( 3292): 	at iep.a(PG:93)
E/HttpOperation( 3292): 	at fhn.a(PG:59)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,E/ExperimentLoader( 3292): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): 	at kfv.a(PG:65)
E/ExperimentLoader( 3292): 	at kff.u(PG:385)
E/ExperimentLoader( 3292): 	at kfb.a(PG:29)
E/ExperimentLoader( 3292): 	at kff.l(PG:132)
E/ExperimentLoader( 3292): 	at ieo.a(PG:43)
E/ExperimentLoader( 3292): 	at iep.a(PG:93)
E/ExperimentLoader( 3292): 	at fhn.a(PG:59)
E/ExperimentLoader( 3292): 	at lex.a(PG:85)
E/ExperimentLoader( 3292): 	at lex.b(PG:132)
E/ExperimentLoader( 3292): 	at fhk.a(PG:1146)
E/ExperimentLoader( 3292): 	at fhk.a(PG:908)
E/ExperimentLoader( 3292): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 3292): 	at ihi.a(PG:22)
E/ExperimentLoader( 3292): 	at kft.a(PG:91)
E/ExperimentLoader( 3292): 	at kfv.a(PG:62)
E/ExperimentLoader( 3292): 	... 12 more
E/ExperimentLoader( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 3292): 	at gde.c(Unknown Source)
E/ExperimentLoader( 3292): 	at gde.b(Unknown Source)
E/ExperimentLoader( 3292): 	at ihi.a(PG:19)
E/ExperimentLoader( 3292): 	... 14 more
I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ProcessCpuTracker(  885): Skipping unknown process pid 8491
,W/ProcessCpuTracker(  885): Skipping unknown process pid 8492
,W/ProcessCpuTracker(  885): Skipping unknown process pid 8496
,W/ProcessCpuTracker(  885): Skipping unknown process pid 8497
W/ProcessCpuTracker(  885): Skipping unknown process pid 8506
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,E/HttpOperation( 3292): [getaccountstatus] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at ixd.a(PG:248)
E/HttpOperation( 3292): 	at ixd.b(PG:206)
E/HttpOperation( 3292): 	at ixd.a(PG:175)
E/HttpOperation( 3292): 	at fig.a(PG:78)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,E/EsSyncAdapterService( 3292): Sync failure
E/EsSyncAdapterService( 3292): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 3292): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 3292): 	at fig.a(PG:78)
E/EsSyncAdapterService( 3292): 	at lex.a(PG:85)
E/EsSyncAdapterService( 3292): 	at lex.b(PG:132)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 3292): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 3292): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 3292): 	at kff.u(PG:385)
E/EsSyncAdapterService( 3292): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 3292): 	... 10 more
E/EsSyncAdapterService( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 3292): 	at kft.a(PG:91)
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 3292): 	... 12 more
E/EsSyncAdapterService( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 3292): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 3292): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 3292): 	... 14 more
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 217933, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  885): mCursor = null
,I/art     (  885): Explicit concurrent mark sweep GC freed 45321(2MB) AllocSpace objects, 30(935KB) LOS objects, 30% free, 36MB/52MB, paused 1.372ms total 91.747ms
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 7
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  885): SIOP:: AP = 300, PST = 306, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  885): stay LED for fully charged
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 303, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 300, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  885): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): stay LED for fully charged
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 8
,I/PowerManagerService(  885): [PWL] Off : 180s ago
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 296, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 9
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 293, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  885): [PWL] Off : 225s ago
,V/AlarmManager(  885): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/TimaService(  885): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  885): TimaServiceHandler.handleMessage what =1
,D/TimaService(  885): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  885): initializing...
,I/TLC_TIMA_PKM_initialize(  885): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  885): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  885): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  885): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  885): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  885): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  885): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  885): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  885): App is not loaded in QSEE
,D/QSEECOMAPI: (  885): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  885): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  885): Trustlet response is completed
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  885): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  885): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  885): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  885): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  885): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  885): stay LED for fully charged
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 8544): MountEmulatedStorage()
,E/Zygote  ( 8544): v2
I/libpersona( 8544): KNOX_SDCARD checking this for 10081
I/libpersona( 8544): KNOX_SDCARD not a persona
,I/ActivityManager(  885): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8544 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8544): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 8544): TimaSignature is unavailable
,D/ActivityThread( 8544): Added TimaKeyStore provider
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 8544): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  885): Killing 7472:com.sec.android.app.clockpackage/u0a91 (adj 15): bgCount ##41
,W/libprocessgroup(  885): failed to open /acct/uid_10091/pid_7472/cgroup.procs: No such file or directory
,E/SMD     (  286): DCD ON
,I/ActivityManager(  885): Killing 7514:com.sec.esdk.elm/u0a104 (adj 15): bgCount ##41
,W/libprocessgroup(  885): failed to open /acct/uid_10104/pid_7514/cgroup.procs: No such file or directory
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 11
,V/AlarmManager(  885): waitForAlarm result :4
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  885): stay LED for fully charged
D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 8039): Starting books sync, d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8068516279599144606&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8068516279599144606&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/art     ( 1677): Explicit concurrent mark sweep GC freed 60961(3MB) AllocSpace objects, 52(3MB) LOS objects, 39% free, 18MB/30MB, paused 989us total 94.465ms
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8068516279599144606&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/BooksSync( 8039): Soft error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8068516279599144606&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 8039): Sync error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8068516279599144606&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 8039): Finished books sync
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 344145, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  885): mCursor = null
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/PowerManagerService(  885): [PWL] Off : 275s ago
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  286): DCD ON
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1677): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6591): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6591): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6591): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6591): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6591): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6591): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6591): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6591): Ignoring header User-Agent because its value was null.
,I/System.out( 6591): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6591): (HTTPLog)-Static: isShipBuild true
,I/System.out( 6591): (HTTPLog)-Thread-1078-214901900: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 12
,V/AlarmManager(  885): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): stay LED for fully charged
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 3292): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at dsf.a(PG:807)
E/HttpOperation( 3292): 	at fhk.a(PG:1126)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 8 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 10 more
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,E/HttpOperation( 3292): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at ieo.a(PG:43)
E/HttpOperation( 3292): 	at iep.a(PG:93)
E/HttpOperation( 3292): 	at fhn.a(PG:59)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,E/ExperimentLoader( 3292): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): 	at kfv.a(PG:65)
E/ExperimentLoader( 3292): 	at kff.u(PG:385)
E/ExperimentLoader( 3292): 	at kfb.a(PG:29)
E/ExperimentLoader( 3292): 	at kff.l(PG:132)
E/ExperimentLoader( 3292): 	at ieo.a(PG:43)
E/ExperimentLoader( 3292): 	at iep.a(PG:93)
E/ExperimentLoader( 3292): 	at fhn.a(PG:59)
E/ExperimentLoader( 3292): 	at lex.a(PG:85)
E/ExperimentLoader( 3292): 	at lex.b(PG:132)
E/ExperimentLoader( 3292): 	at fhk.a(PG:1146)
E/ExperimentLoader( 3292): 	at fhk.a(PG:908)
E/ExperimentLoader( 3292): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 3292): 	at ihi.a(PG:22)
E/ExperimentLoader( 3292): 	at kft.a(PG:91)
E/ExperimentLoader( 3292): 	at kfv.a(PG:62)
E/ExperimentLoader( 3292): 	... 12 more
E/ExperimentLoader( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 3292): 	at gde.c(Unknown Source)
E/ExperimentLoader( 3292): 	at gde.b(Unknown Source)
E/ExperimentLoader( 3292): 	at ihi.a(PG:19)
E/ExperimentLoader( 3292): 	... 14 more
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 3292): [getaccountstatus] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at ixd.a(PG:248)
E/HttpOperation( 3292): 	at ixd.b(PG:206)
E/HttpOperation( 3292): 	at ixd.a(PG:175)
E/HttpOperation( 3292): 	at fig.a(PG:78)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,E/EsSyncAdapterService( 3292): Sync failure
E/EsSyncAdapterService( 3292): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 3292): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 3292): 	at fig.a(PG:78)
E/EsSyncAdapterService( 3292): 	at lex.a(PG:85)
E/EsSyncAdapterService( 3292): 	at lex.b(PG:132)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 3292): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 3292): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 3292): 	at kff.u(PG:385)
E/EsSyncAdapterService( 3292): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 3292): 	... 10 more
E/EsSyncAdapterService( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 3292): 	at kft.a(PG:91)
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 3292): 	... 12 more
E/EsSyncAdapterService( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 3292): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 3292): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 3292): 	... 14 more
D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 352057, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2794): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2794): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  885): mCursor = null
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON,
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 13
,V/AlarmManager(  885): waitForAlarm result :4
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  885): [PWL] Off : 330s ago
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 14
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 15
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,I/PowerManagerService(  885): [PWL] Off : 390s ago
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/bootchecker(  318): bootchecker wake up!!
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 16
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 17
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/PowerManagerService(  885): [PWL] Off : 455s ago
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 18
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/Atfwd_Daemon(  324): Stop the daemon....
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 19
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): stay LED for fully charged
D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 8039): Starting books sync, d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6628369250229910390&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6628369250229910390&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6628369250229910390&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  885): [PWL] Off : 525s ago
,I/PowerManagerService(  885): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  885): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  885): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=885, ws=WorkSource{10082}) (elapsedTime=7026)
,V/AlarmManager(  885): waitForAlarm result :8
,E/BooksSync( 8039): Soft error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6628369250229910390&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 8039): Sync error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6628369250229910390&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 8039): Finished books sync
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 592816, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  885): Explicit concurrent mark sweep GC freed 63700(4MB) AllocSpace objects, 126(2MB) LOS objects, 30% free, 36MB/52MB, paused 2.803ms total 183.217ms
D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  885): mCursor = null
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/TimaService(  885): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  885): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  885): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  885): !@Sync 20
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  885): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  885): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  885): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  885): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  885): stay LED for fully charged
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  885): stay LED for fully charged
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  885): !@Sync 21
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :4
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  885): stay LED for fully charged
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
E/HttpOperation( 3292): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at dsf.a(PG:807)
E/HttpOperation( 3292): 	at fhk.a(PG:1126)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 8 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 10 more
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,E/HttpOperation( 3292): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at ieo.a(PG:43)
E/HttpOperation( 3292): 	at iep.a(PG:93)
E/HttpOperation( 3292): 	at fhn.a(PG:59)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,E/ExperimentLoader( 3292): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): 	at kfv.a(PG:65)
E/ExperimentLoader( 3292): 	at kff.u(PG:385)
E/ExperimentLoader( 3292): 	at kfb.a(PG:29)
E/ExperimentLoader( 3292): 	at kff.l(PG:132)
E/ExperimentLoader( 3292): 	at ieo.a(PG:43)
E/ExperimentLoader( 3292): 	at iep.a(PG:93)
E/ExperimentLoader( 3292): 	at fhn.a(PG:59)
E/ExperimentLoader( 3292): 	at lex.a(PG:85)
E/ExperimentLoader( 3292): 	at lex.b(PG:132)
E/ExperimentLoader( 3292): 	at fhk.a(PG:1146)
E/ExperimentLoader( 3292): 	at fhk.a(PG:908)
E/ExperimentLoader( 3292): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 3292): 	at ihi.a(PG:22)
E/ExperimentLoader( 3292): 	at kft.a(PG:91)
E/ExperimentLoader( 3292): 	at kfv.a(PG:62)
E/ExperimentLoader( 3292): 	... 12 more
E/ExperimentLoader( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 3292): 	at gde.c(Unknown Source)
E/ExperimentLoader( 3292): 	at gde.b(Unknown Source)
E/ExperimentLoader( 3292): 	at ihi.a(PG:19)
E/ExperimentLoader( 3292): 	... 14 more
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 3292): [getaccountstatus] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at ixd.a(PG:248)
E/HttpOperation( 3292): 	at ixd.b(PG:206)
E/HttpOperation( 3292): 	at ixd.a(PG:175)
E/HttpOperation( 3292): 	at fig.a(PG:78)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,E/EsSyncAdapterService( 3292): Sync failure
E/EsSyncAdapterService( 3292): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 3292): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 3292): 	at fig.a(PG:78)
E/EsSyncAdapterService( 3292): 	at lex.a(PG:85)
E/EsSyncAdapterService( 3292): 	at lex.b(PG:132)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 3292): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 3292): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 3292): 	at kff.u(PG:385)
E/EsSyncAdapterService( 3292): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 3292): 	... 10 more
E/EsSyncAdapterService( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 3292): 	at kft.a(PG:91)
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 3292): 	... 12 more
E/EsSyncAdapterService( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 3292): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 3292): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 3292): 	... 14 more
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 633500, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  885): mCursor = null
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 22
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  885): [PWL] Off : 600s ago
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/Watchdog(  885): !@Sync 23
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 24
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  885): [PWL] Off : 680s ago
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 25
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 284, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 26
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 282, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 280, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 27
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  885): [PWL] Off : 765s ago
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,E/SMD     (  286): DCD ON
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 28
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 29
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,D/TimaService(  885): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  885): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  885): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  885): !@Sync 30
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  885): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  885): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  885): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  885): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 290, PST = 272, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 280, PST = 273, CUR = 300
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  885): [PWL] Off : 855s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 31
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 32
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  286): DCD ON
,V/AlarmManager(  885): waitForAlarm result :4
,D/LightsService(  885): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  885): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  885): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/GCM     ( 1677): Message class com.google.f.a.a.i
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  885): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  885): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  885): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  885): unregisterListener ::   
,D/LightsService(  885): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  885): !@Sync 33
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 271, CUR = 300
,V/AlarmManager(  885): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  885): [PWL] Off : 950s ago
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/Watchdog(  885): !@Sync 34
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,E/Watchdog(  885): !@Sync 35
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,V/AlarmManager(  885): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 8039): Starting books sync, d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1837988497819932938&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1837988497819932938&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8039): Authentication error
E/BooksAccountManager( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8039): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 8039): null auth token
,I/qtaguid ( 8039): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 8039, getuid(): 10082
,I/qtaguid ( 8039): Untagging socket 34
,W/ApiaryClient( 8039): Error response from books API: {
W/ApiaryClient( 8039):  "error": {
W/ApiaryClient( 8039):   "errors": [
W/ApiaryClient( 8039):    {
W/ApiaryClient( 8039):     "domain": "global",
W/ApiaryClient( 8039):     "reason": "required",
W/ApiaryClient( 8039):     "message": "Login Required",
W/ApiaryClient( 8039):     "locationType": "header",
W/ApiaryClient( 8039):     "location": "Authorization"
W/ApiaryClient( 8039):    }
W/ApiaryClient( 8039):   ],
W/ApiaryClient( 8039):   "code": 401,
W/ApiaryClient( 8039):   "message": "Login Required"
W/ApiaryClient( 8039):  }
W/ApiaryClient( 8039): }
,W/ApiaryClient( 8039): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1837988497819932938&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8039): Headers suppressed
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  885): !@Sync 36
,E/SMD     (  286): DCD ON
,E/BooksSync( 8039): Soft error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1837988497819932938&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 8039): Sync error
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8039): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1837988497819932938&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8039): Headers suppressed
E/BooksSync( 8039): 
E/BooksSync( 8039): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 8039): Finished books sync
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1089641, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  885): mCursor = null
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,V/AlarmManager(  885): waitForAlarm result :4
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  885): stay LED for fully charged
D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 37
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  885): [PWL] Off : 1050s ago
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,V/AlarmManager(  885): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 38
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,V/AlarmManager(  885): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  885): stay LED for fully charged
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1677): Explicit concurrent mark sweep GC freed 42104(2MB) AllocSpace objects, 31(2MB) LOS objects, 40% free, 18MB/30MB, paused 1.375ms total 64.306ms
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 3292): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at dsf.a(PG:807)
E/HttpOperation( 3292): 	at fhk.a(PG:1126)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 8 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 10 more
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1166): Icon Only
,D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1166): value : false
,D/PanelView( 1166): There is/are notification(s) 
,D/PanelView( 1166): There is/are notification(s) 
,E/HttpOperation( 3292): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at kff.l(PG:132)
E/HttpOperation( 3292): 	at ieo.a(PG:43)
E/HttpOperation( 3292): 	at iep.a(PG:93)
E/HttpOperation( 3292): 	at fhn.a(PG:59)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,E/ExperimentLoader( 3292): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): 	at kfv.a(PG:65)
E/ExperimentLoader( 3292): 	at kff.u(PG:385)
E/ExperimentLoader( 3292): 	at kfb.a(PG:29)
E/ExperimentLoader( 3292): 	at kff.l(PG:132)
E/ExperimentLoader( 3292): 	at ieo.a(PG:43)
E/ExperimentLoader( 3292): 	at iep.a(PG:93)
E/ExperimentLoader( 3292): 	at fhn.a(PG:59)
E/ExperimentLoader( 3292): 	at lex.a(PG:85)
E/ExperimentLoader( 3292): 	at lex.b(PG:132)
E/ExperimentLoader( 3292): 	at fhk.a(PG:1146)
E/ExperimentLoader( 3292): 	at fhk.a(PG:908)
E/ExperimentLoader( 3292): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 3292): 	at ihi.a(PG:22)
E/ExperimentLoader( 3292): 	at kft.a(PG:91)
E/ExperimentLoader( 3292): 	at kfv.a(PG:62)
E/ExperimentLoader( 3292): 	... 12 more
E/ExperimentLoader( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 3292): 	at gde.c(Unknown Source)
E/ExperimentLoader( 3292): 	at gde.b(Unknown Source)
E/ExperimentLoader( 3292): 	at ihi.a(PG:19)
E/ExperimentLoader( 3292): 	... 14 more
E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  885): uri = 14 selection = getSealedState
,D/SecContentProvider2(  885): mCursor = null
,D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 3292): [getaccountstatus] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at kfv.a(PG:65)
E/HttpOperation( 3292): 	at kff.u(PG:385)
E/HttpOperation( 3292): 	at kfb.a(PG:29)
E/HttpOperation( 3292): 	at ixd.a(PG:248)
E/HttpOperation( 3292): 	at ixd.b(PG:206)
E/HttpOperation( 3292): 	at ixd.a(PG:175)
E/HttpOperation( 3292): 	at fig.a(PG:78)
E/HttpOperation( 3292): 	at lex.a(PG:85)
E/HttpOperation( 3292): 	at lex.b(PG:132)
E/HttpOperation( 3292): 	at fhk.a(PG:1146)
E/HttpOperation( 3292): 	at fhk.a(PG:908)
E/HttpOperation( 3292): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3292): 	at ihi.a(PG:22)
E/HttpOperation( 3292): 	at kft.a(PG:91)
E/HttpOperation( 3292): 	at kfv.a(PG:62)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3292): 	at gde.c(Unknown Source)
E/HttpOperation( 3292): 	at gde.b(Unknown Source)
E/HttpOperation( 3292): 	at ihi.a(PG:19)
E/HttpOperation( 3292): 	... 14 more
,D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/EsSyncAdapterService( 3292): Sync failure
E/EsSyncAdapterService( 3292): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 3292): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 3292): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 3292): 	at fig.a(PG:78)
E/EsSyncAdapterService( 3292): 	at lex.a(PG:85)
E/EsSyncAdapterService( 3292): 	at lex.b(PG:132)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 3292): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 3292): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 3292): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 3292): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 3292): 	at kff.u(PG:385)
E/EsSyncAdapterService( 3292): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 3292): 	... 10 more
E/EsSyncAdapterService( 3292): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 3292): 	at kft.a(PG:91)
E/EsSyncAdapterService( 3292): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 3292): 	... 12 more
E/EsSyncAdapterService( 3292): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 3292): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 3292): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 3292): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 3292): 	... 14 more
,I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  885): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1170113, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  885): mCursor = null
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 39
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,V/AlarmManager(  885): waitForAlarm result :8
,V/AlarmManager(  885): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1166): handleTimeUpdate
,D/KeyguardEffectViewController( 1166): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1166): *** don't update sliding image ***
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  885): stay LED for fully charged
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
I/MotionRecognitionService(  885): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1166): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/TimaService(  885): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  885): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  885): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  885): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  885): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  885): Updating Usage Statistics in DB @ 1454430791546
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
,W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
,W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
,W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
,W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
,W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  885): ::getAppControlDB: Exception to create DB
W/System.err(  885): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  885): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  885): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  885): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  885): Done Updating Usage Statistics in DB @ 1454430791771
,E/Watchdog(  885): !@Sync 40
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  885): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  885): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  885): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  885): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 280, PST = 271, CUR = 300
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 271, CUR = 300
,I/PowerManagerService(  885): [PWL] Off : 1155s ago
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 271, CUR = 300
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 41
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 271, CUR = 300
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 271, CUR = 300
,V/AlarmManager(  885): waitForAlarm result :8
,D/BatteryService(  885): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  885): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  885): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  885):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  885): Plugged
,I/MotionRecognitionService(  885): setPowerConnected  = true
,D/BatteryService(  885): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1166): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1166): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1166):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1166): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  885): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  885): !@Sync 42
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  885): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  286): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  286): DCD ON
D/AndroidRuntime( 8872): 
D/AndroidRuntime( 8872): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8872): CheckJNI is OFF
D/AndroidRuntime( 8872): setted country_code = Germany
D/AndroidRuntime( 8872): setted countryiso_code = DE
D/AndroidRuntime( 8872): setted sales_code = DBT
D/AndroidRuntime( 8872): readGMSProperty: start
D/AndroidRuntime( 8872): readGMSProperty: already setted!!
D/AndroidRuntime( 8872): readGMSProperty: end
D/AndroidRuntime( 8872): addProductProperty: start
E/AffinityControl( 8872): AffinityControl: registerfunction enter
D/AndroidRuntime( 8872): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  885): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  885): START PACKAGE DELETE: observer{911601983}
D/PackageManager(  885): pkg{<packageName>}
D/PackageManager(  885): user{0}
D/PackageManager(  885): caller{2000}
D/PackageManager(  885): flags{3}
D/PersonaManagerService(  885): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  885): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  885): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  885): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  885): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  885): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  885): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  885): getApplicationUninstallationEnabled
D/ApplicationPolicy(  885): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  885): !@killApplicatoin: 10200, uninstall pkg
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
I/ActivityManager(  885): Killing 7457:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
I/ActivityManager(  885):   Force finishing activity ActivityRecord{1ec1b3ec u0 com.test.thalitest/.MainActivity t18}
W/ActivityManager(  885): mDVFSHelper.acquire()
I/WindowState(  885): WIN DEATH: Window{b6fb523 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  885): Client connection lost with reason: 4
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1166): value : false
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
I/ActivityManager(  885):   Force finishing activity ActivityRecord{1ec1b3ec u0 com.test.thalitest/.MainActivity t18 f}
W/ActivityManager(  885): Duplicate finish request for ActivityRecord{1ec1b3ec u0 com.test.thalitest/.MainActivity t18 f}
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
I/art     ( 4688): Explicit concurrent mark sweep GC freed 5010(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 320us total 16.925ms
D/FocusedStackFrame(  885): Set to : 0
I/DBG_DM  ( 3781): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 79
I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3781): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 79
I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/DBG_DM  ( 3781): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
W/GeofencerStateMachine( 2211): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1849): mOCRHelper is null
I/art     ( 1578): Explicit concurrent mark sweep GC freed 55410(3MB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 671us total 89.049ms
D/ConnectivityService(  885): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/SecContentProvider2(  885): uri = 14 selection = getSealedState
D/SecContentProvider2(  885): mCursor = null
I/KLMS-2.4.503: ( 7370): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/SecContentProvider2(  885): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  885): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  885): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 79
I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/KLMS-2.4.503: ( 7370): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1454430875486
I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3781): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3781): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3781): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  885): post active user change for 0
D/KnoxTimeoutHandler(  885): postActiveUserChange for user 0
I/DBG_DM  ( 3781): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
I/KLMS-2.4.503: ( 7370): MainReciver(): PACKAGE_REMOVED
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
I/KLMS-2.4.503: ( 7370): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
I/art     (  885): Explicit concurrent mark sweep GC freed 97519(8MB) AllocSpace objects, 230(4MB) LOS objects, 30% free, 36MB/52MB, paused 1.516ms total 189.085ms
I/art     (  885): WaitForGcToComplete blocked for 18.550ms for cause Explicit
D/ResourcesManager(  885): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/RegisteredServicesCache( 1471): empty dynamic service
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
I/art     (  885): Explicit concurrent mark sweep GC freed 7739(358KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 1.732ms total 135.251ms
D/SecContentProvider2(  885): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  885): mCursor = null
I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
I/art     (  885): WaitForGcToComplete blocked for 226.891ms for cause Explicit
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/Zygote  ( 8903): MountEmulatedStorage()
E/Zygote  ( 8903): v2
I/libpersona( 8903): KNOX_SDCARD checking this for 10104
I/libpersona( 8903): KNOX_SDCARD not a persona
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/ActivityManager(  885): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8903 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
I/SELinux ( 8903): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/StatusBarManagerService(  885): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
I/SELinux ( 8903): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
E/SELinux ( 8903): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1166): value : false
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/SurfaceWidgetView( 1493): destroyHardwareResources():56751872
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
V/WindowOrientationListener(  885): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  885): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  885): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  885): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  885): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/TimaKeyStoreProvider( 8903): TimaSignature is unavailable
D/ActivityThread( 8903): Added TimaKeyStore provider
D/Launcher( 1493): onRestart, Launcher: 432205266
D/Launcher( 1493): onStart, Launcher: 432205266
D/Launcher.HomeView( 1493): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2148): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2148): [237392/6] SurfaceWidget drawing first frame
D/Launcher.HomeView( 1493): onStop
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/ResourcesManager(  885): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  885): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/StatusBarManagerService(  885): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/RCPManagerService(  885): PackageReceiver onReceive()
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
I/HarmonyEASService(  885): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/KnoxMUMContainerPolicy(  885): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  885): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  885): uID is 10200
V/EnterpriseBillingPolicy(  885): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  885): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  885): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  885): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  885): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  885): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  885): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  885): removeObsoleteFile: deleting file=18_task.xml
D/TaskPersister(  885): removeObsoleteFile: deleting file=17_task.xml
D/KnoxTimeoutHandler(  885): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/ResourcesManager( 8903): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
I/SurfaceFlinger(  249): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (6/9)
I/SurfaceFlinger(  249): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
I/Timeline( 3781): Timeline: Activity_idle id: android.os.BinderProxy@3ad2c35f time:1296151
D/elm:14451( 8903): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/elm:14451( 8903): ELMEngine.ELMEngine( context ).
D/elm:14451( 8903): MDMBridge.setEnterpriseBridge()
D/StatusBar( 1166): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/elm:14451( 8903): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
I/PhoneStatusBar( 1166): Icon Only
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PanelView( 1166): There is/are notification(s) 
D/PanelView( 1166): There is/are notification(s) 
D/elm:14451( 8903): ElmAgentService : onCreate()
D/elm:14451( 8903): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8903): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8903): MDMBridge.getInstance()
D/elm:14451( 8903): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14451( 8903): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8923): MountEmulatedStorage()
E/Zygote  ( 8923): v2
I/libpersona( 8923): KNOX_SDCARD checking this for 10017
I/libpersona( 8923): KNOX_SDCARD not a persona
I/ActivityManager(  885): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8923 uid=10017 gids={50017, 9997} abi=armeabi-v7a
D/InputMethodManagerService(  885): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/talkback/talkback.apk
W/ContextImpl(  885): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/art     (  315): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 339us total 12.592ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.124ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 7.999ms
I/art     (  885): Explicit concurrent mark sweep GC freed 11677(710KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 36MB/52MB, paused 1.655ms total 209.302ms
I/SELinux ( 8923): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8923): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8923): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/InputMethodManagerService(  885): Got RemoteException sending setActive(false) notification to pid 7457 uid 10200
D/elm:14451( 8903): ElmAgentService : onDestroy().
I/ActivityManager(  885): Killing 7536:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
D/EnterpriseDeviceManagerService(  885): Package has changed for user 0
D/EnterpriseDeviceManagerService(  885): Admin package name: com.google.android.gms
D/TimaKeyStoreProvider( 8923): TimaSignature is unavailable
D/ActivityThread( 8923): Added TimaKeyStore provider
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/ResourcesManager( 8923): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Books/Books.apk
D/PackageManager(  885): delete codoeFile: 
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/PackageManager(  885): result of delete: 1{911601983}
W/ActivityManager(  885): mDVFSHelper.release()
I/Timeline(  885): Timeline: Activity_windows_visible id: ActivityRecord{28004429 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:1296287
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8923): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8923): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8923): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/AndroidRuntime( 8872): Shutting down VM
I/PCWCLIENTTRACE_PushUtil( 7674): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7674): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7674): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7674): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/libprocessgroup(  885): failed to open /acct/uid_10113/pid_7536/cgroup.procs: No such file or directory
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/LockPatternUtilsCache( 1166): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1166): value : false
W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  885): checkUser: useridlist=null, currentuser=0
W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/Zygote  ( 8942): MountEmulatedStorage()
E/Zygote  ( 8942): v2
I/libpersona( 8942): KNOX_SDCARD checking this for 10038
I/libpersona( 8942): KNOX_SDCARD not a persona
I/ActivityManager(  885): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8942 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  885): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  885): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  885): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
I/SELinux ( 8942): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8942): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  885): Killing 7122:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##41
E/SELinux ( 8942): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL

```
