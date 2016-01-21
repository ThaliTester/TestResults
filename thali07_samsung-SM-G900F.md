#### Test 56672827039a409_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
E/BooksSync( 7411): Soft error
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6506747318997500760&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7411): Headers suppressed
E/BooksSync( 7411): 
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7411): Sync error
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6506747318997500760&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7411): Headers suppressed
E/BooksSync( 7411): 
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7411): Finished books sync
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  806): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64531, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  806): Killing 6777:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  806): failed to open /acct/uid_10015/pid_6777/cgroup.procs: No such file or directory
D/SecContentProvider2(  806): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  806): mCursor = null
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
D/PowerManagerService(  806): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1170 (0x0)
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7453): 
D/AndroidRuntime( 7453): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7453): CheckJNI is OFF
D/AndroidRuntime( 7453): setted country_code = Germany
D/AndroidRuntime( 7453): setted countryiso_code = DE
D/AndroidRuntime( 7453): setted sales_code = DBT
D/AndroidRuntime( 7453): readGMSProperty: start
D/AndroidRuntime( 7453): readGMSProperty: already setted!!
D/AndroidRuntime( 7453): readGMSProperty: end
D/AndroidRuntime( 7453): addProductProperty: start
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
W/ProcessCpuTracker(  806): Skipping unknown process pid 7457
W/ProcessCpuTracker(  806): Skipping unknown process pid 7460
W/ProcessCpuTracker(  806): Skipping unknown process pid 7461
W/ProcessCpuTracker(  806): Skipping unknown process pid 7463
W/ProcessCpuTracker(  806): Skipping unknown process pid 7464
W/ProcessCpuTracker(  806): Skipping unknown process pid 7465
W/ProcessCpuTracker(  806): Skipping unknown process pid 7468
W/ProcessCpuTracker(  806): Skipping unknown process pid 7469
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
I/GAV2    ( 7411): Thread[GAThread,5,main]: No campaign data found.
E/AffinityControl( 7453): AffinityControl: registerfunction enter
D/AndroidRuntime( 7453): Calling main entry com.android.commands.am.Am
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
E/PersonaManagerService(  806): inState():  stateMachine is null !!
V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  806): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  806): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  806): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 806  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  806): mDVFSHelper.acquire()
D/FocusedStackFrame(  806): Set to : 0
D/Launcher.HomeView( 1481): onPause
D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7453): Shutting down VM
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/TaskCloserActivity( 7259): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/Zygote  ( 7493): MountEmulatedStorage()
E/Zygote  ( 7493): v2
I/libpersona( 7493): KNOX_SDCARD checking this for 10200
I/libpersona( 7493): KNOX_SDCARD not a persona
I/ActivityManager(  806): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7493 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7493): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 7493): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7493): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/StatusBarManagerService(  806): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/MicrophoneInputStream( 1582): mic_close gfk@1b1f7a1b
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/AudioPolicyManager(  288): stopInput() input 29
V/AudioPolicyManager(  288): releaseInput() 29
V/AudioPolicyManager(  288): closeInput(29)
V/audio_hw_primary(  288): in_standby: enter
I/HotwordRecognitionRnr( 1582): Hotword detection finished
I/HotwordRecognitionRnr( 1582): Stopping hotword detection.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 7493): TimaSignature is unavailable
D/ActivityThread( 7493): Added TimaKeyStore provider
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
V/WindowOrientationListener(  806): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  806): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  806): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  806): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  806): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  806): Display changed displayId=0
D/Launcher.HomeView( 1481): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2068): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2068): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2068): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2068): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SurfaceWidgetView( 1481): destroyHardwareResources():211615327
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2068): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/audio_hw_primary(  288): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  288): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  288): disable_audio_route: reset mixer path: audio-record
D/audio_route(  288): ++++ audio_route_update_mixer ==============
D/audio_route(  288): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  288): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/audio_route(  288): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  288): disable_audio_route: exit
V/audio_hw_primary(  288): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  288): ++++ audio_route_update_mixer ==============
D/audio_route(  288): Setting mixer control: DEC2 Volume
D/audio_route(  288): Setting mixer control: value: 0
D/StatusBarManagerService(  806): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/audio_route(  288): Setting mixer control: SLIM TX7 MUX, value: 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/audio_route(  288): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  288): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/audio_route(  288): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  288): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  288): stop_input_stream: exit: status(0)
V/audio_hw_primary(  288): in_standby: exit:  status(0)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/audio_hw_primary(  288): adev_close_input_stream
V/audio_hw_primary(  288): in_standby: enter
V/audio_hw_primary(  288): in_standby: exit:  status(0)
E/audio_hw_primary(  288): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  288): releaseInput() exit
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/accuweather( 2068): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/accuweather( 2068): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/Launcher( 1481): onTrimMemory. Level: 20
D/ResourcesManager( 7493): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SurfaceWidgetView( 1481): destroyHardwareResources():211615327
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SSRM:m  (  806): SIOP:: AP = 370, PST = 438, CUR = 300
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
I/WebViewFactory( 7493): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7493): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/LibraryLoader( 7493): Loading: webviewchromium
I/LibraryLoader( 7493): Time to load native libraries: 2 ms (timestamps 7376-7378)
I/LibraryLoader( 7493): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7493): Binding Chromium to main looper Looper (main, tid 1) {248965ee}
I/LibraryLoader( 7493): Expected native library version number "",actual native library version number ""
I/chromium( 7493): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/BrowserStartupController( 7493): Initializing chromium process, renderers=0
W/art     ( 7493): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7493): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7493): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7493): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/Adreno-EGL( 7493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7493): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7493): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7493): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7493): Remote Branch: 
I/Adreno-EGL( 7493): Local Patches: 
I/Adreno-EGL( 7493): Reconstruct Branch: 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/SMD     (  283): DCD ON
V/AlarmManager(  806): waitForAlarm result :4
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/Zygote  ( 7524): MountEmulatedStorage()
E/Zygote  ( 7524): v2
I/libpersona( 7524): KNOX_SDCARD checking this for 10179
I/libpersona( 7524): KNOX_SDCARD not a persona
I/ActivityManager(  806): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7524 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 7524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7524): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7524): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/chromium( 7493): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7493): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 7524): TimaSignature is unavailable
W/art     ( 7493): Attempt to remove local handle scope entry from IRT, ignoring
D/ActivityThread( 7524): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/AwContents( 7493): onDetachedFromWindow called when already detached. Ignoring
D/ResourcesManager( 7524): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ResourcesManager( 7524): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/SystemWebViewEngine( 7493): CordovaWebView is running on device made by: samsung
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/art     ( 7493): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7493): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/UMC:Core( 7524): onCreate(): 
D/Activity( 7493): performCreate Call secproduct feature valuefalse
D/Activity( 7493): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/OpenGLRenderer( 7493): Render dirty regions requested: true
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ActivityManager(  806): post active user change for 0
D/KnoxTimeoutHandler(  806): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  806): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/USER_AGENT( 7524): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/8)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/OpenGLRenderer( 7493): Initialized EGL, version 1.4
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
I/OpenGLRenderer( 7493): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7493): Enabling debug mode 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/[SAMSUNG SMARCART NATIVE]( 7524): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7524): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/CSTORAGE( 7524): ================================================
I/CSTORAGE( 7524):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7524): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7524): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7524): FINISHED: initialize rv:0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/InputMethodManagerService(  806): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  806): Displayed com.test.thalitest/.MainActivity: +693ms
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/UMC:SecurityUtils( 7524): Loaded server certificates: 0
D/UMC:SecurityUtils( 7524): Loaded server certificates: 0
D/UMC:SecurityUtils( 7524): timaVersion on the device: 3.0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/UMC:CloudMDMSecurity( 7524): New Flow
D/TimaService(  806): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  806): TIMA: in getTimaVersion
I/        (  806): CCM JNI: In ccm_register_for_default_cert
I/        (  806): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  806): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  806): pInitArgs 0x93661814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  806): &ctx = 0x9fc66c1c
I/TLC_TZ_CCM: (  806): creating new ccm context...
I/TLC_TZ_CCM: (  806): initializing ccm context...
I/TLC_TZ_CCM: (  806): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  806): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  806): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  806): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  806): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  806): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  806): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  806): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  806): Client_Server_Open was called
I/TZ: client_server_communication(  806): IClientServer::IClientServer()
I/TZ: client_server_communication(  806): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  806): IClientServer::~IClientServer()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1078): OPENSWCONN
I/TZ_CCM_SERVER( 1078): creating new ccm context...
I/TZ_CCM_SERVER( 1078): initializing ccm context...
I/TZ_CCM_SERVER( 1078): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1078): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1078): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1078): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1078): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1078): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1078): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1078): QSEECom_get_handle sb_length = 0x9800
D/QSEECOMAPI: ( 1078): App is not loaded in QSEE
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/QSEECOMAPI: ( 1078): Loaded image: APP id = 2
I/TZ: qc_tlc_communication( 1078): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
I/TZ: client_server_communication(  806): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  806): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  806): ctx = 0x92ce1af0, comm = 0x6de78a30, sendmsg = 0x92c77000, recvmsg = 0x92c7bc00
I/TZ_init: (  806): TZ_init: sending initialization request...
I/TZ: client_server_communication(  806): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  806): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
I/TZ_init: (  806): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  806): Exercising TZ_DB_INIT in TLC
I/TZ: client_server_communication(  806): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  806): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/TZ_COMMON: tlc_key_db_util: (  806): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  806): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  806): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  806): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
I/TLC_TZ_CCM: register for default cert: (  806): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  806): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  806): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  806): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  806): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
I/TZ: client_server_communication(  806): Client_Server_Close was called
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1078): CLOSESWCONN
D/QSEECOMAPI: ( 1078): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1078): QSEECom_shutdown_app, app_id = 2
I/TZ: client_server_communication(  806): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7524): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7524): TIMA service call for password change success!!
D/UMC:AdminManager( 7524): init - start
D/UMC:AdminManager( 7524): loadAdmins
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
D/UMC:AdminManager( 7524): startPolicyHandlers
I/UMC:TestPolicyHandler( 7524): Setup is called in testpolicyhandler
D/UMC:AdminManager( 7524): init - end
I/art     (  806): Explicit concurrent mark sweep GC freed 45137(2MB) AllocSpace objects, 14(419KB) LOS objects, 30% free, 36MB/52MB, paused 1.540ms total 117.089ms
V/UMC:AlarmHandler( 7524): Enter loadList
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GSLBManager( 7524): migrateStoredUrlFromOldPref
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/GSLBManager( 7524): migrateStoredUrlFromOldPref : Migration Not Needed
D/UMC:UMCAdmin( 7524): deactivateUMCAdminIfNotRequired : -1
E/UMC:Utils( 7524): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7524): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7524): isContainer : 0
W/LicenseLogService(  806): log() failed
D/EnterpriseDeviceManagerService(  806): isManagedProfileUser(): userId = 0
E/UMC:UMCAdmin( 7524): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7524): isContainer : 0
D/UMC:UMCAdmin( 7524): deactivateUMCAdmin - UMC App Admin deactivated
V/UMC:AlarmHandler( 7524): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/QuickStartReceiver( 7524): Msg Id : 2
D/QuickStartReceiver( 7524): model : SM-G900F
D/QuickStartReceiver( 7524): id : 100
I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Timeline( 7493): Timeline: Activity_idle id: android.os.BinderProxy@1f5cecd9 time:97955
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/Finsky  ( 6685): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6685): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6685): [1] 5.onFinished: Scheduling replication attempt 2.
D/CustomFrequencyManagerService(  806): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 806  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  806): mDVFSHelper.release()
I/Timeline(  806): Timeline: Activity_windows_visible id: ActivityRecord{3fef13c u0 com.test.thalitest/.MainActivity t17} time:97978
D/CustomFrequencyManagerService(  806): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 806  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ActivityManager(  806): Killing 6796:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (6/8)
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/Adreno-ES20( 7493): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7493): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/libprocessgroup(  806): failed to open /acct/uid_10016/pid_6796/cgroup.procs: No such file or directory
D/JsMessageQueue( 7493): Set native->JS mode to OnlineEventsBridgeMode
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/jxcore_app_log( 7493): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359592320
,I/chromium( 7493): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7493): 
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/chromium( 7493): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/CustomFrequencyManagerService(  806): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 806  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,V/AlarmManager(  806): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7493): Initializing JXcore engine
,W/jxcore-log( 7493): JXcore engine is ready
,E/auditd  ( 2096): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  806): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  806): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7570): MountEmulatedStorage()
E/Zygote  ( 7570): v2
I/libpersona( 7570): KNOX_SDCARD checking this for 1000
I/libpersona( 7570): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7570 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 7493): Starting JXcore engine
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/SELinux ( 7570): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7570): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7570): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7570): TimaSignature is unavailable
,D/ActivityThread( 7570): Added TimaKeyStore provider
,D/ResourcesManager( 7570): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7570):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7570):  SeDenialReceiver : File path = null
I/ActivityManager(  806): Killing 6812:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,W/jxcore-log( 7493): Platform android
W/jxcore-log( 7493): 
W/jxcore-log( 7493): Process ARCH arm
W/jxcore-log( 7493): 
,W/libprocessgroup(  806): failed to open /acct/uid_1000/pid_6812/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  806): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
D/PowerManagerService(  806): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  806): lcd : 6 +
,D/lights  (  806): lcd : 6 -
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
D/lights  (  806): lcd : 1 +
,D/lights  (  806): lcd : 1 -
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/jxcore-log( 7493): JXcore Cordova bridge is ready!
I/jxcore-log( 7493): 
,W/jxcore-log( 7493): JXcore engine is started
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/SMD     (  283): DCD ON
,I/jxcore-log( 7493): Toggling radios to true
I/jxcore-log( 7493): 
,D/BluetoothAdapter( 7493): enable()
,D/BluetoothAdapter( 7493): enable(): BT is already enabled..!
,D/WifiService(  806): New client listening to asynchronous messages
,I/WifiManager( 7493): packageName : com.test.thalitest
,D/SecContentProvider(  806): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  806): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  806): mCursor = null
,D/WifiService(  806): setWifiEnabled: true pid=7493, uid=10200
E/WifiService(  806): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  806): Permission Denial: getCurrentUser() from pid=7493, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  806): Failed getting userId using ActivityManagerNative
W/WifiService(  806): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7493, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  806): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  806): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  806): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  806): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  806): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  806): name = wifi_on
,I/WifiService(  806): disconnect: pid=7493, uid=10200
,I/jxcore-log( 7493): Radios toggled
I/jxcore-log( 7493): 
I/wpa_supplicant( 1292): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7493): My device name is: samsung-SM-G900F
I/jxcore-log( 7493): 
,I/wpa_supplicant( 1292): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1292): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1292): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  806): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1292): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1292): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1292): Disconnected - do not scan
I/wpa_supplicant( 1292): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  806): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  806): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  806): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  806): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  806): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  806): InactiveState{ what=143375 }
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
D/WifiP2pService(  806): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  274): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1693): Read error: ssl=0xad244600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1693): SSL shutdown failed: ssl=0xad244600: I/O error during system call, Broken pipe
,E/WifiStateMachine(  806): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  806): updateNetworkInfo()
D/ConnectivityService(  806): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  806): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/WifiTrafficPoller(  806): evaluateTrafficStatsPolling
,E/WifiConfigStore(  806): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/CLocInfoService(  806): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  806): Start Disconnecting Watchdog 1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): Forcing reevaluation
,I/wpa_supplicant( 1292): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1292): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1292): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1292): First Scan Start
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): Validated
I/wpa_supplicant( 1292): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  806): ConnectModeState: Network connection lost 
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
E/WifiStateMachine(  806): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
I/Hs20UtilService( 1295): Starting #6
,I/Hs20UtilService( 1295): Message received 5007
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine(  806): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  806): InactiveState{ what=143375 }
,D/WifiP2pService(  806): P2pEnabledState{ what=143375 }
,D/CommandListener(  274): Clearing all IP addresses on wlan0
,D/ConnectivityService(  806): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,E/WifiStateMachine(  806): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  806): calling update connectivity
D/ConnectivityService(  806):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  806):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  806): Not allowed due to - mEnabled false
,D/ConnectivityService(  806): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/Nat464Xlat(  806): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  806): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  806): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  806): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  806): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  806): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1474): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine(  806): updateConfiguredNetworkExpiration - currTime: 1453396501832
D/WifiStateMachine(  806): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine(  806): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  806): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/WifiTrafficPoller(  806): evaluateTrafficStatsPolling
,I/CLocInfoService(  806): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  806): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  806): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  806): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  806): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  806): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  806): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  806): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  806): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
V/NetworkStats(  806): updateIfacesLocked()
V/NetworkStats(  806): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  806): UpdateStatsForKnox
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  806): currentTimeMillis() cache hit
E/ConnectivityService(  806): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/ConnectivityService(  806): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine(  806): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  806): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  806): setDetailed state send new extra info"NG700"
D/SmartBondingService(  806): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  806): currentTimeMillis() cache hit
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
V/NetworkStats(  806): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
,V/NetworkStats(  806): performPollLocked() took 7ms
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
,I/Hs20UtilService( 1295): Starting #7
,I/Hs20UtilService( 1295): Message received 5007
D/SecContentProvider2(  806): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  806): mCursor = null
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
D/SecContentProvider2(  806): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  806): mCursor = null
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  806): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  806): updateDataUsageMap
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  806): MasterInitialState.processMessage what=3
D/SmartBondingService(  806): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  806): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/SmartBondingService(  806): getSBEnabled() enabled =false
,I/CLocInfoService(  806): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  806): CLoinfo wifi false
D/accuweather( 2068): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
W/SLocation(  806): No Active Data Connection
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  806): getNetworkEnabled : wifi : true mobile : true
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7624): MountEmulatedStorage()
I/libpersona( 7624): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7624): v2
I/libpersona( 7624): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7624 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/SELinux ( 7624): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7624): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SELinux ( 7624): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3765): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/TimaKeyStoreProvider( 7624): TimaSignature is unavailable
,D/ActivityThread( 7624): Added TimaKeyStore provider
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3765): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ResourcesManager( 7624): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7624): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7624): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7624): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7624): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7624): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7624): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7624): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7624): noConnectivity : true
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7651): MountEmulatedStorage()
,E/Zygote  ( 7651): v2
I/libpersona( 7651): KNOX_SDCARD checking this for 10126
I/libpersona( 7651): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7651 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  806): Killing 6550:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 7651): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7651): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7651): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7651): TimaSignature is unavailable
,D/ActivityThread( 7651): Added TimaKeyStore provider
,D/ResourcesManager( 7651): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,W/libprocessgroup(  806): failed to open /acct/uid_10034/pid_6550/cgroup.procs: No such file or directory
,I/MusicStore( 7651): Database version: 104
,D/ResourcesManager( 7651): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,W/ResourcesManager( 7651): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7651): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7651): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7651): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7651): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e8317c8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7651): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7651): GMSCore installation verified
,I/ConfigStore( 7651): Config Database version: 1
,I/wpa_supplicant( 1292): nl80211: Received scan results (2 BSSes)
,I/wpa_supplicant( 1292): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1292): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1292): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  806): [1,453,396,502,884 ms] noteScanEnd no scan source
,E/WifiStateMachine(  806): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2587aab9 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  806): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  806): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  806): setDetailed state send new extra info0x
,I/CLocInfoService(  806): External Intent Received android.net.wifi.SCAN_RESULTS
D/SecContentProvider2(  806): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  806): mCursor = null
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7651): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7651): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7651): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  806): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 1292): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1292): Associated with C0.AA.48
,E/WifiStateMachine(  806): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  806): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/WifiDisplayAdapter(  806): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  288): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  806): getStreamVolume 3 index 70
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
I/MediaRouter( 7651): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/SecContentProvider2(  806): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  806): mCursor = null
,I/wpa_supplicant( 1292): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine(  806): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  806): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  806): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  806): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  806): mCursor = null
,I/wpa_supplicant( 1292): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1292): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1292): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1292): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1292): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1292): Blacklist: Clear (temp) 
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/Zygote  ( 7677): MountEmulatedStorage()
E/Zygote  ( 7677): v2
I/libpersona( 7677): KNOX_SDCARD checking this for 10002
I/libpersona( 7677): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7677 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine(  806): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  806): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  806): Network connection established
,D/WifiNative-HAL(  806): callSECApiVoid - ID [50]
E/WifiStateMachine(  806): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  806): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  806): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  806): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  806): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  806): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  806): Got NetworkAgent Messenger
E/ConnectivityService(  806): updateNetworkInfo()
D/ConnectivityService(  806): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  806): NetworkAgent connected
E/WifiStateMachine(  806): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  806): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  806): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  806): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  806): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  806): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  274): Setting iface cfg
,E/WifiStateMachine(  806): Start Dhcp Watchdog 2
,D/SecContentProvider2(  806): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  806): mCursor = null
I/SELinux ( 7677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/SELinux ( 7677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7677): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  806): calculateWifiScore() report new score 60
I/WifiStateMachine(  806): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  806): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,D/WifiDisplayAdapter(  806): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  806): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  806): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  806): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  806): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/TimaKeyStoreProvider( 7677): TimaSignature is unavailable
,D/ActivityThread( 7677): Added TimaKeyStore provider
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7677): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/NetworkMonitor( 7651): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager(  806): Killing 4728:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/ActivityManager(  806): Killing 6828:com.policydm/1000 (adj 15): bgCount ##41
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  806): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  806): do suspend false
,E/Zygote  ( 7697): MountEmulatedStorage()
,E/Zygote  ( 7697): v2
I/libpersona( 7697): KNOX_SDCARD checking this for 1000
I/libpersona( 7697): KNOX_SDCARD not a persona
,D/SecContentProvider2(  806): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  806): mCursor = null
,D/WifiP2pService(  806): InactiveState{ what=143375 }
,D/WifiP2pService(  806): P2pEnabledState{ what=143375 }
I/ActivityManager(  806): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7697 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/SELinux ( 7697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7697): TimaSignature is unavailable
,D/ActivityThread( 7697): Added TimaKeyStore provider
,D/ResourcesManager( 7697): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7697): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7697): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup(  806): failed to open /acct/uid_10035/pid_4728/cgroup.procs: No such file or directory
W/libprocessgroup(  806): failed to open /acct/uid_1000/pid_6828/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7697): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/DIAGMON_AGENT( 7697): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7697): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7697): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/dhcpcd  ( 7712): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7712): version 5.5.6 starting
,E/dhcpcd  ( 7712): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7712): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7712): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7712): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7712): bssid match
,I/dhcpcd  ( 7712): wlan0: rebinding lease of 192.168.1.135
,E/Zygote  ( 7720): MountEmulatedStorage()
,E/Zygote  ( 7720): v2
I/libpersona( 7720): KNOX_SDCARD checking this for 10011
I/libpersona( 7720): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7720 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7720): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7720): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7720): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7720): TimaSignature is unavailable
,D/ActivityThread( 7720): Added TimaKeyStore provider
,I/dhcpcd  ( 7712): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 7720): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  806): Killing 5193:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,I/FOTA_Client( 7720): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7720): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/dhcpcd  ( 7712): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  806): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  806): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  806): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/FOTA_Client( 7720): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7720): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7720): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7738): MountEmulatedStorage()
E/Zygote  ( 7738): v2
I/libpersona( 7738): KNOX_SDCARD checking this for 10019
I/libpersona( 7738): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7738 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  806): Killing 6034:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/art     (  312): Explicit concurrent mark sweep GC freed 8764(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 272us total 18.377ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.185ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 7.722ms
,I/SELinux ( 7738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7738): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  806): failed to open /acct/uid_10038/pid_5193/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7738): TimaSignature is unavailable
D/ActivityThread( 7738): Added TimaKeyStore provider
,D/ResourcesManager( 7738): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,W/libprocessgroup(  806): failed to open /acct/uid_10042/pid_6034/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7738): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7738): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453396503703
,I/KLMS-2.4.503: ( 7738): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7738): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7738): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  806): Killing 6849:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7770): MountEmulatedStorage()
E/Zygote  ( 7770): v2
I/libpersona( 7770): KNOX_SDCARD checking this for 10037
I/libpersona( 7770): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7770 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7770): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7770): TimaSignature is unavailable
,D/ActivityThread( 7770): Added TimaKeyStore provider
,D/ResourcesManager( 7770): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7770): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  806): failed to open /acct/uid_10045/pid_6849/cgroup.procs: No such file or directory
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7786): MountEmulatedStorage()
E/Zygote  ( 7786): v2
I/libpersona( 7786): KNOX_SDCARD checking this for 1000
I/libpersona( 7786): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7786 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  806): Killing 6872:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/SELinux ( 7786): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7786): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7786): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7786): TimaSignature is unavailable
,D/ActivityThread( 7786): Added TimaKeyStore provider
,W/libprocessgroup(  806): failed to open /acct/uid_10051/pid_6872/cgroup.procs: No such file or directory
,D/ResourcesManager( 7786): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/WifiStateMachine(  806): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  806): InactiveState{ what=143375 }
D/WifiP2pService(  806): P2pEnabledState{ what=143375 }
E/WifiStateMachine(  806): WifiStateMachine DHCP successful
,E/WifiStateMachine(  806): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  806): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  806): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  806): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  806): Not connected state, yet.
E/WifiStateMachine(  806): VerifyingLinkState enter
,D/WifiStateMachine(  806): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  806): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  806): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
,D/WifiNative-HAL(  806): callSECApiInt - ID [210]
,E/WifiStateMachine(  806): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  806): updateNetworkInfo()
,D/ConnectivityService(  806): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  806): Adding iface wlan0 to network 503
,I/CLocInfoService(  806): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  806): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  806): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  806): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  806): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  806): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  806): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  806): Now, connected state.
E/WifiStateMachine(  806): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/WifiTrafficPoller(  806): evaluateTrafficStatsPolling
,I/CLocInfoService(  806): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  806): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine(  806): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  806): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  806): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  806): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  806): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  806): updateSourceRoutes : add src route for:192.168.1.135
,I/WifiTrafficPoller(  806): evaluateTrafficStatsPolling
E/WifiStateMachine(  806): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller(  806): mBoosterFLAG : 0
I/WifiTrafficPoller(  806): current booster mode : FullMode
V/        (  274): QcRouteController
,E/WifiStateMachine(  806): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/WifiNative-HAL(  806): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
I/CLocInfoService(  806): External Intent Received android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
V/        (  274): QcRouteController
,I/WifiStateMachine(  806): REQUEST_POWER_SAVE_ON
,E/Zygote  ( 7813): MountEmulatedStorage()
I/libpersona( 7813): KNOX_SDCARD checking this for 10038
E/Zygote  ( 7813): v2
I/libpersona( 7813): KNOX_SDCARD not a persona
,V/        (  274): QcRouteController
,I/ActivityManager(  806): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7813 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  806): Killing 6890:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,V/        (  274): QcRouteController
,I/SELinux ( 7813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7813): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,V/        (  274): QcRouteController
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,V/        (  274): QcRouteController
,V/        (  274): QcRouteController
,V/        (  274): QcRouteController
,D/ConnectivityService(  806): Setting Dns servers for network 503 to [/192.168.1.1]
,W/libprocessgroup(  806): failed to open /acct/uid_10058/pid_6890/cgroup.procs: No such file or directory
,D/Nat464Xlat(  806): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  806): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  806): calling update connectivity
D/ConnectivityService(  806): ignoring duplicate network state non-change
E/ConnectivityService(  806): updateNetworkInfo()
,D/ConnectivityService(  806): ignoring duplicate network state non-change
E/ConnectivityService(  806): updateNetworkInfo()
D/ConnectivityService(  806): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  806): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  806): calling update connectivity
D/ConnectivityService(  806): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  806): Validated
D/ConnectivityService(  806):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  806):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  806):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  806): currentScore = 0, newScore = 60
D/ConnectivityService(  806):    accepting network in place of null
D/ConnectivityService(  806): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TimaKeyStoreProvider( 7813): TimaSignature is unavailable
,D/ActivityThread( 7813): Added TimaKeyStore provider
,E/CSLegacyTypeTracker(  806): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  806): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  806): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1474): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  806): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  806): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  806): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/EntConnectivity(  806): Not allowed due to - mEnabled false
D/ConnectivityService(  806): calling update connectivity
D/ConnectivityService(  806):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  806):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  806): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  806): Validated NetworkAgentInfo [WIFI () - 503]
D/SmartBondingService(  806): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
D/SmartBondingService(  806): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/SmartBondingService(  806): getSBEnabled() enabled =false
,D/NtpTrustedTime(  806): currentTimeMillis() cache hit
V/NetworkStats(  806): updateIfacesLocked()
V/NetworkStats(  806): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  806): UpdateStatsForKnox
D/ConnectivityService(  806): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  806):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  806):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  806): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  806): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  806): calling update connectivity
D/ConnectivityService(  806):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  806):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  806): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  806): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
,V/NetworkStats(  806): performPollLocked() took 3ms
,D/NtpTrustedTime(  806): currentTimeMillis() cache hit
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  806): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  806): currentTimeMillis() cache hit
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
D/NtpTrustedTime(  806): currentTimeMillis() cache hit
V/NetworkStats(  806): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ResourcesManager( 7813): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7813): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7813): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 7813): PushLog.txt file is not deleted.
D/SPPClientService( 7813): PushLog.txt file is not deleted.
D/SPPClientService( 7813): ============PushLog. stop!
E/SPPClientService( 7813): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7840): MountEmulatedStorage()
I/libpersona( 7840): KNOX_SDCARD checking this for 10045
E/Zygote  ( 7840): v2
I/libpersona( 7840): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7840 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  806): Killing 6245:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/SELinux ( 7840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7840): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7813): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 7840): TimaSignature is unavailable
,D/ActivityThread( 7840): Added TimaKeyStore provider
,D/ResourcesManager( 7840): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,W/libprocessgroup(  806): failed to open /acct/uid_1000/pid_6245/cgroup.procs: No such file or directory
,V/AlarmManager(  806): waitForAlarm result :4
,I/SA      ( 7840): [SSP] onCreated
,I/SA      ( 7840): [TPM] There is no property file
,I/SA      ( 7840): [SCU] isHaveSA() - false
,I/SA      ( 7840): [TPM] getModelProperty : null
,I/SA      ( 7840): [TPM] getCSCProperty : null
,I/SA      ( 7840): [DM] init START
,I/SA      ( 7840): [DM] This device is not a Vodafone
,W/ResourceType( 7840): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7840): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7840): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 7840): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7840): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 7840): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
W/ResourceType( 7840): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7840): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7840): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7840): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,W/ResourceType( 7840): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
,W/ResourceType( 7840): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
W/ResourceType( 7840): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 7840): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7840): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 7840): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 7840): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7840): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 7840): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 7840): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 7840): [SCU] isHaveSA() - false
,I/SA      ( 7840): support phone number id : false
I/SA      ( 7840): [DM] init END
,I/SA      ( 7840): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7840): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7840): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7840): [SLFUCHKMGR] constructor called
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4260, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  806): Plugged
,I/MotionRecognitionService(  806): setPowerConnected  = true
,I/SA      ( 7840): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7840): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
I/SA      ( 7840): [SCU] == networkStateCheck == true
,I/SA      ( 7840): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7840): isChinaCountryCode : false
I/SA      ( 7840): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7840): [OR] == networkStateCheck true ==
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,I/SA      ( 7840): [OR] GetMyCountryZoneTask
,I/SA      ( 7840): [OR] onReceive END
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager(  806): Killing 6618:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,I/SA      ( 7840): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7840): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7840): [SSP] query invoked
,I/SA      ( 7840): [TPMU] GetMccFromDB : null
,D/accuweather( 7317): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/SA      ( 7840): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7840): [TPM] isNoProxy(default) : true
,D/accuweather( 7317): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7317): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7317): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7317): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7317): [KK AccuPhone]>>> RM:136 [0:0]  V init 
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7317): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
E/File    ( 7840): fail readDirectory() errno=2
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7317): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7317): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7317): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7864): MountEmulatedStorage()
E/Zygote  ( 7864): v2
I/libpersona( 7864): KNOX_SDCARD checking this for 1000
I/libpersona( 7864): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7864 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/libprocessgroup(  806): failed to open /acct/uid_10086/pid_6618/cgroup.procs: No such file or directory
I/SELinux ( 7864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7864): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7864): TimaSignature is unavailable
,D/ActivityThread( 7864): Added TimaKeyStore provider
,D/ResourcesManager( 7864): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7864): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7864): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7864): premStatus:2
,I/KnoxUsageLogPro( 7864): isEulaShown : false
,I/KnoxUsageLogPro( 7864): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/SMD     (  283): DCD ON
E/Zygote  ( 7880): MountEmulatedStorage()
,E/Zygote  ( 7880): v2
I/libpersona( 7880): KNOX_SDCARD checking this for 10086
I/libpersona( 7880): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7880 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  806): Killing 6912:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/SELinux ( 7880): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7880): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7880): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  806): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  806): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  806): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  806): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  806): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  806): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/Tethering(  806): MasterInitialState.processMessage what=3
I/CLocInfoService(  806): CLocinfo wifi true 
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2068): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SmartBondingService(  806): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2147): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2147): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3765): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3765): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor( 7651): type=WIFI subType= reason=null isConnected=true
,D/TimaKeyStoreProvider( 7880): TimaSignature is unavailable
,D/ActivityThread( 7880): Added TimaKeyStore provider
,W/libprocessgroup(  806): failed to open /acct/uid_10098/pid_6912/cgroup.procs: No such file or directory
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7880): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7880): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  806): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  806): mCursor = null
,E/Watchdog(  806): !@Sync 3
,D/PushModule( 7880): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7880): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7880): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 7880): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7880): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  806): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7880): [1][a] ChatONV isn't installed.
,D/ChatON  ( 7880): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/Zygote  ( 7899): MountEmulatedStorage()
E/Zygote  ( 7899): v2
I/libpersona( 7899): KNOX_SDCARD checking this for 10088
I/libpersona( 7899): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7899 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  806): Killing 6971:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7899): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7899): TimaSignature is unavailable
,D/ActivityThread( 7899): Added TimaKeyStore provider
,W/libprocessgroup(  806): failed to open /acct/uid_10033/pid_6971/cgroup.procs: No such file or directory
,D/ResourcesManager( 7899): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/SA      ( 7840): [RC New] Execute method=[GET] start
,I/ActivityManager(  806): Killing 6949:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/Headlines( 5537): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5537): getCountryCode(): countryCode = DE
,D/Headlines( 5537): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5537): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,D/HeadlinesCardManager( 5537): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5537): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5537): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5537): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5537): requestUpdateNewsWelcomeCard !!! no welcome card
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/Zygote  ( 7915): MountEmulatedStorage()
,E/Zygote  ( 7915): v2
I/libpersona( 7915): KNOX_SDCARD checking this for 10128
I/ActivityManager(  806): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7915 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 7915): KNOX_SDCARD not a persona
,I/SA      ( 7840): [RC New] Security=[true]
,I/System.out( 7840): Thread-1295(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7840): Thread-1295(ApacheHTTPLog):isShipBuild true
,I/SELinux ( 7915): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/System.out( 7840): Thread-1295(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 7915): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7915): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7915): TimaSignature is unavailable
,D/ActivityThread( 7915): Added TimaKeyStore provider
,D/ResourcesManager( 7915): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  806): failed to open /acct/uid_10099/pid_6949/cgroup.procs: No such file or directory
,D/ConnectivityService(  806): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7915): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7915): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7915): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7915): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/WebViewFactory( 7915): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7915): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7915): Loading: webviewchromium
,I/LibraryLoader( 7915): Time to load native libraries: 4 ms (timestamps 4194-4198)
I/LibraryLoader( 7915): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7915): Binding Chromium to main looper Looper (main, tid 1) {1e8829ba}
,I/LibraryLoader( 7915): Expected native library version number "",actual native library version number ""
,I/chromium( 7915): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7915): Initializing chromium process, renderers=0
,W/art     ( 7915): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 7915): Requires BLUETOOTH permission
,W/chromium( 7915): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7915): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7915): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 7915): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7915): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7915): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7915): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7915): Remote Branch: 
I/Adreno-EGL( 7915): Local Patches: 
I/Adreno-EGL( 7915): Reconstruct Branch: 
,I/NSApplication( 7915): Starting up...
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7970): MountEmulatedStorage()
E/Zygote  ( 7970): v2
,I/libpersona( 7970): KNOX_SDCARD checking this for 10138
I/libpersona( 7970): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7970 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  806): Killing 7013:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/SELinux ( 7970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7970): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7970): TimaSignature is unavailable
,D/ActivityThread( 7970): Added TimaKeyStore provider
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/libprocessgroup(  806): failed to open /acct/uid_10003/pid_7013/cgroup.procs: No such file or directory
,W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7970): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7970): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7970): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7985): MountEmulatedStorage()
,E/Zygote  ( 7985): v2
I/libpersona( 7985): KNOX_SDCARD checking this for 10163
I/libpersona( 7985): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7985 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  806): Killing 7019:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/SELinux ( 7985): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7985): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7985): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7985): TimaSignature is unavailable
,D/ActivityThread( 7985): Added TimaKeyStore provider
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 7985): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/libprocessgroup(  806): failed to open /acct/uid_10020/pid_7019/cgroup.procs: No such file or directory
,W/ResourcesManager( 7985): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7985): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7985): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7985): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SA      ( 7840): [RC New] [v2liruge] api execute + 686
I/SA      ( 7840): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7840): AsyncTask #1 calls detatch()
,I/SA      ( 7840): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7840): [OCP] update openData : PL
,I/SA      ( 7840): [TPMU] getNetworkMcc : 
,D/RCPManagerService(  806): exchangeData() failure , invalid userId
,I/SA      ( 7840): [SCU] saveMccToPreferece Start
,I/SA      ( 7840): [SCU] RegionMCC : 260
I/SA      ( 7840): [SSP] query invoked
,D/RCPManagerService(  806): exchangeData() failure , invalid userId
,I/art     (  806): Explicit concurrent mark sweep GC freed 66156(3MB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 1.307ms total 83.233ms
,D/RCPManagerService(  806): exchangeData() failure , invalid userId
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/SA      ( 7840): [TPMU] GetMccFromDB : null
I/SA      ( 7840): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7840): [SCU] saveMccToPreferece End
,I/SA      ( 7840): [RC New] executeRequest [v2liruge] end. 894
I/SA      ( 7840): [RC New] Execute end
,I/SA      ( 7840): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7840): [OR] GetMyCountryZoneTask Success
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  806): exchangeData() failure , invalid userId
,E/Zygote  ( 8012): MountEmulatedStorage()
E/Zygote  ( 8012): v2
I/libpersona( 8012): KNOX_SDCARD checking this for 10078
I/libpersona( 8012): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8012 uid=10078 gids={50078, 9997} abi=armeabi-v7a
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/art     (  312): Explicit concurrent mark sweep GC freed 8737(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 283us total 12.424ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 10.240ms
,I/SELinux ( 8012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 570us total 8.479ms
I/SELinux ( 8012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8012): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  806): exchangeData() failure , invalid userId
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/RCPManagerService(  806): exchangeData() failure , invalid userId
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,I/jxcore-log( 7493): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7493): 
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7570): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7570): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7570): StateMachine : Current State = 1
D/TimaKeyStoreProvider( 8012): TimaSignature is unavailable
,D/ActivityThread( 8012): Added TimaKeyStore provider
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,I/ActivityManager(  806): Killing 7044:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,D/SecurityLogAgent( 7570): StateMachine : Changed Current State = 1
,I/ActivityManager(  806): Killing 7064:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
D/com.peel.receiver.ConnectivityActionReceiver( 3679): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 8012): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): last run: 1453367781217 -- System.currentTimeMillis()-last_run: 28724757
D/com.peel.receiver.ConnectivityActionReceiver( 3679): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): ... skip last_72_check
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,E/Zygote  ( 8034): MountEmulatedStorage()
E/Zygote  ( 8034): v2
I/libpersona( 8034): KNOX_SDCARD checking this for 10178
I/libpersona( 8034): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8034 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BadgeProvider( 8012): onCreate
D/BadgeProvider( 8012): DatabaseHelper
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7985): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/SELinux ( 8034): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8034): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8034): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/BadgeProvider( 8012): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 8034): TimaSignature is unavailable
,D/ActivityThread( 8034): Added TimaKeyStore provider
,D/Launcher.Model( 1481): reloadBadges entered.
D/BadgeProvider( 8012): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8012): sendNotify, [notify] : null
D/BadgeProvider( 8012): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8012): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8012): update, [UpdateCount] : 1
,D/ResourcesManager( 8034): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  806): Killing 7081:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  806): failed to open /acct/uid_1000/pid_7044/cgroup.procs: No such file or directory
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  806): failed to open /acct/uid_10112/pid_7064/cgroup.procs: No such file or directory
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2443): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2443): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7173): notifyNetworkActivated
,W/libprocessgroup(  806): failed to open /acct/uid_10118/pid_7081/cgroup.procs: No such file or directory
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager(  806): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,W/ContextImpl( 7173): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  806): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
D/SecContentProvider2(  806): mCursor = null
,D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2443): [AccountUtils] Account not ready
W/Kids    ( 2443): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2443): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2443): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2443): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2443): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2443): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2443): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2443): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2443): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2443): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2443): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2443): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/hcjo    ( 7173): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7173): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7173): exit::IDLE
,D/InitializeManagerStateMachine( 7173): entry::NETWORK_CHECK
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7173): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7173): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7173): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7173): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7173): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7173): entry::SUCCESS
D/hcjo    ( 7173): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1295): Starting #8
,D/hcjo    ( 7173): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7173): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
I/Hs20UtilService( 1295): Message received 5007
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine( 7173): exit::SUCCESS
D/InitializeManagerStateMachine( 7173): entry::IDLE
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1295): Starting #9
,I/Hs20UtilService( 1295): Message received 5007
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1295): Starting #10
,I/Hs20UtilService( 1295): Message received 5007
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1295): Starting #11
,I/Hs20UtilService( 1295): Message received 5007
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  806): callSECApi what=220
D/WifiStateMachine(  806): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
I/PCWCLIENTTRACE_PushUtil( 7624): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7624): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7624): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7624): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  806): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=806
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  806): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/DIAGMON_AGENT( 7697): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7697): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
D/lights  (  806): lcd : 8 +
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/lights  (  806): lcd : 8 -
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/FOTA_Client( 7720): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7720): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7720): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7720): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7720): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.503: ( 7738): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.503: ( 7738): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453396506498
,I/KLMS-2.4.503: ( 7738): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7738): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7738): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7738): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/KLMS-2.4.503: ( 7738): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SO_AGENT( 7770): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7813): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7840): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7840): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7840): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7840): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7840): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7840): [SCU] == networkStateCheck == true
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SA      ( 7840): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7840): isChinaCountryCode : false
I/SA      ( 7840): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7840): [OR] == networkStateCheck true ==
I/SA      ( 7840): [OR] GetMyCountryZoneTask
I/SA      ( 7840): [OR] onReceive END
,I/SA      ( 7840): [SRS] prepareGetMyCountryZone
,I/SA      ( 7840): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7840): [SSP] query invoked
,I/SA      ( 7840): [TPMU] GetMccFromDB : null
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7840): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7840): [TPM] isNoProxy(default) : true
I/SA      ( 7840): [RC New] Execute method=[GET] start
,D/accuweather( 7317): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7317): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7864): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7864): premStatus:2
,I/KnoxUsageLogPro( 7864): isEulaShown : false
I/KnoxUsageLogPro( 7864): KnoxUsageReceiver onReceive : not Processible, just return
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/GCM     ( 1693): Connected
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/Headlines( 5537): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1693): Message class com.google.f.a.a.p
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/HeadlinesChannelUtil( 5537): getCountryCode(): countryCode = DE
,D/Headlines( 5537): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5537): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5537): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5537): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5537): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5537): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5537): requestUpdateNewsWelcomeCard !!! no welcome card
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/QuickConnect( 7970): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7970): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7970): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/RCPManagerService(  806): exchangeData() failure , invalid userId
,D/RCPManagerService(  806): exchangeData() failure , invalid userId
,I/SA      ( 7840): [RC New] Security=[true]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7570): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7570): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7570): StateMachine : Current State = 1
D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7570): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 3679): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): last run: 1453367781217 -- System.currentTimeMillis()-last_run: 28725477
D/com.peel.receiver.ConnectivityActionReceiver( 3679): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 3679): ... skip last_72_check
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7493): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7493): 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ChimeraCfgMgr( 2443): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2443): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7173): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7173): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7173): exit::IDLE
D/InitializeManagerStateMachine( 7173): entry::NETWORK_CHECK
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7173): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7173): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7173): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7173): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7173): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7173): entry::SUCCESS
D/hcjo    ( 7173): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/hcjo    ( 7173): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7173): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7173): exit::SUCCESS
D/InitializeManagerStateMachine( 7173): entry::IDLE
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/jxcore-log( 7493): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7493): 
,I/jxcore-log( 7493): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7493): 
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
D/SecContentProvider2(  806): mCursor = null
,D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Kids    ( 2443): [AccountUtils] Account not ready
W/Kids    ( 2443): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2443): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2443): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2443): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2443): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2443): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2443): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2443): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2443): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2443): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2443): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2443): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/jxcore-log( 7493): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7493): 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/jxcore-log( 7493): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7493): 
,I/jxcore-log( 7493): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7493): 
,I/jxcore-log( 7493): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7493): 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/SA      ( 7840): [RC New] [v2liruge] api execute + 573
,I/SA      ( 7840): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 7840): AsyncTask #2 calls detatch()
,I/SA      ( 7840): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7840): [OCP] update openData : PL
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/SA      ( 7840): [TPMU] getNetworkMcc : 
,I/SA      ( 7840): [SCU] saveMccToPreferece Start
I/SA      ( 7840): [SCU] RegionMCC : 260
,I/SA      ( 7840): [SSP] query invoked
,I/SA      ( 7840): [TPMU] GetMccFromDB : null
,I/SA      ( 7840): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7840): [SCU] saveMccToPreferece End
,I/SA      ( 7840): [RC New] executeRequest [v2liruge] end. 680
I/SA      ( 7840): [RC New] Execute end
I/SA      ( 7840): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7840): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine(  806): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  806): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
D/PowerManagerService(  806): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  806): [PWL] On : 76347 (30000 ms ago)
I/PowerManagerService(  806): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  806): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=806, ws=WorkSource{10059}) (elapsedTime=1055)
,I/jxcore-log( 7493): Test app app.js loaded
I/jxcore-log( 7493): 
,I/chromium( 7493): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7493): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7493): BLE advertisement is supported
I/jxcore-log( 7493): 
,E/SMD     (  283): DCD ON
,I/dhcpcd  ( 7712): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7712): wlan0: sendmsg: Cannot assign requested address
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/WifiStateMachine(  806): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  806): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  806): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
E/WifiStateMachine(  806): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  806): identical MTU - not setting
,D/ConnectivityService(  806): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  806): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  274): QcRouteController
,D/SmartBondingService(  806): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  806): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  806): getSBEnabled() enabled =false
D/SmartBondingService(  806): getSBEnabled() enabled =false
D/SmartBondingService(  806): getSBEnabled() enabled =false
,V/        (  274): QcRouteController
,W/NetworkManagementService(  806): route cmd failed: 
W/NetworkManagementService(  806): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  806): '
W/NetworkManagementService(  806): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  806): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  806): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  806): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  806): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  806): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  806): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  806): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  806): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  806): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  806): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  806): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  806): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  806): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  806): calling update connectivity
D/ConnectivityService(  806):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  806):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  806): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524295
D/ConnectivityService(  806): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524295
D/ConnectivityService(  806): calling update connectivity
D/ConnectivityService(  806):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  806):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  806): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/WearableService( 5082): callingUid 10012, callindPid: 5082
,D/ResourcesManager( 7651): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7651): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7651): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7651): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7651): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7651): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7651): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7651): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7651): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7651): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7651): Conditions not met for autocaching.
I/MusicLeanback( 7651): Stop autocaching.
,E/ActivityThread( 7651): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@5f944d2 that was originally bound here
E/ActivityThread( 7651): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@5f944d2 that was originally bound here
E/ActivityThread( 7651): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7651): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7651): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7651): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7651): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7651): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7651): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7651): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7651): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7651): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7651): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7651): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7651): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7651): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7651): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7651): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7651): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7651): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7651): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7651): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7651): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7651): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7651): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7651): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7651): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,V/AlarmManager(  806): waitForAlarm result :8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
W/Search.LoginHelper( 1582): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/SSRM:m  (  806): SIOP:: AP = 430, PST = 437, CUR = 300
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/PackageManager(  806): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  806): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/InputReader(  806): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 1481): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  ( 8099): MountEmulatedStorage()
E/Zygote  ( 8099): v2
I/libpersona( 8099): KNOX_SDCARD checking this for 10034
I/libpersona( 8099): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8099 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/ResourcesManager( 1481): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/SELinux ( 8099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/SELinux ( 8099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Books/Books.apk
,E/SELinux ( 8099): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/RegisteredServicesCache( 1468): empty dynamic service
,D/ResourcesManager( 1481): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1481): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1481): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 8099): TimaSignature is unavailable
D/SecContentProvider2(  806): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  806): mCursor = null
D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ActivityThread( 8099): Added TimaKeyStore provider
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/FeatureConfig( 8099): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  806): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  806): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  806): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  806): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8131): MountEmulatedStorage()
I/libpersona( 8131): KNOX_SDCARD checking this for 10035
E/Zygote  ( 8131): v2
I/libpersona( 8131): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8131 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  806): Killing 7097:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/SELinux ( 8131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8131): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  806): failed to open /acct/uid_1000/pid_7097/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8131): TimaSignature is unavailable
,D/ActivityThread( 8131): Added TimaKeyStore provider
,D/ResourcesManager( 8131): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  806): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 806) eventTime = 108778
,D/PowerManagerService(  806): [s] UserActivityState : 4 -> 1
D/PowerManagerService(  806): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=806 (0x0)
,D/PowerManagerService(  806): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=806, ws=WorkSource{10059}) (elapsedTime=3485)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8155): MountEmulatedStorage()
E/Zygote  ( 8155): v2
I/libpersona( 8155): KNOX_SDCARD checking this for 10017
I/libpersona( 8155): KNOX_SDCARD not a persona
,I/SELinux ( 8155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  806): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=8155 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SELinux ( 8155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8155): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/TimaKeyStoreProvider( 8155): TimaSignature is unavailable
,D/ActivityThread( 8155): Added TimaKeyStore provider
,D/ResourcesManager( 8155): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/BluetoothManager( 8131): getConnectedDevices
,D/-----SIC-----( 8131): ------------------skip uv
,D/-----SIC-----( 8131): ------------------skip SPO2
D/-----SIC-----( 8131): ------------------skip TGH
,I/SecureStorage( 8155): [INFO]: SPID(0x00000000)Processing data
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/SecureStorage(  326): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 8155
I/SecureStorage(  326): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8131): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/ContextImpl( 8131): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,V/MediaPlayer( 8131): decode(35, 19359868, 4230)
,V/MediaPlayerService(  288): decode(30, 19359868, 4230)
,V/MediaPlayerService(  288): player type = 3
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,V/AwesomePlayer(  288): setDefault
,V/AwesomePlayer(  288): reset_l()
,V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
,V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
,V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19359868, 4230)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xb0a54420, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthServiceInstalled() : HealthService is Installed.
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
,V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/ActivityManager(  806): Killing 7134:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
,I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1170): M updateContainers()
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
V/MediaPlayerService(  288): wait for playback complete
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1170): M updateContainers()
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 8131): decode(33, 19213040, 15440)
V/MediaPlayerService(  288): decode(30, 19213040, 15440)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19213040, 15440)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/DatabaseUtils(  806): Writing exception to parcel
E/DatabaseUtils(  806): java.lang.NullPointerException: key == null
E/DatabaseUtils(  806): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  806): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  806): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  806): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  806): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  806): 	at android.os.Binder.execTransact(Binder.java:446)
,I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
,V/MediaPlayerService(  288): wait for playback complete
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/UpdateIcingCorporaServi( 1582): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/ActivityManager(  806): Killing 6738:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,E/Zygote  ( 8207): MountEmulatedStorage()
I/libpersona( 8207): KNOX_SDCARD checking this for 10075
E/Zygote  ( 8207): v2
I/libpersona( 8207): KNOX_SDCARD not a persona
,V/MediaPlayer( 8131): decode(34, 19257568, 9226)
,I/ActivityManager(  806): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8207 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/MediaPlayerService(  288): decode(30, 19257568, 9226)
I/SELinux ( 8207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,I/SELinux ( 8207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8207): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AwesomePlayer(  288): setDefault
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19257568, 9226)
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
,V/MediaPlayerService(  288): wait for prepare
,W/libprocessgroup(  806): failed to open /acct/uid_10166/pid_7134/cgroup.procs: No such file or directory
,V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
D/TimaKeyStoreProvider( 8207): TimaSignature is unavailable
,D/ActivityThread( 8207): Added TimaKeyStore provider
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(2)
,I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xaf709240, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/MediaPlayerService(  288): wait for playback complete
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 8131): decode(37, 19364180, 4890)
,V/MediaPlayerService(  288): decode(31, 19364180, 4890)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
,V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
,V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
,V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(31, 19364180, 4890)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 8, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,D/Utils   (  288): printFileName fd(29) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
,V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
,V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,D/ResourcesManager( 8207): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,W/libprocessgroup(  806): failed to open /acct/uid_10012/pid_6738/cgroup.procs: No such file or directory
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
,I/UpdateIcingCorporaServi( 1582): UpdateCorporaTask done [took 111 ms] updated apps [took 111 ms] 
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
I/AudioPlayer(  288): First fillBuffer call!!
,I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,V/MediaPlayerService(  288): wait for playback complete
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,I/GAV4    ( 7915): Thread[GAThread,5,main]: No campaign data found.
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 8131): decode(39, 19290344, 17329)
V/MediaPlayerService(  288): decode(30, 19290344, 17329)
,V/MediaPlayerService(  288): player type = 3
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/FileShare-Server( 8207): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
,V/MediaPlayerService(  288): wait for playback complete
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
I/OggExtractor(  288): ~OggSource --
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
I/OggExtractor(  288): ~OggExtractor ++
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 8131): decode(40, 19190536, 6644)
V/MediaPlayerService(  288): decode(30, 19190536, 6644)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
,E/Zygote  ( 8237): MountEmulatedStorage()
E/Zygote  ( 8237): v2
I/libpersona( 8237): KNOX_SDCARD checking this for 1000
I/libpersona( 8237): KNOX_SDCARD not a persona
,V/AwesomePlayer(  288): onPrepareAsyncEvent
,I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
I/ActivityManager(  806): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8237 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/AwesomePlayer(  288): checkOffloadExceptions is true
,V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/ActivityManager(  806): Killing 7149:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/SELinux ( 8237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
I/SELinux ( 8237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
,I/AudioPlayer(  288): First fillBuffer call!!
,I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
,V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,D/TimaKeyStoreProvider( 8237): TimaSignature is unavailable
D/ActivityThread( 8237): Added TimaKeyStore provider
,I/AudioPlayer(  288): reset out
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
,V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
,V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 8131): decode(41, 19266876, 23389)
,V/MediaPlayerService(  288): decode(30, 19266876, 23389)
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19266876, 23389)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
,V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
W/libprocessgroup(  806): failed to open /acct/uid_10170/pid_7149/cgroup.procs: No such file or directory
,D/ResourcesManager( 8237): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
,I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  288): wait for playback complete
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 8131): decode(38, 19156232, 8154)
V/MediaPlayerService(  288): decode(30, 19156232, 8154)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
,I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 5, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
,E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,D/ShortcutReceiver( 8237):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 7, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 8131): decode(42, 19129712, 4804)
,V/MediaPlayerService(  288): decode(30, 19129712, 4804)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
,V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  288): wait for playback complete
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 8131): decode(43, 19099164, 9400)
V/MediaPlayerService(  288): decode(30, 19099164, 9400)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/MediaPlayer( 8131): decode(49, 19172584, 4112)
,V/MediaPlayerService(  288): decode(35, 19172584, 4112)
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(35, 19172584, 4112)
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(36) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
,I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
,V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/MediaPlayerService(  288): wait for playback complete
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/AudioPlayer(  288): start of Playback, useOffload 0
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/PackageBroadcastService( 2443): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/AudioPlayer(  288): Audio channels(1)
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
,I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
I/OggExtractor(  288): ~OggExtractor --
V/MediaPlayerService(  288): wait for playback complete
,I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 8131): decode(44, 19307764, 52024)
V/MediaPlayerService(  288): decode(30, 19307764, 52024)
,I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
V/MediaPlayerService(  288): player type = 3
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19307764, 52024)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthServiceInstalled() : HealthService is Installed.
,V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
,V/MediaPlayerService(  288): wait for playback complete
I/AudioPlayer(  288): First fillBuffer call!!
,E/SMD     (  283): DCD ON
,I/PeopleContactsSync( 2443): CP2 sync disabled
,I/ActivityManager(  806): Killing 7194:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
,V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a542e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 8131): decode(45, 19172584, 4112)
,V/MediaPlayerService(  288): decode(30, 19172584, 4112)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19172584, 4112)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xaf709240, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
,I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  288): notify(0xaf709240, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
,V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xaf709240, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/MediaPlayerService(  288): wait for playback complete
V/AwesomePlayer(  288): onCheckAudioStatus
,V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 7, 0, 0)
V/AudioCache(  288): ignored
,V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf709240, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
,D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
,I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
,V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
,V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 8131): decode(46, 19235660, 21825)
V/MediaPlayerService(  288): decode(30, 19235660, 21825)
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19235660, 21825)
V/AwesomePlayer(  288): reset_l()
,V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
,V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xaf7091f0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xaf7091f0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,W/libprocessgroup(  806): failed to open /acct/uid_10054/pid_7194/cgroup.procs: No such file or directory,
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf7091f0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 8131): decode(47, 19134596, 21552)
V/MediaPlayerService(  288): decode(30, 19134596, 21552)
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xb0a09290, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
,I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
,I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 5, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(2)
,I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
I/AudioPlayer(  288): First fillBuffer call!!
,I/SecureStorage(  326): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  326): [INFO]: SPID(0x00000005)PID: 8155, TID: 8169
I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 7, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a09290, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
,V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
,V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 8131): decode(48, 19228560, 7017)
V/MediaPlayerService(  288): decode(30, 19228560, 7017)
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
,V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xb0a54420, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
V/AwesomePlayer(  288): mAudioTrackVector clear
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
,V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
,V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xb0a54420, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
,V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0),
V/AudioCache(  288): notify(0xb0a54420, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,V/MediaPlayerService(  288): wait for playback complete
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb0a54420, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/SecureStorage( 8155): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 8155): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 8131): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper( 8131): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 8131): Open platform.db in secure mode
,D/SecSQLiteDatabase( 8131): Android Version: 5.0
D/SecSQLiteDatabase( 8131): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 8131): openSecureDatabase...
,I/SecSQLiteDatabase( 8131): private openSecureDatabase...
,I/SecSQLiteConnectionPool( 8131): OpenSecure
I/SecSQLiteConnectionPool( 8131): OpenSecure with password
I/SecSQLiteConnectionPool( 8131): openSecureConnectionLocked
,I/SecSQLiteDatabase( 8131): ...private openSecureDatabase
I/SecSQLiteDatabase( 8131): ...openSecureDatabase
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/SecSQLiteOpenHelper( 8131): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 8131): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8131): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 8131): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 8131): 	at java.lang.Integer.invalidInt(Integer.java:138)
,W/System.err( 8131): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 8131): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 8131): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 8131): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
,W/System.err( 8131): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8131): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8131): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7624): mConnectivityHandler : connected
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7624): [hasSamungAccount] - No Samsung Account
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/CSTORAGE( 7624): ================================================
,I/CSTORAGE( 7624):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7624): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7624): [GetString-S]
,E/art     ( 7624): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 7624): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7624): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7624): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7624): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7624): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7624): [ensureRegistration] - No Samsung account
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7712): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/SMD     (  283): DCD ON
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/FactoryTest( 6456): Not factory mode
D/FactoryTest( 6456): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6456): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6456): still no open session command from host, so toast
,W/ContextImpl( 6456): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6456): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,I/Timeline( 6456): Timeline: Activity_launch_request id:com.android.settings time:113703
E/PersonaManagerService(  806): inState():  stateMachine is null !!
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  806): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  806): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 806  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  806): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/MTPRx   ( 6456): started activity for popup
,I/SQLiteSecureOpenHelper( 3556): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3556): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 6456): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6456): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6456): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6456): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6456): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6456): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6456): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6456): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  806): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  806): Invalid thumbnail dimensions: 576x576
,W/InputMethodManagerService(  806): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@27405100 attribute=null, token = android.os.BinderProxy@3653c72b
,I/SQLiteSecureOpenHelper( 3556): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3556): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6456): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6456): dev.kiessupport is : TRUE
,D/Activity( 6456): performCreate Call secproduct feature valuefalse
D/Activity( 6456): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ActivityManager(  806): post active user change for 0
D/KnoxTimeoutHandler(  806): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  806): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,I/Timeline( 7493): Timeline: Activity_idle id: android.os.BinderProxy@1f5cecd9 time:113934
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/art     (  806): Explicit concurrent mark sweep GC freed 58793(3MB) AllocSpace objects, 9(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.358ms total 94.960ms
,I/GAV3    ( 8131): Thread[GAThread,5,main]: No campaign data found.
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7712): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7712): wlan0: no IPv6 Routers available
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7173): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7173): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7173): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7173): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7173): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7173): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7173): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7173): entry::IDLE
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/SMD     (  283): DCD ON
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7173): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7173): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7173): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7173): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7173): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7173): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7173): entry::IDLE
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/CustomFrequencyManagerService(  806): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 806  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  806): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  806): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 806  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  806): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 806  tag : ACTIVITY_RESUME_BOOSTER@10
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  806): SIOP:: AP = 410, PST = 430, CUR = 300
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,V/AlarmManager(  806): waitForAlarm result :4
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
I/MotionRecognitionService(  806): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3241): Disconnected process message: 10
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6685): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6685): [1] 5.onFinished: Installation state replication failed.
,E/SMD     (  283): DCD ON
,D/Finsky  ( 6685): [1] 5.onFinished: Scheduling replication attempt 3.
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ActivityManager(  806): Waited long enough for: ServiceRecord{2ab70597 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/SMD     (  283): DCD ON,
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560,
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness(),
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8,
,V/AlarmManager(  806): waitForAlarm result :4
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/SMD     (  283): DCD ON
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8,
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen,
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  806): SIOP:: AP = 370, PST = 418, CUR = 300
,D/X       (  806): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1222):  LEVEL : 0
,E/SMD     (  283): DCD ON
,E/Zygote  ( 8352): MountEmulatedStorage()
E/Zygote  ( 8352): v2
I/libpersona( 8352): KNOX_SDCARD checking this for 10054
I/libpersona( 8352): KNOX_SDCARD not a persona
,I/SELinux ( 8352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  806): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8352 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 8352): TimaSignature is unavailable
D/ActivityThread( 8352): Added TimaKeyStore provider
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 8352): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8352): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8352): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8352): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8352): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8352): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8352): core_num = 4
,W/linker  ( 8352): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8352): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8352): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8352): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8352):  SIOP_LEVEL: 0
,I/ActivityManager(  806): Killing 5030:com.android.defcontainer/u0a5 (adj 15): bgCount ##41
,W/libprocessgroup(  806): failed to open /acct/uid_10005/pid_5030/cgroup.procs: No such file or directory
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8,
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
,I/MotionRecognitionService(  806): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8,
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/SMD     (  283): DCD ON
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560,
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  806): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  806): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  806): lcd : 5 +
,D/lights  (  806): lcd : 5 -
,D/lights  (  806): lcd : 1 +
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/lights  (  806): lcd : 1 -
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness(),
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/SMD     (  283): DCD ON
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/Watchdog(  806): !@Sync 4
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/StatusBar.NetworkController( 1170): applyOpen
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/SMD     (  283): DCD ON
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/SSRM:m  (  806): SIOP:: AP = 350, PST = 404, CUR = 300
,D/X       (  806): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1222):  LEVEL : -1
,E/TranscodeReceiver( 8352): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 8352):  SIOP_LEVEL: -1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  806): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  806): CMD_RSSI_POLL : out!
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,V/AlarmManager(  806): waitForAlarm result :4
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  806): Plugged
,I/MotionRecognitionService(  806): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 1 -> 1
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerManagerService(  806): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  806): Nap time (uid 1000)...
I/PowerManagerService(  806): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  806): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  806): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  806): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  806): handleSandman : startDream()
D/InputManager-JNI(  806): setDeviceInteractive: 0
,D/InputManager-JNI(  806): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  806): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  806): Sleeping (uid 1000)...
D/PowerManagerService(  806): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  806): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  806): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
D/InputManager-JNI(  806): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  806): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  806): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  806): 	.unregisterCallback : 1, client=
,D/SContextService(  806): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3c7544c, Service = Auto Rotation, used = 1
,W/CAE     (  806): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  806): stop(ContextProvider.java:149)
,V/CAE     (  806): clear(AutoRotationRunner.java:182)
,V/CAE     (  806): disable(AutoRotationRunner.java:171)
,I/CAE     (  806): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager(  806): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/CAE     (  806): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  806): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CAE     (  806): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  806): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  806): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  806): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  806): removeSContextService() : service = Auto Rotation
D/SContextService(  806): ===== SContext Service List =====
,D/SContextManager(  806):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2c0bdc3a, service=Auto Rotation
,D/KeyguardViewMediator( 1170): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1170): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1170): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1170): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/KeyguardViewMediator( 1170): timeout : 5000
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SQLiteSecureOpenHelper( 3556): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3556): getDatabaseLocked(b,b,pwd)...
,D/DisplayPowerController(  806): ColorFade: onAnimationStart
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 0
D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
D/DisplayPowerController(  806): getFinalBrightness : 8 -> 0
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 0
D/lights  (  806): lcd : 0 +
,D/lights  (  806): lcd : 0 -
,D/KeyguardViewMediator( 1170): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1170): handleNotifyScreenOff
,D/Finsky  ( 6685): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6685): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6685): [1] 5.onFinished: Scheduling replication attempt 4.
,D/LightsService(  806): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 806) 
D/LightsService(  806): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  806): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  806): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  806): unregisterListener ::   
D/lights  (  806): led_pattern : 5 +
,D/BatteryService(  806): turn on LED for fully charged
,D/lights  (  806): led_pattern : 5 -
D/LightsService(  806): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  806): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  806): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  806): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  806): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,I/CAE     (  806): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 17, 15, 40,
,D/SensorHubManager(  806): SendSensorHubData: send data = -63, 14, 17, 15, 40
D/Sensorhubs(  297): sendContextData: -63, 14, 17, 15, 40
,E/LightSensor(  806): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  806):  handler : SCREEN_OFF end 
,D/AutomaticBrightnessController(  806): mCallbacks.updateBrightness()
,D/DisplayPowerController(  806): getFinalBrightness : 8 -> 0
,D/NotificationService(  806): ACTION_SCREEN_OFF
,D/LightsService(  806): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 806) 
D/LightsService(  806): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
D/WifiStateMachine(  806): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  806): handleScreenStateChanged Exit: false
,D/LightsService(  806): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine(  806): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  806): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  806): do suspend true
,D/SensorManager(  806): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  806): unregisterListener ::   
D/LightsService(  806): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  288): adev_set_parameters: enter: screen_state=off
V/voice   (  288): voice_set_parameters: enter: screen_state=off
V/voice   (  288): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  288): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  288): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  288): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  288): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  806): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  806): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  806): Bridge Server is not available
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1170): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1170): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  806): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  806): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1468): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1170):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1170): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1170): dismissHelpPopup 
,D/accuweather( 2068): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2068): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2068): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  806): !@ ColorFade entry
,D/DisplayPowerController(  806): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  806): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  806): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  806): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  806): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,I/AutomaticBrightnessController(  806): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  806): unregisterListener ::   
,E/Sensors (  806): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  806): unregisterListener ::   
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DisplayPowerController(  806): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  806): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  806): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  806): Display changed displayId=0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBar.NetworkController( 1170): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/SSRM:m  (  806): SIOP:: AP = 350, PST = 393, CUR = 300
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/ActivityManager(  806): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  806): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  806): [PWL] sb release: PowerManagerService.Broadcasts
,I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1228406016)
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1228406016) wakelock released: 1, error no: 22
I/rmt_storage(  268): 
,I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
D/SurfaceControl(  806): Excessive delay in setPowerMode(): 254ms
D/PowerManagerService(  806): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  806): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  806): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  806): Got set_interactive hint
,I/PowerManagerService(  806): [PWL] Off : 0s ago
,I/PowerManagerService(  806): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  806): [PWL]     mDisplayReady : false
D/DisplayPowerController(  806): getFinalBrightness : 0 -> 0
D/PowerManagerService(  806): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  806): [PWL] sb release: PowerManagerService.Display
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  806): waitForAlarm result :4
,D/KeyguardViewMediator( 1170): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/KeyguardViewMediator( 1170): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  806): [PWL] Off : 5s ago
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 340, PST = 385, CUR = 300
,E/SMD     (  283): DCD ON
,V/AlarmManager(  806): waitForAlarm result :4
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  806): stay LED for fully charged
D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
I/MotionRecognitionService(  806): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1693): Explicit concurrent mark sweep GC freed 26707(1531KB) AllocSpace objects, 15(1215KB) LOS objects, 40% free, 17MB/29MB, paused 571us total 55.914ms
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6655): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6655): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6655): 	at kfv.a(PG:65)
E/HttpOperation( 6655): 	at kff.u(PG:385)
E/HttpOperation( 6655): 	at kfb.a(PG:29)
E/HttpOperation( 6655): 	at kff.l(PG:132)
E/HttpOperation( 6655): 	at dsf.a(PG:807)
E/HttpOperation( 6655): 	at fhk.a(PG:1126)
E/HttpOperation( 6655): 	at fhk.a(PG:908)
E/HttpOperation( 6655): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6655): 	at ihi.a(PG:22)
E/HttpOperation( 6655): 	at kft.a(PG:91)
E/HttpOperation( 6655): 	at kfv.a(PG:62)
E/HttpOperation( 6655): 	... 8 more
E/HttpOperation( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6655): 	at gde.c(Unknown Source)
E/HttpOperation( 6655): 	at gde.b(Unknown Source)
E/HttpOperation( 6655): 	at ihi.a(PG:19)
E/HttpOperation( 6655): 	... 10 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
E/HttpOperation( 6655): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6655): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6655): 	at kfv.a(PG:65)
E/HttpOperation( 6655): 	at kff.u(PG:385)
E/HttpOperation( 6655): 	at kfb.a(PG:29)
E/HttpOperation( 6655): 	at kff.l(PG:132)
E/HttpOperation( 6655): 	at ieo.a(PG:43)
E/HttpOperation( 6655): 	at iep.a(PG:93)
E/HttpOperation( 6655): 	at fhn.a(PG:59)
E/HttpOperation( 6655): 	at lex.a(PG:85)
E/HttpOperation( 6655): 	at lex.b(PG:132)
E/HttpOperation( 6655): 	at fhk.a(PG:1146)
E/HttpOperation( 6655): 	at fhk.a(PG:908)
E/HttpOperation( 6655): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6655): 	at ihi.a(PG:22)
E/HttpOperation( 6655): 	at kft.a(PG:91)
E/HttpOperation( 6655): 	at kfv.a(PG:62)
E/HttpOperation( 6655): 	... 12 more
E/HttpOperation( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6655): 	at gde.c(Unknown Source)
E/HttpOperation( 6655): 	at gde.b(Unknown Source)
E/HttpOperation( 6655): 	at ihi.a(PG:19)
E/HttpOperation( 6655): 	... 14 more
,E/ExperimentLoader( 6655): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6655): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6655): 	at kfv.a(PG:65)
E/ExperimentLoader( 6655): 	at kff.u(PG:385)
E/ExperimentLoader( 6655): 	at kfb.a(PG:29)
E/ExperimentLoader( 6655): 	at kff.l(PG:132)
E/ExperimentLoader( 6655): 	at ieo.a(PG:43)
E/ExperimentLoader( 6655): 	at iep.a(PG:93)
E/ExperimentLoader( 6655): 	at fhn.a(PG:59)
E/ExperimentLoader( 6655): 	at lex.a(PG:85)
E/ExperimentLoader( 6655): 	at lex.b(PG:132)
E/ExperimentLoader( 6655): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6655): 	at fhk.a(PG:908)
E/ExperimentLoader( 6655): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6655): 	at ihi.a(PG:22)
E/ExperimentLoader( 6655): 	at kft.a(PG:91)
E/ExperimentLoader( 6655): 	at kfv.a(PG:62)
E/ExperimentLoader( 6655): 	... 12 more
E/ExperimentLoader( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6655): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6655): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6655): 	at ihi.a(PG:19)
E/ExperimentLoader( 6655): 	... 14 more
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
D/SecContentProvider2(  806): mCursor = null
,D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6655): [getaccountstatus] Unexpected exception
E/HttpOperation( 6655): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6655): 	at kfv.a(PG:65)
E/HttpOperation( 6655): 	at kff.u(PG:385)
E/HttpOperation( 6655): 	at kfb.a(PG:29)
E/HttpOperation( 6655): 	at ixd.a(PG:248)
E/HttpOperation( 6655): 	at ixd.b(PG:206)
E/HttpOperation( 6655): 	at ixd.a(PG:175)
E/HttpOperation( 6655): 	at fig.a(PG:78)
E/HttpOperation( 6655): 	at lex.a(PG:85)
E/HttpOperation( 6655): 	at lex.b(PG:132)
E/HttpOperation( 6655): 	at fhk.a(PG:1146)
E/HttpOperation( 6655): 	at fhk.a(PG:908)
E/HttpOperation( 6655): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6655): 	at ihi.a(PG:22)
E/HttpOperation( 6655): 	at kft.a(PG:91)
E/HttpOperation( 6655): 	at kfv.a(PG:62)
E/HttpOperation( 6655): 	... 12 more
E/HttpOperation( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6655): 	at gde.c(Unknown Source)
E/HttpOperation( 6655): 	at gde.b(Unknown Source)
E/HttpOperation( 6655): 	at ihi.a(PG:19)
E/HttpOperation( 6655): 	... 14 more
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/EsSyncAdapterService( 6655): Sync failure
E/EsSyncAdapterService( 6655): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6655): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6655): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6655): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6655): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6655): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6655): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6655): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6655): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6655): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6655): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6655): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6655): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6655): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6655): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6655): 	... 10 more
E/EsSyncAdapterService( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6655): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6655): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6655): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6655): 	... 12 more
E/EsSyncAdapterService( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6655): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6655): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6655): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6655): 	... 14 more
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/SyncManager(  806): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 124871, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  806): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  806): mCursor = null
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService(  806): [PWL] Off : 15s ago
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  806): waitForAlarm result :8
,D/SSRM:m  (  806): SIOP:: AP = 330, PST = 376, CUR = 300
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  283): DCD ON
,E/Watchdog(  806): !@Sync 5
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 320, PST = 367, CUR = 300
,I/PowerManagerService(  806): [PWL] Off : 30s ago
,E/SMD     (  283): DCD ON
,V/AlarmManager(  806): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1693): Vacuum at: now=1453396572785 tag=VacuumService
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1693): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/Finsky  ( 6685): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6685): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6685): [1] 5.onFinished: Scheduling replication attempt 5.
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/Uploader( 1693): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1693): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1693): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1693): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1693): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1693): (HTTPLog)-Static: isShipBuild true
I/System.out( 1693): (HTTPLog)-Thread-202-918257188: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1693): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,I/qtaguid ( 1693): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,E/SMD     (  283): DCD ON
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,W/Uploader( 1693):  no longer exists, so no auth token.
,I/qtaguid ( 1693): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  283): DCD ON
,V/AlarmManager(  806): waitForAlarm result :4
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 320, PST = 359, CUR = 300
,E/SMD     (  283): DCD ON
,V/AlarmManager(  806): waitForAlarm result :4
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
I/MotionRecognitionService(  806): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/BatteryService(  806): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7411): Starting books sync, d
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7411): Authentication error
E/BooksAccountManager( 7411): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7411): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7411): null auth token
,I/qtaguid ( 7411): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,I/qtaguid ( 7411): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,I/qtaguid ( 7411): Untagging socket 34
,W/ApiaryClient( 7411): Error response from books API: {
W/ApiaryClient( 7411):  "error": {
W/ApiaryClient( 7411):   "errors": [
W/ApiaryClient( 7411):    {
W/ApiaryClient( 7411):     "domain": "global",
W/ApiaryClient( 7411):     "reason": "required",
W/ApiaryClient( 7411):     "message": "Login Required",
W/ApiaryClient( 7411):     "locationType": "header",
W/ApiaryClient( 7411):     "location": "Authorization"
W/ApiaryClient( 7411):    }
W/ApiaryClient( 7411):   ],
W/ApiaryClient( 7411):   "code": 401,
W/ApiaryClient( 7411):   "message": "Login Required"
W/ApiaryClient( 7411):  }
W/ApiaryClient( 7411): }
,W/ApiaryClient( 7411): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3764721554491669444&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7411): Headers suppressed
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7411): Authentication error
E/BooksAccountManager( 7411): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7411): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7411): null auth token
,I/qtaguid ( 7411): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,I/qtaguid ( 7411): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,I/qtaguid ( 7411): Untagging socket 34
,W/ApiaryClient( 7411): Error response from books API: {
W/ApiaryClient( 7411):  "error": {
W/ApiaryClient( 7411):   "errors": [
W/ApiaryClient( 7411):    {
W/ApiaryClient( 7411):     "domain": "global",
W/ApiaryClient( 7411):     "reason": "required",
W/ApiaryClient( 7411):     "message": "Login Required",
W/ApiaryClient( 7411):     "locationType": "header",
W/ApiaryClient( 7411):     "location": "Authorization"
W/ApiaryClient( 7411):    }
W/ApiaryClient( 7411):   ],
W/ApiaryClient( 7411):   "code": 401,
W/ApiaryClient( 7411):   "message": "Login Required"
W/ApiaryClient( 7411):  }
W/ApiaryClient( 7411): }
,W/ApiaryClient( 7411): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3764721554491669444&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7411): Headers suppressed
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7411): Authentication error
E/BooksAccountManager( 7411): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7411): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7411): null auth token
,I/qtaguid ( 7411): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,I/qtaguid ( 7411): Untagging socket 34
,W/ApiaryClient( 7411): Error response from books API: {
W/ApiaryClient( 7411):  "error": {
W/ApiaryClient( 7411):   "errors": [
W/ApiaryClient( 7411):    {
W/ApiaryClient( 7411):     "domain": "global",
W/ApiaryClient( 7411):     "reason": "required",
W/ApiaryClient( 7411):     "message": "Login Required",
W/ApiaryClient( 7411):     "locationType": "header",
W/ApiaryClient( 7411):     "location": "Authorization"
W/ApiaryClient( 7411):    }
W/ApiaryClient( 7411):   ],
W/ApiaryClient( 7411):   "code": 401,
W/ApiaryClient( 7411):   "message": "Login Required"
W/ApiaryClient( 7411):  }
W/ApiaryClient( 7411): }
,W/ApiaryClient( 7411): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3764721554491669444&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7411): Headers suppressed
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/BooksSync( 7411): Soft error
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3764721554491669444&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7411): Headers suppressed
E/BooksSync( 7411): 
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7411): Sync error
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3764721554491669444&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7411): Headers suppressed
E/BooksSync( 7411): 
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7411): Finished books sync
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  806): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160723, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  806): Explicit concurrent mark sweep GC freed 70067(3MB) AllocSpace objects, 34(999KB) LOS objects, 30% free, 36MB/52MB, paused 1.514ms total 164.621ms
,D/SecContentProvider2(  806): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  806): mCursor = null
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
,D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6655): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6655): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6655): 	at kfv.a(PG:65)
E/HttpOperation( 6655): 	at kff.u(PG:385)
E/HttpOperation( 6655): 	at kfb.a(PG:29)
E/HttpOperation( 6655): 	at kff.l(PG:132)
E/HttpOperation( 6655): 	at dsf.a(PG:807)
E/HttpOperation( 6655): 	at fhk.a(PG:1126)
E/HttpOperation( 6655): 	at fhk.a(PG:908)
E/HttpOperation( 6655): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6655): 	at ihi.a(PG:22)
E/HttpOperation( 6655): 	at kft.a(PG:91)
E/HttpOperation( 6655): 	at kfv.a(PG:62)
E/HttpOperation( 6655): 	... 8 more
E/HttpOperation( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6655): 	at gde.c(Unknown Source)
E/HttpOperation( 6655): 	at gde.b(Unknown Source)
E/HttpOperation( 6655): 	at ihi.a(PG:19)
E/HttpOperation( 6655): 	... 10 more
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
D/SecContentProvider2(  806): mCursor = null
,D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6655): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6655): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6655): 	at kfv.a(PG:65)
E/HttpOperation( 6655): 	at kff.u(PG:385)
E/HttpOperation( 6655): 	at kfb.a(PG:29)
E/HttpOperation( 6655): 	at kff.l(PG:132)
E/HttpOperation( 6655): 	at ieo.a(PG:43)
E/HttpOperation( 6655): 	at iep.a(PG:93)
E/HttpOperation( 6655): 	at fhn.a(PG:59)
E/HttpOperation( 6655): 	at lex.a(PG:85)
E/HttpOperation( 6655): 	at lex.b(PG:132)
E/HttpOperation( 6655): 	at fhk.a(PG:1146)
E/HttpOperation( 6655): 	at fhk.a(PG:908)
E/HttpOperation( 6655): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6655): 	at ihi.a(PG:22)
E/HttpOperation( 6655): 	at kft.a(PG:91)
E/HttpOperation( 6655): 	at kfv.a(PG:62)
E/HttpOperation( 6655): 	... 12 more
E/HttpOperation( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6655): 	at gde.c(Unknown Source)
E/HttpOperation( 6655): 	at gde.b(Unknown Source)
E/HttpOperation( 6655): 	at ihi.a(PG:19)
E/HttpOperation( 6655): 	... 14 more
,E/ExperimentLoader( 6655): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6655): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6655): 	at kfv.a(PG:65)
E/ExperimentLoader( 6655): 	at kff.u(PG:385)
E/ExperimentLoader( 6655): 	at kfb.a(PG:29)
E/ExperimentLoader( 6655): 	at kff.l(PG:132)
E/ExperimentLoader( 6655): 	at ieo.a(PG:43)
E/ExperimentLoader( 6655): 	at iep.a(PG:93)
E/ExperimentLoader( 6655): 	at fhn.a(PG:59)
E/ExperimentLoader( 6655): 	at lex.a(PG:85)
E/ExperimentLoader( 6655): 	at lex.b(PG:132)
E/ExperimentLoader( 6655): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6655): 	at fhk.a(PG:908)
E/ExperimentLoader( 6655): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6655): 	at ihi.a(PG:22)
E/ExperimentLoader( 6655): 	at kft.a(PG:91)
E/ExperimentLoader( 6655): 	at kfv.a(PG:62)
E/ExperimentLoader( 6655): 	... 12 more
E/ExperimentLoader( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6655): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6655): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6655): 	at ihi.a(PG:19)
E/ExperimentLoader( 6655): 	... 14 more
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
,D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6655): [getaccountstatus] Unexpected exception
E/HttpOperation( 6655): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6655): 	at kfv.a(PG:65)
E/HttpOperation( 6655): 	at kff.u(PG:385)
E/HttpOperation( 6655): 	at kfb.a(PG:29)
E/HttpOperation( 6655): 	at ixd.a(PG:248)
E/HttpOperation( 6655): 	at ixd.b(PG:206)
E/HttpOperation( 6655): 	at ixd.a(PG:175)
E/HttpOperation( 6655): 	at fig.a(PG:78)
E/HttpOperation( 6655): 	at lex.a(PG:85)
E/HttpOperation( 6655): 	at lex.b(PG:132)
E/HttpOperation( 6655): 	at fhk.a(PG:1146)
E/HttpOperation( 6655): 	at fhk.a(PG:908)
E/HttpOperation( 6655): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6655): 	at ihi.a(PG:22)
E/HttpOperation( 6655): 	at kft.a(PG:91)
E/HttpOperation( 6655): 	at kfv.a(PG:62)
E/HttpOperation( 6655): 	... 12 more
E/HttpOperation( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6655): 	at gde.c(Unknown Source)
E/HttpOperation( 6655): 	at gde.b(Unknown Source)
E/HttpOperation( 6655): 	at ihi.a(PG:19)
E/HttpOperation( 6655): 	... 14 more
,E/EsSyncAdapterService( 6655): Sync failure
E/EsSyncAdapterService( 6655): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6655): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6655): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6655): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6655): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6655): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6655): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6655): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6655): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6655): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6655): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6655): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6655): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6655): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6655): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6655): 	... 10 more
E/EsSyncAdapterService( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6655): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6655): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6655): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6655): 	... 12 more
E/EsSyncAdapterService( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6655): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6655): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6655): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6655): 	... 14 more
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  806): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 185159, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  806): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  806): mCursor = null
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  283): DCD ON
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  806): SIOP:: AP = 320, PST = 354, CUR = 300
,I/PowerManagerService(  806): [PWL] Off : 50s ago
,E/SMD     (  283): DCD ON
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  806): waitForAlarm result :4
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
,I/MotionRecognitionService(  806): setPowerConnected  = true
,D/BatteryService(  806): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6685): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6685): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6685): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  283): DCD ON
,E/Watchdog(  806): !@Sync 6
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 320, PST = 343, CUR = 300
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON,
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 310, PST = 333, CUR = 300
,E/SMD     (  283): DCD ON
,V/AlarmManager(  806): waitForAlarm result :4
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  806): stay LED for fully charged
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
I/MotionRecognitionService(  806): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  806): [PWL] Off : 75s ago
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,V/AlarmManager(  806): waitForAlarm result :8
,D/SSRM:m  (  806): SIOP:: AP = 310, PST = 327, CUR = 300
,E/SMD     (  283): DCD ON
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
,I/MotionRecognitionService(  806): setPowerConnected  = true
,D/BatteryService(  806): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,E/Watchdog(  806): !@Sync 7
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 310, PST = 323, CUR = 300
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 310, PST = 319, CUR = 300
,E/SMD     (  283): DCD ON
,V/AlarmManager(  806): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  806): stay LED for fully charged
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
I/MotionRecognitionService(  806): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7411): Starting books sync, d
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7411): Authentication error
E/BooksAccountManager( 7411): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7411): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7411): null auth token
,I/qtaguid ( 7411): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,I/qtaguid ( 7411): Untagging socket 34
,W/ApiaryClient( 7411): Error response from books API: {
W/ApiaryClient( 7411):  "error": {
W/ApiaryClient( 7411):   "errors": [
W/ApiaryClient( 7411):    {
W/ApiaryClient( 7411):     "domain": "global",
W/ApiaryClient( 7411):     "reason": "required",
W/ApiaryClient( 7411):     "message": "Login Required",
W/ApiaryClient( 7411):     "locationType": "header",
W/ApiaryClient( 7411):     "location": "Authorization"
W/ApiaryClient( 7411):    }
W/ApiaryClient( 7411):   ],
W/ApiaryClient( 7411):   "code": 401,
W/ApiaryClient( 7411):   "message": "Login Required"
W/ApiaryClient( 7411):  }
W/ApiaryClient( 7411): }
,W/ApiaryClient( 7411): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3415526260597768028&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7411): Headers suppressed
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7411): Authentication error
E/BooksAccountManager( 7411): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7411): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7411): null auth token
,I/qtaguid ( 7411): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,I/qtaguid ( 7411): Untagging socket 34
,W/ApiaryClient( 7411): Error response from books API: {
W/ApiaryClient( 7411):  "error": {
W/ApiaryClient( 7411):   "errors": [
W/ApiaryClient( 7411):    {
W/ApiaryClient( 7411):     "domain": "global",
W/ApiaryClient( 7411):     "reason": "required",
W/ApiaryClient( 7411):     "message": "Login Required",
W/ApiaryClient( 7411):     "locationType": "header",
W/ApiaryClient( 7411):     "location": "Authorization"
W/ApiaryClient( 7411):    }
W/ApiaryClient( 7411):   ],
W/ApiaryClient( 7411):   "code": 401,
W/ApiaryClient( 7411):   "message": "Login Required"
W/ApiaryClient( 7411):  }
W/ApiaryClient( 7411): }
,W/ApiaryClient( 7411): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3415526260597768028&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7411): Headers suppressed
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  806): [PWL] Off : 105s ago
,I/PowerManagerService(  806): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  806): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  806): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=806, ws=WorkSource{10082}) (elapsedTime=2039)
,E/SMD     (  283): DCD ON
,I/art     ( 1693): Explicit concurrent mark sweep GC freed 64213(3MB) AllocSpace objects, 62(4MB) LOS objects, 40% free, 18MB/30MB, paused 844us total 90.745ms
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7411): Authentication error
E/BooksAccountManager( 7411): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7411): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7411): null auth token
,I/qtaguid ( 7411): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,I/qtaguid ( 7411): Untagging socket 34
,W/ApiaryClient( 7411): Error response from books API: {
W/ApiaryClient( 7411):  "error": {
W/ApiaryClient( 7411):   "errors": [
W/ApiaryClient( 7411):    {
W/ApiaryClient( 7411):     "domain": "global",
W/ApiaryClient( 7411):     "reason": "required",
W/ApiaryClient( 7411):     "message": "Login Required",
W/ApiaryClient( 7411):     "locationType": "header",
W/ApiaryClient( 7411):     "location": "Authorization"
W/ApiaryClient( 7411):    }
W/ApiaryClient( 7411):   ],
W/ApiaryClient( 7411):   "code": 401,
W/ApiaryClient( 7411):   "message": "Login Required"
W/ApiaryClient( 7411):  }
W/ApiaryClient( 7411): }
,W/ApiaryClient( 7411): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3415526260597768028&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7411): Headers suppressed
D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7411): Soft error
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3415526260597768028&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7411): Headers suppressed
E/BooksSync( 7411): 
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7411): Sync error
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3415526260597768028&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7411): Headers suppressed
E/BooksSync( 7411): 
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7411): Finished books sync
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  806): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 216517, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  806): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  806): mCursor = null
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  806): SIOP:: AP = 310, PST = 316, CUR = 300,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
,D/BatteryService(  806): stay LED for fully charged
,I/MotionRecognitionService(  806): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  283): DCD ON
,E/Watchdog(  806): !@Sync 8
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 310, PST = 314, CUR = 300
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  806): SIOP:: AP = 300, PST = 312, CUR = 300
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  806): waitForAlarm result :4
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  806): stay LED for fully charged
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
I/MotionRecognitionService(  806): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
D/SecContentProvider2(  806): mCursor = null
,D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6655): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6655): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6655): 	at kfv.a(PG:65)
E/HttpOperation( 6655): 	at kff.u(PG:385)
E/HttpOperation( 6655): 	at kfb.a(PG:29)
E/HttpOperation( 6655): 	at kff.l(PG:132)
E/HttpOperation( 6655): 	at dsf.a(PG:807)
E/HttpOperation( 6655): 	at fhk.a(PG:1126)
E/HttpOperation( 6655): 	at fhk.a(PG:908)
E/HttpOperation( 6655): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6655): 	at ihi.a(PG:22)
E/HttpOperation( 6655): 	at kft.a(PG:91)
E/HttpOperation( 6655): 	at kfv.a(PG:62)
E/HttpOperation( 6655): 	... 8 more
E/HttpOperation( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6655): 	at gde.c(Unknown Source)
E/HttpOperation( 6655): 	at gde.b(Unknown Source)
E/HttpOperation( 6655): 	at ihi.a(PG:19)
E/HttpOperation( 6655): 	... 10 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6655): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6655): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6655): 	at kfv.a(PG:65)
E/HttpOperation( 6655): 	at kff.u(PG:385)
E/HttpOperation( 6655): 	at kfb.a(PG:29)
E/HttpOperation( 6655): 	at kff.l(PG:132)
E/HttpOperation( 6655): 	at ieo.a(PG:43)
E/HttpOperation( 6655): 	at iep.a(PG:93)
E/HttpOperation( 6655): 	at fhn.a(PG:59)
E/HttpOperation( 6655): 	at lex.a(PG:85)
E/HttpOperation( 6655): 	at lex.b(PG:132)
E/HttpOperation( 6655): 	at fhk.a(PG:1146)
E/HttpOperation( 6655): 	at fhk.a(PG:908)
E/HttpOperation( 6655): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6655): 	at ihi.a(PG:22)
E/HttpOperation( 6655): 	at kft.a(PG:91)
E/HttpOperation( 6655): 	at kfv.a(PG:62)
E/HttpOperation( 6655): 	... 12 more
E/HttpOperation( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6655): 	at gde.c(Unknown Source)
E/HttpOperation( 6655): 	at gde.b(Unknown Source)
E/HttpOperation( 6655): 	at ihi.a(PG:19)
E/HttpOperation( 6655): 	... 14 more
,E/ExperimentLoader( 6655): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6655): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6655): 	at kfv.a(PG:65)
E/ExperimentLoader( 6655): 	at kff.u(PG:385)
E/ExperimentLoader( 6655): 	at kfb.a(PG:29)
E/ExperimentLoader( 6655): 	at kff.l(PG:132)
E/ExperimentLoader( 6655): 	at ieo.a(PG:43)
E/ExperimentLoader( 6655): 	at iep.a(PG:93)
E/ExperimentLoader( 6655): 	at fhn.a(PG:59)
E/ExperimentLoader( 6655): 	at lex.a(PG:85)
E/ExperimentLoader( 6655): 	at lex.b(PG:132)
E/ExperimentLoader( 6655): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6655): 	at fhk.a(PG:908)
E/ExperimentLoader( 6655): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6655): 	at ihi.a(PG:22)
E/ExperimentLoader( 6655): 	at kft.a(PG:91)
E/ExperimentLoader( 6655): 	at kfv.a(PG:62)
E/ExperimentLoader( 6655): 	... 12 more
E/ExperimentLoader( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6655): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6655): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6655): 	at ihi.a(PG:19)
E/ExperimentLoader( 6655): 	... 14 more
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
,D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6655): [getaccountstatus] Unexpected exception
E/HttpOperation( 6655): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6655): 	at kfv.a(PG:65)
E/HttpOperation( 6655): 	at kff.u(PG:385)
E/HttpOperation( 6655): 	at kfb.a(PG:29)
E/HttpOperation( 6655): 	at ixd.a(PG:248)
E/HttpOperation( 6655): 	at ixd.b(PG:206)
E/HttpOperation( 6655): 	at ixd.a(PG:175)
E/HttpOperation( 6655): 	at fig.a(PG:78)
E/HttpOperation( 6655): 	at lex.a(PG:85)
E/HttpOperation( 6655): 	at lex.b(PG:132)
E/HttpOperation( 6655): 	at fhk.a(PG:1146)
E/HttpOperation( 6655): 	at fhk.a(PG:908)
E/HttpOperation( 6655): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6655): 	at ihi.a(PG:22)
E/HttpOperation( 6655): 	at kft.a(PG:91)
E/HttpOperation( 6655): 	at kfv.a(PG:62)
E/HttpOperation( 6655): 	... 12 more
E/HttpOperation( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6655): 	at gde.c(Unknown Source)
E/HttpOperation( 6655): 	at gde.b(Unknown Source)
E/HttpOperation( 6655): 	at ihi.a(PG:19)
E/HttpOperation( 6655): 	... 14 more
,E/EsSyncAdapterService( 6655): Sync failure
E/EsSyncAdapterService( 6655): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6655): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6655): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6655): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6655): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6655): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6655): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6655): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6655): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6655): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6655): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6655): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6655): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6655): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6655): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6655): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6655): 	... 10 more
E/EsSyncAdapterService( 6655): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6655): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6655): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6655): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6655): 	... 12 more
E/EsSyncAdapterService( 6655): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6655): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6655): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6655): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6655): 	... 14 more
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  806): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 252905, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  806): Explicit concurrent mark sweep GC freed 45589(2MB) AllocSpace objects, 40(1225KB) LOS objects, 30% free, 36MB/52MB, paused 1.447ms total 121.388ms
,D/SecContentProvider2(  806): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  806): mCursor = null
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,V/AlarmManager(  806): waitForAlarm result :8
,I/PowerManagerService(  806): [PWL] Off : 140s ago
,D/SSRM:m  (  806): SIOP:: AP = 300, PST = 310, CUR = 300
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,E/Watchdog(  806): !@Sync 9
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 300, PST = 308, CUR = 300
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 300, PST = 306, CUR = 300
,E/SMD     (  283): DCD ON
,V/AlarmManager(  806): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  806): stay LED for fully charged
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  806): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 300, PST = 305, CUR = 300
,E/SMD     (  283): DCD ON
,D/TimaService(  806): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  806): TimaServiceHandler.handleMessage what =1
,D/TimaService(  806): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  806): initializing...
,I/TLC_TIMA_PKM_initialize(  806): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  806): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  806): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  806): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  806): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  806): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  806): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  806): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  806): App is not loaded in QSEE
,D/QSEECOMAPI: (  806): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  806): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  806): Trustlet response is completed
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
,I/MotionRecognitionService(  806): setPowerConnected  = true
,D/BatteryService(  806): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  283): DCD ON
,E/Watchdog(  806): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  806): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  806): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  806): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  806): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  283): DCD ON
,I/PowerManagerService(  806): [PWL] Off : 180s ago
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  283): DCD ON
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  806): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  283): DCD ON
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  806): waitForAlarm result :4
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  806): stay LED for fully charged
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
I/MotionRecognitionService(  806): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7411): Starting books sync, d
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7411): Authentication error
E/BooksAccountManager( 7411): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7411): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7411): null auth token
,I/qtaguid ( 7411): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,V/AlarmManager(  806): waitForAlarm result :4
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8590): MountEmulatedStorage()
,E/Zygote  ( 8590): v2
,I/libpersona( 8590): KNOX_SDCARD checking this for 10081
I/libpersona( 8590): KNOX_SDCARD not a persona
,I/SELinux ( 8590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8590): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  806): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8590 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/qtaguid ( 7411): Untagging socket 34
,D/TimaKeyStoreProvider( 8590): TimaSignature is unavailable
,D/ActivityThread( 8590): Added TimaKeyStore provider
,W/ApiaryClient( 7411): Error response from books API: {
W/ApiaryClient( 7411):  "error": {
W/ApiaryClient( 7411):   "errors": [
W/ApiaryClient( 7411):    {
W/ApiaryClient( 7411):     "domain": "global",
W/ApiaryClient( 7411):     "reason": "required",
W/ApiaryClient( 7411):     "message": "Login Required",
W/ApiaryClient( 7411):     "locationType": "header",
W/ApiaryClient( 7411):     "location": "Authorization"
W/ApiaryClient( 7411):    }
W/ApiaryClient( 7411):   ],
W/ApiaryClient( 7411):   "code": 401,
W/ApiaryClient( 7411):   "message": "Login Required"
W/ApiaryClient( 7411):  }
W/ApiaryClient( 7411): }
,D/ResourcesManager( 8590): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,W/ApiaryClient( 7411): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7754164490910254181&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7411): Headers suppressed
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7411): Authentication error
E/BooksAccountManager( 7411): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7411): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7411): null auth token
,I/qtaguid ( 7411): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,E/SMD     (  283): DCD ON
,I/qtaguid ( 7411): Untagging socket 34
,W/ApiaryClient( 7411): Error response from books API: {
W/ApiaryClient( 7411):  "error": {
W/ApiaryClient( 7411):   "errors": [
W/ApiaryClient( 7411):    {
W/ApiaryClient( 7411):     "domain": "global",
W/ApiaryClient( 7411):     "reason": "required",
W/ApiaryClient( 7411):     "message": "Login Required",
W/ApiaryClient( 7411):     "locationType": "header",
W/ApiaryClient( 7411):     "location": "Authorization"
W/ApiaryClient( 7411):    }
W/ApiaryClient( 7411):   ],
W/ApiaryClient( 7411):   "code": 401,
W/ApiaryClient( 7411):   "message": "Login Required"
W/ApiaryClient( 7411):  }
W/ApiaryClient( 7411): }
,W/ApiaryClient( 7411): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7754164490910254181&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7411): Headers suppressed
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  806): uri = 14 selection = getSealedState
,D/SecContentProvider2(  806): mCursor = null
D/SecContentProvider2(  806): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  806): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  806): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7411): Authentication error
E/BooksAccountManager( 7411): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7411): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7411): null auth token
,I/qtaguid ( 7411): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7411, getuid(): 10082
,I/qtaguid ( 7411): Untagging socket 34
,W/ApiaryClient( 7411): Error response from books API: {
W/ApiaryClient( 7411):  "error": {
W/ApiaryClient( 7411):   "errors": [
W/ApiaryClient( 7411):    {
W/ApiaryClient( 7411):     "domain": "global",
W/ApiaryClient( 7411):     "reason": "required",
W/ApiaryClient( 7411):     "message": "Login Required",
W/ApiaryClient( 7411):     "locationType": "header",
W/ApiaryClient( 7411):     "location": "Authorization"
W/ApiaryClient( 7411):    }
W/ApiaryClient( 7411):   ],
W/ApiaryClient( 7411):   "code": 401,
W/ApiaryClient( 7411):   "message": "Login Required"
W/ApiaryClient( 7411):  }
W/ApiaryClient( 7411): }
,W/ApiaryClient( 7411): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7754164490910254181&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7411): Headers suppressed
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7411): Soft error
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7754164490910254181&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7411): Headers suppressed
E/BooksSync( 7411): 
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7411): Sync error
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7411): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7754164490910254181&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7411): Headers suppressed
E/BooksSync( 7411): 
E/BooksSync( 7411): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7411): Finished books sync
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  806): Killing 5683:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/SyncManager(  806): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 307509, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2852): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2852): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ConnectivityService(  806): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CountryDetector(  806): No listener is left
,D/SecContentProvider2(  806): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  806): mCursor = null
,W/libprocessgroup(  806): failed to open /acct/uid_10050/pid_5683/cgroup.procs: No such file or directory
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  806): waitForAlarm result :8
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  806): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  283): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  806): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  806): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  806): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  806):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  806): Plugged
,I/MotionRecognitionService(  806): setPowerConnected  = true
,D/BatteryService(  806): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  283): DCD ON
,E/Watchdog(  806): !@Sync 11
,E/SMD     (  283): DCD ON
,I/jxcore-log( 7493): --= Surplus to requirements =--
I/jxcore-log( 7493): 
,I/jxcore-log( 7493): ****TEST TOOK:  ms ****
I/jxcore-log( 7493): 
I/jxcore-log( 7493): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7493): 
,D/AndroidRuntime( 8652): 
D/AndroidRuntime( 8652): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8652): CheckJNI is OFF
,D/AndroidRuntime( 8652): setted country_code = Germany
,D/AndroidRuntime( 8652): setted countryiso_code = DE
,D/AndroidRuntime( 8652): setted sales_code = DBT
,D/AndroidRuntime( 8652): readGMSProperty: start
,D/AndroidRuntime( 8652): readGMSProperty: already setted!!
D/AndroidRuntime( 8652): readGMSProperty: end
D/AndroidRuntime( 8652): addProductProperty: start
,E/AffinityControl( 8652): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8652): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  806): START PACKAGE DELETE: observer{752809378}
D/PackageManager(  806): pkg{<packageName>}
D/PackageManager(  806): user{0}
D/PackageManager(  806): caller{2000}
D/PackageManager(  806): flags{3}
D/PersonaManagerService(  806): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  806): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  806): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  806): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  806): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  806): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  806): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  806): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  806): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  806): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  806): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  806): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  806): Killing 7493:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  806):   Force finishing activity ActivityRecord{3fef13c u0 com.test.thalitest/.MainActivity t17}
,D/FocusedStackFrame(  806): Set to : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  806): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiService(  806): Client connection lost with reason: 4
,I/ActivityManager(  806): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,I/art     ( 4507): Explicit concurrent mark sweep GC freed 5010(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 337us total 37.360ms
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 1582): Explicit concurrent mark sweep GC freed 20854(1317KB) AllocSpace objects, 1(39KB) LOS objects, 40% free, 16MB/27MB, paused 767us total 73.131ms
,I/InputReader(  806): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,W/GeofencerStateMachine( 2169): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1834): mOCRHelper is null
,I/KLMS-2.4.503: ( 7738): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7738): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453396748874
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/KLMS-2.4.503: ( 7738): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7738): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/SecContentProvider2(  806): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  806): mCursor = null
D/ResourcesManager(  806): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/art     (  806): Explicit concurrent mark sweep GC freed 33895(2MB) AllocSpace objects, 29(659KB) LOS objects, 30% free, 36MB/52MB, paused 2.426ms total 218.839ms
I/art     (  806): WaitForGcToComplete blocked for 145.312ms for cause Explicit
,D/ResourcesManager(  806): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/RegisteredServicesCache( 1468): empty dynamic service
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/EnterpriseDeviceManagerService(  806): Package has changed for user 0
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/EnterpriseDeviceManagerService(  806): Admin package name: com.google.android.gms
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/Zygote  ( 8681): MountEmulatedStorage()
E/Zygote  ( 8681): v2
I/libpersona( 8681): KNOX_SDCARD checking this for 10104
I/libpersona( 8681): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8681 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 8681): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8681): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8681): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/TimaKeyStoreProvider( 8681): TimaSignature is unavailable
,D/ActivityThread( 8681): Added TimaKeyStore provider
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8681): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SurfaceWidgetView( 1481): destroyHardwareResources():211615327
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Drive/Drive.apk
,V/WindowOrientationListener(  806): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  806): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  806): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  806): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  806): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/Launcher( 1481): onRestart, Launcher: 1072636680
,D/Launcher( 1481): onStart, Launcher: 1072636680
D/Launcher.HomeView( 1481): onStart
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2068): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2068): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/ResourcesManager(  806): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/StatusBarManagerService(  806): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBarManagerService(  806): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/elm:14451( 8681): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/elm:14451( 8681): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8681): MDMBridge.setEnterpriseBridge()
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/InputMethodManagerService(  806): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  806): Got RemoteException sending setActive(false) notification to pid 7493 uid 10200
,D/elm:14451( 8681): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/ContextImpl(  806): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8155): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8155): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8155): onReceive() : package name is not s health. Return !!!
,D/elm:14451( 8681): ElmAgentService : onCreate()
,D/elm:14451( 8681): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8681): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8681): MDMBridge.getInstance()
D/elm:14451( 8681): MDMBridge.getAllLicenseInfoFromSDK()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/elm:14451( 8681): MDMBridge.getAllLicenseInfoFromSDK()
,I/PCWCLIENTTRACE_PushUtil( 7624): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7624): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7624): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7624): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/elm:14451( 8681): ElmAgentService : onDestroy().
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
I/art     (  806): Explicit concurrent mark sweep GC freed 12288(547KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 4.787ms total 274.047ms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/RCPManagerService(  806): PackageReceiver onReceive()
,I/HarmonyEASService(  806): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline(  806): Timeline: Activity_windows_visible id: ActivityRecord{12a41f71 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:348195
D/KnoxMUMContainerPolicy(  806): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,D/BackupManagerService(  806): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  806): Receieved: android.intent.action.PACKAGE_REMOVED
,E/Zygote  ( 8703): MountEmulatedStorage()
E/Zygote  ( 8703): v2
,I/libpersona( 8703): KNOX_SDCARD checking this for 10038
I/libpersona( 8703): KNOX_SDCARD not a persona
V/EnterpriseBillingPolicy(  806): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  806): uID is 10200
V/EnterpriseBillingPolicy(  806): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  806): getProfileForApplication - enter
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/EnterpriseBillingPolicyStorage(  806): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  806): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  806): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  806): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  806): getBillingProfileForVpnEngine - end - null
,I/ActivityManager(  806): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8703 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8703): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8703): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8703): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  806): Killing 7336:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,D/TaskPersister(  806): removeObsoleteFile: deleting file=17_task.xml
,D/TaskPersister(  806): removeObsoleteFile: deleting file=17_task_thumbnail.png
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  806): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/TimaKeyStoreProvider( 8703): TimaSignature is unavailable
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ActivityThread( 8703): Added TimaKeyStore provider
,W/ResourcesManager(  806): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  806): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  806): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 8703): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/libprocessgroup(  806): failed to open /acct/uid_10094/pid_7336/cgroup.procs: No such file or directory
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/PackageManager(  806): delete codoeFile: 
,D/PackageManager(  806): result of delete: 1{752809378}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  806): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  806): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  806): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  806): clearDefaults: com.test.thalitest
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/CrashAnrDetector(  806): onPackageRemoved : com.test.thalitest
,W/ResourcesManager( 8099): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SPPClientService( 8703): ============PushLog. commonIsShipBuild. stop!
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/SPPClientService( 8703): [PushClientApplication] Push log off : This is Ship build version
,W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/AndroidRuntime( 8652): Shutting down VM
,W/ResourcesManager( 8099): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SPPClientService( 8703): PushLog.txt file is not deleted.
D/SPPClientService( 8703): PushLog.txt file is not deleted.
D/SPPClientService( 8703): ============PushLog. stop!
,W/ResourcesManager( 8099): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,E/Zygote  ( 8719): MountEmulatedStorage()
E/Zygote  ( 8719): v2
I/libpersona( 8719): KNOX_SDCARD checking this for 10042
I/libpersona( 8719): KNOX_SDCARD not a persona
,W/ResourcesManager( 8099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager(  806): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8719 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager(  806): Killing 7351:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,I/SELinux ( 8719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8719): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     (  312): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 336us total 16.812ms
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 263us total 10.456ms
,D/TimaKeyStoreProvider( 8719): TimaSignature is unavailable
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 7.907ms
,D/ActivityThread( 8719): Added TimaKeyStore provider
W/libprocessgroup(  806): failed to open /acct/uid_10103/pid_7351/cgroup.procs: No such file or directory
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8719): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8719): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8719): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8099): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8099): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8099): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/ResourcesManager( 8099): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8099): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/System.err( 8719): java.lang.NoSuchMethodException: getImeiInCDMAGSMPhone []
,W/System.err( 8719): 	at java.lang.Class.getMethod(Class.java:665)
,W/System.err( 8719): 	at com.sec.pcw.util.c.c(SourceFile:295)
W/System.err( 8719): 	at com.sec.pcw.service.account.a.b(SourceFile:250)
,W/System.err( 8719): 	at com.sec.pcw.service.account.a.a(SourceFile:52)
W/System.err( 8719): 	at com.mfluent.asp.datamodel.Device.r(SourceFile:359)
,W/System.err( 8719): 	at com.mfluent.asp.datamodel.Device.<init>(SourceFile:248)
W/System.err( 8719): 	at com.mfluent.asp.datamodel.t.a(SourceFile:136)
W/System.err( 8719): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:484)
,W/System.err( 8719): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 8719): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
,W/System.err( 8719): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
W/System.err( 8719): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
W/System.err( 8719): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
,W/System.err( 8719): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8719): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
,W/System.err( 8719): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8719): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 8719): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 8719): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8719): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 8719): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 8719): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,F/libc    ( 8719): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa1b06a70 in tid 8719 (sdk.samsunglink)
,F/libc    ( 8719): Failed while talking to debuggerd: Broken pipe
,E/audit_log( 2096): File locking failed. error= Bad file number
E/audit_log( 2096): File locking failed. error= Bad file number
,I/EventHub(  806): Removing device '/dev/input/event4' due to inotify event
,I/EventHub(  806): Removing device '/dev/input/event5' due to inotify event
,I/ActivityManager(  806): Process com.samsung.android.sdk.samsunglink (pid 8719)(adj 0) has died(236,497)
,I/SA      ( 7840): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7840): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,F/libc    ( 1797): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77e0044c in tid 1797 (d.process.acore)
,F/libc    ( 1797): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7828ee10 in tid 1860 (ContactsProvide)
,F/libc    ( 1797): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2096): File locking failed. error= Bad file number
,I/Zygote  (  312): Process 8719 exited due to signal (7)
,I/ActivityManager(  806): Process android.process.acore (pid 1797)(adj 0) has died(242,497)
,I/EventHub(  806): Removing device '/dev/input/event6' due to inotify event
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8749): MountEmulatedStorage()
I/libpersona( 8749): KNOX_SDCARD checking this for 10050
E/Zygote  ( 8749): v2
I/libpersona( 8749): KNOX_SDCARD not a persona
I/ActivityManager(  806): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8749 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SharedPreferencesImpl( 5989): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,I/EventHub(  806): Removing device '/dev/input/event7' due to inotify event
,I/Zygote  (  312): Process 1797 exited due to signal (7)
,I/SELinux ( 8749): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8749): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/EventHub(  806): Removing device '/dev/input/event8' due to inotify event
,I/EventHub(  806): Removing device '/dev/input/event9' due to inotify event
,D/TimaKeyStoreProvider( 8749): TimaSignature is unavailable
,D/ActivityThread( 8749): Added TimaKeyStore provider
,D/ResourcesManager( 8749): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8749): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8749): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8749): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8749): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8749): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 8749): Unable to create files subdir /data/data/com.android.mms/cache
E/ActivityThread( 8749): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  806): Removing device '/dev/input/event10' due to inotify event
,D/AndroidRuntime( 8749): Shutting down VM
,E/AndroidRuntime( 8749): FATAL EXCEPTION: main
E/AndroidRuntime( 8749): Process: com.android.mms, PID: 8749
E/AndroidRuntime( 8749): java.lang.RuntimeException: Unable to instantiate application com.android.mms.MmsApp: java.lang.ClassNotFoundException: Didn't find class "com.android.mms.MmsApp" on path: DexPathList[[zip file "/system/framework/imsmanager.jar", zip file "/system/framework/twframework.jar", zip file "/system/framework/multiwindow.jar", zip file "/system/framework/com.google.android.maps.jar", zip file "/system/framework/minimode.jar", zip file "/system/priv-app/SecMms_Candy/SecMms_Candy.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8749): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime( 8749): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4980)
E/AndroidRuntime( 8749): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8749): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8749): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8749): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8749): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8749): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8749): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8749): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8749): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8749): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.android.mms.MmsApp" on path: DexPathList[[zip file "/system/framework/imsmanager.jar", zip file "/system/framework/twframework.jar", zip file "/system/framework/multiwindow.jar", zip file "/system/framework/com.google.android.maps.jar", zip file "/system/framework/minimode.jar", zip file "/system/priv-app/SecMms_Candy/SecMms_Candy.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8749): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8749): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8749): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8749): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime( 8749): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime( 8749): 	... 10 more
E/AndroidRuntime( 8749): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/SecMms_Candy/SecMms_Candy.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 8749): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8749): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8749): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8749): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8749): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8749): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8749): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8749): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8749): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8749): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8749): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8749): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8749): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8749): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8749): 		at, android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8749): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8749): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 8749): 		... 10 more
E/AndroidRuntime( 8749): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/SecMms_Candy/SecMms_Candy.apk'
E/AndroidRuntime( 8749): 		... 27 more
E/AndroidRuntime( 8749): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/SecMms_Candy/arm/SecMms_Candy.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8749): 		... 27 more
E/AndroidRuntime( 8749): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8749): 		... 27 more
E/AndroidRuntime( 8749): 	Suppressed: java.lang.ClassNotFoundException: com.android.mms.MmsApp
E/AndroidRuntime( 8749): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8749): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8749): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8749): 		at java.lang.ClassLoade
F/libc    ( 8749): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7195e498 in tid 8749 (com.android.mms)
F/libc    ( 8749): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2096): File locking failed. error= Bad file number
,I/EventHub(  806): Removing device '/dev/input/event11' due to inotify event
,I/ActivityManager(  806): Process com.android.mms (pid 8749)(adj 0) has died(241,497)
,I/TactileAssist(  806): enable value -1
I/TactileAssist(  806): internal enable value -1
I/TactileAssist(  806): intensity value -1
I/TactileAssist(  806): saveAppList value true
,I/TactileAssist(  806): List of disabled apps :
,I/TactileAssist(  806): de.zalando.mobile
,E/SharedPreferencesImpl(  806): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
,I/Zygote  (  312): Process 8749 exited due to signal (7)
,E/Zygote  ( 8766): MountEmulatedStorage()
E/Zygote  ( 8766): v2
I/libpersona( 8766): KNOX_SDCARD checking this for 10058
I/libpersona( 8766): KNOX_SDCARD not a persona
,I/ActivityManager(  806): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8766 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,E/SMD     (  283): DCD ON
,I/SELinux ( 8766): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8766): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/TimaKeyStoreProvider( 8766): TimaSignature is unavailable
,D/ActivityThread( 8766): Added TimaKeyStore provider
,D/ResourcesManager( 8766): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ContextImpl( 8766): Unable to create files subdir /data/data/com.sec.android.app.soundalive/cache
W/ResourcesManager( 8766): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/ActivityThread( 8766): Unable to setupGraphicsSupport due to missing cache directory
,D/AndroidRuntime( 8766): Shutting down VM
,I/ActivityManager(  806): Killing 7367:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,E/AndroidRuntime( 8766): FATAL EXCEPTION: main
E/AndroidRuntime( 8766): Process: com.sec.android.app.soundalive, PID: 8766
E/AndroidRuntime( 8766): java.lang.RuntimeException: Unable to instantiate receiver com.sec.android.app.soundalive.compatibility.Compatibility$Receiver: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.app.soundalive.compatibility.Compatibility$Receiver" on path: DexPathList[[zip file "/system/framework/multiwindow.jar", zip file "/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8766): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2926)
E/AndroidRuntime( 8766): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 8766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
E/AndroidRuntime( 8766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8766): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8766): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8766): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8766): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8766): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.app.soundalive.compatibility.Compatibility$Receiver" on path: DexPathList[[zip file "/system/framework/multiwindow.jar", zip file "/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8766): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8766): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8766): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8766): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2921)
E/AndroidRuntime( 8766): 	... 9 more
E/AndroidRuntime( 8766): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 8766): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8766): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8766): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8766): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8766): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8766): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8766): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8766): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8766): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8766): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8766): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8766): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8766): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8766): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8766): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8766): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8766): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 8766): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4980)
E/AndroidRuntime( 8766): 		at android.app.Act,ivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8766): 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8766): 		... 7 more
E/AndroidRuntime( 8766): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk'
E/AndroidRuntime( 8766): 		... 27 more
E/AndroidRuntime( 8766): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/SoundAlive_20_L/arm/SoundAlive_20_L.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8766): 		... 27 more
E/AndroidRuntime( 8766): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8766): 		... 27 more
E/AndroidRuntime( 8766): 	Suppressed: java.lang.ClassNotFoundException: com.sec.android.app.soundalive.compatibility.Compatibility$Receiver
E/AndroidRuntime( 8766): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8766): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8766): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8766): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 8766): 		... 11 more
E/AndroidRuntime( 8766): 	Caused by: java.lang.NoC
F/libc    ( 8766): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7195e498 in tid 8766 (.app.soundalive)
F/libc    ( 8766): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2096): File locking failed. error= Bad file number
I/UpdateIcingCorporaServi( 1582): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  806): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8782): MountEmulatedStorage()
E/Zygote  ( 8782): v2
I/libpersona( 8782): KNOX_SDCARD checking this for 10003
I/libpersona( 8782): KNOX_SDCARD not a persona
I/ActivityManager(  806): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=8782 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a

```
